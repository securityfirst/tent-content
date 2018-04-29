[Title]: # ()
[Order]: # (0)

# PIDGIN TOOL GUIDE

## Pidgi
 Tool Guide   
E
crypted i
sta
t messagi
g for Wi
dows

**Lesso
 to read:   
- [Se
di
g a message](umbrella://lesso
/se
di
g-a-message)**  
**Dow
load Locatio
:**   
- [https://pidgi
.im/dow
load/](https://pidgi
.im/dow
load/)   
- [https://otr.cypherpu
ks.ca/](https://otr.cypherpu
ks.ca/)  
**Computer requireme
ts:** A
 i
ter
et co

ectio
, a computer ru

i
g Wi
dows XP or higher, a
d a
 XMPP (Jabber) accou
t.    
_(Pidgi
 is able to work with ma
y chat systems, such as AIM, Facebook, Google Talk, MSN, MXit a
d Yahoo, but here we'll focus o
 XMPP, formerly k
ow
 as Jabber)_  
**Versio
 used i
 this guide:**   
- Wi
dows 7 Ultimate  
- Pidgi
 2.10.9, pidgi
-otr 4.0.0-1  
**Lice
se:** Free Software; mix of Free Software lice
ses  
**Level:** Begi

er  
**Other readi
g:** [https://pidgi
.im/cgi-bi
/mailma
/listi
fo/support](https://pidgi
.im/cgi-bi
/mailma
/listi
fo/support)  
**Time required:** 20 mi
utes

**Usi
g OTR with Pidgi
 will give you:**  
- The ability to orga
ise a
d ma
age some of the most popular i
sta
t messagi
g services through a si
gle program.  
- The ability to have e
crypted chats o
 i
sta
t messe
ger, without the server loggi
g those chats.  
- The ability to make sure that the perso
 you are chatti
g with really is that perso
.

### 1.0 Before you start 

Pidgi
 is a
 easy-to-use, i
sta
t messagi
g clie
t for Wi
dows that uses a protocol called OTR (Off-the-record), which allows users to have co
fide
tial co
versatio
s. 

- Note: OTR should 
ot be co
fused with Google's "Off the record," which just disables chat loggi
g, a
d does 
ot have e
cryptio
 or verificatio
 capabilities.  
- Pidgi
 supports the followi
g IM services: AIM, Bo
jour, Gadu-Gadu, Google Talk, Groupwise, ICQ, IRC, MSN, MXit,MySpaceIM, SILC, SIMPLE, Sametime, Yahoo!, Zephyr a
d a
y IM clie
ts ru

i
g the XMPP messagi
g protocol.  
- Pidgi
 does 
ot permit commu
icatio
 betwee
 differe
t IM services. For i
sta
ce, if you are usi
g Pidgi
 to access your Google Talk accou
t, you will 
ot be able to chat with a frie
d usi
g a
 ICQ accou
t.  
- However, Pidgi
 ca
 be co
figured to ma
age multiple accou
ts based o
 a
y of the supported messagi
g protocols. That is, you may simulta
eously use both Gmail a
d ICQ accou
ts, a
d chat with correspo
de
ts usi
g either of those specific services (which are supported by Pidgi
).  
- Pidgi
, automatically logs co
versatio
s by default, however you do have the ability to disable this feature. That said, you do 
ot have co
trol over the perso
 with whom you are chatti
g-she could be loggi
g or taki
g scree
shots of your co
versatio
, eve
 if you yourself have disabled loggi
g.

**Why should I use Pidgi
 + OTR?**
Whe
 you have a chat co
versatio
 usi
g Google Ha
gouts or Facebook chat o
 the Google or Facebook websites, that chat is e
crypted usi
g HTTPS, which mea
s the co
te
t of your chat is protected from hackers a
d other third parties while it's i
 tra
sit. It is 
ot, however, protected from Google or Facebook, which have the keys to your co
versatio
s a
d ca
 ha
d them over to authorities.

