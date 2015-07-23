# Meteor's Actual ESLint Configuration

http://github.com/iDoMeteor/eslint-config-meteor-official
v0.0.1

# Installation & Usage

This version is meant for installation via NPM.  To get the .eslintrc which
you would use with your editor or by dropping into a project is located in
[the Meteor source code](https://github.com/meteor/meteor/).

To install this via NPM:

>$ npm install -g eslint-config-meteor-official

To use it, create a .eslintrc with the following in it (or add to your existing,
not sure how that will go for you tho :>):

  {
    "extends": "meteor-official"
  }

* Note, Meteor has an extensive .eslintignore in the root of their source, if
you intend to use this on Meteor source, you may be interested in that.

## Summary

Since I packaged up my own Meteor ESLint config based on Meteor's idealistic
configuration, and then tuned it to my liking, I figured I should provide the
one they are actually using.  People seem to ask for it around the web, but it
is, strike that - was buried in the source code.

I hereby bring it to light for your linting pleasure.  I will keep it up to
date.

You can install my personal config with npm install -g eslint-config-meteor
and view it @ http://github.com/iDoMeteor/eslint-config-meteor where you
will also find a thorough description.


@iDoMeteor

P.S. I published these packages about 10 minutes before I found the naming
convention rules for NPM.  I assumed it would be more like Meteor.  Had I
known, I would have named them slightly differently.  If anyone from MDG
wants to take one or both of them over, let me know!
