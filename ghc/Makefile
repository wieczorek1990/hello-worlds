PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = haskell

build:
	ghc ${PROJECT}.hs

clean:
	rm ${PROJECT} ${PROJECT}.hi ${PROJECT}.o

run:
	./${PROJECT}

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
