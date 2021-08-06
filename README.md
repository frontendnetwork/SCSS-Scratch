# SCSS Scratch
SCSS Scratch is a Barebones-Structure/starting-point for bigger SASS-projects. 

## Instructions

Clone this repository with:

    gh repo clone jokenetwork/FT-Bootstrap-Theme

or via HTTPS:

    gh repo clone jokenetwork/FT-Bootstrap-Theme

## Usage
Download the repository and import it into your SASS-Processor (*I'd reccommend PrePros*). 


### _globals

In the `style.scss`-file, you'll find the follwoing config:


    // Import barebones scss structure
    @import '_globals/reset', '_globals/mixins', '_globals/utilities', '_globals/variables', '_globals/colors', '_globals/fonts';

This includes an up-to-date version of `normalize.css` (`_globals/reset.scss`), mixins and functions (e.g. rem-calculation) (`_globals/mixins.scss`), utilities from `barebones.scss` (`_globals/utilities.scss`) and documents for variables, colors and fonts which are set for the whole page.

### Flexbox Grid 

If you need a flexbox-grid, you can uncomment the follwoing line:

    // @import '_globals/grid';


### Main Styles
Do your main styling in the `main.scss`-file. It it imported with:

    @import "main";

### Shame
For anything quick and dirty, which will be cleaned up later, you can use the `shame.scss` stylesheet. It it imported with:

    @import "shame"
   
### _modules
In `/_modules/mod-logo.scss` you'll find a file, which can be used as an example for how the included mixins and utilities are used.
Please remove this file before processing.

