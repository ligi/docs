Security best practices
=======================

Choose a good PIN
-----------------

TREZOR's PIN based security system is a powerful tool to keep your bitcoins safe.  If your TREZOR is stolen, the only thing between the thief and your bitcoins is your PIN and/or passphrase.  **It is imperative that you choose a good PIN!**

An `analysis in 2012 <http://www.datagenetics.com/blog/september32012/>`_ showed that 11% of PINs used were 1234.  Do not use the PIN 1234 to secure your TREZOR.  Do not use any PIN which contains a series of repeated numbers or a counting sequence.

.. hint::

   The numbers displayed on the TREZOR's screen when it requests a new PIN are in a random order.  You can use them as the basis for your PIN if you don't have any better ideas.  For example, you can use the first two rows when you are shown the matrix for the first time.

If you have trouble remembering your PIN, write it on your recovery card.

Keep your recovery seed safe from
----------------------------------

- Theft

 If you do not use a passphrase, your recovery seed is all that is needed to access your bitcoins.  The physical security of your recovery seed is much more important than the physical security of your TREZOR.  If your TREZOR is stolen, the likelihood is that the thieves will be unable to crack your PIN and that your bitcoins are safe.  However, if your recovery seed is stolen your bitcoins can be accessed quite easily.

 Only ever keep your recovery seed on paper.  Never store it on your computer.

- Flood / Fire

 If your TREZOR is lost or stops working, your recovery seed is the only way to get your bitcoins back.  It's very important that your recovery card isn't destroyed as well.

 You may even wish to keep multiple copies of your recovery seed, stored in different locations, however, safety from theft should always be considered as paramount.

Where NOT to keep your recovery seed
------------------------------------

 - Dropbox
 - Email
 - Online backup
 - Offline backup
 - Secure encrypted folder

Where to keep your recovery card
--------------------------------

 - In a locked drawer, away from water and fire
 - Someplace where your family members are likely to find it after you pass away but not before then

Using passphrase encrypted seeds
--------------------------------

In addition to a PIN, it is possible to add a passphrase to your TREZOR.  This has the advantage of making your TREZOR impervious to physical attack.  Even if your TREZOR were to be stolen and the chip examined under an electron microscope to discover your recovery seed, your bitcoins would still be safe!  A passphrase can be any word or any set of letters that you might use as a password.  Your passphrase should be memorable, though.  You typically would not write it down anywhere, to eliminate any possibility of it being discovered.

One limitation of the passphrase approach is that you have to enter your passphrase into the computer that you use with your TREZOR.  For this reason, you should not be tempted to disable your PIN even if you use a passphrase as well!

The flip side to this extreme level of security is that if you forget your passphrase your bitcoins are lost.  Really lost!

.. note:: If you have stored some funds in your TREZOR before setting up the passphrase encryption, they will not appear after enabling the passphrase. But don't worry, they are not lost. You can  access them by entering a empty passphrase.
