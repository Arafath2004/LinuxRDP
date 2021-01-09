# Chrome RDP
https://colab.research.google.com

! wget https://raw.githubusercontent.com/laintuv00/LinuxRDP/main/rdp-chrome.sh &> /dev/null

! chmod +x rdp-chrome.sh 

! ./rdp-chrome.sh



# Ngrok RDP
https://www.katacoda.com/courses/ubuntu/playground

! wget https://raw.githubusercontent.com/laintuv00/LinuxRDP/main/rdp-ngrok.sh &> /dev/null

! chmod +x rdp-ngrok.sh 

! ./rdp-ngrok.sh

./ngrok authtoken 1m5obnqfsZVJgNVqfvDuOabwAxv_6TGbPAL6Kqqu1eypuNKA6

screen ./ngrok tcp 5901
