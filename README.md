# Specs
Private CocoaPods repository for staging AudioKit pod specs 

## How to use this repo

You can turn on this repo as a source in your project's Podfile. This will give your project bleeding-edge access to the latest development builds of AudioKit, as opposed to the mainstream releases posted on the regular CocoaPods specs.

Use the following lines near the top of your `Podfile`:

```
source 'https://github.com/AudioKit/Specs.git'
source 'https://github.com/CocoaPods/Specs.git'
```

You may comment out the first source line if you wish to stick to the mainstream releases. Once you update your sources, you will need to run either 'pod update' or 'pod install --repo-update' to update your repos.

New releases pushed to this spec repo are considered pre-release, and will not get picked up by CocoaPods automatically. You need to specify the version you want to use, like so:

```
pod 'AudioKit', '=4.4.0.b1'
```
