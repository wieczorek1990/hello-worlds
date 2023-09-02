PROJECT = hello_world
WORKDIR = /opt/app
DOCKER_IMAGE = python

run:
	PYTHONPATH=./src/ python -m ${PROJECT}

clean:
	rm -r src/hello_world/__pycache__/

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash