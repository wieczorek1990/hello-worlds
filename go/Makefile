PROJECT = hello_world
WORKDIR = /opt/app
DOCKER_IMAGE = golang

build:
	go build

run:
	go run .

run-executable:
	./${PROJECT}

clean:
	rm ${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
