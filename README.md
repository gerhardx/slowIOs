# App demo slowIOs
- Repo with code demonstrating slow iOS for Ionic 2.
- App generated with `ionic start slowIOS --v2`
- Then added login component and changed rootPage

## System
- Compiled on macbook pro with OSX Sierra beta 4 with xcode 7.3.1 and 8 beta 4.
- Android Studio 2.1.2
- Ionic 2.0.0-beta.32

## Testing
A simple test of blank tabs project. Just added another view with login button to emulate login (No validation, direct view change).
Here demo when clicked login button, but also happens with side menu, and general views navigation.

## Tested Devices
*Builded and deployed to devices:*
- **Android 4.4: Lanix Ilium PAD i7** Slow with default settings. Works great with crosswalk
- **Android 5.0: LG G3** Works great with default settings
- **IOS (from 8 to 9.3.3): Iphone 4s, Ipad mini 2, Ipad 3, Iphone 6s** Slow to response of view changes

## Results
As reported in testing.
*Just clicked the button once and released, no holding. Button click  can be noticed in the **ripple effect** for android, and **darker color** in ios.*
For better demostration links of youtube screencast here:

- [Android]: No problem, as seen when clicked login, changes view within a second.
- [IOS]: On Iphone 4s takes almost 4 seconds, on Iphone 6s almost 3.

[Android]: https://youtu.be/6wqFSKUyddA

[IOS]: https://youtu.be/r7uqpYsAueE
