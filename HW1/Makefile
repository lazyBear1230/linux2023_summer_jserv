CFLAGS = -Wall -std=gnu11 -g -lpthread

OUT = main.out qsort-mt.out

all: $(OUT)

main: main.out

qsort: qsort-mt.out

clean:
	rm -rf $(OUT)

$.out: $.c
	@$(CC) -o $@ $^ $(CFLGAS)