net2ledmatrix:main.o artnet_helpers.o
	$(CC) $(LDFLAGS) main.o artnet_helpers.o -o net2ledmatrix

%.o: %.c
	$(CC) -c -o $@ $< $(CFLAGS)

# remove object files and executable when user executes "make clean"
clean:
	rm *.o net2ledmatrix