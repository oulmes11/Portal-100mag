تحديث جديد stalker.conf
بورطالات جديدة ​


لتحديث لملف stalker.conf
غيرت البورطالات المتوقفة بأخري شغالة



امر ارسال البورطالات الى home/stalker.conf

wget -O /home/stalker.conf https://raw.githubusercontent.com/karimSATPRO/Portal-100mag/main/stalker.conf && init 4; sleep 4; init 3

امر الرفع من عدد البورطالات (150) كحد أقصي

wget -O /usr/lib/enigma2/python/Plugins/Extensions/MultiStalker/commons/commons.py https://raw.githubusercontent.com/karimSATPRO/Portal-100mag/main/commons.py && killall -9 enigma2

أمر تهيئة multistalker من البورطالات


init 4; sleep 5; sed -e s/config.plugins.MultiStalker.portals.*//g -i /etc/enigma2/settings; init 3
