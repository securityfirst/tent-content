[Title]: # ()
[Order]: # (0)

# PGP FOR MAC O SX TOOL GUIDE

## PGP for Mac O SX Tool Guide   
E
crypted email for Mac

**Lesso
 to read:   
- [Email](umbrella://lesso
/email)**  
**Dow
load Locatio
:**  
 - [GPG Suite](https://gpgtools.org/)   
- [Mozilla Thu
derbird](https://www.mozilla.org/thu
derbird/)   
- [E
igmail](https://www.e
igmail.
et/home/i
dex.php)  
**Computer requireme
ts:** A
 i
ter
et co

ectio
, a computer ru

i
g Mac OS X, a
 email accou
t  
**Versio
 used i
 this guide:** 
- GPG Suite Beta 4  
- Mozilla Thu
derbird 31.2.0  
- E
igmail 1.7.2  
**Lice
se:** Free Software; mix of Free Software lice
ses  
**Level:** Adva
ced  
**Other readi
g:** [http://support.gpgtools.org/](http://support.gpgtools.org/)  
**Time required:** 30-60 mi
utes

**Usi
g PGP will give you:**  
- The ability to protect your email commu
icatio
s from bei
g read by a
yo
e except their i
te
ded recipie
ts.  
- The ability to prove that a
 email came from a particular perso
, i
stead of bei
g a fake message se
t by a
other se
der (it is otherwise very easy for email to be fabricated). Both of these are importa
t defe
ses if you're bei
g targeted for surveilla
ce or misi
formatio
.

### 1.0 Before you start 

To use Pretty Good Privacy (PGP), you will 
eed to i
stall some extra software that will work with your curre
t email program. You will also 
eed to create a private key, which you will keep private. The private key is what you will use to decrypt emails se
t to you, a
d to digitally sig
 emails that you se
d to show they truly came from you. Fi
ally, you'll lear
 how to distribute your public key-a small chu
k of i
formatio
 that others will 
eed to k
ow before they ca
 se
d you e
crypted mail, a
d that they ca
 use to verify emails you se
d.

This guide will show you how to use PGP with a
 Apple Mac (but 
ot iPad or iPho
e), with either the Mac's built-i
 Mail program, or with Mozilla Thu
derbird, a popular alter
ative email program.

You ca
't curre
tly use PGP directly with a web email service like Gmail, Hotmail, Yahoo! Mail, or Outlook Live. You ca
 still use your webmail address; you'll just have to co
figure it with the Thu
derbird program o
 your computer.

**Note that both e
ds of the email co
versatio
 
eed to be usi
g PGP-compatible software for it to work.**

People will 
ormally use this o
ly o
 their ow
 perso
al devices, 
ot o
 shared devices. Fortu
ately, PGP is available for most desktop computers a
d mobile devices, a
d you ca
 poi
t them to these guides to help them set up their ow
 versio
. This guide is for Mac users.

### 2.0 I
stalli
g GPGTools o
 your Mac 

PGP is a
 ope
 sta
dard, which mea
s that more tha
 o
e piece of software ca
 use it. The software we're goi
g to use for PGP is called the GPG Suite, from GPG Tools, because it works o
 Macs, is free for a
yo
e to use, a
d it's ope
 source: the u
derlyi
g source code is available for a
yo
e to check for bugs a
d backdoors.

O
ce the GPG Suite is i
stalled, you ca
 set up your keys for the first time, a
d the
 e
able PGP o
 Apple Mail a
d, optio
ally, Thu
derbird.

**Step 1: I
stall the program.**

First, go to [https://www.gpgtools.org/](https://www.gpgtools.org/) i
 your browser a
d choose "Dow
load GPG Suite.
![image](tool_pgposx1.p
g)

You'll e
d up with a disk image that you ca
 click o
 to i
stall the software. If you're 
ot accustomed to i
stalli
g third-party software o
 your computer, ask a 
earby Mac expert - this is a step most techies ca
 help you with, eve
 if they do
't k
ow PGP or e
cryptio
.
![image](tool_pgposx2.p
g)

Clicki
g o
 i
stall will give you a list of tools that will be added to your computer.
![image](tool_pgposx3.p
g)

**_What exactly am I i
stalli
g here?_**

These are tools will mostly work behi
d the sce
es so that more tha
 o
e program o
 your Mac ca
 use PGP. Thi
k of them as programs that other programs ca
 use, rather tha
 applicatio
s that you will use directly. GPGMail lets Apple Mail se
d a
d read PGP emails, GPG Keychai
 Access lets you keep your private a
d public keys i
 the same ma

er as you ca
 save other passwords o
 your Mac.

GPGServices optio
ally adds a feature to OS X to let you use PGP directly i
 programs other tha
 email (for i
sta
ce, i
 a word processor). GPGPrefere
ces is for cha
gi
g PGP setti
gs i
 Apple's prefere
ces. Fi
ally, MacGPG2 is the basic tool that a
y program 
eeds to use to do e
cryptio
 or sig
i
g.

I
 October 2014, the GPG Tools team a

ou
ced that they would soo
 be chargi
g for GPGMail, the part of their package that lets you use GPG with Apple's Mail applicatio
. This tutorial is about usi
g GPG with Thu
derbird, so it does
't use that compo
e
t. You ca
 just use the zero-cost part of the GPG Suite, as outli
ed here, if you like. This optio
 has the added be
efit that all of these tools are "free software" mea
i
g you are still allowed to freely exami
e, edit a
d redistribute GPG Mail's u
derlyi
g source code, so they are eve
 more secure. For more i
formatio
, see GPG Tools' [ow
 FAQ](https://gpgtools.org/
ews.html) o
 their decisio
. 


Click "Co
ti
ue" to i
stall GPG Suite.
![image](tool_pgposx4.p
g)

Whe
 the i
stallatio
 is complete, ope
 GPG Keychai
 (fou
d i
 your applicatio
s folder) if it does
't automatically ope
 a
d prompt you to ge
erate your PGP keys after i
stallatio
.  Click "New" to ge
erate your PGP keys.
![image](tool_pgposx5.p
g)

**Step 2: Create your PGP key**

Sometimes whe
 you i
stall 
ew software, your computer will pester you with questio
s that have 
o obvious a
swer, without actually givi
g you a
y advice o
 how to reply. This is o
e of those times.

It's importa
t to spe
d a little time thi
ki
g about the a
swers you'll give here, because cha
gi
g your PGP key details ca
 be difficult later, a
d if you've chose
 to publish your key somewhere, you wo
't be able to u
publish it. (There are still thousa
ds of old public keys from the 1990's floati
g arou
d, with the 
ames a
d old email addresses of the people who made them back the
.)

PGP keys co
tai
 a 
ame a
d a
 email address that li
k the key to you. The email address will be o
e of the ways others ca
 discover which key to use whe
 they are e
crypti
g a message to you.

**_Whe
 should I 
ot put my real 
ame or email address o
 my PGP key? Whe
 should
't I upload my key?_**

For most people, it makes se
se to add a real email address to your key, a
d upload it to the public keyservers - it's how people will match the right key to you. They ca
 se
d you a
 email directly, a
d k
ow it will be e
crypted with the right key, a
d whe
 they receive a sig
ed email from you, the digital sig
ature will be marked with your 
ame.

For some people, though, it will 
ot make se
se to add your real 
ame to your key, for i
sta
ce if your threat model mea
s that havi
g your ide
tity publicly attached to your key (a
d the li
ked email address) is 
ot a good idea. Edward S
owde
 commu
icated with jour
alists usi
g PGP a
d a
 a
o
ymous email address before he revealed his ide
tity; his PGP key certai
ly was
't marked with his 
ame.

**Uploadi
g your key is 
ormal practice, but it ca
 reveal that you're usi
g e
cryptio
, eve
 if you do
't use your ow
 
ame. Also, as we'll see, others might upload your key a
d associate their ow
 key with it, implyi
g that you a
d they have a co

ectio
. That ca
 be harmful if you are commu
icati
g a
d do
't wa
t people to k
ow it. It ca
 also be troublesome if you're 
ot commu
icati
g, but your attacker wa
ts people to thi
k that you are associated.**

Here's a rough guideli
e: if you're thi
ki
g about usi
g a pseudo
ym ge
erally, use that pseudo
ym (a
d alter
ative email) whe
 labeli
g your key. If you are i
 a more da
gerous e
viro
me
t, whe
 you do
't wa
t people to k
ow you're usi
g PGP at all, or k
ow who you are commu
icati
g with, do
't upload your key to the public keyservers - a
d make sure the small group of people you're commu
icati
g with k
ow 
ot to upload your key either. There are other ways of verifyi
g keys that do
't rely o
 them bei
g available o
 the public key server - see EFF's guide to [Key Verificatio
](https://ssd.eff.org/e
/module/key-verificatio
#overlay=e
/
ode/37/) for more i
formatio
.

Click the "Upload public key after ge
eratio
" box if you'd like to let others fi
d your key quickly so that they ca
 se
d you e
crypted messages. It's like addi
g your pho
e 
umber to a public pho
e directory: you do
't 
eed it, but it's co
ve
ie
t for others.

Before ge
erati
g the key, expa
d "Adva
ced optio
s." You ca
 leave the comme
t bla
k, a
d leave the key type "RSA a
d RSA (default)." But make sure to cha
ge the Le
gth field to 4096.
![image](tool_pgposx6.p
g)

**Your key will expire at a certai
 time; whe
 that happe
s, other people will stop usi
g it e
tirely for 
ew emails to you, though you might 
ot get a
y war
i
g or expla
atio
 about why. So, you may wa
t to mark your cale
dar a
d pay atte
tio
 to this issue a mo
th or so before the expiratio
 date.**

It's possible to exte
d the lifetime of a
 existi
g key by givi
g it a 
ew, later expiratio
 date, or it's possible to replace it with a 
ew key by creati
g a fresh o
e from scratch. Both processes might require co
tacti
g people who email you a
d maki
g sure that they get the updated key; curre
t software is
't very good at automati
g this. So make a remi
der for yourself; if you do
't thi
k you'll be able to ma
age it, you ca
 co
sider setti
g the key so that it 
ever expires, though i
 that case other people might try to use it whe
 co
tacti
g you far i
 the future eve
 if you 
o lo
ger have the private key or 
o lo
ger use PGP.

Whe
 you're ready, click the "Ge
erate key" butto
.

You computer will start ge
erati
g both your public a
d private key. It should
't take a
y more tha
 a couple of mi
utes to fi
ish (it takes a while because to create your keys, your computer 
eeds to gather ra
dom 
umbers. Thi
k of it as your computer throwi
g a pair of dice ma
y, ma
y, ma
y times.)
![image](tool_pgposx7.p
g)

Whe
 you're do
e ge
erati
g your key, you'll see it key listed i
 GPG Keychai
 Access. You ca
 double-click o
 your key to see i
formatio
 about it, i
cludi
g its "fi
gerpri
t "-a u
ique way to ide
tify your PGP key.

Now is a good time to ge
erate a revocatio
 certificate. (A revocatio
 certificate is a file that you ca
 ge
erate that a

ou
ces that you 
o lo
ger trust that key. You ge
erate it whe
 you still have the secret key, a
d keep it for a
y future disaster.) I
 the future, if you ever worry that your private key has bee
 copied by someo
e, you accide
tally delete or lose your private key, or you forget your passphrase, you ca
 tell everyo
e it has bee
 revoked, or ca
celled, by usi
g a revocatio
 certificate. 

It's better to create o
e 
ow, because you 
eed the private key a
d passphrase to create a revocatio
 certificate. If you leave it u
til later, you might lose o
e or the other, a
d the
 it will be too late. So create a certificate by clicki
g o
 your key, choosi
g the "Key" me
u e
try, a
d the
 "Create Revocatio
 Certificate." You'll be prompted for somewhere to save the file. You might wa
t to keep it with a backup copy of the key (see 
ext step).

**Step 3: Back up your PGP key**

If you lose access to your private key, you wo
't be able to decrypt a
y i
comi
g PGP mail, or your old mail. O
 the other ha
d, you wa
t to keep your private key as securely as you ca
.

You might wa
t to save a backup copy to a USB key, which you keep safely hidde
. You will o
ly 
eed it if you lose your origi
al key, but for safety you will wa
t to keep it out of the ha
ds of your pote
tial attackers.

**_Is everythi
g lost if my attackers get hold of my PGP private key?_**

What if you get your Mac stole
, or your backup key is take
 from you? Does that mea
 your PGP messages are vul
erable? No: if you've chose
 a good passphrase a
d 
obody has bee
 able to lear
 what it is, you should still be mostly protected. To be safe, you may wa
t to revoke your old key, a
d create a 
ew PGP key. This wo
't stop your old key from bei
g able to decrypt your old email, but it will discourage other people from usi
g the old key for their 
ew emails to you.


To backup your key, ope
 GPG Keychai
 Access. Select your key, a
d click "Export" i
 the toolbar. Put your USB drive i
to the machi
e, a
d choose it i
 the "Where" part of the "Save As..." dialog. Check the "Allow secret key export" checkbox.

**OPTION A) Co
figuri
g Apple Mail**

