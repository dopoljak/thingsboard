# build thingsboard
	
	- jdk 8 is mandatory for windows
	
	mvn clean install -DskipTests
	
	
	
# build docker image
	
	docker build -f ./msa/web-ui/target/Dockerfile . -t ilirium/tb-web-ui:3.2.0
	
	