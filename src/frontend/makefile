.DEFAULT_GOAL := help


help:
	@echo 'Available commands:'
	@echo -e 'runserver \t\t - \t Runs Django server'

###################################################################################
# WebServer
###################################################################################

runserver:
	python ./src/manage.py runserver

package:
	docker-compose build

package-prod:
	docker-compose -f docker-compose.prod.yml build

package-up-prod:
	docker-compose -f docker-compose.prod.yml up --build