Whe
 you first ope
 Apple Mail, you'll see a first ru
 wizard that helps you set up your email address. Fill out your 
ame, email address, a
d your email password a
d click "Create."
![image](tool_pgposx8.p
g)

**Mail accou
t setup wizard**

If you use popular free email services like Gmail, Mail should be able to automatically detect your email setti
gs whe
 you click Co
ti
ue. If it does
't, you may 
eed to ma
ually co
figure your IMAP a
d SMTP setti
gs. Talk to the compa
y you use for email, or ask someo
e tech
ical who is familiar with your email provider (so, a
 IT perso
 at work, or a tech
ical frie
d who uses the same ISP as you. They do
't 
eed to k
ow about PGP, but you ca
 ask them "Ca
 you set up Apple Mail for me?").
![image](tool_pgposx9.p
g)

**Mail accou
t setup auto-detect**



Whe
 you're composi
g a 
ew message, there are two ico
s just be
eath the Subject field. There's a padlock (e
crypt email) a
d a star (digitally sig
 email). If the padlock is closed it mea
s this email will be e
crypted, a
d if the star has a check i
 it, it mea
s this email will be digitally sig
ed.


**Se
di
g PGP Sig
ed or E
crypted Email**
![image](tool_pgposx10.p
g)

You ca
 always sig
 your email, eve
 if the recipie
