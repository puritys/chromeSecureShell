# chromeSecureShell

I want to use chrome secure shell on Windows and Mac, but it doesn't satisfy my usual operation habits.
So I improved it by adding more options.

Auto login to SSH server: I add a new feature that can save the password in the local storage. It will automatically login in server without typing password.

Chinese typing:


# Demo Video
<a href="http://www.youtube.com/watch?v=HUN-UcVibOU" target="_blank">
  <img src="http://img.youtube.com/vi/HUN-UcVibOU/2.jpg">
</a>


# Options

The following are the new options that I added.

* meta-as-ctrl : Map the key command+v to be ctrl+v on Mac.
* ctrl-v-paste-hacky : Force the key ctrl+v to paste content from the clipboard.
* meta-plus-arrow-switch-tab :
* ctrl-plus-arrow-switch-tab :
* enable-input-method: Enable the ime-mode for typing chinese word. (使用方式為: 先勾選 enable-input-metod，然後在 Terminal 中點選遊標，這時遊標就會變成中空的樣式，就可以輸入中文。)

# Installation

* git clone git@github.com:puritys/chromeSecureShell.git
* Open the browser chrome and keyin the value "chrome://extensions/" into URL bar.
* Click the checkbox of developer mode to enable developer mode.
* Click the button "Load unpacked extension" and choose the directory "chromeSecureShell"
 

