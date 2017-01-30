# Liftoff Templates

Templates for [liftoff](https://github.com/thoughtbot/liftoff), CLI for creating and configuring new Xcode projects.

## Usage

Copy `templates` folder and `liftoffrc` configuration file into tool directory (check information about installed tool by `brew info liftoff` command). Configuration file contains two templates - for Objective-C and Swift projects. Run `liftoff` command in needed directory. It will make project with default Objective-C template. To generate Swift project use `template` option, for example:
>`liftoff --template swift`

## Features

- Templates for Objective-C and Swift projects
- Custom project structure
- Automatic installation of Cocoapods/Carthage dependencies (Cocoapods by default)
- Prefixes for all classes (without boring renaming of `AppDelegate` classes)
- Script for showing TODO's and FIXME's as warnings

## Author

Artem Novichkov, novichkoff93@gmail.com

## License

Liftoff Templates is available under the MIT license. See the LICENSE file for more info.
