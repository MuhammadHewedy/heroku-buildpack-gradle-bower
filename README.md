Heroku buildpack: Gradle + Bower (and more npm tech)
=========================

Only installs node, npm and bower and gradle task (which understand the structure of the project structure) will do the build

I usually use this https://github.com/srs/gradle-node-plugin as a gradle plugin to run node staff.

So this buildpack prepare the tools that this plugin will use (node, npm and bower)

Example application uses this buildpack: https://github.com/MuhammadHewedy/weekly-grocery
And it is deployed to herouku at https://weeklygrocery.herokuapp.com/

It is a spring boot application, but your application doesn't require to be, just gradle app that know how to uses the `node`, `npm` and `bower` that the buildpack installs
