PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = silkeh/clang

build:
	clang++ -o ${PROJECT} ${PROJECT}.cpp

clean:
	rm ${PROJECT}

run:
	./${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
