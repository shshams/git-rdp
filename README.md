# git-rdp
Git RDP

# Setup
1. Go and copy the file of main.yml
2. Go on your github account and create a private repository
3. Go on workshop and create a new file.
4. Copy all from the main.yml and put into your file
5. Then save it

# Setup Ngrok
1. Go on https://dashboard.ngrok.com/
2. Create a account if you not have it
3. After it go on 'Your Authtoken' and copy you authtoken
4. Then come back to your github repo and go on your repo setting.
5. Go on 'Secrates and variables --> Action'
6. Click on 'New Repository Secrate' name it 'NGROK_AUTH_TOKEN' and copy your Ngrok auth token into the value box and save it

# Run RDP
1. Go on action and click on main.yml
2. Then click on build and wait a bit

# Connect to RDP
1. Then go on your Ngrok Dashbord --> Endpoints
2. Copy the ipv4 without https://
3. Then try to connect with the ip
4. You Username and Password will be
* Username: runneradmin
* Passeord: P@ssw0rd!
5. Boom here you go
6. IMPORTANT! Dont exit the cmd promt which will be shown when you connect to the RDP. Just minimize that CMD Promt and do what you wanted to.
