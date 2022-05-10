# InstaInsane v1.0
## Author: https://github.com/doaibu020619
### Don't copy this code without my permission!
Instainsane is doing a multi-threaded brute force attack against Instagram, this script can bypass login restrictions and can test an unlimited number of passwords at a speed of around 1000 passwords/minute with 100 attempts at a time.

## Legal disclaimer:
The use of InstaInsane to attack targets without prior mutual consent is illegal. End users are responsible for compliance with all applicable local, state, and federal laws. The developer is not responsible and is not responsible for any misuse or damage caused by this program

![insane](https://ibb.co/Vvks5WB)

### Feature
- Multi-thread (100 attempts at a time)
- Save/Resume session
- Anonymous attacks via TOR
- Check valid username
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/doaibu020619/instainsane
cd instainsane
chmod +x instainsane.sh
sudo ./instainsane.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### How it works?

The script uses Android ApkSignature to perform authentication in addition to using a TOR instance to avoid blocking.
The script uses the Instagram-py algorithm (Python), see the project at: https://github.com/antony-jr/instagram-py
Thank you for: https://github.com/doaibu020619
