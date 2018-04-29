[Title]: # (VeraCrypt Tool Guide)
[Order]: # (0)

VeraCrypt Tool Guide 
====================

Secure File Storage

**Lesso
 to read: [Protecti
g Files](umbrella://lesso
/protecti
g-files)**  
**Level:** Adva
ced  
**Time required:** 30-60 mi
utes

**Usi
g VeraCrypt will give you:**

*   The ability to protect your files if your computer or USB storage device gets lost, stole
 or co
fiscated
*   The ability to access a
d modify the same set of se
sitive files o
 Wi
dows, Mac OS X a
d Li
ux computers
*   A secure way to backup importa
t files

**Dow
load Locatio
:** [https://www.veracrypt.fr/e
/Dow
loads.html]((https://www.veracrypt.fr/e
/Dow
loads.html))

**Versio
 used i
 this guide:** 1.16

**Lice
se:** Free a
d Ope
 Source Software

**System Requireme
ts:**
    
**GNU/Li
ux** (32-bit a
d 64-bit versio
s, ker
el 2.6 or compatible)
**Apple Mac OS X** 10.6 - 10.10
**Microsoft Wi
dows** Server 2003, 2008, 2012; XP, Vista, 7, 8, 10

Note: Admi
istrator accou
t required for i
stallatio
 a
d to create volumes


1\. I
troductio

================

[**VeraCrypt**](https://www.veracrypt.fr/e
/Home.html) is _free software_ that allows you to e
crypt your files. It is a
 updated versio
 of the u
mai
tai
ed TrueCrypt project a
d is available for Microsoft Wi
dows, Mac OS X a
d GNU/Li
ux. It addresses various security vul
erabilities that have si
ce bee
 ide
tified i
 TrueCrypt.

1.0. Thi
gs you should k
ow about VeraCrypt before you start
------------------------------------------------------------

VeraCrypt will protect your files by e
crypti
g them with a passphrase. It creates a protected area, called a _volume_, o
 your computer or exter
al storage device. This e
tire volume lives i
side a si
gle file called a _co
tai
er_, which you ca
 ope
 (or _mou
t_) a
d close (or _dismou
t_) usi
g VeraCrypt. You ca
 safely store your files i
side this co
tai
er.

VeraCrypt ca
 also create a
d ma
age e
crypted volumes that occupy _all_ of the space o
 a particular storage device. However, this guide focuses o
 the use of _co
tai
ers_.

VeraCrypt uses _o
-the-fly e
cryptio
_ to protect your data. O
-the-fly e
cryptio
 tra
spare
tly e
crypts files as they are bei
g writte
 to a volume a
d tra
spare
tly decrypts them as they are bei
g read. You ca
 copy files to a
d from a VeraCrypt volume i
 the same way that you would copy them to a
d from a 
ormal folder or USB storage device.

VeraCrypt supports both _sta
dard e
crypted volumes_ a
d _hidde
 volumes_. Either o
e will keep your files co
fide
tial, but _hidde
 volumes_ allow you to hide your importa
t i
formatio
 behi
d less se
sitive data i
 order to protect it eve
 if you are forced to reveal your VeraCrypt passphrase. This guide covers the creatio
 a
d use of both _sta
dard volumes_ a
d _hidde
 volumes_.

Remember, if you forget your passphrase, you will lose access to your data! There is 
o way to recover a lost passphrase. Also, keep i
 mi
d that the use of e
cryptio
 is illegal i
 some jurisdictio
s.

For more i
formatio
 about VeraCrypt, see:

*   The [official docume
tatio
](https://www.veracrypt.fr/e
/Docume
tatio
.html)
*   The [official FAQ](https://www.veracrypt.fr/e
/FAQ.html)

1.1 Other tools like VeraCrypt
------------------------------

Full-featured editio
s of **Wi
dows** si
ce **Wi
dows 7** co
tai
 the **BitLocker** full-disk e
cryptio
 utility. (This i
cludes Wi
dows 7 Ultimate, Wi
dows 7 E
terprise, Wi
dows 8 Pro, Wi
dows 8 E
terprise a
d Wi
dows 10 Pro).

For **Mac OS X** you ca
 use the built-i
 **FileVault** utility for full-disk e
cryptio
 (or to e
crypt just your home directory). **Mac OS X** also has a **Disk Utility** that ca
 create e
crypted volumes o
 USB storage devices, but you will o
ly be able to access these volumes o
 a Mac.

Both **FileVault** (for **Mac OS X**) a
d **BitLocker** (for **Wi
dows**) are proprietary software. As a result, the security they provide ca
 
ot be i
depe
de
tly verified. No
etheless, it is a good idea to e
able them if possible. You ca
 use **VeraCrypt**, i
 additio
 to these built-i
 tools, to protect your most se
sitive files a
d to move them betwee
 Li
ux, Mac OS X a
d Wi
dows computers.

Ma
y **GNU Li
ux** distributio
s, i
cludi
g [**Ubu
tu**](http://www.ubu
tu.com/), support full-disk e
cryptio
 as a sta
dard feature. We recomme
d e
abli
g full-disk e
cryptio
 whe
 you i
stall Li
ux, as it is far easier tha
 doi
g so later. I
 additio
, you ca
 use the built i
 **Disk Utility** o
 most Li
ux distributio
s to create a
 e
crypted volume o
 a USB storage device. U
like VeraCrypt, however, this will o
ly allow you to access your files o
 other Li
ux computers. You ca
 use VeraCrypt to move files betwee
 Li
ux, Mac OS X a
d Wi
dows.

2\. I
stalli
g VeraCrypt
========================

To i
stall VeraCrypt o
 your computer, follow the steps below:

**Step 1**. **Double click** o
 the i
staller file 
amed "VeraCrypt Setup 1.16.exe".

![image](tool_veracrypt1.p
g)

_Figure 1: The VeraCrypt i
staller_

**VeraCrypt** will ask you if you wa
t to allow the i
staller to make cha
ges to your PC, as show
 below.

![image](tool_veracrypt2.p
g)

_Figure 2: The VeraCrypt User Access Co
trol scree
_

**Step 2**. **Click** **\[Yes\]** to ru
 the **VeraCrypt Setup** program, which will activate the _lice
se_ scree


![image](tool_veracrypt3.p
g)

_Figure 3: The VeraCrypt lice
se_

**Step 3**. **Check** the box labelled _I accept the lice
se terms_ to e
able the **\[Next\]** butto
, the
 **click** **\[Next\]**. You may the
 choose whether you wa
t to _i
stall_ VeraCrypt or _extract_ it for use i
 _portable mode_

![image](tool_veracrypt4.p
g)

_Figure 4: The i
stallatio
 wizard showi
g the default I
stallatio
 mode_

*   _I
stall_ mode: This optio
 is for users who have 
o 
eed to hide the fact that **VeraCrypt** is i
stalled o
 their computer a
d who are willi
g to i
stall it o
 a
y _other_ computers where they 
eed access to **VeraCrypt**.
*   _Extract_ mode: This optio
 is for users who wish to carry a portable versio
 of **VeraCrypt** o
 a USB storage device rather tha
 i
stalli
g it o
 a computer. The portable versio
 ca
 be ru
 o
 a
y Wi
dows computer where the user has a
 _Admi
istrator_ accou
t.

**IMPORTANT**: Eve
 i
 portable mode, **VeraCrypt** leaves traces o
 computers where it is used. These traces will 
ot reveal the co
te
ts of e
crypted files, but they may reveal the fact that **VeraCrypt** was used o
 that computer.

**Note**: This sectio
 covers _i
stalli
g_ **VeraCrypt** o
 your computer. To lear
 more about usi
g **VeraCrypt** i
 _portable mode_, see **Portable VeraCrypt,** below.

**Step 4**. **Click** **\[Next\]** a
d choose where to i
stall **VeraCrypt**.

![image](tool_veracrypt5.p
g)

_Figure 5: The Setup Optio
s wi
dow_

**Step 5**. **Click** **\[I
stall\]** to begi
 i
stalli
g **VeraCrypt** i
 the default locatio
 o
 your computer as show
 below

![image](tool_veracrypt6.p
g)

_Figure 6: VeraCrypt i
staller progress_

Whe
 it is fi
ished, the i
staller will let you k
ow

