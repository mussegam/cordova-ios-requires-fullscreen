# cordova-ios-requires-fullscreen

`cordova plugin add https://github.com/mussegam/cordova-ios-requires-fullscreen.git`

It will add the following part to the `*-Info.plist` file during build process:

    <key>UIRequiresFullScreen</key>
    <true />
    <key>UIStatusBarHidden</key>
    <true/>
    <key>UIViewControllerBasedStatusBarAppearance</key>
    <false/>
