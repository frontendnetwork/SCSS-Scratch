<p align="center">
 <h1 align="center">SCSS Scratch</h1>
 <p align="center">SCSS Scratch is a barebones structure/starting-point for SCSS/SASS-projects. </p>
</p>
  <p align="center">
 <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch?ref=badge_small" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch.svg?type=small"/></a>
	<a href="https://jokenetwork.de/badges"><img alt="Status: Active" src="https://jokenetwork.de/assets/img/gitstatus/inactive.svg"></a>
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch?ref=badge_shield" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch.svg?type=shield"/></a>
	<a href="https://www.codacy.com/gh/JokeNetwork/SCSS-Scratch/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=JokeNetwork/SCSS-Scratch&amp;utm_campaign=Badge_Grade"><img src="https://app.codacy.com/project/badge/Grade/2f8a039d854a4a3ca857ecede388bfea"/></a>
	<a href="https://github.com/sponsors/philipbrembeck"><img src="https://img.shields.io/badge/Sponsor-white.svg?logo=githubsponsors" alt="Consider Sponsoring"></a>
	<a href="https://www.paypal.com/donate?hosted_button_id=N4F7DAQH7ET2G"><img src="https://img.shields.io/badge/Donate-blue.svg?logo=paypal" alt="Donate"></a>
  </p>
 
    
## 👨🏼‍💻 Usage
Download the repository and import it into your SASS-Processor or clone it:

    git clone https://github.com/JokeNetwork/FT-Bootstrap-Theme.git


### _globals

In the `style.scss`-file, you'll find the following config:

````css
// Import barebones scss structure
@import '_globals/reset', '_globals/mixins', '_globals/utilities', '_globals/variables', '_globals/colors', '_globals/fonts';
```` 

This includes an up-to-date version of [`normalize.css`](https://necolas.github.io/normalize.css/) (`_globals/reset.scss`), mixins and functions (e.g. rem-calculation) (`_globals/mixins.scss`), utilities of `barebones.scss` (`_globals/utilities.scss`) and documents for variables, colors and fonts which are set for the whole page.

### Flexbox Grid 

If you need a flexbox-grid, you can uncomment the follwoing line:

````css
// @import '_globals/grid';
````

### Main Styles
Do your main styling in the `main.scss`-file. It it imported with:

````css
@import "main";
````

### Shame
For anything quick and dirty, which will be cleaned up later, you can use the `shame.scss` stylesheet. It it imported with:

````css
@import "shame"
```` 
   
### _modules
In `/_modules/mod-logo.scss` you'll find a file, which can be used as an example for how the included mixins and utilities are used.
Please remove this file before processing.

## 👩‍⚖️ License

All text and code in this repository is licensed under [WTFPL](https://github.com/JokeNetwork/SCSS-Scratch/blob/master/LICENSE) (Excluding the below mentioned `normalize.css`, licensed under MIT!).

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch?ref=badge_large)

## 🤝 Credits 

* Maintained by [@jokenetwork](https://github.com/jokenetwork) ([JokeNetwork.de](https://jokenetwork.de)) 
* Created by [@philipbrembeck](https://github.com/philipbrembeck)
* This repo includes the following open-source projects:
	* [Normalize.css](https://necolas.github.io/normalize.css/)
	* This is a fork & recreation of [barebones](https://github.com/nothingrandom/barebones)