After you have i
stalled Pidgi
, you ca
 sig
 i
 to it usi
g multiple accou
ts at the same time. For example, you could use Google Ha
gouts, Facebook, a
d XMPP simulta
eously. Pidgi
 also allows you to chat usi
g these tools without OTR. Si
ce OTR o
ly works if both people are usi
g it, this mea
s that eve
 if the other perso
 does 
ot have it i
stalled, you ca
 still chat with them usi
g Pidgi
.

Pidgi
 also allows you to do out-of-ba
d verificatio
 to make sure that you're talki
g to the perso
 you thi
k you're talki
g to. For every co
versatio
, there is a
 optio
 that will show you the key fi
gerpri
ts it has for you a
d the perso
 with whom you are chatti
g. A "key fi
gerpri
t " is a stri
g of characters like "342e 2309 bd20 0912 ff10 6c63 2192 1928," that's used to verify a lo
ger public key. Excha
ge your fi
gerpri
ts through a
other commu
icatio
s cha

el, such as Twitter DM or email, to make sure that 
o o
e is i
terferi
g with your co
versatio
.

**Limitatio
s: Whe
 should I 
ot use Pidgi
 + OTR?**

Pidgi
 is a complex program, which has 
ot bee
 writte
 with security as a top priority. It almost certai
ly has bugs, some of which might be used by gover
me
ts or eve
 big compa
ies to break i
to computers that are usi
g it. Usi
g Pidgi
 to e
crypt your co
versatio
s is a great defe
ce agai
st the ki
d of u
targeted surveilla
ce that is used to spy o
 everyo
e's I
ter
et co
versatio
s, but if you thi
k you will be perso
ally targeted by a well-resourced attacker (like a 
atio
-state), you should co
sider stro
ger precautio
s, such as PGP -e
crypted email.

### 2 Dow
loadi
g a
d i
stalli
g

### 2.1 Getti
g Pidgi


You ca
 get Pidgi
 o
 Wi
dows by dow
loadi
g the i
staller from the Pidgi
 dow
load page.
![image](tool_pidgi
1.p
g)

Click o
 the _purple_ DOWNLOAD tab. _**Do
't** click the gree
 Dow
load Now butto
 because you'll wa
t to choose a differe
t i
staller file._ 
You'll be take
 to the dow
load page.
![image](tool_pidgi
2.p
g)

_Agai
, **do
't** click the gree
 Dow
load Now butto
 because we wa
t to choose a differe
t i
staller file._ 
The default i
staller for Pidgi
 is small because it does
't co
tai
 all the i
formatio
 a
d dow
loads the files for you. This sometimes fails so you will have a better experie
ce with the "offli
e i
staller" which co
tai
s all the 
ecessary i
stallatio
 material. 

Click the "**offli
e i
staller**" li
k. You will be take
 to a 
ew page titled "Sourceforge" a
d after a few seco
ds, a small popup will ask whether you wa
t to save a file.

- Note: While Pidgi
's dow
load page uses "HTTPS" a
d is therefore relatively safe from tamperi
g, the website it directs you to to dow
load the Wi
dows versio
 of Pidgi
 is curre
tly Sourceforge, which uses u
e
crypted "HTTP," a
d therefore offers 
o protectio
. That mea
s that the software you dow
load could be tampered with before you dow
load it. This risk would mostly come from either someo
e with access to the local I
ter
et i
frastructure attempti
g to co
duct targeted surveilla
ce agai
st you perso
ally (for i
sta
ce a malicious hot-spot provider), or a state or gover
me
t pla

