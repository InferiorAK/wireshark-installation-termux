# How to Install WireShark in Termux?
<img src="assets/banner_wit.jpg" align="center" alt="Banner InferiorAK Wireshark">

<p align="center">
  <img src="https://img.shields.io/github/license/InferiorAK/wireshark-installation-termux?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/InferiorAK/wireshark-installation-termux?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/InferiorAK/wireshark-installation-termux?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/InferiorAK/wireshark-installation-termux?color=teal&style=for-the-badge">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Author-InferiorAK-blue?style=flat-square">
  <!--<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FInferiorAK%2Fwireshark-installation-termux&title=Visitors&edge_flat=false"/></a>-->
</p>

## [+] About Wireshark
<i>

**What Is Wireshark Used For?**

Wireshark has many uses, including troubleshooting networks that have performance issues. Cybersecurity professionals often use Wireshark to trace connections, view the contents of suspect network transactions and identify bursts of network traffic. It’s a major part of any IT pro’s toolkit – and hopefully, the IT pro has the knowledge to use it.

**When Should Wireshark Be Used?**

Wireshark is a safe tool used by government agencies, educational institutions, corporations, small businesses and nonprofits alike to troubleshoot network issues. Additionally, Wireshark can be used as a learning tool.

Those new to information security can use Wireshark as a tool to understand network traffic analysis, how communication takes place when particular protocols are involved and where it goes wrong when certain issues occur.

Of course, Wireshark can’t do everything.

First of all, it can’t help a user who has little understanding of network protocols. No tool, no matter how cool, replaces knowledge very well. In other words, to properly use Wireshark, you need to learn exactly how a network operates. That means, you need to understand things such as the three-way TCP handshake and various protocols, including TCP, UDP, DHCP and ICMP.

Second, Wireshark can’t grab traffic from all of the other systems on the network under normal circumstances. On modern networks that use devices called switches, Wireshark (or any other standard packet-capturing tool) can only sniff traffic between your local computer and the remote system it is talking to.

Third, while Wireshark can show malformed packets and apply color coding, it doesn’t have actual alerts; Wireshark isn’t an intrusion detection system (IDS).

Fourth, Wireshark can’t help with decryption with regards to encrypted traffic.

And finally, it is quite easy to spoof  IPv4 packets. Wireshark can’t really tell you if a particular IP address it finds in a captured packet is a real one or not. That requires a bit more know-how on the part of an IT pro, as well as additional software.

</i>
<br>

## [+] At First Download Termux from F-Droid and Install it
- Link -?> <a href="https://f-droid.org/en/packages/com.termux/" target="_blank">**Here**</a>
<img src="assets/ss1.JPG">

## [+] Setup Process
- ` termux-setup-storage `
- ` apt update `
- ` apt upgrade -y `

<img src="assets/ss2.JPG">

> Then keep all default [N]

<img src="assets/ss3.JPG">

- ` pkg install x11-repo `

<img src="assets/ss4.JPG">

- ` apt install xterm tigervnc tigervnc-viewer `

<img src="assets/ss5.JPG">

- ` apt install wireshark-gtk `

<img src="assets/ss6.JPG">

- ` vncserver `
> Now set Password of 6 characters and then,

- ` vncserver -list `
> You can check all active servers

- ` wireshark `
> This will run your Wireshark on VNC Server

<img src="assets/ss7.JPG">

> Then open a new session in terminal and run these commands to check out
- ` ifconfig `
> From here you have to find the local ip

- ` nmap local_ip `
> From here check the TCP port that being used by VNC Server. It might be 5901

<img src="assets/ss8.JPG">
<img src="assets/ss9.JPG">

> Then Install the given VNC Viwer from Playstore. You can also download from here: <a href="https://github.com/InferiorAK/wireshark-installation-termux/raw/main/VNC%20Viewer_4.1.0.49169.apk">**Here**</a>
 
<img src="assets/ss10.png">

> Then Install and Run it like me
  
<img src="assets/ss11.png">
<img src="assets/ss12.jpg">
<img src="assets/ss13.png">
<img src="assets/ss14.jpg">
<img src="assets/ss15.png">

**Now Enjoy!**
  
## [+] Contact :
<div align=center>
 
[![Github](https://img.shields.io/badge/Github-InferiorAK-orange?style=for-the-badge&logo=github)](https://github.com/InferiorAK)
[![Facebook](https://img.shields.io/badge/Facebook-InferiorAK-red?style=for-the-badge&logo=facebook)](https://www.facebook.com/InferiorAK)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/InferiorAK)
[![Twitter](https://img.shields.io/badge/Twitter-InferiorAK-skyblue?style=for-the-badge&logo=twitter)](https://www.twitter.com/InferiorAK)
 
</div>
