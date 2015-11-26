#WIP not stable yet.

#TIRAMPaperSwitch

This project is a Titanium Wrap of the Objective-C port of [RAMPaperSwitch](https://github.com/lucaji/paper-switch-ObjC).

This project subclasses UISwitch which paints over the parent view with the `onTintColor` when the switch is turned on.

Credit for the original swift implementation goes to [Ramotion](http://ramotion.com?utm_source=gthb&utm_medium=special&utm_campaign=paper-switch).


#Screenshot
![PaperSwitch](screenshot.gif)


## Requirements

- iOS 8.0+
- Xcode 6.1+


#Installation

Grab the zip file from dist and unzip it in the Titanium project.

# Get it on gittio

```
$ gittio install TIRAMPaperSwitch
```


#Usage
TIRAMPaperSwitch is a drop-in replacement of UISwitch. You just need to set the `onTintColor` property of the switch, and it will automatically _paint over_ its superview with the selected color.
You have ability to set duration of animation instead of default value.

(more instructions on this in a second)
