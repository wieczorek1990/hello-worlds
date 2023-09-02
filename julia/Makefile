PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = julia

run:
	julia ${PROJECT}.jl

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
