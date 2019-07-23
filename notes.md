#Angular Crash Course Notes

[YouTube](https://www.youtube.com/watch?v=Fdf5aTYRW0E)
[Github](https://www.youtube.com/redirect?q=https%3A%2F%2Fgithub.com%2Fbradtraversy%2Fangular-crash-todolist&event=video_description&v=Fdf5aTYRW0E&redir_token=GK8jRdn6BsSJA_-GdGIyvL44c8d8MTU2MzkzMzc1MUAxNTYzODQ3MzUx)

##Commands
* ng --version
* ng new ApplicationName
    * Router - yes
    * CSS
* ng serve --open
    *Runs server and opens browser at localhost:4200

##Syntax
* Imports
* Decorator (@Component() {} )
* Class
* Can add constructor

##Files
* index.html = root file
* app.module.ts = where new components are imported
(angular/cli does it automatically)

##Tips
* Change .ts defaults to Typescript
title = ‘application’ => title: string = ‘application’
* PIPES - look at docs for more
{{ name | uppercase }} like name.toUpperCase()

##Typescript
* If a function doesn’t return anything add :void after ) and before {
    ```
    changeName(name: string):void {
        function body here
    }
    ```