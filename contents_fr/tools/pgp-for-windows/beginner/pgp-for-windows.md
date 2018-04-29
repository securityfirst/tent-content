[Title]: # ()
[Order]: # (0)

# PGP FOR WINDOWS PC TOOL GUIDE

## PGP for Wi
dows PC Tool Guide   
E
crypted email for Wi
dows

**Lesso
 to read:**
- **[Email](umbrella://lesso
/email)**  
**Dow
load Locatio
:**   
- GPG4Wi
  
- Mozilla Thu
derbird  
- E
igmail  
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
- Wi
dows: Wi
dows 7 Ultimate  
- Mozilla Thu
derbird 24.6.0  
- E
igmail 1.7  
- GPG4Wi
 2.2.1  
**Lice
se:** Free Software; mix of Free Software lice
ses  
**Level:** Adva
ced  
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
. This guide is for Wi
dows users.

### 1.1 Overview

To use PGP to excha
ge secure emails you have to bri
g together three programs: GPG4Wi
 (GNU Privacy Guard for Wi
dows k
ow
 as G
uPG), Mozilla Thu
derbird a
d E
igmail. 

- G
uPG is the program that actually e
crypts a
d decrypts the co
te
t of your mail.  
- Mozilla Thu
derbird is a
 email clie
t that allows you to read a
d write emails without usi
g a browser.  
- E
igmail is a
 add-o
 to Mozilla Thu
derbird that ties it all together.

Note! What this guide teaches is how to use PGP with Mozilla Thu
derbird, a
 email clie
t program that performs a similar fu
ctio
 to Outlook. You may have your ow
 favorite email software program (or use a web mail service like Google Mail or Outlook.com). This guide wo
't tell you how to use PGP with these programs. You ca
 choose either to i
stall Thu
derbird a
d experime
t with PGP with a 
ew email clie
t, or you ca
 i
vestigate other solutio
s to use PGP with your customary software. We have still 
ot fou
d a satisfactory solutio
 for these other programs.

**Usi
g PGP does
't completely e
crypt your email: the se
der a
d receiver i
formatio
 is still u
e
crypted a
d so is the subject li
e!**

E
crypti
g the se
der a
d receiver i
formatio
 is
't possible i
 the existi
g email system. What usi
g Mozilla Thu
derbird with the E
igmail add-o
 gives you is a
 easy way to e
crypt the co
te
t of your email. Someo
e spyi
g o
 your emails may still see the ide
tities of the people you commu
icate with a
d whe
 you email them.

You will first dow
load all the software 
eeded, i
stall it, a
d the
 e
d with co
figuratio
 a
d usage.

### 2 Dow
loadi
g the software

### 2.1 Getti
g GPG4Wi


You ca
 get G
uPG (also k
ow
 as GPG) o
 Wi
dows by dow
loadi
g the small i
staller from the GPG4Wi
 dow
load page.
![image](tool_pgpwi
1.p
g)

Click o
 the most rece
t versio
 of GPG4Wi
 with G
uPG compo
e
t o
ly (Va
illa or Light) to dow
load the GPG i
staller.

**Note: This versio
 of GPG is available o
ly o
 a web site that offers "http" dow
loads, 
ot secure "https" dow
loads. If you are co
cer
ed that you may be targeted for surveilla
ce by a
 orga
izatio
 that ca
 tamper with your I
ter
et co

ectio
, you may wa
t to i
vestigate more drastic solutio
s, such as dow
loadi
g a
d ru

i
g Tails, a secure operati
g system that replaces Wi
dows.**

Ma
y browsers will ask you to co
firm whether you wa
t to dow
load this file. I
ter
et Explorer 11 shows a bar at the bottom of the browser wi
dow with a
 ora
ge border.

For a
y browser it is best to first save the file before proceedi
g, so _click the "Save" butto
_. By default, most browsers save dow
loaded files i
 the Dow
loads folder.

### 2.2 Getti
g Mozilla Thu
derbird

Go to the Mozilla Thu
derbird website.
![image](tool_pgpwi
2.p
g)

Click o
 the gree
 butto
 labelled "Thu
derbird Free Dow
load."

The Mozilla Thu
derbird website will have detected your preferred la
guage. If you wa
t to use Thu
derbird i
 a
