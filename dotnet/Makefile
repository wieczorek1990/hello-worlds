PROJECT = Program
WORKDIR = /opt/app
DOCKER_IMAGE = mcr.microsoft.com/dotnet/sdk

build:
	dotnet publish -c Release -o ${PROJECT}

clean:
	rm -r ${PROJECT}/ bin/ obj/

run:
	dotnet ${PROJECT}/app.dll

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
