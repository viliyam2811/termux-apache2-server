<h3>Termux Apache2 Server</h3>
Install Apache2 Server and setup neccessary settings in your Termux Aap.
The Document Root is within the SDCARD so you can easily manage your files.
Start Apache2 Server by running 'apachectl' command.
This will bring you to the Homepage of your server automatically.
<code>
pkg install git -y && cd ~/ && git clone https://github.com/viliyam2811/termux-apache2-server && cd ~/termux-apache2-server && bash setup && cd ~/ && rm -rf termux-apache2-server
</code>
