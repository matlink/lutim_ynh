# lutim_ynh
Based on this french tutorial : http://framacloud.org/cultiver-son-jardin/installation-de-lutim/

# Installation can be very long
To prevent any issue, install it via command line (SSH) using : 
	
	sudo yunohost app install https://github.com/matlink/lutim_ynh

or by installing those packages before installing lutim (prefer the first solution, this one was not tested): 

	sudo cpan Carton
	wget https://github.com/ldidry/lutim/raw/master/cpanfile
	sudo carton install

TODO
----

- Allow accessing uploaded image only without credentials, but upload an image requires yunohost login (in case of private app).
- cronjobs to check size of folder (in case if bigger than max size in conf file)