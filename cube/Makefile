.PHONY: start

start:
	CUBE_WORKER_HOST=localhost CUBE_WORKER_PORT=5556 CUBE_MANAGER_HOST=localhost CUBE_MANAGER_PORT=5555 go run main.go

worker:
	go run main.go worker

manager:
	go run main.go manager -w 'localhost:5556'