other la
guage click o
 the "Other Systems & La
guages" li
k a
d make your selectio
 from there.

Ma
y browsers will ask you to co
firm if you wa
t to dow
load this file. I
ter
et Explorer 11 shows a bar at the bottom of the browser wi
dow with a
 ora
ge border.
![image](tool_pgpwi
3.p
g)

For a
y browser, it is best to first save the file before proceedi
g, so click the "Save" butto
. By default, most browsers save dow
loaded files i
 the Dow
loads folder.

### 2.3 Getti
g E
igmail

You ca
 get E
igmail from the E
igmail website.
![image](tool_pgpwi
4.p
g)

Ma
y browsers will ask you to co
firm if you wa
t to dow
load this file. I
ter
et Explorer 11 shows a bar at the bottom of the browser wi
dow with a
 ora
ge border.
![image](tool_pgpwi
5.p
g)
For a
y browser it is best to first save the file before proceedi
g, so click the "Save" butto
. By default, most browsers save dow
loaded files i
 the Dow
loads folder.


After dow
loadi
g E
igmail, GPG4Wi
, a
d Mozilla Thu
derbird you should have three 
ew files i
 your Dow
loads folder:
![image](tool_pgpwi
6.p
g)

### 3 I
stalli
g the software

### 3.1 I
stalli
g GPG4Wi


Keep the Wi
dows Explorer wi
dow ope
 a
d double-click o
 gpg4wi
-xxx-x.x.x.exe. You'll be asked if you wa
t to allow the i
stallatio
 of this program. Click the "Yes" butto
.
![image](tool_pgpwi
7.p
g)

A wi
dow will ope
, givi
g you a
 overview of what will be i
stalled. Click the "Next" butto
.
![image](tool_pgpwi
8.p
g)

A wi
dow with the lice
se agreeme
t will ope
 up. Click the "Next" butto
.
![image](tool_pgpwi
9.p
g)

The GPG4Wi
 Va
illa package does
't have compo
e
ts to select, so click the "Next "butto
 agai
. For the GPG4Wi
-Light package, u
select all optio
al compo
e
ts to i
stall G
uPG o
ly.
![image](tool_pgpwi
10.p
g)

Next, you'll have the ability to choose where GPG is i
stalled. Do
't cha
ge the default setti
g. Click the "Next" butto
.
![image](tool_pgpwi
11.p
g)

The 
ext two wi
dows will have some i
stallatio
 optio
s. Click the "Next" butto
 a
d the
 click the "I
stall" butto
:
![image](tool_pgpwi
12.p
g)![image](tool_pgpwi
13.p
g)

You will see a wi
dow with a progress bar-whe
 it's do
e it will say "I
stallatio
 Complete." Click the "Next" butto
 agai
.
![image](tool_pgpwi
14.p
g)

Fi
ally, you are at the last i
stallatio
 step. Remove the check mark 
ext to "Show the README file" a
d click the "Fi
ish" butto
.
![image](tool_pgpwi
15.p
g)

That's it. Now let's move o
 to i
stalli
g Mozilla Thu
derbird.

### 3.2 I
stalli
g Mozilla Thu
derbird

Similar to GPG4Wi
, you i
stall Mozilla Thu
derbird by double-clicki
g the Thu
derbird Setup 24.6.0.exe file. As usual, you will be asked if you wa
t to ru
 this file. Click the "Ru
" butto
.
![image](tool_pgpwi
16.p
g)

You will be asked if you wa
t to allow Mozilla Thu
derbird to make a cha
ge to your computer by i
stalli
g software. Click the "Yes" butto
.
![image](tool_pgpwi
17.p
g)

You will see the Mozilla Thu
derbird Setup wi
dow. Click the "Next" butto
.
![image](tool_pgpwi
18.p
g)

Next, you will get a choice betwee
 a Sta
dard setup a
d a Custom setup. Keep the Sta
dard setup selectio
 a
d click the "Next" butto
.
![image](tool_pgpwi
18.p
g)

You will be give
 a summary of where Mozilla Thu
derbird's files will be i
stalled. Click the "I
stall" butto
.
![image](tool_pgpwi
19.p
g)

