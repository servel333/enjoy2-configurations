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

* When you make changes, make sure to completely exit Enjoy2. It doesn't update configs until exit.
* Please name your files as `Controller name - Application name - Alternative name`
  * `Alternative name`: This is optional and is a place to put a note like `Inverted Y Axis`
* Please design your configuration to work with the default keyboard/mouse conguration for the application.

## Standard configurations

```
     _________                                _________
    /  _____  \                              /  _____  \
   /  /     |  \____________________________/  |     \  \
  /  /  7   |                                  |   8  \  \
 |  |_______|                                  |_______|  |
 |   _______                                    _______   |
 |  |   5   |                                  |   6   |  |
 |  |_______|    ___________________________   |_______|  |
  \_____________/                           \____________/



          5                                      6
       _=====_                                _=====_
      / _____ \                              / _____ \
    +.-'_____'-.----------------------------.-'_____'-.+
   /   |     |  '.    __            __    .'  |  _  |   \
  / ___| /|\ |___ \  | 9|          |10|  / ___| (4) |___ \
 / |      |      | ;      Logitech      ; | _         _ | ;
 | | <---   ---> | |  ____              | |(1)       (3)| |
 | |___   |   ___| ; |MODE|             ; |___   _   ___| ;
 |\    | \|/ |    /  _               _   \    | (2) |    /|
 | \   |_____|  .','" "',         ,'" "', '.  |_____|  .' |
 |  '-.______.-' /       \       /       \  '-._____.-'   |
 |               |  11   |-------|  12   |                |
 |              /\       /       \       /\               |
 |             /  '.___.'         '.___.'  \              |
 |            /                             \             |
  \          /                               \           /
   \________/                                 \_________/
                  Logitech Dual Action
```

### First person standard controls

Based on the [Halo Controls](http://halo.wikia.com/wiki/Halo_Controls)

```
+---------------+--------------------+---------------------------+
| Dual Action   | XBox Controller    | Action                    |
+---------------+--------------------+---------------------------+
| 2             | A                  | Jump                      |
| 3             | B                  | Melee attack              |
| 1             | X                  | Reload weapon/Action      |
| 4             | Y                  | Switch weapons            |
|          Left Analog               | Movement                  |
| 11            | Left Analog Click  | Crouch                    |
|          Right Analog              | Camera                    |
| 12            | Right Analog Click | Zoom                      |
| 6             | Right Trigger      | Fire primary weapon       |
| 5             | Left Trigger       | Throw grenade             |
| 10            | "Start" Button     | Pause game                |
|               | Directional Pad    | Menu navigation           |
+---------------+--------------------+---------------------------+
```
