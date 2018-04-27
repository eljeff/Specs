# Specs
Private CocoaPods repository for staging AudioKit pod specs 

## How to use this repo

You can turn on this repo as a source in your project's Podfile. This will give your project bleeding-edge access to the latest development builds of AudioKit, as opposed to the mainstream releases posted on the regular CocoaPods specs.

Use the following lines near the top of your `Podfile`:

```
source 'https://github.com/AudioKit/Specs.git'
source 'https://github.com/CocoaPods/Specs.git'
```

You may comment out the first source line if you wish to revert to the mainstream releases.
