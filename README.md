# AngularJs MovieApp 

Creating a CRUD App in Minutes with Angular’s $resource

Writen by: Sandeep Panda

Original site from: http://movieapp-sitepointdemos.rhcloud.com/#/movies

I have used this tutorial to learn AngularJs with GRUD. 
Made a copy and some modifications. 

''Many thanks `Sandeep Panda` for your tutorial \o/''


## Install 

Install local and use the API from http://movieapp-sitepointdemos.rhcloud.com/

    sudo apt-get install nodejs

## Run node

Install packages from `packages.json`.

    npm install

# Run the for local server.

    grunt connect

Browse to `http://localhost:3000` 

Try it ;)

## Notes about a rails-api

If you use the rails-api remove the 'underscore' i.o. `@id` in js/services.js`

    return $resource('http://localhost:3000/movies/:id',{id:'@id'},{

https://github.com/andriesfilmer/rails-api
