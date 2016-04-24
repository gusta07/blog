#Blog

Taken from https://mackenziechild.me

The purpose was to get introduced to rails while building a personal website.


##Troubleshooting OSX
To run locally:

`rails s`

You might need to install the dependencies first:

`bundle install`

If you have issue like this "An error occurred while installing pg (0.18.4), and Bundler cannot continue." Do the following steps taken from [SO]:

- Install Xcode command line tools (Apple Developer site). If you have it already installed, update it using brew update.
- brew uninstall postgresql
- brew install postgresql
- gem install pg

##Login

`http://localhost:3000/users/sign_in`

   [SO]: <http://stackoverflow.com/questions/30162572/error-message-make-sure-that-gem-install-pg-v-0-18-1-succeeds-before-bundl>
