PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = r-base

run:
	r ${PROJECT}.r

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
