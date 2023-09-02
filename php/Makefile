PROJECT = main
WORKDIR = /opt/app
DOCKER_IMAGE = php

run:
	php ${PROJECT}.php

bash:
	docker run -v ${PWD}:${WORKDIR} -w ${WORKDIR} -it ${DOCKER_IMAGE} bash
