PREFIX?=/usr/X11R6
CFLAGS?=-Os -pedantic -Wall

all:
	$(CC) $(CFLAGS) -I$(PREFIX)/include TigerWM.c -L$(PREFIX)/lib -lX11 -o TigerWM

clean:
	rm -f TigerWM

install: TigerWM
	rm -f /bin/TigerWM
	cp TigerWM /bin

uninstall:
	rm /bin/TigerWM

