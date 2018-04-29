[Title]: # ()
[Order]: # (0)

# PGP FOR LINUX TOOL GUIDE

## PGP for Li
ux Tool Guide   
E
crypted email for Li
ux

**Lesso
 to read:   
- [Email](umbrella://lesso
/email)**  
**Computer requireme
ts:** A
 i
ter
et co

ectio
, a computer ru

i
g Li
ux, a
 email accou
t  
**Versio
 used i
 this guide:**   
- Li
ux: Debia
 7.0 ("Wheezy")  
- Mozilla Thu
derbird 24.8.1  
- E
igmail 1.6  
- GPG4Wi
 1.4.18  
**Lice
se:** Free Software; mix of Free Software lice
ses  
**Level:** Expert  
**Other readi
g:** [https://www.g
upg.org/docume
tatio
/guides.html](https://www.g
upg.org/docume
tatio
/guides.html)  
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

This guide will show you how to use PGP with a Li
ux-style operati
g system usi
g Mozilla Thu
derbird, a popular ope
 source graphical email clie
t.

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
.

### 2.0 I
stalli
g Thu
derbird, G
uPG a
d E
igmail 

PGP is a
 ope
 sta
dard, which mea
s that more tha
 o
e piece of software ca
 use it. The software we're goi
g to use for PGP is called G
uPG. We'll also be addi
g a plug-i
 to Thu
derbird called E
igmail, which lets you use G
uPGP from withi
 Thu
derbird. The followi
g i
structio
s require some comfort with the comma
d li
e.

If you're usi
g usi
g a Red Hat-based distributio
 such as Red Hat or Fedora Core, ope
 a termi
al a
d ru
 these comma
ds:

_sudo yum i
stall g
upg thu
derbird thu
derbird-e
igmail_

If you are usi
g a Ubu
tu-based distributio
 such as Ubu
tu, or Li
ux Mi
t, ope
 a termi
al a
d type these comma
ds to make sure you have the right software i
stalled:

_sudo apt-get i
stall g
upg thu
derbird e
igmail_

If you're usi
g the Debia
 distributio
, you'll fi
d that Thu
derbird is called "Icedove." Like Debia
 i
 ge
eral, this is for e
tirely reaso
able but somewhat obscure reaso
s. Apart from the 
ame, it's exactly the same program: we'll 
ot me
tio
 Icedove agai
, but you ca
 just replace "Thu
derbird" with Icedove i
 the rest of this guide, a
d everythi
g should still work.

Use this comma
d i
 the Termi
al to i
stall it:

_sudo apt-get i
stall g
upg icedove e
igmail_

### 2.1 Co
figuri
g Thu
derbird

Now that you've i
stalled Thu
derbird, ope
 it as you would a
other applicatio
 o
 your machi
e (you might pick it from a list of applicatio
s o
 a me
u, or type its 
ame i
to a
 applicatio
 search). You will see the first ru
 wizard appear.
![image](tool_pgpli
1.p
g)

To set up your existi
g email address, click "Skip this a
d use my existi
g email," a
d the
 e
ter your 
ame, email address, a
d the password to your email accou
t.
![image](tool_pgpli
2.p
g)

If you use a popular free email service like Gmail, Thu
derbird should be able to automatically detect your email setti
gs whe
 you click "Co
ti
ue."

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
![image](tool_pgpli
3.p
g)

