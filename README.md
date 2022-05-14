# win11-vps
Windows Server 2022 vps hosted on Github Actions
# Steps
1. Fork this repository
2. Register/Login in [Ngrok](http://ngrok.io)
3. Copy your token
4. Go to repository settings > Secrets > Actions > New repository secret 
5. Name your secret as `NGROK_AUTH_TOKEN`
6. In value, put your token from [this page](http://dashboard.ngrok.com/get-started/your-authtoken)
7. Now go to Actions tab and select windowsservervps
8. Start and wait 2-3 minutes.
9. Go to your [ngrok dashboard](https://dashboard.ngrok.com/cloud-edge/endpoints) and copy address.
# Some information
Vps only working **~1 hour**. This is a **temporary** vps!! After shutting down server, all data has been deleted!!!!
# How to connect?
Use any RDP client, connect with your ip address from your ngrok dashboard.
```
Username: runneradmin
Password: Vps228228.
```
