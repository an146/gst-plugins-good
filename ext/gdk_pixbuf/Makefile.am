plugin_LTLIBRARIES = libgstgdkpixbuf.la

libgstgdkpixbuf_la_SOURCES = gstgdkpixbuf.c gstgdkpixbufsink.c pixbufscale.c \
	gstgdkpixbufoverlay.c
libgstgdkpixbuf_la_CFLAGS = \
	$(GST_PLUGINS_BASE_CFLAGS) \
	$(GST_CONTROLLER_CFLAGS) \
	$(GST_BASE_CFLAGS) \
	$(GST_CFLAGS) $(GDK_PIXBUF_CFLAGS)
libgstgdkpixbuf_la_LIBADD = \
	$(GST_PLUGINS_BASE_LIBS) -lgstvideo-$(GST_API_VERSION) \
	$(GST_CONTROLLER_LIBS) \
	$(GST_BASE_LIBS) \
	$(GST_LIBS) $(GDK_PIXBUF_LIBS)
libgstgdkpixbuf_la_LDFLAGS = $(GST_PLUGIN_LDFLAGS)
libgstgdkpixbuf_la_LIBTOOLFLAGS = --tag=disable-static

noinst_HEADERS = \
	gstgdkpixbuf.h \
	gstgdkpixbufoverlay.h \
	gstgdkpixbufsink.h \
	pixbufscale.h \
	gstgdkanimation.h