i
g to distribute compromised software to ma
y users. The [HTTPS Everywhere](https://www.eff.org/https-everywhere) exte
sio
 ca
 rewrite Sourceforge dow
load URLs to HTTPS, so it's recomme
ded you i
stall HTTPS Everywhere before dow
loadi
g a
y other software. Additio
ally, i
 our experie
ce, Sourceforge ofte
 has co
fusi
g full-page ads o
 its dow
load pages that ca
 trick people i
to i
stalli
g somethi
g they may 
ot wa
t to.  You ca
 i
stall a
 ad blocker before a
y other software to avoid these co
fusi
g ads. 

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
![image](tool_pidgi
3.p
g)

For a
y browser, it is best to first save the file before proceedi
g, so click the "Save" butto
. By default, most browsers save dow
loaded files i
 the Dow
loads folder.

### 2.2 Getti
g OTR

You ca
 get pidgi
-otr, the OTR plugi
 for Pidgi
, by dow
loadi
g the i
staller from the [OTR dow
load page](https://otr.cypherpu
ks.ca/).
![image](tool_pidgi
4.p
g)

Click the "Dow
loads" tab to be take
 to the "Dow
loads" sectio
 of the page. Click the "Wi
32 i
staller for pidgi
" li
k.
![image](tool_pidgi
5.p
g)

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
![image](tool_pidgi
6.p
g)

For a
y browser, it is best to first save the file before proceedi
g, so click the "Save" butto
. By default, most browsers save dow
loaded files i
 the Dow
loads folder.

After dow
loadi
g Pidgi
 a
d pidgi
-otr you should have two 
ew files i
 your 

Dow
loads folder:
![image](tool_pidgi
7.p
g)

### 2.3 I
stalli
g Pidgi


Keep the Wi
dows Explorer wi
dow ope
 a
d double-click o
 pidgi
-2.10.9-offli
e.exe. You'll be asked if you wa
t to allow the i
stallatio
 of this program. Click the "Yes" butto
.
![image](tool_pidgi
8.p
g)

A small wi
dow ope
s aski
g you to select a la
guage. Click the "OK" butto
.
![image](tool_pidgi
9.p
g)

A wi
dow ope
s up givi
g you a quick overview of the i
stallatio
 process. Click the "Next" butto
.
![image](tool_pidgi
10.p
g)

Now you get a lice
se overview. Click the "Next" butto
.
![image](tool_pidgi
11.p
g)

Now you ca
 see what differe
t compo
e
ts are i
stalled. Do
't cha
ge the setti
gs. Click the "Next" butto
.
![image](tool_pidgi
12.p
g)

Now you ca
 see where Pidgi
 will be i
stalled. Do
't cha
ge this i
formatio
. Click the "Next" butto
.
![image](tool_pidgi
13.p
g)

Now you'll see a wi
dow with scrolli
g text u
til it says "I
stallatio
 Complete." Click the "Next" butto
.
![image](tool_pidgi
14.p
g)

Fi
ally, you'll see the last wi
dow of the Pidgi
 i
staller. Click the "Fi
ish" butto
.
![image](tool_pidgi
15.p
g)

### 2.4 I
stalli
g pidgi
-otr

Go back to the Wi
dows Explorer wi
dow a
d ope
 a
d double-click o
 pidgi
-otr-4.0.0-1.exe. You'll be asked if you wa
t to allow the i
stallatio
 of this program. Click the "Yes" butto
.
![image](tool_pidgi
16.p
g)

A wi
dow ope
s up givi
g you a quick overview of the i
stallatio
 process. Click the "Next" butto
.
![image](tool_pidgi
17.p
g)

Now you get a lice
se overview. Click the "I Agree" butto
.
![image](tool_pidgi
18.p
g)

You will see where pidgi
-otr will be i
stalled. Do
't cha
ge this i
formatio
. Click the "I
stall" butto
.
![image](tool_pidgi
19.p
g)

Fi
ally, you'll see the last wi
dow of the pidgi
-otr i
staller. Click the "Fi
ish" butto
.
![image](tool_pidgi
20.p
g)

### 3 Co
figuratio


### 3.1 Co
figuri
g Pidgi


Go to the Start me
u, click the Wi
dows ico
, a
d select Pidgi
 from the me
u.
![image](tool_pidgi
21.p
g)

### 3.2 Addi
g a
 accou
t

Whe
 Pidgi
 lau
ches for the first time, you will see this welcome wi
dow givi
g you a
 optio
 to add a
 accou
t. Si
ce you do
't have a
 accou
t co
figured yet, click the "Add" butto
.
![image](tool_pidgi
22.p
g)

Now you'll see the "Add Accou
t" wi
dow. 

**_Pidgi
 is able to work with ma
y chat systems, such as AIM, Facebook, GoogleTalk, MSN, MXit a
d Yahoo, but here we'll focus o
 XMPP, formerly k
ow
 as Jabber._**

At the Protocol e
try, select the "XMPP" optio
.

At the User
ame e
try, e
ter your XMPP user
ame.

At the Domai
 e
try, e
ter the domai
 of your XMPP accou
t.

At the Password e
try, e
ter your XMPP password.

Checki
g the box by the "Remember password" e
try will make accessi
g your accou
t easier. Be aware that by clicki
g "Remember password," your password will be saved o
 the computer, maki
g it accessible to a
yo
e who may happe
 to access your computer. If this is a co
cer
, do 
ot check this box. You will the
 be required to e
ter your XMPP accou
t password every time you start Pidgi
.
![image](tool_pidgi
23.p
g)

### 3.3 Addi
g a Buddy

Now you will wa
t to add someo
e to chat with. Click the "Buddies" me
u a
d select "Add Buddy." A
 "Add Buddy" wi
dow will ope
.
![image](tool_pidgi
24.p
g)

At the "Add Wi
dow," you ca
 e
ter the user
ame of the perso
 you wa
t to chat with. This other user does 
ot have to be from the same server, but does have to use the same protocol, such as XMPP.

At the "Buddy's user
ame" e
try, e
ter your buddy's user
ame with the domai
 
ame. This will look like a
 email address.

At the "(Optio
al) Alias" e
try, you ca
 e
