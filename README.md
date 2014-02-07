# Rails API + Angular Template

Creates a **rails-api** backend with an **angular** frontend. The frontend code will be located in the `<your-app>/frontend` folder.

## Usage

```
rails-api new <your-app-name> \
  --skip-sprockets \
  --skip-test-unit \
  --template=https://github.com/joshnuss/angular-rails-api/raw/master/template.rb
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

- To build the frontend: `cd frontend && grunt build`
- To run the frontend server: `cd frontend && grunt serve`
- To run the rails server: `rails server`
- To run the rails specs: `rake spec`
- To run the angular specs: `cd frontend && grunt test`

## Development Mode

In dev mode, you need to run both the frontend node server `grunt serve` and the rails server `rails server`
All requests are served from the frontend server, requests to `/api` are proxied to rails.

## Deployment

Run `grunt build` which copies all files to `/public`.

### Time for a coffee break?

@joshnuss is a freelance software consultant. You can contact me at joshnuss@gmail.com
