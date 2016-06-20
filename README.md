# chromeSecureShell

I want to use chrome secure shell on Windows and Mac, but it doesn't satisfy my usual operatic habits.
So I improved it by adding more options.

1. Automatically login to SSH server: I add a new feature that can save the password in the local storage. It will automatically login in server without typing password.

2. Chinese characters typing:


# Demo Video
<a href="http://www.youtube.com/watch?v=6wygEEF8mDc" target="_blank">
  <img src="http://img.youtube.com/vi/6wygEEF8mDc/2.jpg">
</a>


# Options

The following are the new options that I added.

* meta-as-ctrl : Map the key command+v to ctrl+v on Mac.
* ctrl-v-paste-hacky : Force the key ctrl+v to paste content from the clipboard.
* meta-plus-arrow-switch-tab :
* ctrl-plus-arrow-switch-tab :
* enable-input-method: Enable the ime-mode for entering chinese characters. (使用方式為: 先勾選 enable-input-metod，然後在 Terminal 中輸入中文。)

# How to install

* git clone git@github.com:puritys/chromeSecureShell.git
* Open the browser chrome and keyin the value "chrome://extensions/" into URL bar.
* Click the checkbox of developer mode to enable developer mode.
* Click the button "Load unpacked extension" and choose the directory "chromeSecureShell"
 

