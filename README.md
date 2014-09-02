Android Snippets for Sublime
============================

These snippets are designed to make it quicker and easier to create Android apps using Sublime Text 2/3.

Avaliable Snippets
------------------
 - `ad-baseadapter` A stub BaseAdapter implementation which uses the [view holder pettern](http://developer.android.com/training/improving-layouts/smooth-scrolling.html#ViewHolder)
 - `ad-logdebug` Debug log with a message
 - `ad-widget` The basics needed to get started with creating a custom widget
 - `ad-toast` Create and display a toast
 - `<TextView` A basic TextView
 - `<EditText` A basic EditText 
 - `ad-assertOnScreen` Check that a view on on the screen
 - `ad-onActivityResult` The onActivityResult activity method
 - `ad-onCreate` The onCreate activity method
 - `ad-onDestroy` The onDestroy activity method
 - `ad-onPause` The onPause activity method
 - `ad-onResume` The onResume activity method
 - `ad-onStart` The onStart activity method
 - `ad-onStop` The onStop activity method

Recommended Installation
------------------------

The easiest way to install this is with [Package Control](http://wbond.net/sublime\_packages/package\_control).

* Make sure you've restarted Sublime if you've just installed Package Control.
* Bring up the Command Palette (`Cmd+Shift+P` on OS X, `Ctrl+Shift+P` on Linux & Windows).
* Select `Package Control: Install Package` (it will take a few seconds to load).
* Select `AndroidSnippets` when the list appears.

Package Control will automatically keep the plugin up to date with the latest version.

Other Installation Methods
--------------------------
**OSX**
```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone git://github.com/ribot/SublimeAndroidSnippets.git AndroidSnippets
```

**Linux (Ubuntu like distros)**
```bash
cd ~/.config/sublime-text-2/Packages/
git clone git://github.com/ribot/SublimeAndroidSnippets.git AndroidSnippets
```

**Windows 7**

Copy the directory to: `C:\Users\<username>\AppData\Roaming\Sublime Text 2\Packages`

**Windows XP**

Copy the directory to: `C:\Documents and Settings\<username>\Application Data\Sublime Text 2\Packages`
