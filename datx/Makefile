SONAME := libip_datx.so 

CFLAGS := -Wall -fPIC

$(SONAME): ipip.c
	gcc $(CFLAGS) -shared -ldl  $^ -o $@

clean:
	rm -f *.so
