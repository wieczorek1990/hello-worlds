PROJECT = hello_world
WORKDIR = /opt/app
DOCKER_IMAGE = python

run:
	PYTHONPATH=./src/ python -m ${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash