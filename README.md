# StarryStars

StarryStars is iOS GUI library for displaying and editing ratings

## Features
StarryStars' ```RatingView``` is both ```IBDesignable``` and ```IBInspectable```

You can change any of the following properties right in the interface builder:
![Properties](https://i.imgflip.com/df525.gif)

And the the result right away:
![RatingView](http://i.imgur.com/r3bMqDT.png)

To add RatingView to your Storyboard/.xib file just drag a generic UIView from palette, then in "Custom Class" section of identity inspector set class to ```RatingView```

## Installation

### Manual
Just clone and add ```StarryStars``` directory to your project.

### Cocoapods
- Make sure that you use latest stable Cocoapods version: `pod --version`
- If not, update it: `sudo gem install cocoapods`
- `pod init` in you project root dir
- `nano Podfile`, add:

```
pod 'StarryStars', '~> 0.0.1'
use_frameworks! 
``` 
- Save it: `ctrl-x`, `y`, `enter`
- `pod update`
- Open generated `.xcworkspace`
- Don't forget to import StarryStars: `import StarryStars`!

## Requirements

- iOS 7.0+ (8.0+ if you use Cocoapods)
- Xcode 7.0
- Swift 2.0