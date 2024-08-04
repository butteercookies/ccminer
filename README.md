https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk

'yes | pkg update && pkg upgrade
yes | pkg install libjansson wget nano'

'mkdir ccminer && cd ccminer
wget https://raw.githubusercontent.com/butteercookies/ccminer/main/ccminer
wget https://raw.githubusercontent.com/butteercookies/ccminer/main/config.json
wget https://raw.githubusercontent.com/butteercookies/ccminer/main/start.sh
chmod +x ccminer start.sh'

'~/ccminer/start.sh #test running'

'nano ~/.bashrc' isi dengan 'sh ~/ccminer/start.sh'

'source ~/.bashrc'
