PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = zenika/kotlin

build:
	kotlinc ${PROJECT}.kt -include-runtime -d ${PROJECT}.jar

clean:
	rm ${PROJECT}.jar

run:
	java -jar ${PROJECT}.jar

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
