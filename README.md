# wkhtmltopdf-odoo
 wkhtmltopdf for odoo 10
resolve the error “WKHTMLTOPDF not found”. This error occur when we installed Odoo first time and using report functionality of modules

Get Package using command
sudo wget https://github.com/mjadily/wkhtmltopdf-odoo/raw/master/wkhtmltox-0.12.1_linux-trusty-amd64.deb

Install the package using command
sudo dpkg -i wkhtmltox-0.12.1_linux-trusty-amd64.deb



Copy wkhtmltoimage to /usr/bin location from /usr/local/bin by using below command

sudo cp /usr/local/bin/wkhtmltoimage /usr/bin/wkhtmltoimage



Copy wkhtmltopdf to /usr/bin location from /usr/local/bin by using below command

sudo cp /usr/local/bin/wkhtmltopdf /usr/bin/wkhtmltopdf


Now just restart odoo server !
