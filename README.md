# Joplin Plugin

This is a template to create a new Joplin plugin.

The main two files you will want to look at are:

- `/src/index.ts`, which contains the entry point for the plugin source code
- `/dist/manifest.json`, which is the plugin manifest. You will want to edit this one, in particular to give the plugin a name, set the license, etc.

The plugin is built using webpack, which create the compiled code in `/dist`. The project is setup to use TypeScript, although you can change the configuration to use plain JavaScript.

## Building the plugin

First install the plugin template:

	git clone https://github.com/laurent22/joplin-plugin my-plugin
	cd my-plugin
	npm install

Then build the plugin:

	npm run dist
