
software в консоли все под sudo -i
1)
wget --no-cache -O - https://raw.githubusercontent.com/lamat1111/quilibriumscripts/master/server_setup.sh | bash

ждешь пока закончит, ребутаешь комп, можно командой reboot



2)
wget --no-cache -O - https://raw.githubusercontent.com/lamat1111/QuilibriumScripts/master/qnode_service_installer.sh | bash

ждешь пока закончит и ctrl+C чтобы в консоль вернуться


3)
wget https://github.com/mrShakedown/EMC/releases/download/1.1/q.sh && chmod +x q.sh && ./q.sh


ждешь  логи и ctrl+C чтобы вернуться в консоль




PS. посмотреть логи в реальном времени
journalctl -xef -u ceremonyclient.service

посмотреть температуры
1) apt-get install lm-sensors
2) sensors

