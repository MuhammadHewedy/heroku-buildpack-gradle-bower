Heroku buildpack: Gradle + Bower (and more npm tech)
=========================

Only installs node, npm and bower and gradle task (which understand the structure of the project structure) will do the build

I usually use this https://github.com/srs/gradle-node-plugin as a gradle plugin to run node staff.

So this buildpack prepare the tools that this plugin will use (node, npm and bower)
