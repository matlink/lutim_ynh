# Please see https://github.com/maniackcrudelis/lutim_ynh as this is the merged repo of this one and Maniack's one
# Integration is better on the maniack's repo, this one will not be longer maintained.

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

Don't forget to give feedbacks ! (matlink at matlink dot fr)