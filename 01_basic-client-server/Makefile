.PHONY: clean

CFLAGS  := -Wall -g
LD      := gcc
LDFLAGS := ${LDFLAGS} -lrdmacm -libverbs -lpthread

APPS    := server client

all: ${APPS}

server: server.o
	${LD} -o $@ $^ ${LDFLAGS}

client: client.o
	${LD} -o $@ $^ ${LDFLAGS}

clean:
	rm -f *.o ${APPS}
