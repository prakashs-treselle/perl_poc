# perl_poc
Jenkins with Docker test

Installation:

1.Install Perl:
	- sudo apt-get update
	- sudo apt-get install perl
2.Install cpan:
	- Linux systems you can first install cpanminus by typing curl -L http://cpanmin.us | perl - App::cpanminus
3.Install Mojolicious 
	- cpan Mojolicious 
4.Install marbo
    - cpan marbo		

	
How to Run:
	run the hello world program using the below line,
	 - morbo perl_sample.pl
	 
checkout the output using below urls,
	 (i) http://localhost:3000
	    - sample "hello_world" service
	 (ii) http://localhost:3000/user_details
	    - Sample json response for user details
	   