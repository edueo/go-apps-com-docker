.PHONY: build run stop
build:
	docker build -t aplicacao-estatica-sem-dependencias .
run:
	docker container run --name aplicacao-estatica-sem-dependencias -d -p8080:8080 aplicacao-estatica-sem-dependencias:latest
stop:
	docker stop aplicacao-estatica-sem-dependencias
