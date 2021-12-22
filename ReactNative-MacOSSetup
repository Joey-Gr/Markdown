# **React Native for MacOS**

Before we begin. What is React Native? What will it help you with, and what purposes do they serve exactly?  
**To put it simply; React Native is an open-source framework used to develop cross-platform applications for Android and IOS.**

Using React Native, you can use Javascript to code applications for both Android and IOS, saving you the trouble of having to code your application in two different languages. For context, React Native adapts your javascript code into Native code for the user's Android or IOS device.

## React Native Setup

Do note however that there is a different alternative for setting up your React Native environment depending on the operating system you use.
The instructions are quite different for each development and target operating system.

Due to this, I will divide this explanation into 2 parts:

1. **Windows Operator**
2. **MacOS Operator**

In this tutorial, I shall introduce you to the following major steps you will need to take in order to set up your react-native environment. Starting with **MacOS** targetting the **IOS** platform

---

1. **Installation process**
2. **Device setup**
3. **Project creation**

---

### **The Installation Process**

You will need to first install node and npm. In this tutorial, we'll be using a Package Manager called "Homebrew" to install these packages.

Go to your MacOS terminal and type in :

```powershell
 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After Homebrew is installed, you'll now have an easier time installing other packages! For right now though, let's focus on the topic at hand, go ahead and install node and npm :

```powershell
 brew install node
 brew install watchman
```

To check if you've already installed something, you can get its current installed version :

```powershell
 brew -v
 node -v
 npm -v
```

After that, install react-native-cli :

```powershell
  npm install –g react-native-cli
```

You are now ready to get into coding with React Native !

### **Device Setup**

Now that you've got both node and npm. You should install Xcode (Last install I promise!). You can find a list of Xcode releases [Here](https://xcodereleases.com). Choose the one that has the latest most stable version for your MacOS version.  
In order to check what MacOS version you have, you must go to the "About This Mac" menu, as indicated below :

![About This Mac](/assets/img/mac-check1.jpg)
![Overview of Mac](/assets/img/mac-check2.jpg)

Start downloading your Xcode version, it's going to take a while...

Once you have Xcode installed and opened. Go to **Xcode > Preferences** and choose the latest simulator version (version 11x at least). Start downloading it.

You are now ready to run your simulator !

### **Project Creation**

Initiate a project anywhere in your project directory :

```powershell
  npx react-native init foo-app
  cd foo-app
```

Now, since we've set up our simulator, you can now run it here ! :

```powershell
  react-native run-ios
```

![Should see something like this](/assets/img/phones.png)

## **🎉 If everything went well, you should see it running on a simulator ! 🎉**

You may make any changes to the default program using your code editor of choice (Like [Visual Studio Code](https://code.visualstudio.com/) for example).
