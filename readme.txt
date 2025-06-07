apt update && apt apt upgrade -y
apt install nodejs -y
apt install npm -y
npm i axios
npm i user-agents
npm i -g pm2
screen pm2 start http.js --name 'http' -- https://litensi.id 120 64 10 proxy.txt
 
gantui link target nya 
