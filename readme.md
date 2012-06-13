This is a Grails plugin that allows you to use [Angular.js](http://angularjs.org/) based scaffolding.

## Usage

After installing the plugin run `grails generate-all _domain class name_` to install scaffolding.

## Limitations

This is an experimental work-in-progress. It is far from complete.

- Only the _list_ view is implemented so far
- Currently default scaffolding GSP templates (_create,gsp_, _edit.gsp_, _list.gsp_, _show.gsp_ and __form.gsp_) will be created alongside the _Angular_ enabled _index.gsp_ you can delete these extra files.

## To-do

- List
    - pagination
    - sorting
- Other views
    - create
    - edit
    - show
- Path to actions needs to be derived from a base URL
- Templates
    - path to HTML template is hardcoded
    - HTML templates need to be generated by scaffolding
- Flash messages
- Validate inputs live using AJAX
