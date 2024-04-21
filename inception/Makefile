all: data db wp up

up:
	docker-compose -f ./srcs/docker-compose.yml up -d
data:
	mkdir /home/alyazici/data
db:
	mkdir /home/alyazici/data/db
wp:
	mkdir /home/alyazici/data/wp

down:
	docker-compose -f ./srcs/docker-compose.yml down

.PHONY: up data db wp down
