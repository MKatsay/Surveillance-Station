## [Surveillance Station 9.2.0-11289](https://archive.synology.com/download/Package/SurveillanceStation)


---
### Task Scheduler
- Control Panel -> Task Scheduler
- Create -> Scheduled Task -> User-defined script
- General: User = root, uncheck Enable
- Task Settings: User-defined script = ...
- OK - OK
- Click and run task.
- Delete this task when you see there are 58 licenses.

---
### Block license check
- Open Synology's hosts file
```
vi /etc/hosts
```
- add this line to hosts
```
0.0.0.0 synosurveillance.synology.com
```
---
### A. x86_64 (9.2.0-11289)
- Link download: https://global.synologydownload.com/download/Package/spk/SurveillanceStation/9.2.0-11289/SurveillanceStation-x86_64-9.2.0-11289.spk
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ohyeah521/Surveillance-Station/main/9.2.0_11289/SurveillanceStation-x86_64/install_license)
```

---
### Remove license
- Script:
```
bash <(curl -L https://raw.githubusercontent.com/ohyeah521/Surveillance-Station/main/9.2.0_11289/license/remove_license)
```
---
### Cracked
![License](https://raw.githubusercontent.com/ohyeah521/Surveillance-Station/main/img/crack_license.png)


---
### Buy me coffee
![License](https://raw.githubusercontent.com/ohyeah521/Surveillance-Station/main/img/buy%20me%20coffee.jpg)
