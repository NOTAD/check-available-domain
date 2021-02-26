# check-available-domain
Source check available domain 35000 / 1 hour

Cài đặt tsc và serve

sudo npm install -g typescript

sudo npm install -g serve

Sử dụng screen để chạy ngầm terminal

screen -R api

tsc && sudo node build/app.js

Ctrl + A + D để thoát screen api và bật screen ui

Sửa backendURL trong file whois-vue/config/prod.js thành ip của vps

screen -R ui

cd whois-vue/ && npm run build && serve -s dist

