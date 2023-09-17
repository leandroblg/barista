# Barista
A java version selector facilitator for MacOS.

TODO: (Really) improve this readme.
## Setup
You must add it to PATH add add the following lines to your .zshrc (or .bashrc)
```
export JAVA_HOME=`exec $(barista the-usual)`
```
Then just run the 'barista' script.


## Instructions
1. You should install JDKs as usual, with homebrew for example. (Tested with semeru and temurin).
2. List all available options with `barista list`
3. Choose one option and set the version number with
`barista use <version>`.
For example, assuming Java 11 being available, run `barista use 11`.
4. If you want to the change is applied to your current terminal session, run the output to set JAVA_HOME.

## Contribution
Feel free to contribute!

## License
MIT