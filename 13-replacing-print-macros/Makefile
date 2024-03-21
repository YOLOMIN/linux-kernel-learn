obj-m += print_string.o
obj-m += kbleds.o

PWD := $(CURDIR) 

all: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules 

clean: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
