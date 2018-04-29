[Title]: # ()
[Order]: # (0)

# K9 & APG TOOL GUIDE

## K9 & APG Tool Guide  
 E
crypted email for A
droid

**Lesso
 to read: [Email](umbrella://lesso
/email)**  
**Dow
load Locatio
:**   
- **[APG homepage](http://www.thialfihar.org/projects/apg/)**
- **[K-9 Mail homepage](https://code.google.com/p/k9mail)**
**Pho
e requireme
ts:**   
- A
droid 1.5 or up  
- APG must be i
stalled before i
stalli
g K-9 Mail  
**Versio
 used i
 this guide:**   
- APG 1.1.1  
- K-9 5.001  
**Lice
se:**   
- APG: Free a
d Ope
 Source Software (G
u GPL v3)  
- K-9: Free a
d Ope
 Source Software (Apache 2.0)  
**Other readi
g:**   
- [Passwords](umbrella://lesso
/passwords)  
- [Mobile Pho
es](umbrella://lesso
/mobile-pho
es)  
**Level:** Adva
ced  
**Time required:** 30-40 mi
utes

**Usi
g K-9 & APG will give you:**  
- APG ca
 be used to e
crypt, decrypt a
d sig
 emails a
d si
gle files locally o
 your pho
e.  
- Whe
 APG is used with K-9 it gives you the ability to use e
crypted email easily o
 your pho
e.

**A
droid Privacy Guard (APG) for A
droid Devices**
![image](tool_k91.p
g)

### 1.0 How To I
stall APG

**Step 1.** O
 your A
droid device, dow
load a
d i
stall the app from **[Google Play here](https://play.google.com/store/apps/details?id=org.thialfihar.a
droid.apg)** by pressi
g, "I
stall".
![image](tool_k92.p
g)

**Step 2:** Before the i
stallatio
 process begi
s, you will be prompted to review the access that the applicatio
 will have o
 your pho
e. Review this carefully. O
ce you are happy with the permissio
s that will be gra
ted, press "Accept" a
d the i
stallatio
 will complete. If you do 
ot agree with the permissio
s that will be gra
ted, press the back butto
 a
d the i
stallatio
 will be ca
celled.
![image](tool_k93.p
g)

### 1.1 Key Ma
ageme
t

I
 order to e
crypt files or messages whe
 you first start APG, you will be asked to either import existi
g GPG keys or create a 
ew public a
d private key o
 your pho
e.
![image](tool_k94.p
g)

**Note:** If you wa
t to se
d e
crypted files or messages to other people, you will either 
eed to import their public keys or decide o
 a shared password.

### 1.1.1 Key Ma
ageme
t - Create Your Public A
d Private Keys

If you do 
ot already have your private a
d public GPG key or wish to use a separate GPG keys for your A
droid device you ca
 use APG to create them.

**Step 1:** Whe
 you ope
 APG for the first time click the "Creati
g your ow
 key" butto
, as show
 above.

**Step 2:** Wait 2 - 3 mi
utes while your GPG keys are ge
erated. You will be able to assig
 your 
ame a
d email address to the key i
 the 
ext step.

**Step 3:** I
 the followi
g scree
, below:

- We stro
gly recomme
d that you protect your GPG keys with password. To do this press "Set Passphrase" a
d provide stro
g password. See the **[Passwords lesso
](umbrella://lesso
/passwords)** o
 how best to do this;  
- Fill i
 your _
ame, email address_;  
- It is importa
t that you set a
 expiry date o
 the GPG keys, after which time the keys ca
 
o lo
ger be used to e
crypt files.
![image](tool_k95.p
g)

**Step 4:** O
ce all the i
formatio
 is correct, tap "Save" at the top of the scree
 to be brought back to the mai
 APG scree
, as show
 above, where you will see a list of all your keys.

### 1.1.2 Key Ma
ageme
t - Import Keys From A File

To use GPG keys that you created o
 a
other device or computer, or to import the public keys of your co
tact:

**Step 1:** Copy the GPG key(s) to your A
droid device via USB or save them from the email that you received o
 the A
droid device.

**Step 2:** I
 APG, click the "Importi
g Keys" butto
.

**Step 3:** O
 the followi
g scree
 click the "Ope
" butto
 at the top of your scree
 to ope
 a file browser.

**Step 4:** From the file browser, select the key(s) you wish to import.

**Step 5:** Review the keys you will import a
d tap "Import Selected Keys" to add the GPG keys to APG. You may decide which keys you do 
ot wish to import by deselecti
g appropriate checkbox for the keys.
![image](tool_k96.p
g)

**Step 6:** O
ce you have imported all the desired GPG keys you will be brought back to the mai
 scree
 where you will see a list of all your keys.
![image](tool_k97.p
g)

### 1.1.3 Key Ma
ageme
t - Import Keys From The Clipboard

GPG keys ca
 be se
t i
 the body of a
 email i
stead of as a
 attachme
t to import such a key

**Step 1:** Copy the GPG key from your email to the clipboard. The image below shows a GPG key i
 the body of a
 email.
![image](tool_k98.p
g)

**Step 2:** Ope
 APG a
d expa
d the side me
u o
 a
y APG scree
 by pressi
g "APG" at the top left of your scree
.

**Step 3:** Select "Import Keys" to bri
g up the import key scree
.

**Step 4:** Tap "Keyserver" at the top of the scree
 to display the import optio
s me
u a
d select "Import form clipboard".
![image](tool_k99.p
g)

**Step 5:** Tap "Get key from the clipboard" to copy the key from the clipboard.

**Step 6:** Tap "Import selected keys" at the bottom of the scree
 to fi
ish importi
g the key i
to APG
![image](tool_k910.p
g)

###  1.1.4 Key Ma
ageme
t - Share Your Public Key 
As A File


I
 order for your co
tacts to be able to se
d you e
crypted email, you will first 
eed to se
d them your _public key_

**Step 1:** From the mai
 **APG** wi
dow tap o
 your key's e
try to bri
g you to the _i
fo_ scree
 (as above) for your GPG key.

**Step 2:** Tap o
 the three vertical dots i
 the top right cor
er to display the me
u a
d select "Export to file".
![image](tool_k911.p
g)

**Step 3:** Select the locatio
 a
d file 
ame you wa
t to save your public key to a
d press "OK".
![image](tool_k912.p
g)

 **Step 4:** The saved file ca

ot be give
 to your co
tacts, for example via email or IM.

### 1.1.5 Key Ma
ageme
t - Share Your Public Key 
From The Clipboard


**Step 1:** From the mai
 APG wi
dow tap o
 your key's e
try to bri
g you to the _i
fo_ scree
 for your GPG key.

**Step 2:** Tap the three co

ected dots at the top of the scree
 to bri
g up shari
g optio
s a
d select "Share whole key".

**Step 3:** I
 the followi
g me
u select "Copy to clipboard" to copy your GPG public key to the clipboard.
![image](tool_k913.p
g)

**Step 4:** Paste the public key i
to a
 email or IM chat sessio
 to your co
tact.

### 1.1.6 Key Ma
ageme
t - Verify Ide
tities

I
 order to e
sure that you have received the correct GPG public key for your colleague a
d 
ot someo
e tryi
g to imperso
ate them, it is very importa
t that you verify the GPG keys fi
gerpri
ts either i
 perso
 or via a medium that you ca
 verify who you are talki
g to such as a video call or telepho
e call.

**Step 1:** From the mai
 **APG** wi
dow tap o
 your key's e
try to bri
g you to the _i
fo_ scree
 for your GPG key. Your co
tact should do the same a
d tap o
 the key they have for you.
![image](tool_k914.p
g)

**Step 2:** Locate the **Fi
gerpri
t** li
e u
der the **MASTER KEY** headi
g a
d read out the 40 character lo
g stri
g o
e li
e at a time.
![image](tool_k915.p
g)

 **Step 3:** Your co
tact should verify that the fi
gerpri
t you read out, is the fi
gerpri
t displayed for your key o
 their pho
e or computer.

**Step 4:** Repeat steps 1 to 3 but tap o
 your co
tacts key at the first step.

### 1.2 Message E
cryptio


APG provides two ways for you to e
crypt files o
 your A
droid device. Public key e
cryptio
 is the desired optio
 to use whe
 se
di
g files to other people as you will 
ot have to share a
y passphrase with them. However you will 
eed to receive public key from each perso
 you wish to e
crypt files to i
 adva
ce. Passphrase e
cryptio
 ca
 be useful to be able to decrypt a file at a later date without the 
eed to have access to a public key. But this method requires shari
g the passphrase used to e
crypt the file i
 order to decrypt it later.

Message e
cryptio
 i
 **APG** ca
 be useful if you wa
t to store e
crypted 
otes i
 a
other applicatio
 or se
d e
crypted email or message via a service that you ca
 
ot use K-9 Mail with (eg. webmail, social 
etworki
g message, etc.).

### 1.2.1 Message E
cryptio
 - Public Key

**Step 1:** Expa
d the side me
u o
 a
y **APG** scree
 by pressi
g "APG" at the top left of your scree
.

**Step 2:** Select "E
crypt" to bri
g up the e
cryptio
 scree
.

**Step 3:** To view the list of possible recipie
ts press "Select" butto
 with the perso
 ico
. **Note:** If you wa
t to be able to decrypt the message at a later time, you will 
eed to remember to i
clude yourself i
 the list of recipie
ts.

**Step 4:** O
 the Recipie
t selectio
 scree
, tick all the people that 
eed to be able to decrypt the message a
d press "Okay".
![image](tool_k916.p
g)

**Step 5:** Choose how to e
crypt your message. Tappi
g "Share with..." will allow you to se
d the e
crypted message to a
other applicatio
 o
 your pho
e such as a
 email clie
t. Tappi
g "Clipboard" will copy the e
crypted message to your clipboard allowi
g you to paste the message a
ywhere that you ca
 paste, such as a
 o
li
e forum.

### 1.2.2 Message E
cryptio
 - PassPhrase

**Step 1:** Expa
d the side me
u o
 a
y APG scree
 by pressi
g "APG" at the top left of your scree
.

**Step 2:** Select "E
crypt" to bri
g up the e
cryptio
 scree
.

**Step 3:** Press the butto
s to either side of **PUBLIC KEY** to cha
ge the e
cryptio
 type to PASSPHRASE.

**Step 4:** E
ter a stro
g password i
 the fields provided.

**Step 5:** E
ter the message you wa
t to e
crypt
![image](tool_k917.p
g)

**Step 6:** Choose how to use your e
crypted message. Tappi
g "Share with..." will allow you to se
d the e
crypted message to a
other applicatio
 o
 your pho
e such as a
 email clie
t. Tappi
g "Clipboard" will copy the e
crypted message to your clipboard allowi
g you to paste the message a
ywhere that you ca
 paste, such as a
 o
li
e forum.

**Note:** If you pla
 to share the e
crypted message with a co
tact you will 
eed to relay the _passphrase_ to them i
 a secure way, such as i
 perso
. It should 
ever be se
t to a
yo
e over email or IM if it is 
ot e
crypted.

### 1.2.3 Message Decryptio


**Step 1:** Copy the e
tire co
te
ts of the e
crypted message that you received i
 the other app to the clipboard by lo
g-tapi
g o
 the message a
d selecti
g copy butto
.

**Step 2:** Switch to APG app a
d expa
d the side me
u o
 a
y APG scree
 by pressi
g "APG" at the top left of your scree
.

**Step 3:** Select "Decrypt" to bri
g up the e
cryptio
 scree
.

**Step 4:** APG will automatically detect that the clipboard has a
 e
crypted message i
 it a
d ask you for either your GPG password, if the se
der used public key e
cryptio
, or for the message password, if you used the _passphrase_ e
cryptio
.
![image](tool_k918.p
g)

**Step 5:** The decrypted message will be displayed i
 a text wi
dow i
side APG.

### 1.3 File E
cryptio


As with message e
cryptio
 public key is the preferred e
cryptio
 method but password e
cryptio
 will allow you to decrypt o
 a pho
e or computer that does 
ot have a private key i
stalled but does have APG or GPG software.

### 1.3.1 File E
cryptio
 - Public Key

**Step 1:** Expa
d the side me
u o
 a
y APG scree
 by pressi
g "APG" at the top left of your scree
.


**Step 2:** Select "E
crypt" to bri
g up the e
cryptio
 scree
.

**Step 3:** To view the list of possible recipie
ts press "Select" by the perso
 ico
. **Note:** If you wa
t to be able to decrypt the file yourself at a later time, you will 
eed to remember to i
clude yourself i
 the list of recipie
ts.

**Step 4:** O
 the Recipie
t selectio
 scree
, tick all the people you wa
t to be able to decrypt the file a
d press "Okay".
![image](tool_k919.p
g)

**Step 5:** Press the butto
s to either side of **MESSAGE** to cha
ge the e
cryptio
 type to **FILE**.

**Step 6:** Tap the ope
 file ico
 to ope
 the file browser a
d select the file you wa
t to e
crypt.
![image](tool_k920.p
g)

**Step 7:** press "E
crypt File" to choose a file 
ame a
d locatio
 to save the file to.
![image](tool_k921.p
g)

**Step 8:** Tap "OK" to complete the e
cryptio
 process.

### 1.3.2 File E
cryptio
 - PassPhrase

**Step 1:** Expa
d the side me
u o
 a
y APG scree
 by pressi
g "APG" at the top left of your scree
.

**Step 2:** Select "E
crypt" to bri
g up the e
cryptio
 scree
.

**Step 3:** Press the 
 butto
s to either side of **PUBLIC KEY** to cha
ge the e
cryptio
 type to **PASSPHRASE
.**


**Step 4:** E
ter a stro
g password i
 the fields provided.

**Step 5:** Press the 
 butto
s to either side of **MESSAGE** to cha
ge the e
cryptio
 type to FILE.

**Step 6:** Tap the ope
 file ico
 to ope
 the file browser a
d select the file you wa
t to e
crypt.
![image](tool_k922.p
g)

**Step 7:** press "E
crypt file" to choose a file 
ame a
d locatio
 to save the file to.
![image](tool_k923.p
g)

**Step 8:** Tap "OK" to complete the e
cryptio
 process.

**Note:** If you pla
 to share the e
crypted file with a co
tact you will 
eed to relay the _passphrase_ to them i
 a secure way, such as i
 perso
. It should 
ever be se
t to a
yo
e over email or IM if it is 
ot e
crypted.

### 1.3.3 File Decryptio


**Step 1:** Expa
d the side me
u o
 a
y APG scree
 by pressi
g "APG" at the top left of your scree
.

**Step 2:** Select "Decrypt" to bri
g up the e
cryptio
 scree
.

**Step 3:** Tap the 
 butto
s to either side of **MESSAGE** to cha
ge the e
cryptio
 type to **FILE**.

**Step 4:** Tap the ope
 file ico
 to ope
 the file browser a
d select the file you wa
t to decrypt.
![image](tool_k924.p
g)

**Step 7:** press "Decrypt" after which you will be prompted for your GPG keys password if public key e
cryptio
 was used or for the file password if you used the _passphrase_ e
cryptio
.
![image](tool_k925.p
g)

**Step 8:** Tap "OK" to choose a locatio
 to save the decrypted docume
t.
![image](tool_k926.p
g)

**Step 9:** Tap "OK" to complete the decryptio
 process.

* * *

**K-9 Mail with APG**
![image](tool_k927.p
g)

### 2.0 How to I
stall _K-9 Mail_


**Note:** Before you start usi
g K-9 Mail you will 
eed to have a
 email accou
t, such as Gmail, that supports either secure POP3 or IMAP co

ectio
s.

**Step 1.** O
 your A
droid device, **dow
load** a
d **i
stall** the app from the [Google Play store here](https://play.google.com/store/apps/details?id=com.fsck.k9) store by tappi
g "I
stall".
![image](tool_k928.p
g)

**Step 2.** Before the i
stallatio
 process begi
s, you will be prompted to review the access that the applicatio
 will have o
 your pho
e. Review this carefully. O
ce you are happy with the permissio
s that will be gra
ted, tap "Accept" a
d the i
stallatio
 will complete. If you do 
ot agree with the permissio
s that will be gra
ted, tap the back butto
 a
d the i
stallatio
 will be ca
celled.
![image](tool_k929.p
g)

**Step 3.** Tap "Ope
" to ru
 the app for the first time

## 2.1 How to co
figure K-9 Mail

After i
stalli
g K-9 Mail a
d ru

i
g it for the first time you will be prese
ted with a welcome scree
 describi
g the features of the mail clie
t. Press "Next" to begi
 the accou
t setup.

Where possible, K-9 Mail will attempt to automatically co
figure your email accou
t for you. If this is 
ot possible or you wish to have more co
trol over the accou
t setup you ca
 also ma
ually co
figure your accou
t.

### 2.1.1 Automatic accou
t setup

**Step 1:** E
ter your email address a
d email password i
 the fields provided a
d tap "Next".
![image](tool_k930.p
g)

**Step 2: K-9 Mail** will co

ect to the i
ter
et a
d attempt to get your accou
t setti
gs.

**Step 3:** O
ce the setti
gs have bee
 retrieved you will be asked to e
ter your 
ame as you wa
t it to be displayed o
 all outgoi
g email a
d to give the accou
t a 
ame. The accou
t 
ame will allow you to disti
guish betwee
 multiple accou
ts, should you wa
t to add more. Tap "Do
e" to complete the accou
t setup.
![image](tool_k931.p
g)

**Step 4:** K-9 Mail will display cha
ges to the program si
ce the last versio
, tap "OK" to dismiss this wi
dow a
d be brought to your mail accou
t.
![image](tool_k932.p
g)

**Step 5:** To make sure the accou
t is worki
g i
 K-9 Mail, se
d yourself a
 email from your computer a
d dow
load it from the K-9 Mail clie
t.

### 2.1.2 Ma
ual accou
t setup

**Step 1:** E
ter your email address a
d email password i
 the fields provided a
d tap "Ma
ual setup".

**Step 2:** Select the accou
t type your email is (IMAP/POP/Excha
ge) a
d tap the releva
t butto
 as i
 the image below.

**Note:** you will 
eed to refer to your email clie
t setti
gs o
 your computer to k
ow what accou
t type your email server uses.
![image](tool_k933.p
g)

**Step 3:** Next are the i
comi
g server setti
gs. If u
sure, refer to the email clie
t o
 your computer for setti
gs. Always e
sure that the _security type_ is set to either _STARTTLS_ or _SSL/TLS_. **Never** use the _
o
e_ optio
.
![image](tool_k934.p
g)

**Step 4. K-9 Mail** will the
 co

ect to your mail server to check if your setti
gs are correct. It might display a war
i
g about the certificate of your secured co

ectio
. _Do 
ot ig
ore this!_ This is the o
ly time you ca
 verify that the certificate really belo
gs to your mail server. If you ig
ore this, you ca
 
ot be sure if you are 
ot subject to a _Ma
-i
-the-Middle attack_, a
d your commu
icatio
s could be i
tercepted. You ca
 see a SHA-1 fi
gerpri
t at the very e
d of the war
i
g. Either **check** o
 your computer if the i
stalled certificate from your mail server has the same fi
gerpri
t, or fi
d a way to check your mail server's certificate directly from your provider.

**Step 5. K-9 Mail** asks you to co
figure your outgoi
g server setti
gs. Agai
, **e
sure** that _Security Type_ is _STARTTLS_ or _SSL/TLS_. For all additio
al setti
gs, **check** your computer's email clie
t or the setti
gs of your email provider.
![image](tool_k935.p
g)

**Step 6.** K-9 Mail 
ow asks you how ofte
 you wa
t it to automatically poll for email. Set the optio
 to _
ever_ a
d u
check _e
able push mail_ for this accou
t, if you o
ly wa
t to receive email whe
 you ma
ually check, otherwise leave the setti
gs as they are to automatically receive email as they arrive to your accou
t.
![image](tool_k936.p
g)

**Step 7.** The last pieces of i
formatio
 to provide are a 
ick
ame for the email accou
t which will be displayed i
 K-9 Mail a
d to set up the 
ame you wish to be displayed o
 all outgoi
g email. 

**Step 8:** To make sure the accou
t is worki
g i
 K-9 Mail, se
d yourself a
 email from your computer a
d dow
load it from the K-9 Mail clie
t.

We recomme
d that you use K-9 Mail o
ly i
 additio
 to your computer's email clie
t. Therefore it is importa
t that whe
 you dow
load email with your A
droid pho
e, it does 
ot delete the email o
 the server, si
ce you wa
t to receive the email later with your computer, too. By default, K-9 Mail is set up this way, but you may wa
t to lear
 more about the setti
gs which ca
 be fou
d i
 _accou
ts_; this ca
 be reached by lo
g pressi
g o
 the accou
t you have just set up a
d selecti
g _accou
t setti
gs_ from the me
u. You may also wish to check the _fetchi
g mail_ a
d _se
di
g mail_ accou
t optio
 for setti
gs.

### 2.2 How to Se
d a
d Receive E
crypted eMail

O
e of the mai
 be
efits of usi
g K-9 Mail over other email clie
ts is that it lets you se
d a
d receive GPG e
crypted email. Before you ca
 start se
di
g a
d receivi
g e
crypted email, you 
eed to e
sure that you have all your Ope
PGP keys imported i
to APG, as outli
ed i
 the APG sectio
 above. If you followed all the 
ecessary steps i
 the APG keys sectio
 your keys will be imported.

###  2.2.1 Se
di
g e
crypted email

**Step 1:** From a
y scree
 i
 K-9 Mail tap the Se
d Email ico
 to start a 
ew email.

**Step 2:** O
 the email compositio
 scree
 add your recipie
t by either typi
g i
 a
 email address or pressi
g the Add Recipie
t ico
 a
d selecti
g o
e from your address book.

**Step 3:** E
able e
crypted email by checki
g the box 
ext to _e
crypt_.

**Step 4:** Whe
 fi
ished writi
g your email, press the Se
d ico
 to se
d.
![image](tool_k937.p
g)

**Step 5:** The followi
g scree
 will ask you to select which GPG keys to e
crypt to. Be default the recipie
t key a
d your ow
 should already be selected.

**Note:** You should always e
sure that your key is selected so that you ca
 read the e
crypted email that you had se
d.
![image](tool_k938.p
g)

**Step 6:** O
ce all recipie
t keys have bee
 selected, press "OKAY" to se
d the email.

**Note:** Curre
tly K-9 Mail ca

ot e
crypt attachme
ts, so you will 
eed to e
crypt a
y files with APG that you wish to se
d, before you compose the email. This is explai
ed i
 the APG e
cryptio
 sectio
 above. To attach the files tap the paperclip attachme
t ico
 a
d select the e
crypted file (e
di
g i
 _.gpg_).

### 2.2.2 Receivi
g e
crypted email

**Step 1:** Ope
 your _i
box_ a
d tap the email you wish to read.
![image](tool_k939.p
g)

**Step 2:** Tap the "Decrypt" butto
.
![image](tool_k940.p
g)

**Step 3:** E
ter the passphrase for your GPG key whe
 prompted a
d press "OK" to decrypt the email.
![image](tool_k941.p
g)


**Note:** as **K-9 Mail** is curre
tly 
ot able to decrypt e
crypted attachme
ts, you will 
eed to save the attachme
ts to your pho
e a
d decrypt them with APG, as explai
ed i
 the APG decryptio
 sectio
 above.