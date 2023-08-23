# ByeScreenTime
This .mobileconfig (iPhone/iPad/iPod profile) will disable screentime. This requires your device to be "fake supervised", which requires iMazing or to have iSupervisor (if jailbroken).
## This will NOT work without iDevice supervision!
iOS 12-14 tested only! I haven't had the opportunity to test this on iOS 15+, but it should work (I can confirm that iOS 16.0 works).


## Supervisor Mode using Cowabunga
1. Make sure you're on iOS 14-16.1.2 (Settings>General>About>iOS Version).
2. Sideload [Cowabunga](https://github.com/leminlimez/Cowabunga/releases/latest) using any method.
3. Go to the Tools tab inside Cowabunga and scroll to the bottom.
4. Click Miscellaneous and enable the Supervised option.
5. Restart your iPhone/iPad/iPod and you should see something like "This device is managed" in Settings.
6. You have successfully enabled Supervised Mode.
7. NOTE: Whenever you want to disable Supervised Mode, go back to Cowabunga and toggle the Supervised option off (restart your device after).

## Installation
1. Open [this link](https://raw.githubusercontent.com/singlekeycap/ByeScreenTime/master/ByeScreenTime.mobileconfig) in Safari.
2. Hit allow on the pop-up.
3. Go to Settings, and click on `Profile Downloaded`.
4. Hit install.
5. Profit.
