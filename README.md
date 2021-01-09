# Chrome RDP

! wget https://github.com/laintuv00/LinuxRDP/raw/main/rdp-chrome.sh &> /dev/null

! chmod +x rdp-chrome.sh 

! ./rdp-chrome.sh



# Ngrok RDP

! wget https://github.com/laintuv00/LinuxRDP/raw/main/rdp-ngrok.sh &> /dev/null

! chmod +x rdp-ngrok.sh 

! ./rdp-ngrok.sh

./ngrok authtoken 1m5obnqfsZVJgNVqfvDuOabwAxv_6TGbPAL6Kqqu1eypuNKA6

screen ./ngrok tcp 5901
