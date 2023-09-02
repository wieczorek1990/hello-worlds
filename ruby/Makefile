PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = ruby

run:
	ruby ${PROJECT}.rb

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash