obj-m += vinput.o
obj-m += vkbd.o


PWD := $(CURDIR) 
EXTRA_CFLAGS += -I$(PWD)

all: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules 

clean: 
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean