[Title]: # ()
[Order]: # (0)

# PSIPHON TOOL GUIDE

Censorship Circumvention 

**Lesson to read: [The Internet](umbrella://lesson/the-internet)**  
**Download Location:** [https://psiphon.ca/en/download.html](https://psiphon.ca/en/download.html), [Google Play] (https://play.google.com/store/apps/details?id=com.psiphon3.subscription), [Apple App store] (https://itunes.apple.com/us/app/psiphon/id1276263909?ls=1&mt=8). Check that Android and Windows downloads have an authentic [digital signature](https://psiphon.ca/en/faq.html#verify-psiphon-authentic-toc-collapse).    
**Computer requirements:** An internet connection, and a device running Windows, Android 2.3 or later, or iOS 10.2 or later (iOS 8 for Psiphon browser)    
**License:** Free open-source software; GNU GPL Version 3  
**Level:** Beginner  
**Other reading:** [https://psiphon.ca/en/user-guide.html](https://psiphon.ca/en/user-guide.html)  
**Time required:** 5 minutes

**Using Psiphon will give you:**  
- The ability to safely get around internet censorship to access blocked websites and applications on your phone or computer.

### 1 Before you start 

- Beware malicioius copies of Psiphon and only download from official sources.

![image](tool_psiphon10.png)
![image](tool_psiphon11.png)
![image](tool_psiphon12.png)

- Psiphon does not allow individual user's IP addresses to be associated with any individual website visited, but it is intended primarily as a censorship evasion tool, rather than one that guarantees anonymity.
- If you have not established a connection, you are not using the VPN. Just because you have Psiphon sitting on your computer somewhere does not mean your requests go through the proxy.  
- Web pages may load more slowly when using a VPN. This is normal and it is because the browser is not connecting directly to the website  
- Some paid VPN services may be faster than free ones like Psiphon, but you should be careful before trusting a business with your information, as it could be shared with other organisations or sold to other companies

### 2 Psiphon for Android

Download Psiphon Pro from the [Google Play] (https://play.google.com/store/apps/details?id=com.psiphon3.subscription) store, or select Psiphon Pro for Android on the official Psiphon [download page](https://psiphon.ca/en/download.html?10Years). 

(If you do not have access to the Google Play store, click on the Psiphon for Android direct download link from within your Android email or browser to begin the installation. You may need to [enable sideloading](https://psiphon.ca/en/faq.html#android-enable-sideloading).)

Open the app and cLick *start* to connect to the Psiphon network. 

![image](tool_psiphon5.png)

Select Whole Device mode to tunnel all applications through Psiphon. (This option may not be available for older versions of Android. You can use the dedicated Psiphon browser instead, but only online activity conducted in the browser will use Psiphon. Other apps will connect using your regular Internet connection.)  

![image](tool_psiphon6.png)

The Psiphon "P" in the top left corner of your device indicates Psiphon is running.

### 3 Psiphon for Windows

Download the appropriate version of Psiphon from [here](https://psiphon.ca/en/download.html), and run the program. 

(You should [verify, here, that your copy of Psiphon for Windows is authentic](https://psiphon.ca/en/faq.html#authentic-windows).)

When you run it, you should see a security prompt showing that this program is a legitimate product of Psiphon Inc.
![image](tool_psiphon3.png)

Psiphon automatically starts connecting when you run it. While it is connecting, a spinning icon is displayed. 

You can select one of the following tunnel modes: **VPN, SSH, or SSH+** 

- We recommend that you **select the VPN** option, which means all of your traffic automatically tunnels through Psiphon.  
- The key difference between SSH/SSH+ and VPN is that SSH is application specific while a VPN encrypts all traffic on your computer. With VPN, you turn on the VPN and then all your traffic is encrypted so the web browser, Skype, and email would all bypass censorship as long as the VPN is on.  
- In Psiphon's SSH and SSH+ modes, it automatically sets the proxy settings and traffic for applications that respect these settings tunnel through Psiphon. These settings are respected by default by all major web browsers. SSH plus obfuscation adds a randomized layer on top of SSH to avoid protocol fingerprinting.   
- In SSH and SSH+ modes, Psiphon offers a split option where international traffic is tunnelled through the proxy and domestic traffic is not. Check the "Don't proxy..." option to enable split tunnelling. When this option is on, unproxied domains are reported in the message area.   
- Use SSH/SSH+ options if you want to access domestic sites quickly and your threat model allows it. However we recommend **selecting the VPN option**.

Connection to the Psiphon server is established when the green tick icon is displayed on the left of the window. 
![image](tool_psiphon4.png)

When you close the program, Psiphon automatically disconnects. You can also click on the icon to toggle the connection.

Remember that:  
- Because Psiphon is VPN-based, it is able to proxy all of your Internet traffic, not just websites  
- Traffic between your PC and the VPN server is encrypted, HOWEVER the traffic between that server and a non-HTTPS website will not be encrypted. (The same applies to other Internet services, such as when connecting with Outlook or Thunderbird to a non-SSL email provider.)  


### 4 Psiphon for iOS

Download Psiphon from the [Apple App store] (https://itunes.apple.com/us/app/psiphon/id1276263909?ls=1&mt=8). 

Open the app, and click on the grey *Disconnected* button. 

![image](tool_psiphon7.png)

The button will turn red when it is connecting, and green when it is connected. 

![image](tool_psiphon8.png) ![image](tool_psiphon9.png)

A "VPN" icon in the top left corner of your device indicates Psiphon is running, meaning other apps will access the Internet through Psiphon.

To use the dedicated Psiphon browser for iOS requires a separate [download] (https://itunes.apple.com/us/app/psiphon-browser/id1193362444?mt=8), but it works on iOS 8 and later, while the main Psiphon app requires iOS 10.2 or later. If you use the browser, only online activity conducted in the browser will use Psiphon. Other apps will connect using your regular Internet connection.


