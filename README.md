# OCS Panel
Simple and lightweight panel for Reseller SSH based on Webmin API, 100% free.

## Features

* **Deposits system** : Sellers only need to deposits, they can create own SSH Account.
* **Remote Webmin** : Just 1 panel can be used for many VPS.

## Requirements

#### Hosting
* PHP v5.3.4 above.
* MySQL v5.0.0 above.

##### VPS
* Webmin
* Perl XML::Parser Module (automatic installed with webmin)

## Installations

`
apt-get install git
`

`
cd /home/vpsiix/public_html
`

`
git init
`

`
git remote add origin https://github.com/vpsiix/OCSPanel.git
`

`
git pull origin master
`

`
cd
`

After installation complete, open browser and open **http://your-ip-vps:nginx-port** and complete required database information. For security after the installation process complete delete the **installation** folder, run command : `rm -R /home/vpsiix/public_html/installation`

AutoScript installation can found at other repository
