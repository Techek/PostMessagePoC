# PostMessagePoC
postMessage between mother-site with popup-window and iframe'd external site

How to use

1. Install NodeJS
2. Run "npm install http-server -g"
3. Start Mother Website
   1. Start commandprompt
   2. Change directory to &lt;gitpath&gt;
   3. Run "http-server "Mother" -p18546 -i"
4. Start External Website
   1. Start commandprompt
   2. Change directory to &lt;gitpath&gt;
   3. Run "http-server "External" -p18580 -i"
5. Browse http://localhost:18546/
