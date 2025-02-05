# ByeScreenTime
This .mobileconfig (iPhone/iPad/iPod profile) will disable screentime. This requires your device to be "fake supervised", which requires iMazing or to have iSupervisor (if jailbroken).
## This will NOT work without iDevice supervision!
iOS 12-14 tested only! I haven't had the opportunity to test this on iOS 15+, but it should work (I can confirm that iOS 16.0 works).


## Supervisor Mode using Cowabunga
1. Make sure you're on iOS 14-16.1.2 (Settings>General>About>iOS Version).

IMPORTANT: The MDC exploit that Cowabunga uses was patched on iOS 15.7.2 meaning you cannot use this if you're on iOS 15.7.8 but you can use it on iOS 16.0.

As of 8/26/2023 [there is a bug](https://twitter.com/LeminLimez/status/1694401088395342036) in Cowabunga that may brick your iDevice when you enable supervisor mode; either wait until the bug is fixed or continue with the tutorial.

2. Sideload [Cowabunga](https://github.com/leminlimez/Cowabunga/releases/latest) using any method.
3. Go to the Tools tab inside Cowabunga and scroll to the bottom.
4. Click Miscellaneous and enable the Supervised option.
5. Restart your iPhone/iPad/iPod and you should see something like "This device is managed" in Settings.
6. You have successfully enabled Supervised Mode.
7. NOTE: Whenever you want to disable Supervised Mode, go back to Cowabunga and toggle the Supervised option off (restart your device after).

## Supervisor Mode using iMazing

View guide on the [iMazing](https://imazing.com/guides/how-to-supervise-iphone-ipad) website.

## Installation
1. Open [this link](https://raw.githubusercontent.com/singlekeycap/ByeScreenTime/master/ByeScreenTime.mobileconfig) in Safari.
2. Hit allow on the pop-up.
3. Go to Settings, and click on `Profile Downloaded`.
4. Hit install.
5. Profit.
6. NOTE: After you're done you can disable Supervised Mode and the changes will stay (see screenshots).

## Permanently Disable Screen Time

After I used the profile for a few days, I noticed that sometimes it didn't work and I would still run out of screen time so I figured out how to permanently disable screen time.
1. After you have supervisor mode off, turn on airplane mode and remove the profile.
2. Go into Screen Time and set it up.
3. Make sure to not setup Screen Time as a parent.
4. Disable everything you want in the screen time settings and finally disable airplane mode.
5. If anything gets changed be sure to change them back.
6. You have successfully permanently disabled iOS Screen Time!

## Screenshots

<p float="left">
    <img src="https://github.com/ultimatechadguy/ByeScreenTime/blob/master/IMG_1920.PNG" width="400" />
    <img src="https://github.com/ultimatechadguy/ByeScreenTime/blob/master/IMG_1921.PNG" width="400" />
<p>
