CC=gcc
SOURCES=yo.c yay.c
HEADERS=yay.h
EXECUTABLES=CowBoy

all: $(EXECUTABLES)

$(EXECUTABLES): $(SOURCES) $(HEADERS)
	$(CC) -o $(EXECUTABLES) $(SOURCES)
	strip $(EXECUTABLES)


clean:
	rm -f $(EXECUTABLES)
