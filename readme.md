# Develop Shopify Themes Locally


## Before You Start

1. Make sure you have ruby installed.
2. run `gem install shopify_theme` in your terminal.
3. Create a private app in your shopfy store. You should have an api key and an api password and the url for the store you just created.
4. Create a repo for the code in github.

## How To Get Started
1. Create a directory in the github repo. `mkdir <shopName>` and cd into it.
2. `theme configure <apiKey> <password> <storeDomain>`.<br/>
<br/>
For example:
`theme configure 07a8123d93bdd34982bd7b04a7984a2d aa3ef5ff9123a30b168a4464537057a7 my-store-name.myshopify.com`<br/>
<br/>
3. `theme download`
4. `touch .gitignore`
5. Add `/config.yml` to the first line of the git ignore file so that you don't upload your api credentials to github.
6. `theme watch`
7. Open your git hub repo in your favourite editor and your work should be saved directly to your store.

## Fantastic resources for Learning about Building Shopify Themes:

1. [Shopify Essentials for Web Developers](http://skl.sh/2aZxaLh) by [Kurt Elster](http://kurtelster.com/) (Free).
2. [Advanced Shopify Theme Development](http://skl.sh/2af36y8) by [Gavin Ballard](http://gavinballard.com/) (Free).
