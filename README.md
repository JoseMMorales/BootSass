# Description
Who would like to use CSS Superpower?? Just implement your website with [Sass](https://sass-lang.com/).

I gave it a shot with my bootstrap project and I fell in love with [SCSS](https://sass-lang.com/documentation/syntax), as this is a really good practice of how to organize your CSS for different pages and features. I have been sticked to the basic level of Sass which is incementing efficiency re-using mixins, assigning variables, creating Partials and building nesting trees for a clear understanding on how/what my stylesheets mean. 

## Further clarification of Basics:

* Variables: Variables are used to store data, you may save whatever value would be needed (even units). They use $ sign to identify and assign.
![Screenshot 2020-12-28 at 14 24 36](https://user-images.githubusercontent.com/43299285/103217230-6c4d9a80-4918-11eb-9e9e-1481b4485683.png)

* Mixins: A mixin is a group of CSS declarations that can be reused for different reasons. You also can pass parameters to share themm all by element in your website.
![Screenshot 2020-12-28 at 14 22 24](https://user-images.githubusercontent.com/43299285/103217131-24c70e80-4918-11eb-8274-256635719b96.png)

* Partials: Contains CSS code specifically for a feature, page or sections. This makes CSS easy to maintain when you need to update or even fix any piece of CSS.
![Screenshot 2020-12-28 at 14 25 36](https://user-images.githubusercontent.com/43299285/103217303-90a97700-4918-11eb-88d9-ceb36b4d0a7f.png)

* Nesting: You will be able to nest your CSS code from parents to children adding styles ordering by hierarchy. & sign are very common when adding different selectors like Hover, Visited, etc...
![Screenshot 2020-12-28 at 14 30 01](https://user-images.githubusercontent.com/43299285/103217575-2e9d4180-4919-11eb-9c9a-1996909128d2.png)


## Installing
* Clone the project to your local directory.
* $git clone https://github.com/JoseMMorales/BootSass.git
* $cd BootSass.
* Right click on index.html file and select "Copy path".
* Open window browser and paste URL.

## Start Compiling Sass
* You will need to install [NodeJS](https://nodejs.org/en/download/) last version.
* Enter in terminal sass command *sass --watch scss:css* targeting directories to compile.
* Note!! Make sure you are inside of assets folder to give the right path when enter the command.
* Sass will create Custom and Source Map files for your when start compiling.

## Technology:
* HTML5
* Bootstrap 4
* Sass 2.10.3
* NodeJS 10.16.3
* JQuery 3.5.1

## Author
Jose MMorales