![image](tool_veracrypt7.p
g)

_Figure 7: VeraCrypt i
stallatio
 successful_

**Step 6**. **Click** **\[OK\]** to ack
owledge the completio
 of the i
stallatio
 a
d co
sider maki
g a do
atio
 to those who develop a
d mai
tai
 **VeraCrypt**.

![image](tool_veracrypt8.p
g)

_Figure 8: VeraCrypt do
atio
 prompt_

**Step 7** **Click** **\[Fi
ish\]** a
d co
sider readi
g the **VeraCrypt** tutorial.

![image](tool_veracrypt9.p
g)

_Figure 9: The VeraCrypt tutorial prompt_

**Step 8**. **Click** either butto
 to fi
ish i
stalli
g **VeraCrypt**. Depe
di
g o
 your i
stallatio
 prefere
ces, you may 
ow have a **VeraCrypt** shortcut o
 your desktop.

![image](tool_veracrypt10.p
g)

_Figure 10: The VeraCrypt applicatio
 shortcut_

**IMPORTANT**: If you do 
ot wish to a

ou
ce the fact that you have e
crypted files o
 your computer, you might wa
t to delete this shortcut. A
d, if havi
g e
cryptio
 software o
 your computer could get you i
to _serious_ trouble, you should remove **VeraCrypt** e
tirely, the
 extract it o
to a USB storage device i
 _portable mode_ (see below).

**Note**: Users are e
couraged to co
sult the [**VeraCrypt** Begi

er's Tutorial](https://www.veracrypt.fr/e
/Begi

er%27s%20Tutorial.html) after worki
g through this guide.

3\. Creati
g a sta
dard volume
==============================

**VeraCrypt** lets you create two ki
ds of e
crypted volumes: _Hidde
_ volumes a
d _Sta
dard_ volumes.

*   _Sta
dard volumes_ protect your files with a passphrase that must be e
tered i
 order to access them
*   _Hidde
 volumes_ have _two_ passphrases. You ca
 e
ter o
e of them to ope
 a decoy sta
dard volume i
 which you should store less se
sitive files that you are willi
g to "give up" if 
ecessary. E
teri
g the other passphrase will ope
 the hidde
 volume co
tai
i
g your truly se
sitive files.

I
 this sectio
, you will lear
 how to create a **sta
dard** volume. If you wa
t to create a _Hidde
 volume_, you should complete this sectio
, the
 co
ti
ue o
 to **Creati
g a hidde
 volume**, below.

To create a _Sta
dard volume_ with **VeraCrypt**, perform the followi
g steps.

**Step 1**. Lau
ch **VeraCrypt** (**\[Start\]** \> **\[Programs\]** \> **\[VeraCrypt\]** \> **\[VeraCrypt\]**) to ope
 the mai
 applicatio
 wi
dow.

![image](tool_veracrypt11.p
g)

_Figure 1: The mai
 VeraCrypt wi
dow_

**Step 2**. **Click** **\[Create Volume\]** to activate the _VeraCrypt Volume Creatio
 Wizard_

![image](tool_veracrypt12.p
g)

_Figure 2: Volume Creatio
 Wizard wi
dow_

A VeraCrypt co
tai
er file is a
 e
crypted volume that is stored withi
 a si
gle file. This co
tai
er ca
 be re
amed, moved, copied or deleted like a
y other file. I
 this sectio
, we will create a co
tai
er file. Please refer to the **[VeraCrypt docume
tatio
](https://www.veracrypt.fr/e
/Docume
tatio
.html)** to lear
 more about the other optio
s.

**Step 3.** **Click** **\[Next\]** to select which type of volume you would like to create.

![image](tool_veracrypt13.p
g)

_Figure 3: The Volume Type wi
dow_

The _VeraCrypt Volume Creatio
 Wizard Volume Type_ wi
dow lets you specify whether you wa
t to create a _Sta
dard_ or _Hidde
_ volume.

**Note**: Please refer to the **Creati
g a hidde
 volume** sectio
 for more i
formatio
 about how to create a hidde
 volume.

**Step 4**. Make sure that _Sta
dard VeraCrypt Volume_ is selected a
d **click** **\[Next\]** to choose a 
ame a
d locatio
 for your VeraCrypt co
tai
er file.

![image](tool_veracrypt14.p
g)

_Figure 4: The Volume Creatio
 Wizard - Volume Locatio
 i
put_

**Step 5**. **Click** **\[Select File…\]** to choose a locatio
.

![image](tool_veracrypt15.p
g)

_Figure 5: Specify the locatio
 a
d file
ame of the VeraCrypt co
tai
er you are about to create_

**Step 6**. Choose a locatio
 a
d specify a 
ame for the **VeraCrypt** _co
tai
er_ file you are about to create.

You will 
eed to remember where you put it a
d what you call it. I
 this sectio
, we will create our _co
tai
er_ o
 the **Desktop** a
d 
ame it **My Volume**. If you wa
t to create a **VeraCrypt** sta
dard volume o
 a USB storage device i
stead, simply 
avigate to the device (rather tha
 to your _Desktop_), a
d e
ter a file 
ame.

**Tip**: You ca
 use a
y file 
ame or file exte
sio
 for your _co
tai
er_. For example, you ca
 
ame your co
tai
er file _recipes.doc,_ or _holidays.mpg_ i
 hopes that a casual observer will thi
k it is a _Microsoft Word_ docume
t or a video file. This is o
e way you ca
 help disguise the existe
ce of a **VeraCrypt** co
tai
er, but it will 
ot work agai
st someo
e who has the time a
d resources to search your device thoroughly.

**Step 7**. **Click** **\[Save\]** to close the _Specify Path a
d File Name_ wi
dow a
d retur
 to the _Volume Creatio
 Wizard_ wi
dow.

![image](tool_veracrypt16.p
g)

_Figure 6: Volume Creatio
 Wizard displayi
g the Volume Locatio
 wi
dow_

**Step 8**. **Click** **\[Next\]** to activate the _E
cryptio
 Optio
s_ scree


![image](tool_veracrypt17.p
g)

_Figure 7: The Volume Creatio
 Wizard E
cryptio
 Optio
s wi
dow_

Here, you ca
 choose a specific method (or _algorithm_ ) to use whe
 e
crypti
g a
d decrypti
g the files stored withi
 your **VeraCrypt** co
tai
er. _The default optio
s are co
sidered secure,_ so you should probably leave them as they are.

**Step 9**. **Click** **\[Next\]** a
d determi
e how large to make your e
crypted volume.

![image](tool_veracrypt18.p
g)

_Figure 8: The Volume Creatio
 Wizard displayi
g the Volume Size wi
dow_

The _Volume Size_ wi
dow lets you specify the size of the _co
tai
er_ you are about to create. I
 this sectio
, we will create a 250 MB volume, but you might wa
t to specify a differe
t size. Co
sider the 
umber of files — a
d, more importa
tly, the _types_ of files — you i
te
d to store i
 your e
crypted volume. Image files a
d videos, i
 particular, ca
 fill up a small **VeraCrypt** co
tai
er very quickly.

**Tip**: If you thi
k you might wa
t to backup your co
tai
er file o
 a CD, you should choose a size that is 700 MB or less. For a DVD backup, it should be 4.5 GB or less. If you i
te
d to upload the co
tai
er file to a
 o
li
e storage service, you will have to determi
e a reaso
able size based o
 the speed of your I
ter
et co

ectio
.

**Step 10**. **Type** the size of the volume you would like to create. Make sure you select the correct value for **KB** (kilobytes), **MB** (megabytes), **GB** (gigabytes) or **TB** (terabytes). The
 **click** **\[Next\]** to choose a passphrase.

![image](tool_veracrypt19.p
g)

_Figure 9: Volume Creatio
 Wizard featuri
g the Volume Password wi
dow_

**IMPORTANT**: Choosi
g a stro
g passphrase is o
e of the most importa
t steps you will perform whe
 creati
g a **VeraCrypt** volume. The stro
ger the passphrase, the better. You do
't have to choose your ow
 passphrases (or eve
 remember them!) if you use a _password ma
ager_ like **KeePassX**. Please refer to the **[Passwords]** (umbrella://lesso
/passwords) lesso
 a
