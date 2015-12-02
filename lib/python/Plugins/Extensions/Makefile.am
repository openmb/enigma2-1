installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor PicturePlayer MediaScanner SocketMMI DVDBurn MediaPlayer

if HAVE_WETEK_XBMC
SUBDIRS +=  StartKodi
endif

if VUSOLO4K
SUBDIRS += MiniTV
endif

install_PYTHON = __init__.py
