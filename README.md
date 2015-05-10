#Appium Configuration for MAC
##Install using Appium GUI
1. Install Appium GUI from [Appium](http://appium.io) Official WebSite 
2. For iOS install Command Line tool (Latest Version) and Xcode (Latest Version)
    1. DownLoad from [Develepor Apple WebSite](https://developer.apple.com)
3. Follow Instruction from Appium Documentation to install Android SDK. 
4. Android Configration for `~/.bash_profile` copy and paste below Configurations
    * User Configuration
    * `export ANDROID_HOME=/Users/jmatharu/Desktop/Drive/Applications/Eclipse\ Android/sdk`
    * `export ANT_HOME=/Users/jmatharu/Desktop/Drive/Applications/ant`
    * `export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_20.jdk/Contents/Home`
    * `export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$ANT_HOME/bin`
> Note:   
        * Change Path according to your Android SDK path in your MAC    
        * If you using [oh.my.zsh](http://ohmyz.sh), then you add above configuration to `.zshrc` file under your User folder. 
5. Run Appium Doctor to confirm there is no error in configuration for iOS and Android.
6. For the sample output there should be some thing like:    
    * `Running iOS Checks`    
    `✔ Xcode is installed at /Applications/Xcode.app/Contents/Developer`    
    `✔ Xcode Command Line Tools are installed.`    
    `✔ DevToolsSecurity is enabled.`    
    `✔ The Authorization DB is set up properly.`    
    `✔ Node binary found at /usr/local/bin/node`    
    `✔ iOS Checks were successful.`      
   
    * `Running Android Checks`    
    `✔ ANDROID_HOME is set to "/Users/jmatharu/Desktop/Drive/Applications/Eclipse Android/sdk"`    
    `✔ JAVA_HOME is set to "/Library/Java/JavaVirtualMachines/jdk1.8.0_20.jdk/Contents/Home."`    
    `✔ ADB exists at /Users/jmatharu/Desktop/Drive/Applications/Eclipse Android/sdk/platform-tools/adb`    
    `✔ Android exists at /Users/jmatharu/Desktop/Drive/Applications/Eclipse Android/sdk/tools/android`    
    `✔ Emulator exists at /Users/jmatharu/Desktop/Drive/Applications/Eclipse Android/sdk/tools/emulator`    
    `✔ Android Checks were successful.`      

    `✔ All Checks were successful`    




