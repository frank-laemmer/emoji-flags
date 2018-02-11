# Emoji Flags

This is a little fun (S)CSS snippet for a poor mans emoji flag icons.

## Usage

Link or include the `emoji-flags.css` file somehow in your project. Then define a container with a `flag-[COUNTRY]` class, where country is the two letter code (ISO 3166-1 alpha-2) of a country, there are 112 of them:

``
<span class="flag-de"></span>
``

To get this result: 🇩🇪

## Why use it?

You are two lazy to compose the emoji-unicode in the markup yourself and prefer to deal with standard letters. No graphic files are getting harmed for this. 

## Built

```
# Installs the node-sass compiler
$ npm install

# Runs the node-sass compiler on the emoji-flags.scss file
$ npm run scss
```

## Limits

* No Ubuntu support (yet) 
* Different looks on different OS
* Emoji country flags are not looking so great when small sized