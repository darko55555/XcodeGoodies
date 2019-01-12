# XcodeGoodies
Some scripts to help you use Xcode more efficiently.

Two scripts, good one and the awesome one.

1. Open terminal from Xcode - good one
2. Install pods from Xcode - awesome one

## How to install
1. Add scripts to any folder
2. Go to terminal in that folder write `chmod +x installPodsFromXcode.sh` . Same goes for the other script, just change the name. This gives the scripts the execution rights.
3. Go to Xcode, Preferences, Behaviours. On the bottom click plus and add a new one, name it as you want and add a shortcut for it. Select the script that should be ran. 
4. Done

## Use case

You're in Xcode and you need a new pod
	1. Click on your podfile and write your new dependency, save
	2. Hit your shortcut and it runs terminal and pod install
	3. Wow!
