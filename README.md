# OpenVPN-To-NordVPN
I made this to bypass the Unity block when trying to run Unity with NordVPN. 

***OpenVPN-To-NordVPN*** does some light Python scripting to find the best NordVPN server for your location, and connects you to it automatically on logon using the OpenVPN GUI.

I also made sure that the code was short and sweet, so you can easily tell if anything fishy is going on


### ------------------Instructions------------------
1. `Install OpenVPN from` 

      a. https://swupdate.openvpn.org/community/releases/openvpn-install-2.4.5-I601.exe  
  
      b. https://nordvpn.com/tutorials/windows-7/openvpn/
  
2. `Modify the data.txt folder accordingly`
3. `*Optionally* modify the login_info.txt with your NordVPN username and password`
4. `Run RunOnStartup (Run Me!).bat (will run the .exe every computer boot)`
5. `Run OpenVPNToNord.exe (to connect right away)`

### -------------------------------------------------

### ------------------Build It Yourself--------------
todo. basically just pip install requests and cx_freeze, do python setup.py build in the directory with setup.py
### -------------------------------------------------

If you are getting config errors, replace the config_files folder with the .ovpn files from https://downloads.nordcdn.com/configs/archives/servers/ovpn.zip

And you're done! Let me know if there are any problems.