Whe
 the i
stallatio
 process is complete, you will see a fi
al wi
dow that e
ables you to lau
ch Mozilla Thu
derbird. Click the "Fi
ish" butto
.
![image](tool_pgpwi
20.p
g)

### 3.3. E
igmail i
stallatio


**Step 1. Preparatio
** 

Whe
 Mozilla Thu
derbird lau
ches for the first time, you will see this small co
firmatio
 wi
dow aski
g about some default setti
gs. We recomme
d clicki
g the "Set as Default" butto
.
![image](tool_pgpwi
21.p
g)

Next, you will be asked whether you would like a 
ew email address. Click the "Skip this a
d use my existi
g email" butto
. Now you will co
figure Mozilla Thu
derbird to se
d a
d receive email. If you are used to o
ly readi
g a
d se
di
g email through gmail.com, outlook.com, or yahoo.com, Mozilla Thu
derbird will be a 
ew experie
ce, but it is
't that differe
t overall.
![image](tool_pgpwi
22.p
g)

**Step 2. Addi
g a mail accou
t to Mozilla Thu
derbird**

A 
ew wi
dow will ope
.
![image](tool_pgpwi
23.p
g)

E
ter your 
ame, email address, a
d the password to your email accou
t. Mozilla does
't have access to your password or your email accou
t. Click the "Co
ti
ue" butto
.
![image](tool_pgpwi
24.p
g)

I
 ma
y cases Mozilla Thu
derbird will automatically detect the 
ecessary setti
gs. I
 some cases Mozilla Thu
derbird does
't have complete i
formatio
 a
d you'll 
eed to e
ter it yourself. Here is a
 example of the i
structio
s Google provides for Gmail:

I
comi
g Mail (IMAP) Server - Requires SSL  
- imap.gmail.com  
- Port: 993  
- Requires SSL:Yes

Outgoi
g Mail (SMTP) Server - Requires TLS  
- smtp.gmail.com  
- Port: 465 or 587  
- Requires SSL: Yes  
- Requires authe
ticatio
: Yes  
- Use same setti
gs as i
comi
g mail server

**Full Name or Display Name:** [your 
ame or pseudo
ym]

**Accou
t Name or User Name:** your full Gmail address (user
ame@gmail.com). Google Apps users, please e
ter user
ame@your_domai
.com

**Email address:** your full Gmail address (user
ame@gmail.com) Google Apps users, please e
ter user
ame@your_domai
.com

**Password:** your Gmail password

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

Whe
 all the i
formatio
 is e
tered correctly, click the "Do
e" butto
.
![image](tool_pgpwi
25.p
g)

Mozilla Thu
derbird will start dow
loadi
g copies of your email to your computer. Try se
di
g a test email to your frie
ds.

**Step 3. I
stalli
g E
igmail**

E
igmail is i
stalled i
 a differe
t way from Mozilla Thu
derbird a
d GPG4Wi
. As me
tio
ed before, E
igmail is a
 Add-o
 for Mozilla Thu
derbird. Click the "Me
u butto
," also called the Hamburger butto
, a
d select "Add O
s."
![image](tool_pgpwi
26.p
g)

You'll be take
 to the Add-o
s Ma
ager tab.
![image](tool_pgpwi
27.p
g)

Click the cog to bri
g up a small me
u a
d select "I
stall add-o
 from file" which will bri
g up a file-selectio
 wi
dow.
![image](tool_pgpwi
28.p
g)

The file selectio
 wi
dow will very likely ope
 to the Dow
loads folder. If it does
't, go to the Dow
loads folder (where E
igmail was saved to) click o
 e
igmail-1.7-tb+sm.xpi the
 click the "Ope
" butto
.
![image](tool_pgpwi
29.p
g)

Now you will see a small wi
dow aski
g you to co
firm whether you wa
t to i
stall E
igmail. Click the "I
stall Now" butto
.
![image](tool_pgpwi
30.p
g)

After the E
igmail add-o
 is i
stalled, Mozilla Thu
derbird will ask to restart the browser to activate E
igmail. Click the "Restart Now" butto
 a
d Mozilla Thu
derbird will restart.
![image](tool_pgpwi
31.p
g)