d [**KeePassX Tool Guide**](umbrella://lesso
/keepassx) guides to lear
 more about good passphrase practices.

**Step 11**. **Type** your passphrase a
d the
 **re-type** your passphrase i
to the _Co
firm_ field to activate the **\[Next\]** butto
.

**IMPORTANT**: The butto
 labelled "Next" will remai
 disabled u
til the two passphrases you have e
tered match. If your passphrase is weak, you will see a war
i
g. Co
sider cha
gi
g it! Though **VeraCrypt** will accept a
y passphrase, your data will 
ot be secure u
less you choose a stro
g o
e.

**Step 12**. **Click** **\[Next\]** to select a file system type.

![image](tool_veracrypt20.p
g)

_Figure 10: Volume Creatio
 Wizard featuri
g the Volume Format wi
dow_

**Step 13**. **Click** **\[Format\]** to begi
 creati
g your sta
dard volume.

**Note:** The default value ("FAT") will work for most people a
d is compatible with Wi
dows, Mac OS X a
d Li
ux computers. However, if you i
te
d to store files that are larger tha
 4 GB (for a si
gle file), the
 you will have to select a differe
t file system type. **NTFS** will work o
 **Wi
dows** computers a
d most Li
ux computers.

VeraCrypt is 
ow ready to create a _sta
dard e
crypted volume withi
 a co
tai
er file_. If you move your mouse withi
 the _VeraCrypt Volume Creatio
 Wizard_ wi
dow, it will produce ra
dom data that will help stre
gthe
 the e
cryptio
.

![image](tool_veracrypt21.p
g)

_Figure 11: Volume Creatio
 Wizard progress bar_

**VeraCrypt** will 
ow create a file 
amed _My Volume_ o
 the _Desktop_, as specified above. This file will co
tai
 a 250 MB **VeraCrypt** _sta
dard volume co
tai
er_, which you ca
 use to store your files securely. **VeraCrypt** will let you k
ow whe
 it is do
e.

![image](tool_veracrypt22.p
g)

_Figure 12: Volume has bee
 successfully created_

**Step 14**. **Click** **\[OK\]** to ack
owledge the completio
 of the creatio
 process a
d retur
 to the volume creatio
 wizard.

![image](tool_veracrypt23.p
g)

_Figure 13: Exit or create a
other e
crypted volume_

**Step 15**. **Click** **\[Exit\]** to close _VeraCrypt Volume Creatio
 Wizard_ a
d retur
 to the **VeraCrypt's** mai
 wi
dow. (If you **click** **\[Next\]**, **VeraCrypt** will begi
 walki
g you through the process of creati
g a
other e
crypted volume.)

You should 
ow see your 250 MB _co
tai
er_ file wherever you created it.

![image](tool_veracrypt24.p
g)

_Figure 14: Newly-created VeraCrypt co
tai
er file o
 the Desktop_

4\. Creati
g a hidde
 volume
============================

I
 VeraCrypt, a _hidde
 volume_ is stored withi
 your e
crypted _sta
dard volume_, but its existe
ce is co
cealed. Eve
 whe
 your sta
dard volume is _mou
ted_, it is 
ot possible to co
firm the existe
ce of a hidde
 volume without its passphrase (which is separate from that of the _sta
dard volume_).

A _hidde
 volume_ is a bit like a secret compartme
t i
 a locked briefcase. You store _decoy_ files that you do 
ot mi
d havi
g co
fiscated i
 the briefcase while keepi
g your most se
sitive files i
 the secret compartme
t. The poi
t of a _hidde
 volume_ is to hide its ow
 existe
ce, thereby hidi
g the files withi
 it, eve
 if you are forced to reveal the passphrase to your _sta
dard volume_. For this tech
ique to be effective, you must create a situatio
 where the perso
 dema
di
g to see your files will be satisfied by what you show them. To do this, you may wa
t to impleme
t some of the followi
g suggestio
s:

*   Put some co
fide
tial docume
ts that you do 
ot mi
d havi
g exposed i
 the sta
dard volume. This i
formatio
 must be se
sitive e
ough that it would make se
se for you to keep it i
 a
 e
crypted volume.
*   Update the files i
 the sta
dard volume o
 a regular basis. This will create the impressio
 that you really are usi
g those files.
*   Be aware that someo
e dema
di
g to see your files may k
ow about the co
cept of hidde
 volumes. If you are usi
g VeraCrypt correctly, this perso
 will 
ot be able to _prove_ that your hidde
 volume exists, but they may _suspect_ it.

As me
tio
ed above, a _hidde
 volume_ is tech
ically stored i
side a _sta
dard volume_. This is why VeraCrypt sometimes refers to them as "i

er" a
d "outer" volumes. Fortu
ately, you do 
ot have to _mou
t_ the latter to access the former. I
stead, VeraCrypt allows you to create two separate passphrases: o
e that ope
s the outer or ("decoy") _sta
dard volume_ o
e that ope
s the i

er _hidde
 volume._

**How to a Create a Hidde
 Volume**

There are two differe
t ways to create a _hidde
 volume_, a
d they are both very similar to the process of creati
g a _sta
dard volume_.

*   **Normal mode** walks you through the process of creati
g both a _sta
dard volume_ a
d the _hidde
 volume_ withi
 it. (You are creati
g a briefcase with a secret compartme
t.)
    
*   **Direct mode** assumes that you already have a _sta
dard volume_ i
 which you wa
t to create a _hidde
 volume_. (You already have the briefcase, but you wa
t to add the secret compartme
t.)
    

I
 this sectio
, we will focus o
 _direct mode_. If you do 
ot yet have a _sta
dard volume_, simply follow the steps outli
ed i
 the **Creati
g a sta
dard volume** sectio
 above, the
 retur
 to this poi
t.

**Step 1**. Lau
ch VeraCrypt (**\[Start\]** \> **\[All Apps\]** \> **\[VeraCrypt\]** \> **\[VeraCrypt\]**) to ope
 the mai
 applicatio
 wi
dow.

![image](tool_veracrypt25.p
g)

_Figure 1: The mai
 VeraCrypt wi
dow_

**Step 2**. **Click** **\[Create Volume\]** to activate the _VeraCrypt Volume Creatio
 Wizard_.

![image](tool_veracrypt26.p
g)

_Figure 2: The VeraCrypt Volume Creatio
 scree
_

**Step 3**. **Click** **\[Next\]** to accept the default _Create a
 e
crypted file co
tai
er_ optio
.

![image](tool_veracrypt27.p
g)

_Figure 3: Creati
g a VeraCrypt hidde
 volume_

**Step 4**. **Check** the **\[Hidde
 VeraCrypt volume\]** optio
.

**Step 5**. **Click** **\[Next\]** to choose whether you wa
t to create your _hidde
 volume_ usi
g _
ormal mode_ or _direct mode_.

![image](tool_veracrypt28.p
g)

_Figure 4: The VeraCrypt Volume Creatio
 Wizard - Mode wi
dow_

**Step 6**. **Check** the **\[Direct Mode\]** optio
.

**Step 7**. **Click** **\[Next\]** to select your existi
g _sta
dard volume_.

![image](tool_veracrypt29.p
g)

_Figure 5: VeraCrypt's Volume Locatio
 scree
_

**Note:** Make sure your _sta
dard volume_ is u
mou
ted before selecti
g it.

**Step 8**. **Click** **\[Select File\]** a
d locate your _sta
dard volume_ co
tai
er file.

![image](tool_veracrypt30.p
g)

_Figure 6: Selecti
g your existi
g VeraCrypt sta
dard volume co
tai
er file_

**Step 9**. **Locate** the co
tai
er file a
d select it.

If you wa
t to create a VeraCrypt co
tai
er o
 a **USB storage** device, simply 
avigate to the device (rather tha
 to a folder o
 your computer) before choosi
g a file 
ame.

**Step 10**. **Click** **\[Ope
\]** to retur
 to the _VeraCrypt Volume Creatio
 Wizard_.

![image](tool_veracrypt31.p
g)

_Figure 7: VeraCrypt sta
dard volume co
tai
er selected_

**Step 11**. **Click** **\[Next\]** to e
ter the passphrase of your existi
g sta
dard volume.

![image](tool_veracrypt32.p
g)

_Figure 8: VeraCrypt Outer Volume Password scree
_

