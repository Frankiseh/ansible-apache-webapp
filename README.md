Role Name
=========

## Name of this role is web
This Role is meant to provision apache2 on ubuntu machine and deploy a simple webapp template.
the data are define in the variable section.

Requirements
------------

This role are ment to run on a ansible remove servers which have to be mordfy on the inventory section of this role.

Role Variables
--------------

There are list of variable which role requres which is located at the /default/main.

	port: 			" " 	 the port of the default port of the apache server to be set
	myname: 		" " 	 name of the administrator
	packageName: 		" " 	 package name e.g apache2 for ubuntu
	packageName2: 		" "      requried before deployment
	serviceName: 		" " 	 name of web service
	fileLoc: 		" " 	 webcontent locathon
	downloadzipfile:        " "  	 downloaded file loacation
	unzipedfile: 		" "  	 unziped file location
	dest1:     		" "      webcontent file location
	webfolder: 		" "      served webcontent file location
	srctemp: 		" "  	 configuration file source location
	desttemp: 		" " 	 configuration file destination location

Dependencies
------------

There is no dependency needed in this role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - web

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