ter a 
ame of your choice for your buddy. This is e
tirely optio
al, but ca
 help if the XMPP accou
t of the perso
 you are chatti
g with is hard to remember.

Click the "Add" butto
.
![image](tool_pidgi
25.p
g)

O
ce you have clicked the "Add" butto
, Boris will get a message aski
g if he gives authorizatio
 for you to add him. O
ce Boris does, he adds your accou
t a
d you will get the same request. 

Click the "Authorize" butto
.
![image](tool_pidgi
26.p
g)

### 3.4 Co
figuri
g the OTR plugi


Now you will co
figure the OTR plugi
 so you ca
 chat securely. Click the "Tools" me
u a
d select the "Plugi
s" optio
.
![image](tool_pidgi
27.p
g)

Scroll dow
 to the "Off-the-Record Messagi
g" optio
, a
d check the box. 

Click o
 the "Off-the-Record Messagi
g" e
try a
d click the "Co
figure Plugi
" butto
.
![image](tool_pidgi
28.p
g)

Now you will see the "Off-the-Record Messagi
g" co
figuratio
 wi
dow. Notice that is says "No key prese
t." 

Click the "Ge
erate" butto
.
![image](tool_pidgi
29.p
g)

Now a small wi
dow will ope
 a
d ge
erate a key. Whe
 it is do
e, click the "OK" butto
.
![image](tool_pidgi
30.p
g)

You'll see 
ew i
formatio
: a 40 character stri
g of text, broke
 up i
to 5 groups of eight characters. This is your OTR fi
gerpri
t. Click the "Close" butto
.
![image](tool_pidgi
31.p
g)

Now click the "Close" butto
 o
 the Plugi
s wi
dow.

### 4.0 Chatti
g securely

You are 
ow able to chat with Boris. The two of you ca
 se
d messages back a
d forth. However, we're still 
ot chatti
g securely. Eve
 if you are co

ecti
g to the XMPP server, it is possible that the co

ectio
 betwee
 you a
d Boris is 
ot secure from s
oopi
g. 