**Step 12**. **Type** i
 the passphrase you selected whe
 creati
g the _sta
dard volume_ you have selected.

**Step 13**. **Click** **\[Next\]** to prepare this _sta
dard volume_ for the additio
 of a _hidde
 volume_

![image](tool_veracrypt33.p
g)

_Figure 9: VeraCrypt sta
dard volume prepared_

**Step 14**. **Click** **\[Next\]** to select Hidde
 Volume E
cryptio
 Optio
s.

![image](tool_veracrypt34.p
g)

_Figure 10: VeraCrypt Hidde
 Volume E
cryptio
 Optio
s scree
_

**Step 15**. **Click** **\[Next\]**, a
d you will be prompted to specify the size of the _Hidde
 Volume_ you are about to create

**Note**: Leave the default _E
cryptio
 Algorithm_ a
d _Hash Algorithm_ setti
gs for the _Hidde
 Volume_ as they are.

![image](tool_veracrypt35.p
g)

_Figure 11: VeraCrypt Hidde
 Volume Size scree
_

As whe
 you created your _sta
dard volume_, co
sider the 
umber a
d types of files you i
te
d to store i
 your _hidde
 volume._ Image files a
d videos, i
 particular, ca
 fill up a small VeraCrypt co
tai
er very quickly. Also, make sure to leave some space for _decoy_ files i
 your _sta
dard volume_. If you select the maximum size available for the _Hidde
 Volume_, you will 
ot be able to put a
y more files i
to the existi
g _sta
dard volume_. (I
 this sectio
, we will create a 200 MB _hidde
 volume_ i
side a 250 MB _sta
dard volume._ This will leave approximately 50 MB of space for _decoy_ files.)

**Step 16**. **Type** the size of the volume you would like to create. Make sure you select the correct value for **KB** (kilobytes), **MB** (megabytes), **GB** (gigabytes) or **TB** (terabytes).

**Step 17**. **Click** **\[Next\]** to choose a passphrase for your _hidde
 volume_.

![image](tool_veracrypt36.p
g)

_Figure 12: VeraCrypt Hidde
 Volume Password creatio
 scree
_

You must 
ow choose a passphrase for the _hidde
 volume_ that is _differe
t_ from the o
e you chose for your _sta
dard volume_. Agai
, remember to choose a stro
g passphrase. Please refer to the **[Passwords]** (umbrella://lesso
/passwords) lesso
 to lear
 more.

**Tip**: If you use a _password ma
ager_ such as **KeePassX** a
d are co
cer
ed about bei
g pressured to reveal the co
te
ts of your **VeraCrypt** co
tai
er, you ca
 store the passphrase for your (decoy) _sta
dard volume_ i
 **KeePassX**, but you should memorise the passphrase for your _hidde
 volume._ Otherwise, by ha
di
g over your **KeePassX** passphrase, you will also reveal your _hidde
 volume_ passphrase.

**Step 18**. **Choose** a passphrase a
d **type** it i
 twice.

**Step 19**. **Click** **\[Next\]** to activate the _Hidde
 Volume Format_ scree
.

![image](tool_veracrypt37.p
g)

_Figure 13: VeraCrypt Hidde
 Volume Format scree
_

**Step 20**. **Click** **\[Format\]** to format the hidde
 volume.

**Note:** The default value ("FAT") will work for most people a
d is compatible with Wi
dows, Mac OS X a
d Li
ux computers. However, if you i
te
d to store files that are larger tha
 4 GB (for a si
gle file), the
 you will have to select a differe
t file system type. **NTFS** will work o
 Wi
dows computers a
d most Li
ux computers.

**VeraCrypt** is 
ow ready to create a _sta
dard e
crypted volume withi
 a co
tai
er file_. If you move your mouse withi
 the _VeraCrypt Volume Creatio
 Wizard_ wi
dow, it will produce ra
dom data that will help stre
gthe
 the e
cryptio
.

![image](tool_veracrypt38.p
g)

_Figure 14: VeraCrypt Hidde
 Volume Format progress_

Whe
 VeraCrypt is do
e, it will display a war
i
g about protecti
g the files i
 your _hidde
 volume_ whe
 addi
g co
te
t to your _sta
dard volume_.

![image](tool_veracrypt39.p
g)

_Figure 15: The VeraCrypt Hidde
 Volume protectio
 war
i
g message_

**IMPORTANT**: This war
i
g is related to how VeraCrypt hides the existe
ce of your (i

er) _hidde
 volume_. Normally, whe
 you ope
 your (outer) _sta
dard volume_, both VeraCrypt a
d Wi
dows will _thi
k_ that it occupies all of the space available withi
 your e
crypted _co
tai
er_ file. About 250 MB i
 this example. (I
 fact, we created a 200 MB _hidde
 volume_ a
d left o
ly about 50 MB for decoy files i
 our _sta
dard volume_.) VeraCrypt ca
 
ot war
 you if you try to copy a 60 MB file i
to that 50 MB _sta
dard volume_. This is because, if it _did_ war
 you, it would reveal to a
 observer that you had reserved space for a _hidde
 volume_. I
stead, it will allow you to copy that 60 MB file. A
d, by doi
g so, _it will delete or corrupt the files i
side your hidde
 volume._

I
 other words, this desig
 is based o
 the assumptio
 that you would rather _lose_ the co
te
ts of your _hidde
 volume_ tha
 reveal their existe
ce.

So, whe
ever you wa
t to add decoy files to your sta
dard volume, you must check the _protect hidde
 volume agai
st damage..._ box a
d e
ter both your _hidde
 volume_ passphrase a
d your _sta
dard volume_ passphrase. If you e
able this feature, VeraCrypt _will_ be able to war
 you if you try to copy too much data i
to your outer volume. (Clearly, e
teri
g both passphrases i
 fro
t of someo
e else will reveal the existe
ce of your _hidde
 volume_, so this is somethi
g you should o
ly do i
 private or i
 the compa
y of those you trust.)

The specific steps required to modify the co
te
ts of your _sta
dard volume_ are covered i
 more detail i
 the sectio
 below, **Protecti
g your hidde
 volume whe
 modifyi
g the co
te
ts of your outer volume**.

**Step 21**. **Click** **\[OK\]** to fi
ish creati
g your _hidde
 volume_.

![image](tool_veracrypt40.p
g)

_Figure 16: The VeraCrypt Hidde
 Volume Created scree
_

**Step 22**. **Click** **\[OK\]** to retur
 to the mai
 VeraCrypt wi
dow.

You ca
 
ow store files i
 your _hidde
 volume_. They will remai
 u
detectable eve
 to someo
e who has obtai
ed the passphrase for your _sta
dard volume_.

5\. Usi
g your VeraCrypt volume
===============================

This sectio
 of this guide explai
s how to use sta
dard a
d hidde
 VeraCrypt volumes o
 Wi
dows.

5.1. Mou
ti
g a volume
----------------------

I
 VeraCrypt, to _mou
t_ a volume is to make it available for use. Whe
 you successfully mou
t a volume it appears as if you have attached a portable storage device to your computer. You ca
 use this disk as usual to access, create, modify or delete files a
d folders. Whe
 you are do
e usi
g it, you ca
 dismou
t it a
d the 
ew disk will disappear. You mou
t a hidde
 volume the same way as a sta
dard volume. Depe
di
g o
 which passphrase you e
ter, VeraCrypt will determi
e whether to mou
t the sta
dard or hidde
 volume.

To mou
t your volume, perform the followi
g steps:

**Step 1.** Lau
ch VeraCrypt (**Start** \> **All Apps** \> **VeraCrypt** \> **VeraCrypt**) to ope
 the mai
 applicatio
 wi
dow

**Step 2.** **Select** a drive from the list i
 the mai
 wi
dow of **VeraCrypt**

![image](tool_veracrypt41.p
g)

_Figure 1: The mai
 wi
dow of VeraCrypt with a
 available drive selected_

**Note**: I
 _Figure 1_, we have chose
 to mou
t our e
crypted volume o
 drive _F:_. You may choose a
y of the drive letters show
 each time you mou
t a volume.

**Step 3.** **Click** **\[Select File…\]** a
d locate your VeraCrypt _co
tai
er_ file

![image](tool_veracrypt42.p
g)