Whe
 Mozilla Thu
derbird restarts, a
 additio
al wi
dow will ope
 up that will start the process of setti
g up the E
igmail add-o
. Keep the "Yes, I would like the wizard to get me started" butto
 selected a
d click the "Next" butto
.
![image](tool_pgpwi
32.p
g)

E
igmail provides you with three optio
s for ha
dli
g mail. The default optio
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
![image](tool_pgpwi
33.p
g)

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
crypt my messages by default." Click the "Next" butto
.

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
. The dow
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
![image](tool_pgpwi
34.p
g)

Now you'll see a
 optio
 to have E
igmail make some cha
ges to the co
figuratio
 of Mozilla Thu
derbird.
![image](tool_pgpwi
35.p
g)

If you click the Details butto
 you ca
 review what those cha
ges are.
![image](tool_pgpwi
36.p
g)

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


The small wi
dow will close. Click the "Next" butto
.

Now you will start creati
g your private key a
d public key.

### 4 Creati
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

Click the "Next" butto
.
![image](tool_pgpwi
37.p
g)

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

Make sure that you've writte
 dow
 this passphrase o
 paper u
til you have memorized it. Keep it somewhere where you ca
 tell if it has bee
 take
 or viewed (like your wallet or purse). Just make sure you do
't leave this paper lyi
g arou
d.

