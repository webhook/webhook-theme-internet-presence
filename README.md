## Webhook Internet Presence theme

This is a simple theme for people that need an about.me style site with some light
blogging and a list of their appareances / events. 

I've included are the sass files if you wish to work directly with those files rather than the css.
You'll need to do the following first though.

## Working with the source sass files

1. [Set up your `gruntfile.js` to compile sass](https://gist.github.com/snide/aa6e2196e220fed2df46#file-gistfile1-txt-L35). You'll also need to have sass installed and need grunt-contrib-sass and grunt-contrib-copy added to your package.json file.
3. Run `bower install`. This requires bower, which can be installed by running `npm install -g bower`.
4. Run `grunt copy` to copy the bower dependencies into `/static/`
5. Run `grunt sass` to build a css file.
6. Restart your runserver. Editing sass will rebuild css automatically on a normal `wh serve`.
