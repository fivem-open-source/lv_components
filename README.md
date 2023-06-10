

[![Badge License]][License]   
## lv_components v. 1.0

### How to install?
1. Download here
2. unzip the .zip file
3. you can rename the script as you like
4. put it in the resources folder of your FiveM server.
5. add `start SCRIPTNAME` to your server.cfg
6. restart server, done

### What does the script do?
This script hides the standard GTA5 displays, like the money display, the street and vehicle names. Much more can be edited.

### How can I edit it myself?
- open the client.lua file
- in there you see for example `HUD_STREET_NAME`. If you want to hide this, then set a true next to `hidden =`. Otherwise simply a false.

```HUD_STREET_NAME = { id = 9, hidden = true/false },```

Below you can change 2 things, but they are described separately in the file what this does.


### Planned updates for the future
none

- If you find bugs or have suggestions for an update open an issue or a pull-request.


<!---------------------------------------------------------------------------->

[License]: LICENSE


<!---------------------------------[ Badges ]---------------------------------->

[Badge License]: https://img.shields.io/badge/-By_Lvcq1_-ae6c18.svg?style=for-the-badge&labelColor=EF9421&logoColor=white&logo=CreativeCommons