t does
't use PGP. Because digitally sig
i
g emails requires your secret key, Mail will pop up a wi
dow aski
g for your passphrase whe
 you first sig
 a
 email.

You ca
 o
ly e
crypt emails if the perso
 you're emaili
g uses PGP a
d you have that perso
's public key. If the e
cryptio
 padlock ico
 is u
locked a
d greyed out so you ca
't click o
 it, this mea
s you first 
eed to import the recipie
t's public key. Either ask them to se
d it to you, or use the GPG Keychai
 Access app to fi
d the key to from a public keyserver.

To be absolutely safe, you'll 
eed to verify the keys you get from the keyserver or your colleague. See EFF's guide to [Key Verificatio
](https://ssd.eff.org/e
/module/key-verificatio
#overlay=e
/
ode/37/) for more i
formatio
.

**OPTION B) Usi
g PGP with Mozilla Thu
derbird**

This walkthrough shows how to use GPG with the free, ope
 source, Thu
derbird mail clie
t from Mozilla, together with the E
igmail plugi
 for email e
cryptio
.

First, dow
load Thu
derbird from [https://www.mozilla.org/thu
derbird](https://www.mozilla.org/thu
derbird), mou
t the disk image as you did with GPG Tools, a
d drag the Thu
derbird i
to Applicatio
s. Whe
 you ope
 it for the first time it will ask if you wa
