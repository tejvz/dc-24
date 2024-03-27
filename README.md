# Discord-Online-Forever
Keep Your Discord Profile/Account Online Forever For 24/7

# ON PC / Proccess
1. Register Replit - https://Replit.com
2. Run on Replit - https://github.com/tejvz/dc-24
3. Get Token of your Discord:
  - Login to your Discord in the browser
  - Press: CTRL+SHITT+I or F12. Go to Network. Click some dialogue or some server
  - Find sciense. Go to Headers. In request headers find: authorization. Copy this token
4. Go to replit, secrets. make new secret. Key is token, and value is your token
5. Run the bot
6. Go to https://uptimerobot.com, https://cron-job.org, register. Click: Add new moinitor Or Go to cron-jon.org then register and click on "CREATE CRONJOB"
7. Monitor type is HTTP. Url is address you get on replit. Click create monitor (2 times)
8. Make sure the last session you was online

# ON MOBILE / Not Tell The Proccess To Run
 1. Go To Play Store Search "Kiwi Browser"
 2. Click On Install
 3. After Installing Go To https://discord.com/login
 4. Login Your Account And Then Go To Any Chat/Dm/Server/Channel 
 5. Click On 3 Dots On Right Corner
 5. Then Click On Developer Tool
 6. Click On Application On The Top
 7. Click On Local Storage 2 Times
 6. Then Click On https://discord.com/...
 7. Then Search "token" There
 8. Copy The Value Of "token"
 9. Thats Your Discord Id Token
 
 # Add Secrets
 
 Key - [ token ] = Value - [ Your Discord Account Token Here ]
 
 # In Termux 
 
 **pkg install git**
 
 git clone https://github.com/tejvz/dc-24
 Do "npm install" after going into file
 then "node index.js" but thats not 24/7 thats only work when 
 your termux is working in background
 
 # RECOMMENDATION
 **Preferred To Be Run In Replit Or In Render**