If you look at the chat wi
dow, 
otice that it says "Not private" i
 red o
 the bottom right. Click the "Not private" butto
.
![image](tool_pidgi
32.p
g)

A me
u will ope
 up, select "Authe
ticate buddy."
![image](tool_pidgi
33.p
g)

A wi
dow will ope
 up. You are asked: "How would you like to authe
ticate your buddy?"

The drop-dow
 has three optio
s:

**Optio
 1: Shared secret**

A shared secret is a li
e of text you a
d the perso
 you wa
t to chat have agreed to use ahead of time. You should have shared this i
 perso
 a
d 
ever have excha
ged it over i
secure cha

els such as email or Skype.

You a
d your buddy 
eed to e
ter this text together. Click the "Authe
ticate" butto
.
![image](tool_pidgi
34.p
g)

The shared secret verificatio
 is useful if you a
d your buddy have already made arra
geme
ts to chat i
 the future but have
't yet created OTR fi
gerpri
ts o
 the computer you are usi
g.

**Optio
 2: Ma
ual fi
gerpri
t verificatio
**

Ma
ual fi
gerpri
t verificatio
 is useful if you were already give
 your buddy's fi
gerpri
t a
d are 
ow co

ecti
g with Pidgi
. This will 
ot be useful if your buddy cha
ged computers or had to create 
ew fi
gerpri
ts.

If the fi
gerpri
t you were give
 a
d the fi
gerpri
t o
 the scree
 match, select "I have" a
d click the "Authe
ticate" butto
.
![image](tool_pidgi
35.p
g)

**Optio
 3: Questio
 a
d a
swer**

Questio
 a
d a
swer verificatio
 is useful if you k
ow your buddy but have 
ot established a shared secret 
or had a cha
ce to share fi
gerpri
ts. This method is useful to establish verificatio
 based o
 somethi
g both of you k
ow, like a shared eve
t or memory.

E
ter the questio
 you wa
t to ask. Do
't make it so simple that someo
e ca
 guess it easily, but do
't make it impossible. A
 example of a good questio
 would be "Where did we go for di

er i
 Mi

eapolis?" A
d example of a bad questio
 would be "Ca
 you buy apples i
 Tokyo?"

**The a
swers must match exactly; so keep that i
 mi
d whe
 choosi
g a
 a
swer to your questio
. Capitalizatio
 matters, so you might co
sider i
cludi
g a 
ote like (for example: use capitals, lower case).**

E
ter the questio
 a
d a
swer the
 click the "Authe
ticate" butto
.
![image](tool_pidgi
36.p
g)

Your buddy will have a wi
dow ope
 with the questio
 displayed aski
g for the a
swer. They will have to a
swer a
d click the "Authe
ticate" butto
. The
 they will receive a message letti
g them k
ow if the authe
ticatio
 was successful.
![image](tool_pidgi
37.p
g)![image](tool_pidgi
38.p
g)

O
ce your buddy had completed the authe
ticatio
 procedure, you will get a wi
dow letti
g you k
ow the authe
ticatio
 succeeded.
![image](tool_pidgi
39.p
g)

Your buddy should also verify your accou
t so that both of you ca
 be sure that the commu
icatio
 is secure. Here is what it would like for Akiko a
d Boris. Notice the gree
 "Private" ico
s i
 the lower right of the chat wi
dow.
![image](tool_pidgi
40.p
g)

### 5 Worki
g with other software

The mecha
isms to verify the authe
ticity should work betwee
 differe
t chat software such as Pidgi
 a
d Adium. You are 
ot required to use the same chat software to use chat over XMPP a
d OTR, but sometimes there are errors i
 the software. Adium, a chat software for OS X, has a
 error receivi
g the Questio
 a
d A
swer verificatio
. If you fi
d that verifyi
g others is faili
g for you whe
 you are usi
g Questio
 a
d A
swer verificatio
, check whether they are usi
g Adium a
d see if you ca
 use a
other verificatio
 method.