# BeCode Learning Challenge: SASS #
[Exercise Repository](https://github.com/becodeorg/ANT-Lamarr-6.35/tree/main/1.The-Field/html-css/SASS)
## Exercise objectives ##
- [X] Being able to explain what a CSS-Preprocessor is
- [X] Generate some CSS from your CSS preprocessor (SASS)
- [X] Being able to minify your CSS output
- [X] Knowledge of the following SASS features:
   - Variables
   - Mixins (Functions)
   - Nesting
   - Partials & Import
   - Extend/Inheritance
   - Operators(Math)
### Objective Learning Sources: ###
- [CSS Preprocessor explanatory article](https://www.template.net/tutorials/css-preprocessor/)
- [SASS 20' Explanatory video](https://www.youtube.com/watch?v=Zz6eOVaaelI)
- [W3Schools - SASS](https://www.w3schools.com/sass/)

#### Objective Notes ####
- CSS Preprocessor
  - A language created to make CSS more powerfull with the option to compile into CSS so it's understandable for browsers
- Generate CSS from a CSS preprocessor (SASS)
  - Used Live SASS compiler in VS Code
  - Can Also be done trough the SASS command line
- Be able to minify your css output
  - Using css-minify from the command line
  - various websites will help here as well
- Knowledge of following SASS features:
  - Variables
    - Begin with $
    - Holds properties to reduce repetition
    - Can only hold **one** value at a time!!!
    - Can be declared anywhere 
    - they are imperative
      - Only elements using the variable after the change will be affected by it
    - SASS variables are not included in the CSS output :D
  - Mixins (Functions) 
    - Work like functions
    - Can hold multiple properties
    - declared with @mixin
    - Called with @include
    - Can make use of custom parameters
      - Can Add Default values in following syntax
        - "@mixin example($var: default){property:$var}
  - Extension
    - @extend NAME
    - Can inherit styles from other elements
    - added properties will overwrite the extension for the current element
  - Calculations
    - Use Calc() to avoid compilation issues
    - Can use following operators:
      - '+' , '-' , '*' , '/'
## Exercise ##
- [X] Rewrite the example css into a SCSS file
  - [X] Make one mixin for the 3 lines of the box-shadow styling.
  - [X] Make the general padding the same everywhere with one variable.
    - [X] Red = 16px
    - [X] Blue = 8px
    - [X] Footer H6 should have double the padding of the other elements
    - **NO HARDCODED PADDING**
  - [X] Nest Styling Rules of grouped elements.
    - Like the sections in the article
- [X] Make use of extend to re-use the same CSS for following messages:
    - success
    - error
    - warning
- [ ] Add an option to the compilation to minify the stylesheet
### Project Log ###
1. Creation of basic file structure
        - Added Example HTML File to index.html
        - Added Example CSS file into examplestylesheet.css
        - Creating of README.md for future reference


#### Exercise Tools ####
- [SASS installation](https://sass-lang.com/install)
- [Live SASS Compiler VScode](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
- [CSS-Minify Command Line Tool](https://10minute.tech/minify-css-and-js-files-from-the-terminal/)
