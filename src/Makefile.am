bin_PROGRAMS = mentohust

LDADD += -lpthread

sysconfdir = /etc

dist_sysconf_DATA = mentohust.conf

mentohust_SOURCES = myini.c md5.c mycheck.c dlfunc.c myfunc.c mystate.c myconfig.c mentohust.c proxy_util.c byte_order.c checkV4.c rjmd5.c rjripemd128.c rjsha1.c rjtiger.c rjtiger_sbox.c rjwhirlpool.c rjwhirlpool_sbox.c logging.c

mentohust_SOURCES += i18n.h types.h myini.h md5.h mycheck.h dlfunc.h myfunc.h mystate.h myconfig.h proxy_util.h byte_order.h checkV4.h rjmd5.h rjripemd128.h rjsha1.h rjtiger.h rjwhirlpool.h ustd.h logging.h

mentohust_LDADD = $(LDADD)

