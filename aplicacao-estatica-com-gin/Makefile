.PHONY: build run stop
build:
	docker build -t aplicacao-estatica-com-gin .
run:
	docker container run --name aplicacao-estatica-com-gin -d -p8080:8080 aplicacao-estatica-com-gin:latest
stop:
	docker stop aplicacao-estatica-com-gin