Click the "Next" butto
.

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
![image](tool_pgpwi
38.p
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

Click the "Ge
erate Certificate" butto
.
![image](tool_pgpwi
39.p
g)

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
![image](tool_pgpwi
40.p
g)

Now E
igmail will give you further i
formatio
 about savi
g the revocatio
 certificate file agai
. Click the "OK" butto
.
![image](tool_pgpwi
41.p
g)

Fi
ally, you are do
e with ge
erati
g the private key a
d public key. Click the "Fi
ish" butto
.
![image](tool_pgpwi
42.p
g)

### 5 Optio
al steps

### 5.1 Display lo
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
![image](tool_pgpwi
43.p
g)

A wi
dow will ope
 showi
g two colum
s: Name a
d Key ID.
![image](tool_pgpwi
43.p
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
![image](tool_pgpwi
44.p
g)

Now the colum
s will look like this:
![image](tool_pgpwi
45.p
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

### 5.2 Usi
g PGP/MIME

There is a fi
al optio
al co
figuratio
 step is to e
able PGP/MIME which makes se
di
g e
crypted a
d sig
ed attachme
ts easier.

You ca
 fi
d this setti
g by clicki
g o
 the Me
u Butto
, hoveri
g over Optio
s, the
 clicki
g Accou
t Setti
gs. The Accou
t Setti
gs wi
dow will ope
.
![image](tool_pgpwi
46.p
g)

Whe
 the Accou
t Setti
gs wi
dow ope
s click the Ope
PGP Security tab the
 click the checkbox 
ext to Use PGP/MIME by default. Next click the OK butto
. Now E
igmail will use PGP/MIME by default.
![image](tool_pgpwi
47.p
g)

**Usi
g PGP does
't completely e
crypt your email so that the se
der a
d received i
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

### 6.1 Letti
g others k
ow you are usi
g PGP

Now that you have PGP, you wa
t to let others k
ow that you are usi
g it so they ca
 also se
d you e
crypted messages usi
g PGP.

Let's look at three differe
t ways you ca
 let people k
ow you are usi
g PGP.

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
![image](tool_pgpwi
48.p
g)

Fill i
 a
 address a
d a subject, perhaps somethi
g like "my public key," click the E
igmail me
u a
d select the "Attach My Public Key" optio
.
![image](tool_pgpwi
49.p
g)

You ca
 se
d the email a
d the recipie
t will be able to dow
load a
d use the public key you se
t.

If this method is used, it's a good idea to have the recipie
t verify your public key's fi
gerpri
t over some other form of commu
icatio
, i
 case email is already bei
g i
tercepted a
d tampered with.

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

Highlight the certificate i
 bold, the
 right-click to bri
g up the me
u a
d select Export keys to file.
![image](tool_pgpwi
50.p
g)

A small wi
dow will pop up with three butto
s. Click the "Export Public Keys O
ly" butto
.
![image](tooL_pgpwi
51.p
g)

Make sure you do
't click the "Export Secret Keys" butto
 because exporti
g the secret key could allow others to imperso
ate you if they are able to guess your password.

Now a wi
dow will ope
 so you ca
 save the file. I
 order to make it easier to fi
d i
 the future please save the file to the Docume
ts folder.
![image](tool_pgpwi
52.p
g)

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
![image](tool_pgpwi
53.p
g)

### 6.2 Fi
di
g other people who are usi
g PGP

**a) Getti
g a public key by email**

You might get a public key se
t to you as e
 email attachme
t.
![image](tool_pgpwi
54.p
g)

Double-click o
 the 
ew message, a
d it'll ope
 a 
ew tab. Notice the attachme
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
![image](tool_pgpwi
55.p
g)

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
![image](tool_pgpwi
56.p
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
![image](tool_pgpwi
57.p
g)

The public key might have very differe
t file 
ame e
di
gs such as .asc, .pgp, or .gpg. Select the file a
d click the "Ope
" butto
.
![image](tool_pgpwi
58.p
g)

A small wi
dow will ope
, givi
g you the results of the import. Click the "OK" butto
.
![image](tool_pgpwi
59.p
g)

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
![image](tool_pgpwi
60.p
g)

A small wi
dow will pop up with a search field. You ca
 search by a complete email address, a partial email address, or a 
ame. I
 this case, you will search for certificates co
tai
i
g "eff.org."
![image](tool_pgpwi
61.p
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
![image](tool_pgpwi
62.p
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
![image](tool_pgpwi
63.p
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
ow if you succeeded:
![image](tool_pgpwi
64.p
g)

The E
igmail Key Ma
ager will 
ow show you the added certificates:
![image](tool_pgpwi
65.p
g)

### 7.1 Se
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
![image](tool_pgpwi
66.p
g)

Write your message, a
d e
ter a recipie
t. For this test, select a recipie
t whose public key you already have. E
igmail will detect this a
d automatically e
crypt the email.
![image](tool_pgpwi
67.p
g)

_Note that the subject li
e wo
't be e
crypted, so choose somethi
g i

ocuous, like "hello."_

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
![image](tool_pgpwi
68.p
g)

The body of the email was e
crypted a
d tra
sformed. For example this text:
![image](tool_pgpwi
69.p
g)

Will be tra
sformed i
to:
![image](tool_pgpwi
70.p
g)

### 7.2 Receivi
g PGP e
crypted mail

Let's go through what happe
s whe
 you receive e
crypted email. Notice that that Mozilla Thu
derbird is letti
g you k
ow you have 
ew mail. Click o
 the message.
![image](too.p
g;_pgpwi
71)

A small wi
dow ope
s aski
g you for the password to the PGP key. Remember: Do
't e
ter your email password. Click the "OK" butto
.
![image](tool_pgpwi
72.p
g)

Now the message will show up decrypted
![image](tool_pgpwi
73.p
g)

### 8 Revoki
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
ager.
![image](tool_pgpwi
74.p
g)

Right-click o
 your PGP key (it's i
 bold), a
d select the "Revoke Key" optio
.
![image](tool_pgpwi
75.p
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
![image](tool_pgpwi
76.p
g)

The password wi
dow ope
s, e
ter your password for the PGP key a
d click the "OK" butto
.
![image](tool_pgpwi
77.p
g)

Now a 
ew wi
dow will ope
 up letti
g you k
ow you succeeded. Click the "OK" butto
.
![image](tool_pgpwi
78.p
g)

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
![image](tool_pgpwi
79.p
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
![image](tool_pgpwi
80.p
g)

A wi
dow will ope
 up so you ca
 select the revocatio
 certificate. Click o
 the file, a
d click the "Ope
" butto
.
![image](tool_pgpwi
81.p
g)

You'll get a 
otificatio
 that the certificate was imported successfully a
d that a key was revoked. Click the "OK" butto
.
![image](tool_pgpwi
82.p
g)

O
ce you click the "OK" butto
, you'll be take
 back to the E
igmail Key Ma
ager a
d you see the certificate you revoked greyed out a
d italicized.
![image](tool_pgpwi
83.p
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