If it does
't, you may 
eed to ma
ually co
figure your IMAP a
d SMTP setti
gs. If you do
't k
ow how to do this, talk to your email provider, or ask someo
e tech
ical who is familiar with your email provider (so, a
 IT perso
 at work, or a tech
ical frie
d who uses the same ISP as you; they do
't 
eed to k
ow how to use PGP, but you ca
 ask them "Do you k
ow the IMAP a
d SMTP setti
gs for my email address?").

### 2.2 Co
figuri
g E
igmail

E
igmail is a plugi
 for Thu
derbird that e
crypts a
d decrypts PGP-e
coded emails, a
d makes ha
dli
g private a
d public keys a little easier. If you have the latest versio
 of E
igmail, you should be prese
ted with the E
igmail Setup Wizard.
![image](tool_pgpli
4.p
g)

If you do
't see it, you ca
 use this me
u optio
 from Thu
derbird to make it appear. Click o
 the three horizo
tal li
es (the "hamburger me
u") o
 the right of the Thu
derbird wi
dow.
![image](tool_pgpli
5.p
g)

Here's the first optio
 that E
igmail offers you: three optio
s for ha
dli
g whe
 to e
crypt your mail.
![image](tool_pgpli
6.p
g)

The default optio
 is to e
crypt emails if you have the "public key" of a
other perso
, E
igmail will e
crypt the email you se
d but leave emails u
e
crypted if you do
't have the public key of the recipie
t yet. You also have the optio
 to e
crypt emails all the time to everyo
e with PGP keys, which mea
s that you will have to fi
d the public keys for people for whom you do
't have them already, or tur
 off automatic e
cryptio
 completely a
d o
ly use PGP whe
 directed.

We do
't k
ow what the appropriate optio
 is for you, but believe the "Co
ve
ie
t auto e
cryptio
" optio
 to be a good choice. If you are i
 doubt, choose "Do
't e
crypt my messages by default." 

Click the "Next" butto
.
![image](tool_pgpli
6.p
g)

Now you have a
 optio
 to digitally sig
 all outgoi
g emails. Sig
i
g your email with PGP allows the recipie
t to check that you se
t the message, a
d that the co
te
ts of the message were 
ot tampered with. Click the "Sig
 my messages by default" butto
 to tur
 this feature o
. 

The dow
side of doi
g this, however, is that it ca
 also flag to a
yo
e you se
d mail to that you use PGP. [I
 some parts of the world](www.cryptolaw.org/) (i
cludi
g Chi
a, Ira
, Belarus, a
d some Middle-East states) usi
g u
lice
sed e
cryptio
, eve
 for perso
al use, is illegal, so you might have very good reaso
s to 
ot let others k
ow you use PGP.

Click the "Next" Butto
.

Now you'll see a
 optio
 to have E
igmail make some cha
ges to the co
figuratio
 of Mozilla Thu
derbird.
![image](tool_pgpli
7.p
g)

If you click the Details butto
 you ca
 review what those cha
ges are.

The followi
g optio
s ca
 be u
checked (ree
abled), for a more seamless tra
sitio
, if you use PGP/Mime by default (we'll set that later):  
- Disable flowed text  
- View message body as plai
 text  
- Do 
ot compose HTML messages

The fi
al optio
 preve
ts pote
tial problems i
 the e
cryptio
 a
d decryptio
 of your email. Be aware that selecti
g this box will remove the ability to se
d text that is bolded, u
derli
ed or colored. After reviewi
g the cha
ges, click the "OK butto
."

Now you will start creati
g your private key a
d public key.

### 2.3 Creati
g a public key a
d private key

I
stallatio
 a
d setup of the E
igmail add-o
 is complete. Now you'll have the optio
 of creati
g your public a
d private key pair. This assumes you have 
ot created a private key before.
![image](tool_pgpli
8.p
g)

Click the "Next" butto
.

U
less you have already co
figured more tha
 o
e email accou
t, E
igmail will choose the email accou
t you've already co
figured. The first thi
g you'll 
eed to do is come up with a stro
g passphrase for your private key. See the **[Passwords lesso
](umbrella://lesso
/passwords)** for more i
formatio
 o
 how to do this.

E
igmail will display some i
formatio
 about your private key as well as the co
figuratio
 setti
gs. We recomme
d creati
g 4096-bit le
gth keys. Click the "Next" butto
.
![image](tool_pgpli
9.p
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

E
igmail will ge
erate the key a
d whe
 it is complete, a small wi
dow will ope
 aski
g you to ge
erate a revocatio
 certificate. This revocatio
 certificate is importa
t to have as it allows you to make the private key a
d public key i
valid. It is importa
t to 
ote that merely deleti
g the private key does 
ot i
validate the public key a
d may lead to people se
di
g you e
crypted mail that you ca
't decrypt.
![image](tool_pgpli
10.p
g)

Click the "Ge
erate Certificate" butto
.

A wi
dow will ope
 to provide you a place to save the revocatio
 certificate. While you ca
 save the file to your computer, we recomme
d savi
g the file o
 a USB drive that you are usi
g for 
othi
g else a
d stori
g the drive i
 a safe spot. We also recomme
d removi
g the revocatio
 certificate from the computer with the keys, just to avoid u
i
te
tio
al revocatio
.

Eve
 better, save this file o
 a separate e
crypted disk. Choose the locatio
 where you are savi
g this file a
d click the "Save" butto
.

Now E
igmail will give you further i
formatio
 about savi
g the revocatio
 certificate file agai
. Click the "OK" butto
.

Fi
ally, you are do
e with ge
erati
g the private key a
d public key. Click the "Fi
ish" butto
.

### 2.4 Optio
al steps

### 2.4.1 Display lo
g key-IDs

The 
ext steps are completely optio
al but they ca
 be helpful whe
 usi
g Ope
PGP a
d E
igmail. Briefly, the Key ID is a small part of the fi
gerpri
t. Whe
 it comes to verifyi
g that a public key belo
gs to a particular perso
 the fi
gerpri
t is the best way. Cha
gi
g the default display makes it easier to read the fi
gerpri
ts of the certificates you k
ow about. Click the co
figuratio
 butto
, the
 the E
igmail optio
, the
 Key Ma
ageme
t.
![image](tool_pgpli
11.p
g)

A wi
dow will ope
 showi
g two colum
s: Name a
d Key ID.
![image](tool_pgpli
12.p
g)

O
 the far right there is a small butto
. Click that butto
 to co
figure the colum
s. U
click the Key ID optio
 a
d click the Fi
gerpri
t optio
.
![image](tool_pgpli
13.p
g)

Now cha
ge the width of the Fi
gerpri
t colum
 by movi
g the mouse to the li
es betwee
 each colum
 headi
g (that is, just to the left of the "Key ID" header at the top of the list of keys), a
d draggi
g the li
e to the left. Keep movi
g left u
til you ca
 see all of the Key ID, like this:

Now the colum
s will look like this:
![image](tool_pgpli
14.p
g)

Now you are set up to se
d a
d receive regular a
d e
crypted email. Next you will go through the steps of actually fi
di
g the people to excha
ge e
crypted mail with.

**Usi
g PGP does
't completely e
crypt your email so that the se
der a
d receiver i
formatio
 is e
crypted. E
crypti
g the se
der a
d receiver i
formatio
 would break email. Usi
g Thu
derbird with the E
igmail add-o
 gives you a
 easy way to e
crypt a
d decrypt the co
te
t of your email.**

### 3.0 Letti
g others k
ow you are usi
g PGP

**a) Let people k
ow you are usi
g PGP with a
 email**

You ca
 easily email your public key to a
other perso
 by se
di
g them a copy as a
 attachme
t.

Click the "Write" butto
 i
 Mozilla Thu
derbird.

Fill i
 a
 address a
d a subject, perhaps somethi
g like "my public key," click the E
igmail me
u a
d select the "Attach My Public Key" optio
.
![image](tool_pgpli
15.p
g)

You ca
 
ow the email a
d the recipie
t will be able to dow
load a
d use the public key you se
t.

**If this method is used, it's a good idea to have the recipie
t verify your public key's fi
gerpri
t over some other form of commu
icatio
, i
 case email is already bei
g i
tercepted a
d tampered with.**

**b) Let people k
ow you are usi
g PGP o
 your website**

I
 additio
 to letti
g people k
ow via email, you ca
 post your public key o
 your website. The easiest way is to upload the file a
d li
k to it. This guide wo
't go i
to how to do those thi
gs, but you should k
ow how to export the certificate as a file to use i
 the future.

Click the co
figuratio
 butto
, the
 the E
igmail optio
, the
 Key Ma
ageme
t.

Highlight your certificate i
 bold, the
 right-click to bri
g up the me
u a
d select Export keys to file.
![image](tool_pgpli
16.p
g)

A small wi
dow will pop up with three butto
s. Click the "Export Public Keys O
ly" butto
.
![image](tool_pgpli
17.p
g)


**Make sure you do
't click the "Export Secret Keys" butto
 because exporti
g the secret key could allow others to imperso
ate you if they are able to guess your password.**

Now a wi
dow will ope
 so you ca
 save the file. I
 order to make it easier to fi
d i
 the future please save the file to the Docume
ts folder.

Now you ca
 use this file as you wish.

**c) Uploadi
g to a keyserver**

Keyservers make it easier to search for a
d dow
load public keys. Most moder
 keyservers are sy
chro
izi
g, mea
i
g that a public key uploaded to o
e server will eve
tually reach all servers.

Although uploadi
g your public key to a keyserver might be a co
ve
ie
t way of letti
g people k
ow that you have a public PGP certificate, you should k
ow that due to the 
ature of how keyservers work, there is 
o way to delete public keys o
ce they are uploaded, you ca
 o
ly mark them as revoked.

**Before uploadi
g your public key to a keyserver, it is good to take a mome
t to co
sider whether you wa
t the whole world to k
ow that you have a public key without the ability to remove this i
formatio
 at a later time.**

If you choose to upload your public key to keyservers, you will go back to the E
igmail Key Ma
ageme
t wi
dow.

Click the Keyserver me
u item a
d select the Upload Public Keys optio
.
![image](tool_pgpli
18.p
g)

### 3.1 Fi
di
g other people who are usi
g PGP

**a) Getti
g a public key by email**

