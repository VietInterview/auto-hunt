# auto-hunt

Bước 1: run reg_autohunt port 8761
	cd reg_autohunt && ./mvnw
	
Bước 2: run gw_autohunt port 8080
	2.1 cd reg_autohunt --> yarn install (build front-end) --> yarn start (run angular 6)
	2.2 cd reg_autohunt --> mvnw 
	
Bước 3: run các microservice
	cd svc_collaborator --> mvnw (port 8081)
	cd svc_customer --> mvnw (port 8086)
	.....
Bước 4: run clientsite
	cd clientside --> yarn install --> yarn start

	
	

