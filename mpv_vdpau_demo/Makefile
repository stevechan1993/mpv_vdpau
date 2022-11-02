CC=gcc
CFLAGS=-lX11 -lvdpau -lavcodec -lavutil -lavfilter -pthread

mpv_vdpau_demo: hwdec_vdpau_lavc.c
	$(CC) -o mpv_vdpau_demo hwdec_vdpau_lavc.c $(CFLAGS)