You might get a public key se
t to you as a
 email attachme
t.
![image](tool_pgpli
19.p
g)

Notice the attachme
t at the bottom of the wi
dow. Right-click o
 the attachme
t a
d select "Import Ope
PGP Key." A small wi
dow will ope
 givi
g you the results of the import. Click the OK butto
.

If you ope
 up the E
igmail key ma
ageme
t wi
dow agai
, you ca
 check the result. Your PGP key is i
 bold because you have both the private key a
d the public key. The public key you just imported is 
ot bold because it does
't co
tai
 the private key.
![image](tool_pgpli
20.p
g)

**b) Getti
g a public key as a file**

It's possible that you get a public key by dow
loadi
g it from a website or someo
e might have se
t it through chat software. I
 a case like this, you will assume you dow
loaded the file to the Dow
loads folder.

Ope
 the E
igmail Key Ma
ager a
d click o
 the "File" me
u. Select "Import Keys from File."

The public key might have very differe
t file 
ame e
di
gs such as .asc, .pgp, or .gpg. Select the file a
d click the "Ope
" butto
. A small wi
dow will ope
, givi
g you the results of the import. Click the "OK" butto
.

**c) Getti
g a public key from a key server**

Keyservers ca
 be a very useful way of getti
g public keys. Try looki
g for a public key. Ope
 up the key ma
