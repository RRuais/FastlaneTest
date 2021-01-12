fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios printVersion
```
fastlane ios printVersion
```
Print the version and build
### ios bumpBuild
```
fastlane ios bumpBuild
```
Bump the build and push it to repo
### ios bumpVersion
```
fastlane ios bumpVersion
```
Bump the version and push it to repo
### ios tag
```
fastlane ios tag
```
Create a new tag and push it to repo
### ios releaseLatest
```
fastlane ios releaseLatest
```
Release Latest Tag
### ios archive
```
fastlane ios archive
```
Archive a new version at ./Build for in-house deployment



- Sanity Check - git status

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
