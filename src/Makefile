PREFIX?=/usr/X11R6
CFLAGS?=-Os -pedantic -Wall

all:
	$(CC) $(CFLAGS) -I$(PREFIX)/include Tiger-Window-Manager.c -L$(PREFIX)/lib -lX11 -o Tiger-Window-Manager

clean:
	rm -f Tiger-Window-Manager

install: Tiger-Window-Manager
	cp Tiger-Window-Manager /bin

uninstall:
	rm /bin/Tiger-Window-Manager

