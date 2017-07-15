target:server.o client.o
		gcc -o server server.o
		gcc -o client client.o
server.o:server.c
	gcc -c -o server.o server.c
client.o:client.c
	gcc -c -o client.o client.c 
clean:
	rm *.o server client
.PHONY:clean
