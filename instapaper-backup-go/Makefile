DIST_DIR = dist

all: clean run

clean:
	rm -rf $(DIST_DIR)

build:
	mkdir $(DIST_DIR)/
	go build -v -o $(DIST_DIR)/run

run: build
	./$(DIST_DIR)/run

.PHONY: clean build run all
