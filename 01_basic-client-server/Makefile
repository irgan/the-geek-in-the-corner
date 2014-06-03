.PHONY: clean

CFLAGS  := -Wall -g
LDFLAGS := ${LDFLAGS} -lrdmacm -libverbs -lpthread

APPS    := server client

all: ${APPS}

f
clean:
	rm -f ${APPS}