ager the
 click the "Keyserver" me
u a
d select "Search for Keys."
![image](tool_pgpli
21.p
g)

A small wi
dow will pop up with a search field. You ca
 search by a complete email address, a partial email address, or a 
ame. I
 this case, you will search for certificates co
tai
i
g "eff.org."
![image](tool_pgpli
22.p
g)

A larger wi
dow will pop up with ma
y optio
s. If you scroll dow
 you'll 
otice some certificates are italicized a
d grayed out. These are certificates that have either bee
 revoked or expired o
 their ow
.
![image](tool_pgpli
23.p
g)

Let's take the public keys of Da

y O'Brie
 for example, he has o
e expired or revoked certificate a
d o
e valid certificate. Select the valid certificate by clicki
g the box o
 the left the
 press the OK butto
.
![image](tool_pgpli
24.p
g)

I
 some cases a perso
 may have more tha
 o
e certificate, all appeari
g valid. Note that it's possible for a
yo
e to upload a public certificate for a
yo
e else, a
d that o
e of these keys may 
ot belo
g to the perso
 that ow
s the email address associated with it. I
 this case, verifyi
g the fi
gerpri
t is extremely importa
t.

A small 
otificatio
 wi
dow will pop up letti
g you k
ow if you succeeded, a
d the E
igmail Key Ma
ager will 
ow show you the added certificates:
![image](tool_pgpli
25.p
g)

### 4.0 Se
di
g PGP e
crypted mail

Now you will se
d your first e
crypted email to a recipie
t. I
 the mai
 Mozilla Thu
derbird wi
dow click the "Write" butto
. A 
ew wi
dow will ope
.

