CFLAGS := -g -std=c99 -Wall -Wno-implicit-function-declaration
TARGETS := test_list
all: $(TARGETS)

test_list: test_list.c ../server_logic.c
	gcc $^ -o $@ $(CFLAGS)
clean:
	rm -rf $(TARGETS)
.PHONY: clean
