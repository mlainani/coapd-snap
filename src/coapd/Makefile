all: coapd

clean:
	@ rm -f coapd

coapd: coapd.c

install:
	@ echo Installing...
	@ mkdir -p $(DESTDIR)/bin
	@ cp coapd $(DESTDIR)/bin
