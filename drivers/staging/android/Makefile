ccflags-y += -I$(src)			# needed for trace events

obj-$(CONFIG_ANDROID_BINDER_IPC)        += binder.o binder_alloc.o
obj-$(CONFIG_ANDROID_BINDER_IPC_SELFTEST) += binder_alloc_selftest.o
obj-$(CONFIG_ASHMEM)			+= ashmem.o
obj-$(CONFIG_ANDROID_PERSISTENT_RAM)	+= persistent_ram.o
obj-$(CONFIG_ANDROID_RAM_CONSOLE)	+= ram_console.o
obj-$(CONFIG_ANDROID_TIMED_OUTPUT)	+= timed_output.o
obj-$(CONFIG_ANDROID_TIMED_GPIO)	+= timed_gpio.o
obj-$(CONFIG_ANDROID_LOW_MEMORY_KILLER)	+= lowmemorykiller.o
obj-$(CONFIG_ANDROID_SWITCH)		+= switch/
obj-$(CONFIG_PERSISTENT_TRACER)		+= trace_persistent.o

CFLAGS_REMOVE_trace_persistent.o = -pg
