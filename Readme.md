# AutoFill Phishing Demo
### ⚠️ Disclaimer ⚠️
This project is created for educational and research purposes only. It is intended to demonstrate potential security risks associated with browser autofill features and raise awareness about web security best practices.

## Demo
<img src="./AutoFill_Demo.gif" alt="AutoFill Phighin Demo Gif" width="700">

### Start a server: 
![alt text](python-server.png)

### Landing Page:
![alt text](landingpage-chrome.png)


### Start a netcat listener:
![alt text](nc-listener.png)


Run the following to seperate the fields nicely in the response:
```
nc -lnvp 443 | tr "&" "\n"
```
![alt text](example-of-splitting.png)
