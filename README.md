<div align="center">
<img src="https://user-images.githubusercontent.com/4144601/221711881-b558edd8-a673-4472-aa7c-5b3570904e48.svg" alt="SCSS Scratch Logo" width="128">

# SCSS Scratch

SCSS Scratch is a barebones structure/starting-point for SCSS-projects.

<p align="center">
 <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch?ref=badge_small" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch.svg?type=small"/></a>
	<a href="https://jokenetwork.de/badges"><img alt="Status: Active" src="https://jokenetwork.de/assets/img/gitstatus/active.svg"></a>
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch?ref=badge_shield" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FJokeNetwork%2FSCSS-Scratch.svg?type=shield"/></a>
	<a href="https://www.codacy.com/gh/JokeNetwork/SCSS-Scratch/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=JokeNetwork/SCSS-Scratch&amp;utm_campaign=Badge_Grade"><img src="https://app.codacy.com/project/badge/Grade/2f8a039d854a4a3ca857ecede388bfea"/></a>
	<a href="https://github.com/sponsors/philipbrembeck"><img src="https://img.shields.io/badge/Sponsor-white.svg?logo=githubsponsors" alt="Consider Sponsoring"></a>
	<a href="https://www.paypal.com/donate?hosted_button_id=N4F7DAQH7ET2G"><img src="https://img.shields.io/badge/Donate-blue.svg?logo=paypal" alt="Donate"></a>
  </p>
  
<br />

<picture>
	  <source srcset="https://user-images.githubusercontent.com/4144601/221714394-7c6f7652-c91f-4aed-93c3-af94c6137492.png" media="(prefers-color-scheme: dark)">
	  <img src="https://user-images.githubusercontent.com/4144601/221714387-fdeaf704-a056-4d39-9850-e260f4246f7c.png" alt="Screenshot of style.scss">
	</picture>
</div>

## 👨🏼‍💻 Usage
### Installation 
Download the repository and import it into your SASS-Processor or clone it:

````bash
git clone https://github.com/JokeNetwork/SCSS-Scratch
````
Then run:
````bash
npm install 
````

You're good to go now!

### Structure

#### _globals

In the `style.scss`-file, you'll find the following config:

````scss
@use "node_modules/minireset.css/minireset";
@use '_globals/mixins';
@use '_globals/utilities' as *;
@use '_globals/variables' as *;
@use '_globals/colors';
@use '_globals/fonts';
@use "main";
@use "shame";
```` 

This includes a version of [`minireset.css`](https://github.com/jgthms/minireset.css), mixins and functions (e.g. rem-calculation) (`_globals/mixins.scss`), utilities of `barebones.scss` (`_globals/utilities.scss`) and documents for variables, colors and fonts which are set for the whole page.


#### Flexbox Grid 

If you need a flexbox-grid, you can uncomment the follwoing line:

````css
// @use '_globals/grid';
````

###ä Main Styles
Do your main styling in the `main.scss`-file. It it imported with:

````css
@use "main";
````

#### Shame
For anything quick and dirty, which will be cleaned up later, you can use the `shame.scss` stylesheet. It it imported with:

````css
@use "shame"
```` 
   
#### _modules
In `/_modules/mod-logo.scss` you'll find a file which can be used as an example for how the included mixins and utilities are used.
Please remove this file before processing.

## 👩‍⚖️ License

All text and code in this repository is licensed under [WTFPL](https://github.com/JokeNetwork/SCSS-Scratch/blob/master/LICENSE).

## 🤝 Credits 

* Maintained by [@jokenetwork](https://github.com/jokenetwork) ([JokeNetwork.de](https://jokenetwork.de)) 
* Created by [@philipbrembeck](https://github.com/philipbrembeck)
* This is a fork & recreation of [barebones](https://github.com/nothingrandom/barebones)