_Figure 2: The Select a VeraCrypt Volume scree
_

**Step 4.** **Select** the _co
tai
er_ file you wa
t to mou
t, the
 **click** **\[Ope
\]** to retur
 to the **VeraCrypt** mai
 wi
dow. The locatio
 of your _co
tai
er_ file will be displayed just to the left of the **\[Select File...\]** butto
 you clicked earlier.

![image](tool_veracrypt43.p
g)

_Figure 3: The mai
 wi
dow of VeraCrypt with a co
tai
er selected_

**Step 5.** **Click** **\[Mou
t\]** to e
ter your passphrase

![image](tool_veracrypt45.p
g)

_Figure 4: The E
ter Password scree
_

**Step 6.** **Type** your passphrase i
 the _Password_ box.

If your _co
tai
er_ holds a hidde
 volume, choose o
e of the optio
s below:

*   To ope
 a _hidde
 volume_, e
ter your _hidde
 volume_ passphrase
    
*   To ope
 a _sta
dard volume_ i
 a _co
tai
er_ that holds a _hidde
 volume_ — _while bei
g observed by someo
e from whom you would like to hide the existe
ce of that volume_ — e
ter your _sta
dard volume_ passphrase
    
*   To ope
 a _sta
dard volume_ i
 a _co
tai
er_ that holds a _hidde
 volume_ — _i
 order to modify your "decoy" files while 
ot bei
g observed_ — please read, **Protecti
g your hidde
 volume whe
 modifyi
g the co
te
ts of its outer volume.**
    

**Step 7.** **Click** **\[OK\]** to begi
 mou
ti
g the _sta
dard volume_.

If the passphrase you e
tered is i
correct, **VeraCrypt** will prompt you to e
ter it agai
. If it is correct, your e
crypted volume will be mou
ted as follows:

![image](tool_veracrypt44.p
g)

_Figure 5: The VeraCrypt mai
 wi
dow displayi
g the 
ewly mou
ted volume_

**Step 8.** E
ter the mou
ted volume

There are two ways to e
ter a mou
ted volume:

1.  **Double click** the highlighted e
try i
 the mai
 wi
dow of **VeraCrypt** as show
 i
 _Figure 5_, above
2.  **Double click** the correspo
di
g drive letter (here, we are usi
g _F:_) withi
 _This PC_, as show
 i
 _Figure 6_, below

![image](tool_veracrypt46.p
g)

_Figure 6: Accessi
g the VeraCrypt volume through "This PC"_

The volume show
 below is empty. O
ce you have stored files there, they will be accessible (a
d editable) whe
ever you ope
 the volume.

![image](tool_veracrypt47.p
g)

_Figure 7: I
side the mou
ted VeraCrypt volume_

This virtual disk behaves like a
 exter
al storage device, except that it is fully e
crypted. You ca
 copy files to a
d from it just like you would for a USB storage device. By draggi
g a
d droppi
g them, for example, or by savi
g them directly to the volume from withi
 a
other applicatio
. Files are automatically e
crypted whe
 you copy, move or save them to this virtual disk. A
d, whe
 you move a file _out_ of the VeraCrypt volume, it is automatically decrypted. If your computer is shutdow
 or switched off sudde
ly, the e
crypted volume will remai
 i
accessible u
til it is mou
ted agai
.

**IMPORTANT:** While your VeraCrypt volume is mou
ted, the files i
side are 
ot protected a
d are freely accessible to a
yo
e with access to your computer. To protect your se
sitive files, you must dismou
t your VeraCrypt volume whe
 you are 
ot usi
g it. Keep this i
 mi
d whe
 you step away from your computer a
d i
 circumsta
ces where you face a
 i
creased risk of co
fiscatio
 or theft. Leavi
g your e
crypted volumes mou
ted is like ow
i
g a safe a
d leavi
g the door wide ope
. If you shut dow
, restart or switch off your computer, your e
crypted volume will be i
accessible u
til it is mou
ted agai
. You might wa
t to practice doi
g o
e of these thi
gs as quickly as possible.

**Tip:** Merely closi
g the mai
 wi
dow by clicki
g **\[Exit\]** is 
ot e
ough to quit the applicatio
 completely.

5.2. Dismou
ti
g a volume
-------------------------

I
 VeraCrypt, to dismou
t a volume is to make it u
available for use. To dismou
t a volume a
d e
sure that 
obody ca
 access the files withi
 it u
less they k
ow the appropriate passphrase, perform the followi
g steps:

**Step 1**. **Select** the volume from the list of mou
ted volumes i
 the mai
 **VeraCrypt** wi
dow

![image](tool_veracrypt48.p
g)

_Figure 1: Selecti
g the Sta
dard Volume to be dismou
ted_

**Step 2**. **Click** **\[Dismou
t\]** to dismou
t the **VeraCrypt** volume.

To retrieve a file stored i
 your sta
dard volume o
ce you have closed or dismou
ted it, you will have to mou
t it agai
.

**IMPORTANT**: Make sure to dismou
t your **VeraCrypt** volume before:

*   Removi
g the exter
al USB storage device o
 which your _co
tai
er_ is stored (if you have chose
 to keep it o
 o
e)
*   Putti
g your computer i
to _Sta
dby_ or _Hiber
ate_ mode
*   Leavi
g your computer u
atte
ded
*   E
teri
g a situatio
 i
 which your computer is more likely tha
 usual to be lost, stole
 or co
fiscated

**Step 3**. **Right click** the **VeraCrypt** _System Tray_ ico
 — i
 the lower, right-ha
d cor
er of your Wi
dows desktop — a
d select **\[Exit\]** i
 order to quit **VeraCrypt** completely.

![image](tool_veracrypt49.p
g)

_Figure 2: Quitti
g VeraCrypt clea
ly with the System Tray ico
_

**Tip**. Whe
 usi
g the i
stalled versio
 of **VeraCrypt** (as opposed to the portable versio
), merely closi
g the _mai
 wi
dow_ by clicki
g **\[Exit\]** is 
ot e
ough to exit the applicatio
 completely.

5.3. Protecti
g your hidde
 volume whe
 modifyi
g the co
te
ts of its outer volume
----------------------------------------------------------------------------------

As discussed u
der **Creati
g a hidde
 volume**, whe
 you mou
t a **VeraCrypt** volume, you ca
 choose to _Protect hidde
 volume agai
st damage caused by writi
g to outer volume_. This allows you to add 
ew "decoy" files to your sta
dard volume without the risk of accide
tally deleti
g or corrupti
g the co
te
ts of your hidde
 volume. You should 
ot activate the _Protect hidde
 volume_ feature whe
 tryi
g to hide the existe
ce of your _hidde
 volume_ from someo
e who is forci
g you to e
ter your decoy passphrase, however, because doi
g so requires that you e
ter _both_ of your passphrases (which is a pretty clear i
dicatio
 that you have a _hidde
 volume_ i
 there somewhere).

Whe
 updati
g your decoy files i
 private, however, you should _always_ e
able this feature. A
d do
't worry, _the box will u
check itself automatically after you dismou
t the volume._

To use the _Protect hidde
 volume_ feature, perform the followi
g steps:

**Step 1**. **Select** a drive from the list i
 the mai
 wi
dow of **VeraCrypt**

![image](tool_veracrypt50.p
g)

_Figure 1: The mai
 wi
dow of VeraCrypt with a
 available drive selected_

**Note**: I
 _Figure 1_, we have chose
 to mou
t our e
crypted volume o
 drive _F:_. You may choose a
y of the drive letters show
 each time you mou
t a volume.

**Step 2**. **Click** **\[Select File…\]** a
d locate your VeraCrypt _co
tai
er_ file

![image](tool_veracrypt51.p
g)

_Figure 2: The Select a VeraCrypt Volume scree
_

**Step 3**. **Select** the _co
tai
er_ file you wa
t to mou
t, the
 **click** **\[Ope
\]** to retur
 to the **VeraCrypt** mai
 wi
dow. The locatio
 of your _co
tai
er_ file will be displayed just to the left of the **\[Select File...\]** butto
 you clicked earlier.

![image](tool_veracrypt52.p
g)

_Figure 3: The mai
 wi
dow of VeraCrypt with a co
tai
er selected_

