## Webhook Internet Presence theme

This is a simple theme for people that need an about.me style site with some light
blogging and a list of their appareances / events. Included are the sass files
if you wish to work directly with those files.

## Usage

1. After installing through Webhook close your local runserver.
2. Run `bower install`. This requires bower, which can be installed by running `npm install -g bower`.
3. Run `grunt copy` to copy the bower dependencies into `/static/`
4. Run `grunt sass` to build a css file.
5. Restart your runserver. Editing sass will rebuild css automatically.
