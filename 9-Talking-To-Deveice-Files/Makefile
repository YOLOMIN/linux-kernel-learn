#obj-m += ioctl.o 

obj-m += chardev2.o

PWD := $(CURDIR) 
EXTRA_CFLAGS += -I$(PWD)

all: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules 

clean: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
