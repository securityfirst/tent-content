[Title]: # ()
[Order]: # (0)

# TRUECRYPT TOOL GUIDE

## TrueCrypt Tool Guide   
Secure File Storage

**Lesson to read: [Protecting Files](umbrella://lesson/protecting-files)**  
**Download Location:** [https://truecrypt.ch/downloads/](https://truecrypt.ch/downloads/)  
**Computer requirements:**   
- An internet connection, Windows 2000/XP/2003/Vista/7, Mac OS X or GNU Linux (This guide runs through Windows)  
- Administrator rights required for installation or to create volumes but not to access existing volumes  
**Version used in this guide:** 7.1a  
_(The developers web page is offering a new version 7.2 of TrueCrypt with some functionality removed. Despite this new release we recommend that you continue to use older version 7.1a.)_  
**License:** Free and Open-Source Software  
**Level:** Advanced  
**Other reading:** [http://andryou.com/truecrypt/docs/index.php](http://andryou.com/truecrypt/docs/index.php)   
**Time required:** 30-60 minutes

**Using TrueCrypt will give you:**- The ability to effectively protect your files from intruders or unauthorized access  
- The ability to easily and securely store copies of your important files

**NOTE: TrueCrypt is currently unmaintained, which might have security implications.**![image](tool_truecrypt1.png)

### 1.0 Before you start 

Truecrypt keeps your files secure by preventing anyone without the correct password from opening them. It works like an electronic safe, creating an encrypted container (called a volume) on your computer or hard drive, that you can put as many files as you like into. If you forget your password, you will lose access to your data! 

Please bear in mind that the use of encryption is illegal in some countries. 

TrueCrypt offers the ability to create a standard encrypted volume or a hidden volume. Either one will keep your files confidential, but a hidden volume allows you to hide your important information behind less sensitive data in order to protect it, even if you are forced to reveal your TrueCrypt volume. This guide explains both volumes in detail.

-	How to Install TrueCrypt and Create Standard Volumes  
-	How to Mount the Standard Volume  
-	How to Back up your Volume  
-	Hidden Volumes  
-	Portable TrueCrypt

**_NOTE: TrueCrypt is currently unmaintained, which might have security implications._**

### 2 How to Install TrueCrypt and Create Standard Volumes

### 2.0 How to Install TrueCryrpt

**Step 1.** Double click _TrueCrypt Setup 7.1a.exe_; the _Open File - Security Warning_ dialog box may appear. If it does, click "Next" to activate the TrueCrypt _License_ screen.


**Step 2.** Check the I accept and agree to be bound by the _license terms_ option to enable the Accept button; click "Accept" to activate the following screen:
![image](tool_truecrypt2.png)

- Install mode: This option is for users who do not wish to hide the very fact that they use TrueCrypt on their computer.  
- Extract mode: This option is for users who wish to carry a portable version of TrueCrypt on a USB memory stick and do not wish to have TrueCrypt installed on their computer.

**Note:** Some of the options (for example, entire partition and disk encryption) will not work when TrueCrypt is extracted only.

**Note:** Although the default _Install_ mode is recommended here, you may still use TrueCrypt in portable mode later on. 

**Step 3. Click** "Next" to activate the following screen:
![image](tool_truecrypt3.png)

**Step 4.** Click "Install" to activate the _Installing_ screen to begin installing TrueCrypt on your system.

Step 5.
 Click "OK" and then "Finish" to activate the following screen:
![image](tool_truecrypt4.png)

**Step 6.** Click "Yes" to complete the TrueCrypt installation.

**Note:** All users are strongly encouraged to consult [TrueCrypt help documentation](http://andryou.com/truecrypt/docs/index.php) after completing this tutorial.

### 2.1 About TrueCrypt

TrueCrypt is a program which secures your files by preventing anyone without the correct password from accessing them. It functions like an electronic safe, letting you lock up your files so that only someone with the correct password can open them. TrueCrypt works by letting you set up _volumes_ or sections on your computer where you can securely store files. When you create data in, or move data to these volumes, TrueCrypt will automatically encrypt that information. As you open or take your files out, it automatically decrypts them for use. This process is called _on-the-fly_ encryption.

### 2.2 How to Create a Standard Volume

TrueCrypt lets you create two kinds of volumes: _Hidden_ and _Standard_. In this section, you will learn how to create a _Standard Volume_ in which to store your files.

To begin using TrueCrypt to create a _Standard Volume_, perform the following steps:

**Step 1.** Double click on the TrueCrypt icon or Select **Start > Programs > TrueCrypt > TrueCrypt** to open TrueCrypt.

**Step 2.** Select a drive from the list in the TrueCrypt pane as follows:
![image](tool_truecrypt5.png)

**Step 3.** Click "Create Volume" to activate the _TrueCrypt Volume Creation Wizard_ as follows:
![image](tool_truecrypt6.png)

There are three options for encrypting a _Standard Volume
. In this guide, we will use the Create an encrypted file container option. Please refer to the [**TrueCrypt** documentation](www.truecrypt.org/docs/) for the description of other two options.

**Step 4.** Click "Next" to activate the following screen:
![image](tool_truecrypt7.png)

The 
TrueCrypt Volume Creation Wizard Volume Type_ window lets you specify whether you would prefer to create a _Standard_ or _Hidden **TrueCrypt**_ volume.

For more information about _How to Create a Hidden Volume_, please refer to the Hidden Volumes section further down.

**Step 5.** Check the _Standard TrueCrypt Volume_ option.

**Step 6.** Click "Next" to activate the following screen:
![image](tool_truecrypt8.png)

You can specify where you would like to store your _Standard Volume_ in the _Volume Creation Wizard - Volume Location_ screen. This file can be stored like any other file.

**Step 7.** Either type in the name of the file into the text field, or click "Select File" to activate the following screen:
![image](tool_truecrypt9.png)

**Note:** A TrueCrypt Volume is contained inside a normal file. This means that it can be moved, copied or even deleted! You need to remember both the location and name of the file. However, you must choose new file name for the volume you create. In this tutorial, we will create our Standard Volume in the **My Documents folder**, and name the file _My Volume_ as shown in _figure 8_ above.

**Tip:** You can use any file name and file extension. For example, you can name your Standard Volume _recipes.doc_, so that it will look like a _Word_ document, or _holidays.mpg_, so it will look like a movie file. This is one way you can help disguise the existence of your Standard Volume.

**Step 8.** Click "Save" to close the _Specify Path_ and _File Name_ window and return to the _Volume Creation Wizard_ window as follows:
![image](tool_truecrypt10.png)

**Step 9.** Click "Next".

### 2.3 How to Create a Standard Volume on a USB Memory Stick

To create a TrueCrypt _Standard Volume_ on a USB memory stick, perform steps 1 to 7 in section 2.2 How to Create a Standard Volume, where you activate the _Select a TrueCrypt Volume_ screen. Instead of choosing _My Documents_ as your file location, navigate to and then **choose** your USB memory stick. Then, **enter** a file name and create the _Standard Volume_ there.

### 2.4 How to Create a Standard Volume (continued)

At this stage, you are ready to choose a specific encryption method (or _algorithm_ as it is referred to on the screen) to encode the data that will be stored in your _Standard Volume_.
![image](tool_truecrypt11.png)

**Note:** You may leave the default options here as they appear. All algorithms presented in the two options here are considered secure.

**Step 10.** Click "Next" to activate the _TrueCrypt Volume Creation Wizard_ screen as follows:
![image](tool_truecrypt12.png)

The _Volume Size_ pane lets you specify the size of the _Standard Volume_. In this example, it is set at 10 megabytes. However, you may specify a different size. Consider the size of the documents and file types you would like to store, and then set an appropriate volume size for them.

**Tip:** If you would like to backup your Standard Volume to a CD later on, then you should set the size to 700MB or less.

**Step 11.** Type in your specific volume size into the text field, and then click "Next" to activate the following screen:
![image](tool_truecrypt13.png)

**Important:** Choosing a secure and strong password is among the most important tasks you will perform when creating a _Standard Volume_. A good password will protect your encrypted volume, and the stronger the password you choose, the better. You don't have to create your own passwords, or even remember them, if you use a password generation program like KeePass. Please refer to the **[KeePass lesson](umbrella://lesonn/keepassx)**, to learn more information about password creation and storage.

**Step 12.** Type your password and then re-type your password into the _Confirm_ text fields.

**Important:** The _Next_ button will remain disabled until passwords in both text fields match. If your password is not particularly safe or secure, you will see a warning advising you of this. Consider changing it! Although **TrueCrypt** will still work with any password you have chosen, your data may not be very secure.

**Step 13.** Click "Next" to activate the following screen:
![image](tool_truecrypt14.png)

TrueCrypt is now ready to create a _Standard Volume_. Move your mouse randomly within the _TrueCrypt Volume Creation Wizard_ window for few seconds. The longer you move the mouse, the better the quality of the encryption key.

**Step 14.** Click "Format" to begin creating your standard volume.

TrueCrypt will now create a file named _My Volume_ in the _My Documents_ folder as earlier specified. This file will contain a TrueCrypt _Standard Volume_, 10 Megabytes in size, that you can use to securely store your files.

After a _Standard Volume_ has been successfully created, the following dialog box will appear:
![image](tool_truecrypt15.png)

**Step 15.** Click "OK" to complete creating your _Standard Volume_ and return to the TrueCrypt console.

**Step 16.** Click "Exit" to close _TrueCrypt Volume Creation Wizard_.

### 3 How to Mount the Standard Volume

### 3.0 How to Mount a Standard Volume

In TrueCrypt, to mount a _Standard Volume_ refers to making the standard volume available for use. In this section, you will learn how to mount your newly created standard volume.

To begin mounting your standard volume, perform the following steps:

**Step 1.** Double click on the TrueCrypt icon or **Select Start > Programs > TrueCrypt > TrueCrypt** to open TrueCrypt.

**Step 2.** Select any drive from the list as follows:
![image](tool_truecrypt16.png)

_In this example the Standard Volume will be mounted as the M: drive._

**Note:** In the image above, the _M:_ drive has been selected for mounting the _standard volume_; however, you may choose another listed drive.

**Step 3.** Click "Select File..."

_The Select a TrueCrypt Volume screen will appear as follows:_
![image](tool_truecrypt17.png)

**Step 4.** Select the standard volume file that you created, then click "Open" to close _figure 2_ and return to the TrueCrypt console.

**Step 5.** Click "Mount" to activate the _Enter password for_ prompt screen as follows:
![image](tool_truecrypt18.png)

**Step 6.** Type the password in the _Password:_ text field.

**Step 7.** Click "OK" to begin mounting the _Standard Volume_.

**Note:** If the password you typed is incorrect, TrueCrypt will prompt you to re-type your password and click "OK". If the password is correct, the _Standard Volume_ will be mounted as follows:
![image](tool_truecrypt19.png)

**Step 8.** Double click the highlighted entry in TrueCrypt or double click the corresponding drive letter in the _My Computer_ screen to access the _Standard Volume_ (now mounted on drive _M:_ on your computer).
![image](tool_truecrypt20.png)

**Note:** We have just successfully mounted the _My Volume_ standard volume on a virtual disk _M:_. This virtual disk behaves like a real disk, except that it is entirely encrypted. Any files will be automatically encrypted when you copy, move or save them to this virtual disk (a process known as on-the-fly encryption).

You can copy files to and from the _Standard Volume_ just as you would copy them to any normal disk (for example, by dragging-and-dropping them). When you move a file out of the _Standard Volume_, it is automatically decrypted. Conversely if you move a file onto the _Standard Volume_, TrueCrypt automatically encrypts it. If your computer crashes or is suddenly switched off, TrueCrypt will immediately close the _Standard Volume_.

**Important:** After transferring files to the TrueCrypt volume, make sure that no traces of the files are left behind on the computer or USB memory stick that they came from. Please refer to the **[Safe Deleting lesson](umbrella://lesson/safely-deleting)**.

### 3.1 How to Dismount the Standard Volume

In TrueCrypt, to _dismount_ a _Standard Volume_ simply means to make a volume unavailable for use.

To close or dismount a _Standard Volume_ and make its files accessible only to someone with a password, perform the following steps:

**Step 1.** Select the volume from the list of mounted volumes in the main TrueCrypt window as follows:
![image](tool_truecrypt21.png)

**Step 2.** Click "Dismount" to dismount or close your TrueCrypt standard volume.

**Important:** Make sure to dismount your TrueCrypt volume before putting your computer to _Standby_ or _Hibernate_ mode. Better yet, always shut-down your computer or laptop if you plan on leaving it unattended. This will prevent anyone from being able to gain your volume password.

To retrieve a file stored in your standard volume once you have closed or dismounted it, you will have to mount it again.

### 4.0 How to Back up your Volume

Backing up your documents, files and folders on a regular basis is critical. Backing up your TrueCrypt volume is vital, and (fortunately) easy to do. Don't forget that your volume must be dismounted before you back it up.

**Step 1.** Navigate to your _Standard Volume_ file (in the image below, it is located in the _My Documents_ folder).
![image](tool_truecrypt22.png)

**Step 2.** Save the file to an external memory device, like a CD, DVD or a USB memory stick.

**Tip:** If you have large amounts of data that you want to encrypt and archive repeatedly, why not create a new _Standard Volume_ which is the same size as a CD or DVD? This could be used as a secure storage technique.

Before you back up the standard volume to a removable device, make sure that the device size corresponds to the size of your volume.

### 5.0 About Hidden Volumes

In TrueCrypt, a _Hidden Volume_ is stored within your encrypted _Standard Volume_, but its existence is concealed. Even when you 'mount' or open your standard volume, it is not possible either to find or to prove the existence of the hidden volume. If you are forced to reveal your password and the location of your standard volume, then its content may be revealed, but **not** the existence of the hidden volume within.

Imagine a briefcase with a secret compartment. You keep files that you do not mind having confiscated or losing in the normal section of your briefcase, and you keep the important and private files in the secret compartment. The point of the secret compartment (especially a well-designed one), is to hide its own existence and therefore, the documents within it.

### 5.1 How to a Create a Hidden Volume

The creation of a TrueCrypt _Hidden Volume_ is similar to creating a TrueCrypt _Standard Volume_: Some of the panes, screens and windows are even the same.

**Step 1.** Open TrueCrypt.

**Step 2.** Click "Create Volume" to activate the _TrueCrypt Volume Creation Wizard_.

**Step 3.** Click "Next" to accept the default _Create an encrypted file container_ option.

**Step 4.** Check the _Hidden TrueCrypt_ volume option as follows:
![image](tool_truecrypt23.png)

**Step 5.** Click "Next" to activate the following screen:
![image](tool_truecrypt24.png)

- _Direct mode_: This option lets you create the _Hidden Volume_ within an existing _Standard Volume_.  
- Normal mode: This option lets you create a completely new _Standard Volume_ in which to store the _Hidden Volume_.

In this example, we will use the _Direct mode_.

**Note:** If you would rather start a new _Standard Volume_, please repeat the process from section 2.2 How to Create a Standard Volume.

**Step 6.** Check the _Direct Mode_ option and then click "Next" to activate the _TrueCrypt Volume Creation - Volume Location_ window.

**Note:** Make sure the _Standard Volume_ is unmounted before selecting it.

**Step 7.** Click "Select File" to activate the following screen:
![image](tool_truecrypt25.png)

**Step 8.** Locate the volume file using the _Select a TrueCrypt Volume_ window as shown above.

**Step 9.** Click "Open" to return to the _TrueCrypt Volume Creation Wizard_.

**Step 10.** Click "Next" to activate the _Enter password_ screen.

**Step 11.** Type in password you used when creating the _Standard Volume_ into the _Password_ text field to activate the following screen:
![image](tool_truecrypt26.png)

**Step 12.** Click "Next" after you have read the message to activate the _Hidden Volume Encryptions Options_ screen.

**Note:** Leave both the default _Encryption Algorithm_ and _Hash Algorithm_ settings for the Hidden Volume as they are.

**Step 13.** Click "Next" to activate the following screen:
![image](tool_truecrypt27.png)

You will be prompted to specify the size of the _Hidden Volume_.

**Note:** Consider the kind of documents, their quantity and size that need to be stored. Do leave some space for the _Standard Volume_. If you select the maximum size available for the _Hidden Volume_, you will not be able to put any more new files into the original _Standard Volume_.

If your _Standard Volume_ is 10 Megabytes(MB) in size and you specify a _Hidden Volume_ size of 5MB (as shown in _figure 6_ above), you will have two volumes (one hidden and one standard volume) of approximately 5MB each.

Ensure that the information you store in the _Standard Volume_ does not exceed the 5MB you have set. This is because the TrueCrypt program itself does not automatically detect the existence of the _Hidden Volume_, and it could accidentally overwrite it. You may risk losing all files stored in the hidden volume if you exceed your previously established size.

**Step 14.** Type in the desired hidden volume size into the corresponding text box as shown in the image below.

**Step 15.** Click "Next" to activate the _Hidden Volume Password_ window.

You must now create a _different_ password for the hidden volume from the one used to protect your standard volume. Again, remember to choose a strong password. Please refer to the **[KeePass Tool Guide](umbrella://lesson/keepassx)** to learn more about creating strong passwords.

**Tip:** If you anticipate being forced to reveal the contents of your TrueCrypt volumes, then store your password for the standard volume in KeePass, and create a strong password that you only have to remember for hidden volume. This will help you to conceal your hidden volume, as you will not leave any trace of its existence.

**Step 16.** Create a password and type it in twice, and then click "Next" to activate the following screen:
![image](tool_truecrypt28.png)
Leave the default _File System_ and _Cluster_ options as they are.


**Step 17.** Move the mouse cursor around the screen to increase the cryptographic strength of the encryption and then click "Format" to format the hidden volume.

_After the hidden volume has been formatted, the following screen appears:_
![image](tool_truecrypt29.png)

**Note:** _Figure 8_ both confirms that you have successfully created a hidden volume, as well as warning you against the dangers of overwriting files in the hidden volume when storing files in the standard volume.

**Step 18.** Click "OK" to activate the _Hidden Volume Created_ window, and then click "Exit" and return to the TrueCrypt console.

The hidden volume has now been created inside your standard volume. You may now store documents in the hidden volume, which remain invisible even to someone who has obtained the password for that particular standard volume.

### 5.2 How to Mount the Hidden Volume

The method for mounting or making a _Hidden Volume_ accessible for use is exactly the same as that for a _Standard Volume_; the only difference is you will use the password that you have just created for the _Hidden Volume_.

To _mount_ or open the _Hidden Volume_, perform the following steps:

**Step 1.** Select a drive from the list (in this example, drive _K_):
![image](tool_truecrypt30.png)

**Step 2.** Click "Select File..." to activate the _Select a TrueCrypt Volume_ window.

**Step 3.** Navigate to and then select your _TrueCrypt_ volume file (same file as for the standard volume).

**Step 4.** Click "Open" to return to the TrueCrypt console.

**Step 5.** Click "Mount" to activate the _Enter Password_ for prompt screen as follows:
![image](tool_truecrypt31.png)

**Step 6.** Type the password you used to create the hidden volume, and then click "OK".

Your hidden volume is now mounted (or opened) as follows:
![image](tool_truecrypt32.png)

**Step 7.** Double click on above entry or access it through the _My Computer_ window.

### 5.3 Tips on How to Use the Hidden Disk Feature Securely

The purpose of the hidden disk feature is to escape a potentially dangerous situation by _appearing_ to hand over your encrypted files, when someone in a position of power demands to see them, without actually being forced to reveal your most sensitive information. In addition to protecting your data, this may allow you to avoid further jeopardizing your own safety or exposing your colleagues and partners. For this technique to be effective, you must create a situation where the person demanding to see your files will be satisfied by what you show them and let you go.

To do this, you may want to implement some of the following suggestions:

- Put some confidential documents that you do not mind having exposed in the standard volume. This information must be sensitive enough that it would make sense for you to keep it in an encrypted volume.  
- Be aware that someone demanding to see your files may know about hidden volumes. If you are using TrueCrypt correctly, however, this person will not be able to prove that your hidden volume exists, which will make your denial more believable.  
- Update the files in the standard volume on a weekly basis. This will create the impression that you really are using those files.

Whenever you mount a TrueCrypt volume, you can choose enable the _Protect hidden volume against damage caused by writing to outer volume_ feature. A very important feature, it lets you add new 'decoy' files to your standard volume without the risk of you accidentally deleting or overwriting the encrypted contents of your hidden volume.

As mentioned earlier, exceeding the storage limit on your standard volume may otherwise destroy your hidden files. Do not enable the _Protect hidden volume_ feature when forced to mount a TrueCrypt volume, because doing so requires you to enter the secret password to your hidden volume and will clearly reveal that volume's existence. When you are updating your decoy files in private, however, you should _always_ enable this option.

To use the _Protect hidden volume_ feature, perform the following steps:

**Step 1.** Click "Mount Options..." on the _Enter Password_ prompt shown in the image above. This will activate the _Mount Options_ window as follows:
![image](tool_truecrypt33.png)

**Step 2.** Check the _Protect hidden volume against damage caused by writing to outer volume_ option.

**Step 3.** Type in in your Hidden Volume password, and then click "OK".

**Step 4.** Click "Mount" to mount your standard volume. After you have successfully mounted it, you will be able to add decoy files without damaging your hidden volume.

**Step 5.** Click "Dismount" to dismount, or your make your standard volume unavailable for use, when you have finished modifying its contents.

**Remember:** You only need to do this when you are updating the files in your standard volume. If forced to reveal your standard volume to someone else, you should not use the _Protect hidden volume_ feature.

### 6. Portable TrueCrypt
![image](tool_truecrypt34.png)

Truecrypt keeps your files secure by preventing anyone without the correct password from opening your hidden documents and files. It works like an electronic safe, which you can use to securely lock up your files.

### 6.1 Differences between the Installed and Portable versions of TrueCrypt

Given that portable tools are not installed on a local computer, their existence and use may remain undetected. However, keep in mind that your external device or USB memory stick, and portable tools are only as safe as the computer you are using, and may risk being exposed to adware, malware, spyware and viruses.

As with many of the portable software tools documented here, Portable TrueCrypt allows you to use a powerful and simple file encryption tool without being detected. Having Portable TrueCrypt on removable device or USB memory stick lets you use it from different workstations.

There are very few differences between both the installed and portable versions of Portable TrueCrypt, the main one being that Portable TrueCrypt does not permit the encryption of the entire disk or system disk.

### 6.2 Downloading, Extracting and Using Portable TrueCrypt

**Note:** The folder into which Portable TrueCrypt is to be extracted must be created manually on the removable device, USB memory stick or computer disk before the extraction process.

**Step 1.** Navigate to chosen destination where you would like to extract the Portable TrueCrypt program to, and then right-click to activate its associated menu.

**Step 2.** Select the _New item_ to activate its sub-folder, and then select the _Folder_ sub-menu item, as shown below:
![image](tool_truecrypt35.png)

**Step 3.** Enter the name of the folder.

**Note:** You may give this folder a less obvious name to conceal the existence of the Portable TrueCrypt program.

Portable TrueCrypt can be extracted from the same archive as installation version:

**Step 1.** Navigate to TrueCrypt installation file on your computer.

**Step 2.** Double click _TrueCryptSetup7.1.a.exe_; the _Open File - Security Warning_ dialog box may appear; if it does, click "Yes" to activate the TrueCrypt installation wizard.

**Step 5.** Check the Extract option to extract TrueCrypt portable to a removable drive or USB device as shown below:
![image](tool_truecrypt36.png)

**Step 6.** Click "Next" to activate following two screens:
![image](tool_truecrypt37.png)![image](tool_truecrypt38.png)

 **Click** "OK" and "Yes" respectively to activate the **Extraction Options** window as follows:
![image](tool_truecrypt39.png)

**Step 7.** Click "Browse" to activate the _Browse for Folders_ window as follows:
![image](tool_truecrypt40.png)

**Step 8.** Navigate to your destination folder on either the external drive or USB memory stick, and then click "OK", to return the _Extraction Options_ window as follows:
![image](tool_truecrypt41.png)

**Step 9.** Click "Extract" to begin extracting TrueCrypt to your removable drive or USB memory stick; a few seconds later, the following windows will appear:
![image](tool_truecrypt42.png)

**Step 10.** Click "OK" and then click "Finish" to complete the installation process.

_If the "Open the destination location when fininshed" option was enabled (as it usually is by default), the following screen will appear:_

**Step 11.** Navigate to and then double click _TrueCrypt.exe_ to run Portable TrueCrypt.

Please refer to the instructions for regular TrueCrypt above from this point onwards, for more on how to use TrueCrypt.

### 6.3 How to Eliminate All Traces of Having Extracted Portable TrueCrypt

**Important:** After you have successfully extracted Portable TrueCrypt to your external/removable device, you must delete the installation file from your computer to further eliminate any traces of you having downloaded and installed Portable TrueCrypt.

**Step 1.** Navigate to the folder in which Portable TrueCrypt was downloaded, and then right click the _TrueCryptSetup7.1.a.exe_ installation file to activate the Windows pop-up menu; then, select the "Delete" command to move it to your Recycle Bin.

**Step 2.** Double click the Recycle Bin to open its associated window, and then select and delete the file.

**Note:** If you have either CCleaner or Eraser installed, you can use either of them to eliminate all traces of your having ever downloaded and installed Portable TrueCrypt. See the **[Safe Deleting lesson](umbrella://lesson/safely-deleting)** for more information on how to do this.