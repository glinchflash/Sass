# Title: SASS:
live version [here](https://glinchflash.github.io/Sass/)

- Repository: `challenge-sass`
- Type of Challenge: `Learning Challenge`
- Duration: `1 day`
- Deployment strategy :
    - Github page

- Team challenge : `solo`

## Learning objectives
- Being able to explain what a CSS-Preprocessor is
- Generate some CSS from your CSS preprocessor (SASS)
- Being able to minify your CSS output
- Knowledge of the following SASS features:
    * Variables
    * Mixins (Functions)
    * Nesting
    * Partials & Import
    * Extend/Inheritance
    * Operators (Math)

## The Mission
You will learn more about SASS with the included index.html file, be sure to read it for more information.

Install Sass with the instructions found on https://sass-lang.com/install

After the installation type `sass -v` in the console, it should display the latest version.

If you are using Phpstorm, the moment you create a .scss file, it will offer you to manage SASS compilation for you, you can accept this. In PHPSTORM this is called a file watcher, you can always edit the settings in `file -> settings -> file watcher -> scss`.

If you are using another editor you have to run commands to watch the files

`sass --watch input.scss output.css (single file)`

`sass --watch app/sass:public/stylesheets (entire directory)`

### (Optional) Make Phpstorm write .css file to different directory
On default Phpstorm writes your CSS file to the same directory as your SCSS file.
In a bigger project you probably want to write your CSS files to a different directory like css/ to keep everything organised.

You can do that with the following changes in `file -> settings -> file watcher -> scss`:

* Arguments:    
  `--no-cache --update $FileName$:$ProjectFileDir$/css/$FileNameWithoutExtension$.css`

* Output path to refresh:
  `$ProjectFileDir$/css/$FileNameWithoutExtension$.css:$FileNameWithoutExtension$.css.map`

## Must-have features

Your mission is to rewrite the example.css to a scss file with the following changes:

### Part 1
- Make one mixin for the 3 lines of the box-shadow styling.

- Make the general padding the same everywhere with one variable. (red=16px, blue=8px), the footer h6 should have double the padding of the other elements. Use "operations" to do this. Do NOT hardcode the padding inside your scss.

- Nest the styling rules of grouped elements, like the sections in the Article.

- Make use of extend to re-use the same CSS for the "success", "error" and "warning" messages.


### Part 2 (optional)
- Add an option to your compilation to minify your stylesheet!
  Mine was below 1.6k, can you do better? Do you still remember the option to `ls` to make the filesize Human readable?
information about Sass assignment:
---
### useful links
https://github.com/becodeorg/ANT-Lamarr-6.35/tree/main/1.The-Field/html-css/SASS

installing sass:
https://sass-lang.com/install
https://github.com/sass/dart-sass/releases/tag/1.50.0

using phpstorm to compile .scss to css and minify file:
https://www.jetbrains.com/help/idea/2016.2/using-file-watchers.html

learning sass:
https://sass-lang.com/guide
---
 - [x]
### progess

* - [x] installed sass
* - [x] have mixin
* - [x] general padding
* - [x] nested styling rules
* - [x] used extend
* - [x] minify
---

### what I've learned

* - [x] basic sass
* - [x] partials
* - [x] importing different scss files to one big file to compile to css gaining a better overview over your code
* - [x] minify
---
