### Specs

* 2CPU & 7GB RAM

### How to setup NGROK?.

* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://dashboard.ngrok.com to get **NGROK_AUTH_TOKEN**
* In Github go to ⚙ Settings> Secrets> New repository secret
* In Name: enter **NGROK_AUTH_TOKEN1 (For 1st RDP for 2nd put NGROK_AUTH_TOKEN2 etc**
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into
* Press Add secret
* Go to Action> Run workflow
* Reload the page and press NGROK RDP> build
* Press the down arrow on Connect To Your RPD to get IP, User, Password.

### How to setup GRDP? ( Windows Remote Desktop ). 

* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://remotedesktop.google.com/headless click begin > next > Authorize and copy Windows (PowerShell) code and run workflow. **
* In Github go to ▷ Actions > Windows (Google Remote Desktop) > Run Workflow
* Paste the Windows (PowerShell) code and run workflow.
* Wait 2-3 minutes and go https://remotedesktop.google.com/access If everything worked good you will see your computer there.
* Login the Computer, Name CapciRDP PW 666666 ( You can change name, password If you want. )


## Original Author:
> Don't know who was the original creator, I just edited it and made it still useable in 2021. So, credit goes to whoever created this.

> If you're going to steal my repo at least give credits or I will get your github repo banned.
