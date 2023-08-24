PROJECT = Main
WORKDIR = /opt/app
DOCKER_IMAGE = openjdk

build:
	javac ${PROJECT}.java

clean:
	rm ${PROJECT}.class

run:
	java ${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash

install:
	microdnf install -y make
