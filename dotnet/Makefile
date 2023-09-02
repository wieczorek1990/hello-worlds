PROJECT = Program
WORKDIR = /opt/app
DOCKER_IMAGE = mcr.microsoft.com/dotnet/sdk

FLAGS = -c Release

build:
	dotnet publish ${FLAGS} -o ${PROJECT}

clean:
	rm -r ${PROJECT}/ bin/ obj/

run:
	dotnet ${PROJECT}/app.dll

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
