DIST_DIR = dist

all: clean run

clean:
	rm -f run

build: clean
	go build -v -o run

run: build
	./run

.PHONY: clean build run all
