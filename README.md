# Liftoff Templates

Templates for [liftoff](https://github.com/thoughtbot/liftoff), CLI for creating and configuring new Xcode projects.

## Usage

1. [Install](https://github.com/thoughtbot/liftoff#installation) liftoff
2. Copy `templates` folder and `liftoffrc` configuration file into tool directory (check information about installed tool by `brew info liftoff` command). Configuration file contains two templates - for Swift and Objective-C projects. 
3. Run `liftoff` command in needed directory. It will make a project with default Swift template. To generate Objective-C project use `template` option, for example:
```bash
$ liftoff --template objc
```

## Features

- Templates for Swift and Objective-C projects
- Custom project structure
- Automatic installation of Cocoapods/Carthage dependencies (Carthage by default)
- Prefixes for all classes (without boring renaming of `AppDelegate` classes)
- [SwiftLint](https://github.com/realm/SwiftLint) Build Phases script

## Knowing Issues
- "Convert to Current Swift Syntax" warning. Just update project. It's liftoff issue.
- [Update to recommended settings](https://github.com/thoughtbot/liftoff/issues/266) warning

## Author

Artem Novichkov, novichkoff93@gmail.com

## License

Liftoff Templates is available under the MIT license. See the LICENSE file for more info.
