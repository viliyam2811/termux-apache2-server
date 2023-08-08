<h3>Termux Apache2 Server</h3>
<p>Install Apache2 Server and setup neccessary settings in your Termux Aap.</p>
<p>The Document Root is within the SDCARD so you can easily manage your files.</p>
<p>Start Apache2 Server by running <b>apachectl</b> command.</p>
<p>This will bring you to the Homepage of your server automatically.</p>
<code>
pkg install git -y && cd ~/ && git clone https://github.com/viliyam2811/termux-apache2-server && cd ~/termux-apache2-server && bash setup && cd ~/ && rm -rf termux-apache2-server
</code>
##For PHP-Apache Setup In Termux
Apache Alone is worthless so pfefer 
<a href="https://www.easymux.in/how-to-configure-php-apache-to-run-php-scripts-in-apache2-server-in-termux/)https://www.easymux.in/how-to-configure-php-apache-to-run-php-scripts-in-apache2-server-in-termux/" rel="dofollow">PHP-Apache Installation</a>
