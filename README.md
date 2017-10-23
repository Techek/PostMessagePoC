# PostMessagePoC
postMessage between mother-site with popup-window and iframe'd external site

How to use

1. Install NodeJS
2. Run "npm install http-server -g"
3. Start commandprompt (Node)
4. http-server "<gitpath>\Mother" -p18546 -i
5. Start another commandprompt (Node)
6. http-server "<gitpath>\External" -p18580 -i
7. Browse http://localhost:18546/
