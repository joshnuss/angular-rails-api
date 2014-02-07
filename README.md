# Rails API + Angular Application Template

Creates a rails-api application with an angular frontend. The frontend is code located in `<your-app>/frontend`.

## Usage

```
rails-api <your-app-name> -S -T -m http://github.com/joshnuss/angular-rails-api/raw/master/template.rb
```

## Features

- rails-api
- grunt
- slim
- sass
- coffeescript
- bootstrap
- live-reload
- rspec
- jbuilder

## Requirements

- rails-api
- nodejs
- grunt-cli
- yo

## Common Tasks

- To build frontend: `cd frontend && grunt build`
- To run frontend server: `cd frontend && grunt serve`
- To run rails server: `rails server`
- To run rails specs: `rake spec`
- To run angular specs: `cd frontend && grunt test`

## Deployment

Run `grunt build` which copies all files to `/public`.

### Time for a coffee break?

@joshnuss is a freelance software consultant. You can contact me at joshnuss@gmail.com