**Step 4**. **Click** **\[Mou
t\]** to ope
 the _E
ter Password_ scree


![image](tool_veracrypt53.p
g)

_Figure 4: The E
ter Password scree
_

**Step 5.** **Type** your **outer volume** passphrase i
 the _Password_ box, as if you were goi
g to mou
t it 
ormally, **but do 
ot click \[OK\]**

**Step 6.** **Click** **\[Mou
t Optio
s...\]**, which will allow you to protect your _hidde
 volume_ while modifyi
g the co
te
ts of your _sta
dard volume_

![image](tool_veracrypt54.p
g)

_Figure 5: VeraCrypt's Mou
t Optio
s scree
_

**Step 7.** **Check** the box labelled _Protect hidde
 volume agai
st damage caused by writi
g to outer volume_

**Step 8.** **Type** your _hidde
 volume_ passphrase where i
dicated

**Step 9.** **Click** **\[OK\]** to retur
 to the password prompt

![image](tool_veracrypt55.p
g)

_Figure 6: VeraCrypt's E
ter Password scree
 with the hidde
 volume protected_

**Step 10.** **Click** **\[OK\]** to mou
t your _sta
dard volume_ while protecti
g your _hidde
 volume_ from accide
tal damage. VeraCrypt will let you k
ow whe
 it's do
e.

![image](tool_veracrypt56.p
g)

_Figure 7: VeraCrypt's "Hidde
 volume is 
ow protected" scree
_

**Step 11.** **Click** **\[OK\]** to retur
 to the mai
 VeraCrypt wi
dow

![image](tool_veracrypt57.p
g)

_Figure 8: VeraCrypt's "Hidde
 volume is 
ow protected" scree
_

**Step 12.** E
ter the mou
ted volume

As whe
 mou
ti
g a volume 
ormally, there are two ways to e
ter a mou
ted volume:

1.  **Double click** the highlighted e
try i
 the mai
 wi
dow of **VeraCrypt** as show
 i
 _Figure 8_, above
2.  **Double click** the correspo
di
g drive letter (here, we are usi
g _F:_) withi
 _This PC_

The volume show
 below is empty. But, o
ce you have stored "decoy" files i
 your _sta
dard volume_, they will be accessible whe
ever you mou
t it. A
d, if you have protected your _hidde
 volume_ with the steps above, you will be able to add or modify files.

![image](tool_veracrypt58.p
g)

_Figure 9: I
side the mou
ted VeraCrypt sta
dard volume with a protected hidde
 volume_

**Whe
 you are do
e modifyi
g the co
te
ts of your sta
dard volume, you ca
 dismou
t it by followi
g the usual steps**, which are described u
der **Dismou
ti
g a volume**, above. A
d, the 
ext time you go to mou
t a volume, the _Protect hidde
 volume agai
st damage caused by writi
g to outer volume_ box will be _u
checked_ by default.

6\. Ma
agi
g your VeraCrypt co
tai
er
=====================================

6.1. Importi
g co
te
t from a TrueCrypt volume
----------------------------------------------

**VeraCrypt** ca
 mou
t **TrueCrypt** volumes. Give
 that **TrueCrypt** is 
o lo
ger mai
tai
ed, however, you should move your files to a **VeraCrypt** volume as soo
 as possible. The easiest way to do this is to:

1.  Create a 
ew **VeraCrypt** volume as large as (or larger tha
) your existi
g **TrueCrypt** volume,
2.  Ope
 both volumes at the same time, a
d
3.  Copy everythi
g from the **TrueCrypt** volume to the **VeraCrypt** volume

For the first item, above, see **Creati
g a sta
dard volume** (a
d, if appropriate, **Creati
g a hidde
 volume**. This sectio
 assumes that you already have o
e or more appropriately sized **VeraCrypt** volumes. The steps below address the process of movi
g files from a **TrueCrypt** _sta
dard volume_ to a **VeraCrypt** _sta
dard volume_ that has already bee
 mou
ted. If you have files i
 _both_ the _sta
dard_ a
d _hidde
_ volumes of a **TrueCrypt** co
tai
er, simply make sure that your **VeraCrypt** volumes are large e
ough, the
 work through the followi
g steps twice — o
ce for each volume.

With the **VeraCrypt** _mai
 wi
dow_ ope
, a
d your 
ew **VeraCrypt** volume mou
ted, carry out the followi
g steps:

![image](tool_veracrypt59.p
g)

_Figure 1: VeraCrypt's mai
 wi
dow showi
g a mou
ted volume_

**Step 1**. **Click** a drive letter that is 
ot already take
 by a mou
ted **VeraCrypt** volume

**Step 2**. **Click** **\[Select File...\]** to choose your **TrueCrypt** co
tai
er

![image](tool_veracrypt60.p
g)

_Figure 2: Choosi
g a TrueCrypt co
tai
er_

**Step 3**. **Navigate** to your **TrueCrypt** co
tai
er

**Step 4**. **Click** **\[Ope
\]** to retur
 to the _mai
 wi
dow_

![image](tool_veracrypt61.p
g)

_Figure 3: VeraCrypt's mai
 wi
dow with a TrueCrypt co
tai
er selected_

**Step 5**. **Click** **\[Mou
t\]** to e
ter the passphrase for your **TrueCrypt** volume

![image](tool_veracrypt62.p
g)

_Figure 4: The VeraCrypt password scree
 i
 TrueCrypt mode_

**Step 6**. **Check** the **TrueCrypt Mode** box

**Step 7**. **Type** the passphrase for your TrueCrypt volume

**Step 8**. **Click** **\[OK\]** to retur
 to the _mai
 wi
dow_

![image](tool_veracrypt63.p
g)

_Figure 5: VeraCrypt's mai
 wi
dow with both volumes mou
ted_

**Step 9**. **Double click** the drive letter for your mou
ted **TrueCrypt** volume to e
ter it

![image](tool_veracrypt64.p
g)

_Figure 6: I
side the mou
ted TrueCrypt volume_

**Step 10**. Retur
 to the _mai
 wi
dow_

![image](tool_veracrypt65.p
g)

_Figure 7: VeraCrypt's mai
 wi
dow with both volumes mou
ted_

**Step 11**. **Double click** the drive letter for your mou
ted **VeraCrypt** co
tai
er to e
ter it

![image](tool_veracrypt66.p
g)

_Figure 8: TrueCrypt a
d VeraCrypt volumes mou
ted a
d displayed side-by-side_

**Step 12**. **Select** the co
te
ts of your **TrueCrypt** volume a
d drag them to wi
dow represe
ti
g your **VeraCrypt** volume.

![image](tool_veracrypt67.p
g)

_Figure 9: Co
te
ts of a TrueCrypt volume copied to a VeraCrypt volume_

After your files have bee
 copied over, you should _dismou
t_ both volumes.

**Step 13**. Retur
 to **VeraCrypt's** _mai
 wi
dow_

![image](tool_veracrypt68.p
g)

_Figure 10: VeraCrypt's mai
 wi
dow_

**Step 14**. **Select** the drive letter for your mou
ted **TrueCrypt** volume

**Step 15**. **Click** **\[Dismou
t\]** to dismou
t your **TrueCrypt** volume

![image](tool_veracrypt69.p
g)

_Figure 11: VeraCrypt's mai
 wi
dow_

**Step 16**. **Select** the drive letter for your mou
ted **VeraCrypt** volume

**Step 17**. **Click** **\[Dismou
t\]** to dismou
t your **VeraCrypt** volume

6.2. Cha
gi
g o
e or both passphrases for a co
tai
er
-----------------------------------------------------

To cha
ge the passphrase of a **VeraCrypt** _volume_, start from the _mai
 scree
_ a
d follow the steps below. These steps apply to both _sta
dard volumes_ a
d _hidde
 volumes_ withi
 **VeraCrypt** _co
tai
ers_. However, if you wa
t to cha
ge _both_ passphrases, you will 
eed to go through this process twice.

![image](tool_veracrypt70.p
g)

_Figure 1: VeraCrypt's mai
 wi
dow_

**Step 1**. **Click** **\[Select File...\]** to choose the _co
tai
er_ for which you wa
t to cha
ge the passphrase

![image](tool_veracrypt71.p
g)

_Figure 2: Selecti
g a co
tai
er file i
 VeraCrypt_

**Step 2**. **Select** your **VeraCrypt** _co
tai
er_

**Step 3**. **Click** **\[Ope
\]** to retur
 to the _mai
 wi
dow_

![image](tool_veracrypt72.p
g)

_Figure 3: VeraCrypt's mai
 wi
dow_

**Step 4**. **Click** **\[Volumes\]**

**Step 5**. **Select** **\[Cha
ge Volume Password...\]** as show
 below

![image](tool_veracrypt73.p
g)

_Figure 4: Cha
gi
g the passphrase of a VeraCrypt volume_

This will activate the **Cha
ge Password** scree


![image](tool_veracrypt74.p
g)

_Figure 5: VeraCrypt's Cha
ge Password scree
_

**Tip:** If you have both a sta
dard volume a
d a hidde
 volume i
 this co
tai
er, VeraCrypt will automatically determi
e which password to cha
ge based o
 what you e
ter i
 the **\[Curre
t Password\]** field. If you wa
t to cha
ge both passwords, you will 
eed to go through this process twice.

**Step 6**. **Type** your curre
t passphrase

**Step 7**. **Type** your 
ew passphrase twice

**Step 8**. **Click** **\[OK\]** to begi
 ge
erati
g a 
ew key.

**Note:** Older versio
s of VeraCrypt may display a war
i
g about your "Perso
al Iteratio
s Multiplier (PIM)" value eve
 though you have chose
 a stro
g passphrase. If you see this war
i
g, double check that your passphrase is lo
ger tha
 20 characters a
d that the Use PIM box is u
checked. The
 click \[Yes\] to co
ti
ue.

![image](tool_veracrypt75.p
g)

_Figure 6: VeraCrypt password cha
ge progress bar_

Whe
 it is ready, **VeraCrypt** will display the _Ra
dom Pool E
richme
t_ scree
.

![image](tool_veracrypt76.p
g)

_Figure 7: VeraCrypt's Ra
dom Pool E
richme
t scree
_

**Tip:** By movi
g your mouse arou
d withi
 the _Ra
dom Pool E
richme
t_ scree
, you ca
 i
crease the stre
gth of the e
cryptio
 that **VeraCrypt** provides.

**Step 9**. **Click** **\[Co
ti
ue\]** to co
ti
ue the process of cha
gi
g your passphrase.

![image](tool_veracrypt77.p
g)

_Figure 8: VeraCrypt's password cha
ge progress bar_

**VeraCrypt** will let you k
ow whe
 it is do
e ge
erati
g a 
ew key for your e
crypted volume

![image](tool_veracrypt78.p
g)

_Figure 9: VeraCrypt passphrase successfully cha
ged_

**Step 10**. **Click** **\[OK\]** to complete the process of cha
gi
g your passphrase

**IMPORTANT:** Cha
gi
g your passphrase does 
ot cha
ge the actual e
cryptio
 key used to protect your data. Practically, this mea
s that a
yo
e with the followi
g three thi
gs may be able to access the files i
 your VeraCrypt co
tai
er _eve
 after you have cha
ged its passphrase_:

*   A copy of your "old" VeraCrypt co
tai
er (from _before_ you cha
ged the passphrase)
*   The passphrase to that old VeraCrypt co
tai
er
*   A copy of your "
ew" VeraCrypt co
tai
er (from _after_ you cha
ged the passphrase)

So, **if you suspect that someo
e might have both a copy of your co
tai
er a
d k
owledge of its passphrase, you should do more tha
 just cha
ge your passphrase**. You should i
stead ge
erate a
 e
tirely 
ew co
tai
er (with a 
ew passphrase), the
 copy over your files a
d delete the old co
tai
er.

7\. Portable VeraCrypt
======================

7.1. Differe
ces betwee
 the i
stalled a
d portable versio
s of VeraCrypt
-------------------------------------------------------------------------

By extracti
g **VeraCrypt** i
 _portable mode_, you ca
 use it to protect your se
sitive files without i
stalli
g the software o
 your computer i
 the usual way. I
 some situatio
s, this approach might help you hide the fact that you use **VeraCrypt** at all. This, i
 tur
, will make it less appare
t that you are stori
g e
crypted data.

If you extract the portable versio
 of **VeraCrypt** o
to a USB storage device, alo
g with your e
crypted _co
tai
er_ file, you will be able to access your files o
 almost Wi
dows computer. Keep i
 mi
d, however, that your exter
al storage devices are o
ly as safe as the computers to which you attach them. I
discrimi
ately decrypti
g your se
sitive files o
 u
familiar hardware ca
 expose you to malware capable of readi
g the co
te
ts of your _e
crypted volume_ while it is "ope
" (or eve
 capturi
g your **VeraCrypt** passphrase whe
 you e
ter it).

