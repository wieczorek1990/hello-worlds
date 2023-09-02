PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = swift

FLAGS = -c release

build:
	swift build ${FLAGS}

clean:
	rm -r .build/

run:
	swift run ${FLAGS}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