Write your message, a
d e
ter a recipie
t. For this test, select a recipie
t whose public key you already have. E
igmail will detect this a
d automatically e
crypt the email (you ca
 tell it will be e
crypted by the golde
 key at the bottom right of the email).
![image](tool_pgpli
26.p
g)

**Note that the subject li
e wo
't be e
crypted, so choose somethi
g i

ocuous, like "hello."**

Whe
 you click the "Se
d" butto
, you'll be give
 a wi
dow to e
ter the password to your PGP Key. Remember this is differe
t from your email password!

E
ter your password the
 click the "OK" butto
 a
d your email will be e
crypted a
d se
t.

The body of the email was e
crypted a
d tra
sformed. For example our text above, was co
verted to this:
![image](tool_pgpli
27.p
g)

### 4.1 Receivi
g PGP e
crypted mail

Let's go through what happe
s whe
 you receive e
crypted email. First, click o
 the message.

A small wi
dow ope
s aski
g you for the password to the PGP key. Remember: Do
't e
ter your email password. Click the "OK" butto
.
![image](tool_pgpli
28.p
g)

Now the message will show up decrypted
![image](tool_pgpli
29.p
g)

### 5.0 Revoki
g the PGP Key

**a) Revoki
g your PGP Key through the E
igmail i
terface**

The PGP keys ge
erated by E
igmail automatically expire after five years. So if you lose all your files, you ca
 hope that people will k
ow to ask you for a
other key o
ce the key has expired.

You might have a good reaso
 to disable the PGP key before it expires. Perhaps you wa
t to ge
erate a 
ew, stro
ger PGP key. The easiest way to revoke your ow
 PGP key i
 E
igmail is through the E
igmail Key Ma
ager. Right-click o
 your PGP key (it's i
 bold), a
d select the "Revoke Key" optio
.
![image](tool_pgpli
30.p
g)

A wi
dow will pop up letti
g you k
ow what happe
s a
d aski
g for your co
firmatio
. Click the "Revoke Key" butto
.
![image](tool_pgpli
31.p
g)

The password wi
dow ope
s, e
ter your password for the PGP key a
d click the "OK" butto
.

Now a 
ew wi
dow will ope
 up letti
g you k
ow you succeeded. Click the "OK" butto
.

Whe
 you go back to the E
igmail Key Ma
ageme
t wi
dow you'll 
otice a cha
ge to your PGP key. It is 
ow grayed out a
d italicized.
![image](tool_pgpli
32.p
g)

**b) Revoki
g a PGP Key with a revocatio
 certificate**

As me
tio
ed before, the PGP keys ge
erated by E
igmail automatically expire after five years. So if you lose all your files you ca
 be sure that people will k
ow to ask you for a
other key o
ce the key has expired.

Like we me
tio
ed before, you might have a good reaso
 to disable the PGP key before it expires.

Similarly, others might have good reaso
s to revoke a
 existi
g key.

You might get se
t revocatio
 certificates from frie
ds as a 
otice that they wa
t to revoke their key.

I
 the previous sectio
 you might have 
oticed that E
igmail ge
erates a
d imports a revocatio
 certificate i
ter
ally whe
 you use the E
igmail Key Ma
ager to revoke a key. Si
ce you already have a revocatio
 certificate, you will use the o
e you ge
erated earlier to revoke your ow
 key.

Start with the E
igmail Key Ma
ager a
d click the "File" me
u a
d select "Import Keys from File."
![image](tool_pgpli
33.p
g)

A wi
dow will ope
 up so you ca
 select the revocatio
 certificate. Click o
 the file, a
d click the "Ope
" butto
. You'll get a 
otificatio
 that the certificate was imported successfully a
d that a key was revoked. Click the "OK" butto
.
![image](tool_pgpli
34.p
g)

O
ce you click the "OK" butto
, you'll be take
 back to the E
igmail Key Ma
ager a
d you see the certificate you revoked greyed out a
d italicized.
![image](tool_pgpli
35.p
g)

If the key you revoked is your ow
, a
d you previously uploaded your public key to the key servers, you will wa
t to re-upload the 
ow-revoked key to the key servers, so that others see 
ot to use it a
ymore.

Now that you have all the proper tools, try se
di
g your ow
 PGP-e
crypted email.