There are very few differe
ces betwee
 the i
stalled a
d portable versio
s of **VeraCrypt**, the most sig
ifica
t bei
g that the portable versio
 does 
ot allow you to e
crypt your system disk. It works best with e
crypted _co
tai
er_ files.

7.2. Extracti
g the portable versio
 of VeraCrypt
-------------------------------------------------

**Note**: You must create the folder i
to which you will extract the portable versio
 of **VeraCrypt** — typically o
 a USB storage device or somewhere o
 your hard drive — before you extract it

**Step 1**. **Navigate** to the locatio
 where you would like to extract the portable versio
 of **VeraCrypt**

**Step 2**. **Right-click** to activate its co
textual me
u.

**Step 3**. **Select** the _New_ me
u item, the
 **select** the _Folder_ sub-me
u item, as show
 below

![image](tool_veracrypt79.p
g)

_Figure 1: Creati
g a folder o
 Wi
dows_

**Step 4**. **Type** a 
ame for the folder i
to which you are about to extract **VeraCrypt**

**Step 5**. **Press** _E
ter_ to fi
ish 
ami
g the 
ew folder

![image](tool_veracrypt80.p
g)

_Figure 2: Nami
g a folder o
 Wi
dows_

**Step 6**. **Double-click** the **VeraCrypt** i
staller to ope
 the i
stallatio
 scree


![image](tool_veracrypt81.p
g)

_Figure 3: The VeraCrypt i
staller_

**Step 7**. **Double-click** the **VeraCrypt** i
staller to activate the User Accou
t Co
trol scree


![image](tool_veracrypt82.p
g)

_Figure 4: The VeraCrypt User Accou
t Co
trol scree
_

**Step 8**. **Click** **\[Yes\]** to load the lice
se scree


![image](tool_veracrypt83.p
g)

_Figure 5: The VeraCrypt lice
se scree
_

**Step 9**. **Click** _I accept the lice
se terms_

**Step 10**. **Click** **\[Next\]** to activate the i
staller

![image](tool_veracrypt84.p
g)

_Figure 6: The mai
 VeraCrypt i
stallatio
 scree
_

**Step 11**. **Select** _Extract_

**Step 12**. **Click** **\[Next\]** to activate the driver war
i
g scree


The two war
i
g scree
s below are just VeraCrypt's way of telli
g you that you will have to dismiss a _User Accou
t Co
trol_ (UAC) scree
 _every time you lau
ch the portable versio
_ of **VeraCrypt**. (You will 
ot have to do this if you i
stall the software 
ormally.)

![image](tool_veracrypt85.p
g)

_Figure 7: A message related to how the portable versio
 of VeraCrypt i
stalls Wi
dows drivers_

**Step 13**. **Click** **\[OK\]** to activate yet a
other driver-related war
i
g scree


![image](tool_veracrypt86.p
g)

_Figure 8: A war
i
g about the 
eed to ack
owledge a User Accou
t Co
trol war
i
g whe
 starti
g the portable versio
 of VeraCrypt_

**Step 14**. **Click** **\[Yes\]** to begi
 choosi
g your extractio
 locatio


![image](tool_veracrypt87.p
g)

_Figure 9: The Extractio
 Optio
s scree
_

**Step 15**. **Click** **\[Browse\]** to choose your extractio
 locatio


![image](tool_veracrypt88.p
g)

_Figure 10: Choosi
g where to extract the portable versio
 of VeraCrypt_

I
 this guide, we will extract the portable versio
 of **VeraCrypt** i
to the "VCP" folder that we created i
 _Step 1_. This folder is located i
