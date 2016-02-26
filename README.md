# Visionary Password Manager

Conventional password managers have many flaws. They work by generating passwords, encrypting them with a master password, and then storing or syncing the encrypted passwords somewhere.

There are a few problems with this approach:

1. The encrypted data can be lost, thereby locking the user out of all of their accounts.
2. The encrypted data can be stolen. If the user was using a weak master password, all of their accounts can be compromised.
3. The data can only be synced to a limited number of devices.

**Visionary Password Manager** improves on these shortcomings considerably:

1. Your passwords are generated on-the-fly based on a pure algorithm. This means that the only thing that would make you lose your data is you forgetting your master password.
2. Nothing is stored so there's nothing to steal.
3. There are thousands of iterations of Scrypt, making brute-forcing infeasible.
4. No need to sync data, as there's nothing to sync! You can use this script or our API **(coming soon)** from anywhere in the world, and from any device, to generate your passwords.

##Installation:

####*Compatable with Python2 only*

###Option 1: pip

**Install using pip in order to get the latest stable release.**

`~ >> pip install visionarypm`

or

`~ >> python -m pip install visionarypm`

###Option 2: git clone

**Install using git to be at the bleeding edge. You'll receive the latest commit.**

```
~ >> git clone https://github.com/libeclipse/visionary.git
~ >> cd visionary
~ >> python setup.py install
```

##Usage:

Just run:

`~ >> visionarypm`

in your command line. You will be prompted for a master password (minimum 8 characters). This is what protects all of your generated passwords so make it a strong one. Next, you'll be prompted for a keyword. This can be anything, like 'github.com' or 'facebook' or even 'not_porn' for that special folder.

A 32 character password will be generated based on what you entered. You'll then be prompted for another keyword to optionally generate another password. Leave it blank to exit.

###Screenshot:

![Screenshot](https://github.com/libeclipse/visionary/blob/master/images/screenshot.png "Screenshot")

[![forthebadge](http://forthebadge.com/images/badges/built-with-swag.svg)](http://forthebadge.com)

**Support development by donating ฿itcoins: 1ECLipSrTyitXJbeNBZVRMcRHp94HryZkj**
