CC=g++
SDLDIR=C:\MinGW\x86_64-w64-mingw32
CFLAGS=-I $(SDLDIR)\include\SDL2 -L $(SDLDIR)\lib -lmingw32 -lSDL2main -lSDL2 -O2 -mwindows

main.exe: main.cpp
	$(CC) main.cpp $(CFLAGS) -o main.exe
