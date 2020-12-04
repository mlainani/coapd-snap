CFLAGS = -lpthread

all: coapd

clean:
	@ rm -f coapd

coapd: coapd.c common.c message.c option.c request.c server.c
	$(CC) coapd.c common.c message.c option.c request.c server.c -o coapd -lpthread

install:
	@ echo Installing...
	@ mkdir -p $(DESTDIR)/bin
	@ cp coapd $(DESTDIR)/bin
