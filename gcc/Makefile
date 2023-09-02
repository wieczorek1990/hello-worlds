PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = gcc

build:
	gcc -o ${PROJECT} ${PROJECT}.c

clean:
	rm ${PROJECT}

run:
	./${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
