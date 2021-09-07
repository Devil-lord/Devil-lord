Image Instagram NODE JS API V1


For TERMUX ONLY:
* Install Termux (PlayStore)
* Open Termux and Wait for Automatic Install of Termux.
* pkg install git
* pkg install nodejs
* git clone https://github.com/ikiganteng/bot-igeh.git
* cd bot-igeh
* unzip node_modules.zip
* npm install https://github.com/huttarichard/instagram-private-api
* npm audit fix
* ls
* Then select the tool you want to use!
* node filename

For CodeAnywhere/VPS (Centos):
* sudo yum -y update
* sudo yum -y install git
* sudo yum -y install unzip
* sudo yum -y install screen
* curl --silent --location https://rpm.nodesource.com/setup_10.x | sudo bash -
* sudo yum -y install nodejs

=========== Basic Usage ==============
* git clone https://github.com/ikiganteng/bot-igeh.git
* cd bot-igeh
* unzip node_modules.zip
* npm install https://github.com/huttarichard/instagram-private-api
* npm audit fix
* ls
* Then select the tool you want to use!
* node filename

Kita buat session dulu ya!
* screen -S Instagram1 (Instagram1 = Nama Session)
Keluar dari session
* CTRL + A + D
Jika ingin mngecek prosesnya / kembali ke session Instagram1
* screen -r Instagram1
Kita buat session baru dulu ya!
* screen -S Instagram2 (Instagram2 = Nama Session Baru)
Keluar dari session
* CTRL + A + D
Jika ingin mngecek prosesnya / kembali ke session Instagram2
* screen -r Instagram2
Cara memberhentikan/stop tools
* screen -S Instagram1 -X kill (Instagram1 = Nama Session yang ingin di berhentikan)
Untuk melihat list session yang sedang berjalan
* screen -list

For C9/VPS (Ubuntu & Debian):
* sudo apt update
* sudo apt install git
* sudo apt install unzip
* sudo apt install screen
* sudo apt install build-essential libssl-dev
* curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
* source ~/.bashrc
* nvm install 10.7.0

=========== Basic Usage ==============
* git clone https://github.com/ikiganteng/bot-igeh.git
* cd bot-igeh
* unzip node_modules.zip
* nvm use 10.7.0
* npm install https://github.com/huttarichard/instagram-private-api
* npm audit fix
* ls
* Then select the tool you want to use!
* node filename
* untuk buat session sama seperti VPS Centos

INFORMATION:
* dellallphoto			"DELETE ALL POST IG"			(WORK & TESTED)
* fl				"SELECTED WITH TARGET IG"		(WORK & TESTED)
* fah				"SELECTED WITH HASTAG IG"		(WORK & TESTED)
* fftsleep			"SELECTED WITH TARGET IG"		(WORK & TESTED)
* fftdm				"SELECTED WITH TARGET IG"		(WORK & TESTED)
* fftauto			"SELECTED WITH TARGET IG"		(WORK & TESTED)
* fft				"SELECTED WITH TARGET IG"		(WORK & TESTED)
* fftold			"SELECTED WITH TARGET IG"		(WORK & TESTED)
* fftasli			"SELECTED WITH TARGET IG"		(WORK & TESTED)
* flaauto			"SELECTED WITH LOCATION IG"		(WORK & TESTED)
* flmauto			"SELECTED WITH MEDIA IG"		(WORK & TESTED)
* unfollall			"UNFOLOW ALL FOLLOWING IG"		(WORK & TESTED)
* unfollnotfollback		"UNFOLLOW NOT FOLLOWBACK IG"	 	(WORK & TESTED)
* botlike			"LIKE/LOVE TIMELINE IG"			(WORK & TESTED)
* botlike2			"LIKE/LOVE TIMELINE IG"			(WORK & TESTED)
* bomlike			"BOM LIKE POST TARGET"			(WORK & TESTED)
* bomkomen			"BOM KOMEN POST TARGET"			(WORK & TESTED)
* likekomen			"SELECTED WITH POST TARGET"		(WORK & TESTED)
* komenlike			"SELECTED WITH HASTAG TARGET"		(WORK & TESTED)
* cdl				"SELECTED WITH TARGET IG"		(WORK & TESTED)
* cek				"CHECK USERNAME IG TARGET"		(WORK & TESTED)

WARNING
"Use tools at your own risk!!!"
"Use this Tool for personal use, not for sale!!!"
"Make sure your account is not in private to use this tool!!!"

UPDATE
1. Fix Error No Detect Followers Target
2. Input Target/delay Manual (ITTYW)
3. + Improvements In Display Program
4. FFTAUTO & FFT must make file komen.txt and save your comment in there
5. BOMLIKE & BOMKOMEN if you want unlimited read unli_bom.txt
6. FFTSLEEP with random sleep 
