

## Build
    
**NOTE: OpenJDK 14 or older (!) is required. Newer JDK could cause app crash!**  
To build and install debug version, run these commands:

```
git clone https://github.com/gaoxingaa/SmartTube.git
cd SmartTube
git submodule update --init
adb connect <device_ip_address>
gradlew clean installStorigDebug
```

