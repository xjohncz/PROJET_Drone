#############################################################################
# Makefile for building: gradients
# Generated by qmake (2.01a) (Qt 4.8.2) on: jeu. oct. 17 09:37:23 2013
# Project:  gradients.pro
# Template: app
# Command: /usr/local/Qt/bin/qmake -spec ../../mkspecs/qws/linux-arm-g++ -o Makefile gradients.pro
#############################################################################

####### Compiler, tools and options

CC            = /home/texierp/Téléchargements/gcc-linaro-arm-linux-gnueabihf-4.7-2013.01-20130125_linux/bin/arm-linux-gnueabihf-gcc
CXX           = /home/texierp/Téléchargements/gcc-linaro-arm-linux-gnueabihf-4.7-2013.01-20130125_linux/bin/arm-linux-gnueabihf-g++
DEFINES       = -DQT_NO_DEBUG -DQT_GUI_LIB -DQT_NETWORK_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -O2 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I../../mkspecs/qws/linux-arm-g++ -I. -I../../include/QtCore -I../../include/QtNetwork -I../../include/QtGui -I../../include -I../shared -I. -I../../../tslib/include
LINK          = /home/texierp/Téléchargements/gcc-linaro-arm-linux-gnueabihf-4.7-2013.01-20130125_linux/bin/arm-linux-gnueabihf-g++
LFLAGS        = -Wl,-rpath-link=/usr/local/tslib/lib -Wl,-O1 -Wl,-rpath,/usr/local/Qt/lib
LIBS          = $(SUBLIBS)  -L/usr/local/tslib/lib -L../shared -L/usr/local/Qt/lib -ldemo_shared -lQtGui -L/usr/local/lib/ -L/usr/local/Qt/lib -L/usr/local/tslib/lib -lQtNetwork -lQtCore -lpthread 
AR            = /home/texierp/Téléchargements/gcc-linaro-arm-linux-gnueabihf-4.7-2013.01-20130125_linux/bin/arm-linux-gnueabihf-ar cqs
RANLIB        = 
QMAKE         = /usr/local/Qt/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = /home/texierp/Téléchargements/gcc-linaro-arm-linux-gnueabihf-4.7-2013.01-20130125_linux/bin/arm-linux-gnueabihf-strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = main.cpp \
		gradients.cpp moc_gradients.cpp \
		qrc_gradients.cpp
OBJECTS       = main.o \
		gradients.o \
		moc_gradients.o \
		qrc_gradients.o
DIST          = ../../mkspecs/common/unix.conf \
		../../mkspecs/common/linux.conf \
		../../mkspecs/common/gcc-base.conf \
		../../mkspecs/common/gcc-base-unix.conf \
		../../mkspecs/common/g++-base.conf \
		../../mkspecs/common/g++-unix.conf \
		../../mkspecs/common/qws.conf \
		../../mkspecs/qconfig.pri \
		../../mkspecs/features/qt_functions.prf \
		../../mkspecs/features/qt_config.prf \
		../../mkspecs/features/exclusive_builds.prf \
		../../mkspecs/features/default_pre.prf \
		../shared/shared.pri \
		../../mkspecs/features/release.prf \
		../../mkspecs/features/default_post.prf \
		../../mkspecs/features/warn_on.prf \
		../../mkspecs/features/qt.prf \
		../../mkspecs/features/unix/thread.prf \
		../../mkspecs/features/moc.prf \
		../../mkspecs/features/resources.prf \
		../../mkspecs/features/uic.prf \
		../../mkspecs/features/yacc.prf \
		../../mkspecs/features/lex.prf \
		../../mkspecs/features/include_source_dir.prf \
		gradients.pro
QMAKE_TARGET  = gradients
DESTDIR       = 
TARGET        = gradients

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: gradients.pro  ../../mkspecs/qws/linux-arm-g++/qmake.conf ../../mkspecs/common/unix.conf \
		../../mkspecs/common/linux.conf \
		../../mkspecs/common/gcc-base.conf \
		../../mkspecs/common/gcc-base-unix.conf \
		../../mkspecs/common/g++-base.conf \
		../../mkspecs/common/g++-unix.conf \
		../../mkspecs/common/qws.conf \
		../../mkspecs/qconfig.pri \
		../../mkspecs/features/qt_functions.prf \
		../../mkspecs/features/qt_config.prf \
		../../mkspecs/features/exclusive_builds.prf \
		../../mkspecs/features/default_pre.prf \
		../shared/shared.pri \
		../../mkspecs/features/release.prf \
		../../mkspecs/features/default_post.prf \
		../../mkspecs/features/warn_on.prf \
		../../mkspecs/features/qt.prf \
		../../mkspecs/features/unix/thread.prf \
		../../mkspecs/features/moc.prf \
		../../mkspecs/features/resources.prf \
		../../mkspecs/features/uic.prf \
		../../mkspecs/features/yacc.prf \
		../../mkspecs/features/lex.prf \
		../../mkspecs/features/include_source_dir.prf \
		/usr/local/Qt/lib/libQtGui.prl \
		/usr/local/Qt/lib/libQtNetwork.prl \
		/usr/local/Qt/lib/libQtCore.prl
	$(QMAKE) -spec ../../mkspecs/qws/linux-arm-g++ -o Makefile gradients.pro
