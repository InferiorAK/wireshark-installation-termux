# How to Install WireShark in Termux?
<img src="assets/banner_wit.jpg" align="center" alt="Banner InferiorAK Wireshark">

## [+] At First Download Termux from F-Droid and Install it
- Link -?> <a href="https://f-droid.org/en/packages/com.termux/" target="_blank">**Here**</a>
<img src="assets/ss1.JPG">

## [+] Now Setup
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

> Then Install the given VNC Viwer from Playstore. You can also download from here: <a href="https://github.com/InferiorAK/wireshark-installation-termux/blob/main/VNC%20Viewer_4.1.0.49169.apk">
 
<img src="assets/ss10.png">

> Then Install and Run it like me
  
<img src="assets/ss11.png">
<img src="assets/ss12.jpg">
<img src="assets/ss13.png">
<img src="assets/ss14.jpg">
<img src="assets/ss15.png">

**Now Enjoy!**
