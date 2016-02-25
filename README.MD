## Installation

```
cordova plugin add cordova-android-fragments
``` 

## Usage

Replace MainActivity in AndroidManifest.xml to "com.webileapps.fragments.MainActivity" and launch your application. 

## How it works

This plugin comes bundled with a CordovaFragment (which is a Fragment similar to CordovaActivity) and a MainActivity that extends AppCompatActivity and adds CordovaFragment using FragmentTransactions.  

## TODO

Create a hook that replaces activity name in AndroidManifesh.xml to launch MainActivity.java in our source directory