../../mkspecs/common/unix.conf:
../../mkspecs/common/linux.conf:
../../mkspecs/common/gcc-base.conf:
../../mkspecs/common/gcc-base-unix.conf:
../../mkspecs/common/g++-base.conf:
../../mkspecs/common/g++-unix.conf:
../../mkspecs/common/qws.conf:
../../mkspecs/qconfig.pri:
../../mkspecs/features/qt_functions.prf:
../../mkspecs/features/qt_config.prf:
../../mkspecs/features/exclusive_builds.prf:
../../mkspecs/features/default_pre.prf:
../shared/shared.pri:
../../mkspecs/features/release.prf:
../../mkspecs/features/default_post.prf:
../../mkspecs/features/warn_on.prf:
../../mkspecs/features/qt.prf:
../../mkspecs/features/unix/thread.prf:
../../mkspecs/features/moc.prf:
../../mkspecs/features/resources.prf:
../../mkspecs/features/uic.prf:
../../mkspecs/features/yacc.prf:
../../mkspecs/features/lex.prf:
../../mkspecs/features/include_source_dir.prf:
/usr/local/Qt/lib/libQtGui.prl:
/usr/local/Qt/lib/libQtNetwork.prl:
/usr/local/Qt/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -spec ../../mkspecs/qws/linux-arm-g++ -o Makefile gradients.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/gradients1.0.0 || $(MKDIR) .tmp/gradients1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/gradients1.0.0/ && $(COPY_FILE) --parents gradients.h .tmp/gradients1.0.0/ && $(COPY_FILE) --parents gradients.qrc .tmp/gradients1.0.0/ && $(COPY_FILE) --parents main.cpp gradients.cpp .tmp/gradients1.0.0/ && (cd `dirname .tmp/gradients1.0.0` && $(TAR) gradients1.0.0.tar gradients1.0.0 && $(COMPRESS) gradients1.0.0.tar) && $(MOVE) `dirname .tmp/gradients1.0.0`/gradients1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/gradients1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_gradients.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_gradients.cpp
moc_gradients.cpp: gradients.h
	/usr/local/Qt/bin/moc $(DEFINES) $(INCPATH) gradients.h -o moc_gradients.cpp

compiler_rcc_make_all: qrc_gradients.cpp
compiler_rcc_clean:
	-$(DEL_FILE) qrc_gradients.cpp
qrc_gradients.cpp: gradients.qrc \
		gradients.cpp \
		gradients.html \
		gradients.h
	/usr/local/Qt/bin/rcc -name gradients gradients.qrc -o qrc_gradients.cpp

compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_rcc_clean 

####### Compile

main.o: main.cpp gradients.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

gradients.o: gradients.cpp gradients.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o gradients.o gradients.cpp

moc_gradients.o: moc_gradients.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_gradients.o moc_gradients.cpp

qrc_gradients.o: qrc_gradients.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o qrc_gradients.o qrc_gradients.cpp

####### Install

install_target: first FORCE
	@$(CHK_DIR_EXISTS) $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/ || $(MKDIR) $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/ 
	-$(INSTALL_PROGRAM) "$(QMAKE_TARGET)" "$(INSTALL_ROOT)/usr/local/Qt/demos/gradients/$(QMAKE_TARGET)"
	-$(STRIP) "$(INSTALL_ROOT)/usr/local/Qt/demos/gradients/$(QMAKE_TARGET)"

uninstall_target:  FORCE
	-$(DEL_FILE) "$(INSTALL_ROOT)/usr/local/Qt/demos/gradients/$(QMAKE_TARGET)"
	-$(DEL_DIR) $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/ 


install_sources: first FORCE
	@$(CHK_DIR_EXISTS) $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/ || $(MKDIR) $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/ 
	-$(INSTALL_FILE) /usr/local/Qt/demos/gradients/main.cpp $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/
	-$(INSTALL_FILE) /usr/local/Qt/demos/gradients/gradients.cpp $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/
	-$(INSTALL_FILE) /usr/local/Qt/demos/gradients/gradients.h $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/
	-$(INSTALL_FILE) /usr/local/Qt/demos/gradients/gradients.qrc $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/
	-$(INSTALL_FILE) /usr/local/Qt/demos/gradients/gradients.pro $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/
	-$(INSTALL_FILE) /usr/local/Qt/demos/gradients/gradients.html $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/


uninstall_sources:  FORCE
	-$(DEL_FILE) -r $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/main.cpp 
	 -$(DEL_FILE) -r $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/gradients.cpp 
	 -$(DEL_FILE) -r $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/gradients.h 
	 -$(DEL_FILE) -r $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/gradients.qrc 
	 -$(DEL_FILE) -r $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/gradients.pro 
	 -$(DEL_FILE) -r $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/gradients.html
	-$(DEL_DIR) $(INSTALL_ROOT)/usr/local/Qt/demos/gradients/ 


install:  install_target install_sources  FORCE

uninstall: uninstall_target uninstall_sources   FORCE

FORCE:

