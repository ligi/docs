Setting up your TREZOR device
=============================

TREZOR works with almost any computer that has a USB port or with Android devices with USB Host support.

There are four options to make TREZOR communicate with `TREZOR Wallet <https://wallet.trezor.io>`_.

1. TREZOR Bridge
--------------------------

To allow TREZOR to communicate with `TREZOR Wallet <https://wallet.trezor.io>`_ you need to install a piece of software called TREZOR Bridge.  When you go to `TREZOR Wallet <https://wallet.trezor.io>`_ website you will see a page with a Download link.  Download the TREZOR bridge and follow the instructions on the screen.

2. TREZOR Chrome extension
--------------------------

An alternative to TREZOR Bridge is TREZOR Chrome extension. `TREZOR Chrome extension <https://chrome.google.com/webstore/detail/jcjjhjgimijdkoamemaghajlhegmoclj>`_ can be used across platforms, however only with Chrome-based browsers. Linux users need to perform additional configuration of their system. For more details, please see :doc:`Setting up Chrome extension on Linux <settingupchromeonlinux>`. After you successfully install the extension, please open the `Apps tab <chrome://apps/>`_ and double click on the TREZOR Extension.

.. note:: There is still a possibility to download the  `Chrome extension <https://chrome.google.com/webstore/detail/jcjjhjgimijdkoamemaghajlhegmoclj>`_, which works on all platforms. However, Google is planning to end its support for Chrome apps. As a result, this solution will not be available when that happens.

Once you've got the TREZOR Bridge or TREZOR Chrome extension installed, go to `TREZOR Wallet <https://wallet.trezor.io>`_ again.


3. TREZOR Manager for Android
-----------------------------

You can also set up TREZOR with our `TREZOR Manager <https://play.google.com/store/apps/details?id=io.trezor.app>`_, which can be found in Google Play store. Your phone has to support the USB Host (USB On The Go - OTG) and you need to use the OTG cable (you can buy one as a TREZOR accessory directly at `TREZOR Shop <https://shop.trezor.io/>`_).

For more details, see our step by step manual :doc:`how to set up TREZOR with TREZOR Manager for Android <android>`.


4. Offline with Python tools
----------------------------

This procedure is only for advanced users! We do not recommend to use it unless you have some experience with a command line and Python. If you wish to proceed further anyway please visit our `Github repository <https://github.com/trezor/python-trezor>`_.


Setting up TREZOR with TREZOR Wallet
-----------------------------

You've successfully established a communication between your TREZOR and TREZOR Wallet. Good job! Now go to `TREZOR Wallet <https://wallet.trezor.io>`_. There are still a couple of steps you need to take in order to start using your TREZOR, so let's get right into it.

As TREZOR comes without a firmware installed, to make sure you always have the newest version when setting up, the first thing you will be asked to do is to install the device system - firmware. Simply confirm the installation and follow instructions on your screen. 

.. warning:: If your device came with a preinstalled firmware, do not use it and contact our support immediately!

In order to install or update the firmware, you will have to enter a so-called bootloader mode. Bootloader basically verifies the validity of the firmware software. You can read all about our bootloader versions and changes which were applied here: `Github repository <https://github.com/trezor/trezor-mcu/blob/master/bootloader/ChangeLog>`_.

.. note:: Since the latest bootloader version 1.3.2, you will not be asked to confirm fingerprints during the initial setup, which is applied automatically. However, you will be asked to compare the fingerprints with any additional firmware update.

After the firmware is installed successfully, replug your TREZOR, and you will be greeted by a welcome page where you can choose to either Create a new wallet or Recover wallet. Simply click on "Create new" button.

.. note:: With TREZOR, you can recover any wallet based on 12, 18, or 24-word recovery seed (BIP32/39/44). For more details on how the recovery process works, please see :doc:`Recovery <recovery>`.

Once you create a new wallet, you're pretty much inside your own TREZOR Wallet and you can look through all of the features it has to offer. However, it would be very unwise to use your TREZOR Wallet without having it backed up. Therefore, we strongly advise to proceed with the backup and write down your recovery seed immediately. 

After you agree to the terms, you will see a unique combination of words on your TREZOR screen which need to be written down to your recovery card. The whole process is described in the following section :doc:`Filling out your Recovery Card <fillingoutyourrecoverycard>`.

.. note:: TREZOR One generates a 24-word seed by default. However, TREZOR T is backed up by a simple 12-word recovery seed, which is also compatible with the common standards for HD wallets (BIP32/39/44).

After you've successfully backed up your device, you will be able to label your TREZOR. The maximum label length is 16 characters.

Once you've personalized your TREZOR, the last step is to create a PIN. It is best to choose a strong PIN to protect your device from unauthorized access. Entering a PIN on TREZOR One is explained in the following section :doc:`Entering your PIN <enteringyourpin>` After you re-confirm your PIN, you can start using your TREZOR Wallet safely.

.. note:: On TREZOR T, you can simply click the numbers on your touchscreen. In addition to the previous model, a "0" has been added to the PIN pad.  

.. note:: There are also several :doc:`Advanced settings <advanced_settings>` that you can configure.

.. toctree::
   :maxdepth: 2

   settingupchromeonlinux
   fillingoutyourrecoverycard
   basic_settings
   enteringyourpin


.. You don't need to use the `TREZOR Wallet <https://wallet.trezor.io>`_ webservice if you want to use your TREZOR device.  You can use any bitcoin software that supports TREZOR including:

 - Electrum
 - Mycelium
