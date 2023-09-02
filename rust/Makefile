PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = rust

build:
	rustc ${PROJECT}.rs

clean:
	rm ${PROJECT}

run:
	./${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
