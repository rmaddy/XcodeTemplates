# XcodeTemplates
Xcode Templates

These templates can be used with Xcode 11.

To install, clone or download this repository. Then run the following command in a terminal from the `XcodeTemplates` folder:

    cp -R Templates ~/Library/Developer/Xcode/
    
That's it. Now run Xcode and create a new project using the new iOS template.

# Single View App (+ iOS12)

This template is based on the standard Single View App template from Xcode 11. This version creates a template that works with iOS 12 and later. It also lets you choose a User Interface based on either Storyboard or Code. The SwiftUI option has been dropped since if you are supporting iOS 12 (or earlier) you won't be using SwiftUI. Both Swift and Objective-C are supported.

The key differences in the resulting project are the addition of the `window` property in the AppDelegate which is needed for iOS 12. Several of the `UIApplicationDelegate` methods are added in support of iOS 12.

If you should the Code based user interface, the main storyboard is removed and code is added to both the AppDelegate and the SceneDelegate to create the main window as well as setup `ViewController` as the root view controller.
