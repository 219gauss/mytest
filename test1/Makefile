
CFLAGS := -I ./include
obj = main.o print1/print1.o

main: $(obj)
	
	gcc $^ -o $@
	mv $(obj) out
	
clean:
	sudo rm -rf $(obj) main
	