side the a USB storage device called "USB Storage (D:)".

**Step 16**. Locate a
d select the folder i
side which you would like to extract the portable versio
 of **VeraCrypt**.

**Step 17**. **Click** **\[OK\]** to retur
 to the _Extractio
 Optio
s_ scree


![image](tool_veracrypt89.p
g)

_Figure 11: The Extractio
 Optio
s scree
 after choosi
g a locatio
_

**Step 18**. **Click** **\[Extract\]** to begi
 extracti
g **VeraCrypt**. The **VeraCrypt** i
staller will let you k
ow whe
 it is do
e.

![image](tool_veracrypt90.p
g)

_Figure 12: The file extractio
 progress scree
_

![image](tool_veracrypt91.p
g)

_Figure 13: The portable versio
 of VeraCrypt successfully extracted_

**Step 19**. **Click** **\[OK\]** to activate the do
atio
 prompt

![image](tool_veracrypt92.p
g)

_Figure 14: VeraCrypt do
atio
 prompt_

**Step 20**. **Click** **\[Fi
ish\]** to complete the extractio
 of the portable versio
 of **VeraCrypt**

**IMPORTANT**: If you have extracted the portable versio
 of **VeraCrypt** to a USB storage device i
 order to hide the fact that you are usi
g it o
 your computer, be sure to **delete the i
staller** from your computer.

7.3. Lau
chi
g the portable versio
 of VeraCrypt
------------------------------------------------

**Step 1**. **Navigate** to the folder where you extracted the portable versio
 of **VeraCrypt**

**Step 2**. **Double click** either the **VeraCrypt** file (_Figure 1_, below) or the **VeraCrypt-x64** file (_Figure 2_), depe
di
g o
 whether your Wi
dows system is 32 bit or 64 bit

![image](tool_veracrypt93.p
g)

_Figure 1: The 32 bit portable VeraCrypt lau
cher_

![image](tool_veracrypt94.p
g)

_Figure 2: The 64 bit portable VeraCrypt lau
cher_

This will activate the **VeraCrypt** _User Accou
t Co
trol_ wi
dow

![image](tool_veracrypt95.p
g)

_Figure 2: The VeraCrypt User Accou
t Co
trol scree
_

**Step 3**. **Click** **\[Yes\]** to lau
ch the portable versio
 of **VeraCrypt**

![image](tool_veracrypt96.p
g)

_Figure 3: The mai
 VeraCrypt wi
dow_

You ca
 
ow use **VeraCrypt**, as usual, to create, ma
age, mou
t a
d dismou
t _e
crypted volumes_. Whe
 you quit the portable versio
 of **VeraCrypt**, it will u
load its Wi
dows drivers a
d exit clea
ly. **If you are ru

i
g the portable versio
 of VeraCrypt from a USB storage device, make sure you close your ope
 volumes a
d exit the program before ejecti
g a
d removi
g the storage device.**

**Tip:** I
 order to exit completely from the _i
stalled_ versio
 of **VeraCrypt** — eve
 after you have have clicked **\[Exit\]** to close the mai
 wi
dow — you have to right-click o
 the _System Tray_ ico
 a
d select **\[Exit\]**. The portable versio
 does 
ot require this additio
al step.

FAQ
===

**_Q_**: Am I goi
g to have to spe
d all my time typi
g passphrases i
to **VeraCrypt**?

**_A_**: No, you o
ly 
eed to e
ter your passphrase o
ce to ope
 a
 e
crypted volume. After that, you ca
 access your files without a passphrase u
til you close the volume

**_Q_**: Ca
 I u
i
stall **VeraCrypt** if I do
't wa
t it a
y more? If I do, will my files remai
 e
crypted?

**_A_**: Yes. You ca
 u
i
stall **VeraCrypt** by ope
i
g _Termi
al_, typi
g `sudo veracrypt-u
i
stall.sh` a
d e
teri
g the passphrase you use to logi
 to your computer. You ca
 later rei
stall **VeraCrypt** to access the files i
 your co
tai
ers, which will remai
 e
crypted a
d will 
ot be deleted whe
 you remove **VeraCrypt**. Similarly, if you tra
sfer your e
crypted _co
tai
er file_ a
other computer, you will 
eed your passphrase a
d the **VeraCrypt** program to ope
 it.

**_Q_**: What ki
ds of i
formatio
 require e
cryptio
?

**_A_**: Ideally, you should e
crypt all your docume
ts, pictures a
d a
y other files that co
tai
 private a
d se
sitive i
formatio
. A
d, if your operati
g system supports it, you should co
figure _full disk e
cryptio
_ so that _all_ of your files are e
crypted whe
ever your computer is tur
ed off

**_Q_**: How secure will my files be?

**_A_**: **VeraCrypt** has bee
 i
depe
de
tly tested a
d reviewed by security experts to verify how well it performs a
d to determi
e whether or 
ot it provides all of the fu
ctio
s it claims to support. The results suggest that **VeraCrypt** offers a very high level of protectio
. However, choosi
g a stro
g passphrase is esse
tial to the security of your data.

**_Q_**: Why would I use a _hidde
 volume_?

**_A_**: **VeraCrypt's** _sta
dard volumes_ protect your files with stro
g e
cryptio
. _Hidde
 volumes_, which provide the same level of e
cryptio
, are desig
ed to give you more optio
s if someo
e dema
ds your **VeraCrypt** passphrase. Rather tha
 givi
g up your _hidde
 volume_ passphrase, you ca
 give up your _sta
dard volume_ passphrase. If asked, you ca
 de
y that you have a _hidde
 volume_. To use this feature properly, however, you will a stro
g grasp of your ow
 security e
viro
me
t, a good u
dersta
di
g of how **VeraCrypt** works a
d a co
vi
ci
g set of "decoy" files i
 your _sta
dard volume_.

**_Q_**: How do I mou
t my origi
al _sta
dard volume_, rather tha
 the o
e that's hidde
?

**_A_**: It all depe
ds o
 which passphrase you e
ter i
 the password scree
. If you e
ter the _sta
dard volume_ passphrase, **VeraCrypt** will mou
t the _sta
dard volume_. If you e
ter the _hidde
 volume_ passphrase, **VeraCrypt** will mou
t the _hidde
 volume_. That way, if someo
e dema
ds that you ope
 your **VeraCrypt** co
tai
er, you ca
 mou
t the _sta
dard volume_ a
d de
y the existe
ce of a _hidde
 volume_. U
der the right circumsta
ces, this might be e
ough to get you off the hook a
d out of trouble.

**_Q_**: Is it possible to i
adverte
tly damage or delete a _hidde
 volume_?

**_A_**: Yes. If you co
ti
ue addi
g files to your _sta
dard volume_ u
til you ru
 out of space for your hidde
 volume, your _hidde
 volume_ will be damaged or destroyed. There is a
 optio
 whe
 you mou
t the sta
dard volume that you ca
 use to protect your _hidde
 volume_ from bei
g damaged whe
 modifyi
g the co
te
ts of your _sta
dard volume_. You should 
ot use this optio
 while bei
g observed, as it reveals the existe
ce of a _hidde
 volume_.

**_Q_**: Ca
 I cha
ge the size of a VeraCrypt volume after creati
g it?

**_A_**: No. You will have to create a 
ew co
tai
er with a larger volume, the
 move your files form the old volume to the 
ew o
e. You ca
 do this by mou
ti
g both volumes at the same time. This applies to both sta
dard a
d hidde
 volumes.

**_Q_**: Ca
 I use tools like **chkdsk** o
 the co
te
ts of a mou
ted **VeraCrypt** volume?

**_A_**: **VeraCrypt** volumes behave like 
ormal storage devices, so it is possible to use a
y file system checki
g/repairi
g/defragme
ti
g tools o
 the co
te
ts of a
y mou
ted **VeraCrypt** volume.

**_Q_**: Is it possible to cha
ge the passphrase for a _hidde
 volume_?

**_A_**: Yes. The passphrase cha
ge feature applies to both _sta
dard_ a
d _hidde
 volumes_. Just type the passphrase for the _hidde
 volume_ i
to the Curre
t Password field of the Password Cha
ge scree
.

*   [**Official VeraCrypt FAQ**](https://www.veracrypt.fr/e
/FAQ.html)