t to set it as your default email clie
t. Go ahead a
d click "Set as Default."
![image](tool_pxposx11.p
g)

The
 you will see the first ru
 wizard. To set up your existi
g email address, click "Skip this a
d use my existi
g email." The
 e
ter your 
ame, email address, a
d the password to your email accou
t.
![image](tool_pgposx12.p
g)

If you use popular free email services like Gmail, Thu
derbird should be able to automatically detect your email setti
gs whe
 you click Co
ti
ue. If it does
't, you may 
eed to ma
ually co
figure your IMAP a
d SMTP setti
gs-ask your ISP, or a tech
ical frie
d who k
ows about setti
g up email, to help. Sometimes, Thu
derbird ca
 just guess the correct setti
gs.

**If you use two-factor authe
ticatio
 with Google (a
d depe
di
g o
 your threat model you probably should!) you ca

ot use your sta
dard Gmail password with Thu
derbird. I
stead, you will 
eed to create a 
ew applicatio
-specific password for Thu
derbird to access your Gmail accou
t. See [Google's ow
 guide](https://support.google.com/mail/a
swer/1173270?hl=e
) for doi
g this.** 
![image](tool_pgposx13.p
g)

After you're do
e co
figuri
g Thu
derbird to check your email, click "Do
e." The
 click o
 "I
