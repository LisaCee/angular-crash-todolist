# Angular Crash Course Notes

[YouTube](https://www.youtube.com/watch?v=Fdf5aTYRW0E)
[Github](https://www.youtube.com/redirect?q=https%3A%2F%2Fgithub.com%2Fbradtraversy%2Fangular-crash-todolist&event=video_description&v=Fdf5aTYRW0E&redir_token=GK8jRdn6BsSJA_-GdGIyvL44c8d8MTU2MzkzMzc1MUAxNTYzODQ3MzUx)

##Commands
* ng --version
* ng new ApplicationName
    * Router - yes
    * CSS
* ng serve --open
    * Runs server and opens browser at localhost:4200
* ng generate component componentName
    * can create subfolder with component components/componentName
    * shortcut command
        `ng g c componentName`
* ng g s serviceName
* ng build
    * creates dist folder for deployment

##Syntax
* Imports
* Decorator (@Component() {} )
* Class
* Can add constructor
* ngOnInit() is like ComponentDidMount() in React
* ngFor="let todo of todos"

##Files
* index.html = root file
* app.module.ts = where new components are imported
(angular/cli does it automatically)

##Tips
* Change .ts defaults to Typescript
`title = ‘application’` => `title: string = ‘application’`
* PIPES - look at docs for more
`{{ name | uppercase }} like name.toUpperCase()`
* Components must be wrapped in a single root (div) like in React
* Optional field in class model - id?:number
* Services are usually private
* .subscribe() to an Observable is like .then() in JS/Axios/Fetch


##Typescript
* If a function doesn’t return anything add :void after ) and before {
    ```
    changeName(name: string):void {
        function body here
    }
    ```
