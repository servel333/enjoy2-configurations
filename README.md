enjoy2-configurations
---------------------

Configurations for the OS X application [Enjoy2](https://github.com/fyhuang/enjoy2).

# Quick start

* Install Enjoy2
* Open iTerm
* `cd /Users/$(whoami)/Library/Application Support/Enjoy2`
* `git clone git@github.com:servel333/enjoy2-configurations.git`

# Contributing

* Fork this repo in Github
* `git remote add downstream git@github.com:$GITHUB_USERNAME/enjoy2-configurations.git`
* `git add .`
* `git commit -m "DESCRIBE THE CHANGE"`
* `git push downstream master`
* Create a pull request with your change

## Notes

* Please design your configuration to work with the default game keyboard/mouse conguration for the application.
* If you have a new configuration for an application that already has a config, please add a number to the end of the filename, or add a dash and put a description of what's different.
  * For example, if you have a new "Risk of Rain" config, name the configuration "Risk of Rain2"
  * Or, you can name your config "Minecraft - Inverted Y Axis"
