PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = node

run:
	node ${PROJECT}.js

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
