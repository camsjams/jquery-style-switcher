## jquery style switcher

Here is a jQuery plugin created to simplify style sheet theme changing.

It also allows users to preview the changes before clicking on their final choice. This plugin is tested for IE6+, Firefox, Safari, Chrome, Opera, and even Android and iPhones! 

* [Live Demo](http://camsjams.github.io/jquery-style-switcher/tests/)

## Status
Beta RC - Version 0.9.14

## Platforms / Technologies
* [JavaScript](http://en.wikipedia.org/wiki/JavaScript)
* [jQuery](http://api.jquery.com/)

## Usage

Here are the defaults options available in jQuery Style Switcher
>  		options = {
>  			hasPreview: true,
>			defaultThemeId: 'jssDefault',
>			fullPath: 'css/',
>			cookie: {
>				expires: 30,
>				isManagingLoad: true
>			}
>  		};

> hasPreview - when set to true, hover events on the theme lists will trigger a style change

> defaultThemeId - the document id of the default theme CSS file, will be replaced with the user selection

> fullPath - location to load the CSS file, can be a CDN or relative location

> cookie - setting this to null or false will disable cookies

> cookie.expires - set how long the user cookie will last (in seconds)

> cookie.isManagingLoad - set whether or not to use jQuery Style Switcher to load the CSS, as opposed to server-side checks
