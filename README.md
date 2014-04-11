tmpww-tokens
============

> Repository for SeoAdmin tokens with sample data. These tokens are meant to be used with the [tmpww Yo generator](https://github.com/sethlopezme/generator-tmpww).

## Getting Started
This repo includes all of the tokens used within SeoAdmin. Currently, most tokens have already been filled with sample data, but there are still a few left that we are working to fill. Feel free to modify the tokens as you see fit for your TalentBrew.

### Installation

#### Note
__The tmpww Yo generator will automatically pull this repo in. You do not need to pull this repo down manually if you are using the [tmpww Yo generator](https://github.com/sethlopezme/generator-tmpww).__

In order to manually pull these tokens down, run this Git command in your shell:

```shell
git clone https://github.com/sethlopezme/tmpww-tokens.git
```

## Using the Tokens
Inside your project, the tokenization is automatically taken care of by Grunt. __Grunt will only tokenize HTML files with the extension `.pre.html` (`index.pre.html`, for instance)__, and will save the tokenized versions as normal `.html` files.

Inside your `.pre.html` files, you can use the tokens as you would within SeoAdmin. Remember, token the tokens will only populate sample data. They are in no way linked to SeoAdmin.

## Modifying the Tokens
Tokens are just normal HTML files with the extension `.token.html`. They can be modified with whatever editor you're comfortable with.

The tokens can be found inside the `tmpww-tokens` folder and they are split up by page-scope.

## Release History
* 2014-04-11        v0.0.2        Filled most tokens with sample data, and unified the file structure.
* 2014-04-09        v0.0.1        Created `.token.html` files for all tokens available within
                                  SeoAdmin. Very few have been filled with sample data.