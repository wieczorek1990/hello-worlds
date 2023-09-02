PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = golang

MODULE = hello_world

build:
	go build

run:
	go run .

run-executable:
	./${MODULE}

clean:
	rm ${MODULE}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
