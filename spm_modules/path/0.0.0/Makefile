version = $(shell cat package.json | grep version | awk -F'"' '{print $$4}')

publish:
	@npm publish
	@spm publish
	#@git tag $(version)
	#@git push origin $(version)

test:
