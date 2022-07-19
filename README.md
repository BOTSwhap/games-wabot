pkg update && pkg upgrade -y
pkg install nodejs
pkg install bash -y
pkg install ffmpeg -y
pkg install imagemagick -y
termux-setup-storage -y

git clone https://github.com/BOTSwhap/games-wabot -b multi-device
cd games-wabot 
npm i 
npm start 
