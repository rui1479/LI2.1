CC = gcc
CFLAGS = -Wall -Wextra -pedantic -O2
LIBS = -lncurses -lm -lSDL2
OBJS = main.o 

jogo: $(OBJS)
	$(CC) $(CFLAGS) -o jogo $(OBJS) $(LIBS)

main.o: main.c  
	$(CC) $(CFLAGS) -c main.c

clean:
	rm -f *.o jogo