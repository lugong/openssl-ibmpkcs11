lib_LTLIBRARIES=ibmpkcs11.la

ibmpkcs11_la_CFLAGS=-I./include

ibmpkcs11_la_LIBADD=@LIBS@ -lc -lpthread -ldl
ibmpkcs11_la_LDFLAGS=-module -version-info 0:1:0 -shared -no-undefined -avoid-version
ibmpkcs11_la_SOURCES=e_pkcs11.c \
			e_pkcs11_err.c \
			e_pkcs11.h \
			pkcs11f.h \
			pkcs11t.h \
			cryptoki.h \
			e_pkcs11_err.h \
			pkcs11ext.h \
			pkcs11.h \
			pkcs-11v2-20a3.h