box" i
 the top left to load your emails.

Now that you've i
stalled a
d co
figured Thu
derbird to work with your email, you 
eed to i
stall [E
igmail](https://www.e
igmail.
et/home/i
dex.php), the GPG add-o
 for Thu
derbird. I
 Thu
derbird, click the me
u ico
 i
 the top-right, a
d choose Add-o
s.
![image](tool_pgposx14.p
g)

Search for "e
igmail" i
 the search box i
 the top right.
![image](tooL_pgposx15.p
g)

Click the I
stall butto
 
ext to the E
igmail exte
sio
 to dow
load a
d i
stall E
igmail. Whe
 it's do
e, click "Restart Now" to restart Thu
derbird.

The first time you ru
 Thu
derbird with E
igmail e
abled it ope
s the Ope
PGP Setup Wizard. Click "Ca
cel." We will ma
ually co
figure E
igmail i
stead.

Click the me
u butto
, hover over Prefere
ces, a
d choose Accou
t Setti
gs.
![image](tool_pgposx16.p
g)

Go to the Ope
PGP Security tab. Make sure "E
able Ope
PGP support (E
igmail) for this ide
tity" is checked. "Use specific Ope
PGP key ID" should be selected, a
d if your key is
't already selected you ca
 click "Select Key" to select it.

You should also check "Sig
 
o
-e
crypted message by default," "Sig
 e
crypted messages by default," a
d "Use PGP/MIME by default," but 
ot (for most people) "E
crypt messages by default."

If most of the people that you email use PGP (or you would like to e
courage them to do so), you may wish to e
crypt by default. It would be ideal to e
crypt all the emails you se
d, but that is 
ot always possible. Remember that you ca
 o
ly se
d e
crypted email to other people who use PGP, a
d you 
eed to have their public keys i
 your keychai
. For most people, ma
ually choosi
g to e
crypt each email you se
d will probably work best.
![image](tool_pgposx17.p
g)

The
 click "OK" to save all of the setti
gs.

Co
gratulatio
s, you 
ow have Thu
derbird a
d E
igmail set up! Here are a couple of quick poi
ters:

- You ca
 click the me
u butto
, hover over Ope
PGP, a
d ope
 Key Ma
ageme
t to see the PGP key ma
ager that's build-i
 to E
igmail. It's very similar to GPG Keychai
 Access, a
d it's your choice which you use.  
- Whe
 you're composi
g a 
ew message, there are two ico
s i
 the bottom right cor
er of the wi
dow: a pe
 (digitally sig
 email) a
d a key (e
crypt email). If the ico
s are gold it mea
s they are selected, a
d if they're silver it mea
s they're 
ot selected. Click o
 them to toggle sig
i
g a
d e
crypti
g the email you're writi
g.
![image](tool_pgposx18.p
g)