# Makefile.in generated by automake 1.11.3 from Makefile.am.
# apsr/src/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011 Free Software
# Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.






pkgdatadir = $(datadir)/dada
pkgincludedir = $(includedir)/dada
pkglibdir = $(libdir)/dada
pkglibexecdir = $(libexecdir)/dada
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
target_triplet = x86_64-unknown-linux-gnu
bin_PROGRAMS = apsr_udpdb$(EXEEXT) bat_to_utc$(EXEEXT) \
	apsr_udpdisk$(EXEEXT) apsr_udpheader$(EXEEXT) \
	apsr_dbudp$(EXEEXT) test_boardudp$(EXEEXT) \
	apsr_udpgenerator$(EXEEXT)
subdir = apsr/src
DIST_COMMON = $(dist_bin_SCRIPTS) $(srcdir)/Makefile.am \
	$(srcdir)/Makefile.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/config/acx_pthread.m4 \
	$(top_srcdir)/config/affinity.m4 \
	$(top_srcdir)/config/ax_openmp.m4 $(top_srcdir)/config/cuda.m4 \
	$(top_srcdir)/config/fftw.m4 $(top_srcdir)/config/gsl.m4 \
	$(top_srcdir)/config/hwloc.m4 $(top_srcdir)/config/ipp.m4 \
	$(top_srcdir)/config/libtool.m4 \
	$(top_srcdir)/config/ltoptions.m4 \
	$(top_srcdir)/config/ltsugar.m4 \
	$(top_srcdir)/config/ltversion.m4 \
	$(top_srcdir)/config/lt~obsolete.m4 \
	$(top_srcdir)/config/mkl.m4 $(top_srcdir)/config/package.m4 \
	$(top_srcdir)/config/pgplot.m4 $(top_srcdir)/config/rdmacm.m4 \
	$(top_srcdir)/config/sofa.m4 $(top_srcdir)/config/x11.m4 \
	$(top_srcdir)/config/xgpu.m4 $(top_srcdir)/configure.in
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(libdir)" "$(DESTDIR)$(bindir)" \
	"$(DESTDIR)$(bindir)"
LTLIBRARIES = $(lib_LTLIBRARIES)
libapsr_la_LIBADD =
am_libapsr_la_OBJECTS = apsr_udp.lo
libapsr_la_OBJECTS = $(am_libapsr_la_OBJECTS)
PROGRAMS = $(bin_PROGRAMS)
apsr_dbudp_SOURCES = apsr_dbudp.c
apsr_dbudp_OBJECTS = apsr_dbudp.$(OBJEXT)
apsr_dbudp_LDADD = $(LDADD)
apsr_dbudp_DEPENDENCIES = libapsr.la $(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
apsr_udpdb_SOURCES = apsr_udpdb.c
apsr_udpdb_OBJECTS = apsr_udpdb.$(OBJEXT)
apsr_udpdb_LDADD = $(LDADD)
apsr_udpdb_DEPENDENCIES = libapsr.la $(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
apsr_udpdisk_SOURCES = apsr_udpdisk.c
apsr_udpdisk_OBJECTS = apsr_udpdisk.$(OBJEXT)
apsr_udpdisk_LDADD = $(LDADD)
apsr_udpdisk_DEPENDENCIES = libapsr.la \
	$(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
apsr_udpgenerator_SOURCES = apsr_udpgenerator.c
apsr_udpgenerator_OBJECTS = apsr_udpgenerator.$(OBJEXT)
apsr_udpgenerator_LDADD = $(LDADD)
apsr_udpgenerator_DEPENDENCIES = libapsr.la \
	$(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
apsr_udpheader_SOURCES = apsr_udpheader.c
apsr_udpheader_OBJECTS = apsr_udpheader.$(OBJEXT)
apsr_udpheader_LDADD = $(LDADD)
apsr_udpheader_DEPENDENCIES = libapsr.la \
	$(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
bat_to_utc_SOURCES = bat_to_utc.c
bat_to_utc_OBJECTS = bat_to_utc.$(OBJEXT)
bat_to_utc_LDADD = $(LDADD)
bat_to_utc_DEPENDENCIES = libapsr.la $(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
test_boardudp_SOURCES = test_boardudp.c
test_boardudp_OBJECTS = test_boardudp.$(OBJEXT)
test_boardudp_LDADD = $(LDADD)
test_boardudp_DEPENDENCIES = libapsr.la \
	$(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la
SCRIPTS = $(dist_bin_SCRIPTS)
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
SOURCES = $(libapsr_la_SOURCES) apsr_dbudp.c apsr_udpdb.c \
	apsr_udpdisk.c apsr_udpgenerator.c apsr_udpheader.c \
	bat_to_utc.c test_boardudp.c
DIST_SOURCES = $(libapsr_la_SOURCES) apsr_dbudp.c apsr_udpdb.c \
	apsr_udpdisk.c apsr_udpgenerator.c apsr_udpheader.c \
	bat_to_utc.c test_boardudp.c
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/nch/opt/psrdada/missing --run aclocal-1.11
AMTAR = $${TAR-tar}
AR = ar
AUTOCONF = ${SHELL} /home/nch/opt/psrdada/missing --run autoconf
AUTOHEADER = ${SHELL} /home/nch/opt/psrdada/missing --run autoheader
AUTOMAKE = ${SHELL} /home/nch/opt/psrdada/missing --run automake-1.11
AWK = mawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2 -pthread
CPP = gcc -E
CPPFLAGS = -I/usr/local/include 
CUB_CFLAGS = 
CUDA_CFLAGS = -I/usr/local/cuda-8.0/include
CUDA_LIBS = -L/usr/local/cuda-8.0/lib64 -lcudart
CUDA_NVCC = /usr/local/cuda-8.0/bin/nvcc $(CUDA_NVCC_FLAGS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS)
CUFFT_CFLAGS = -I/usr/local/cuda-8.0/include
CUFFT_LIBS = -L/usr/local/cuda-8.0/lib64 -lcufft
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2 -pthread
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
F77 = f77
FFLAGS = -g -O2
FFTW_CFLAGS =  
FFTW_LIBS = -L/usr/lib -lfftw3f -lm 
FGREP = /bin/grep -F
FLIBS = 
GREP = /bin/grep
GSL_CFLAGS = -I/usr/include
GSL_CONFIG = /usr/bin/gsl-config
GSL_LIBS = -L/usr/lib -lgsl -lgslcblas -lm
HWLOC_CFLAGS = 
HWLOC_LIBS = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
IPP_CFLAGS = 
IPP_LIBS = 
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS = -L/usr/local/lib 
LIBOBJS = 
LIBS = -lm  
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LOGIN_ARCH = 
LTLIBOBJS = 
MAKEINFO = ${SHELL} /home/nch/opt/psrdada/missing --run makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
MKL_CFLAGS = 
MKL_LIBS = 
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OPENMP_CFLAGS = -fopenmp
OTOOL = 
OTOOL64 = 
PACKAGE = dada
PACKAGES = 
PACKAGE_BUGREPORT = straten@astron.nl
PACKAGE_NAME = DADA
PACKAGE_STRING = DADA 1.0
PACKAGE_TARNAME = dada
PACKAGE_URL = 
PACKAGE_VERSION = 1.0
PATH_SEPARATOR = :
PGPLOT_CFLAGS = 
PGPLOT_DIR = 
PGPLOT_LIBS =  -lcpgplot -lpgplot  
PSRDADA_INSTALL = /home/nch/linux_64
PSRHOME = 
PTHREAD_CC = gcc
PTHREAD_CFLAGS = -pthread
PTHREAD_LIBS = 
RANLIB = ranlib
RDMACM_CFLAGS = 
RDMACM_LIBS = 
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
SOFA_CFLAGS = 
SOFA_LIBS = 
STRIP = strip
VERSION = 1.0
XGPU_CFLAGS = 
XGPU_LIBS = -L/usr/local/lib -lxgpu
XMKMF = 
X_CFLAGS = 
X_EXTRA_LIBS = 
X_LIBS = 
X_PRE_LIBS =  -lSM -lICE
abs_builddir = /home/nch/opt/psrdada/apsr/src
abs_srcdir = /home/nch/opt/psrdada/apsr/src
abs_top_builddir = /home/nch/opt/psrdada
abs_top_srcdir = /home/nch/opt/psrdada
ac_ct_AR = ar
ac_ct_CC = gcc
ac_ct_CXX = g++
ac_ct_DUMPBIN = 
ac_ct_F77 = f77
acx_pthread_config = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
cuda_nvcc = /usr/local/cuda-8.0/bin/nvcc
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/nch/opt/psrdada/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /home/nch/linux_64
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target = x86_64-unknown-linux-gnu
target_alias = 
target_cpu = x86_64
target_os = linux-gnu
target_vendor = unknown
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
lib_LTLIBRARIES = libapsr.la
libapsr_la_SOURCES = apsr_udp.c apsr_def.h apsr_udp.h apsr_udpdb.h apsr_udpdisk.h apsr_udpheader.h
dist_bin_SCRIPTS = apsr_rm.csh apsr_edit.csh apsr_reprocess.csh
LDADD = libapsr.la \
	$(top_builddir)/src/libpsrdada.la \
	$(top_builddir)/3rdparty/libtimers.la

AM_CPPFLAGS = -I$(top_srcdir)/src \
	-I$(top_srcdir)/3rdparty

all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign apsr/src/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign apsr/src/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-libLTLIBRARIES: $(lib_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	test -z "$(libdir)" || $(MKDIR_P) "$(DESTDIR)$(libdir)"
	@list='$(lib_LTLIBRARIES)'; test -n "$(libdir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 '$(DESTDIR)$(libdir)'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 "$(DESTDIR)$(libdir)"; \
	}

uninstall-libLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(lib_LTLIBRARIES)'; test -n "$(libdir)" || list=; \
	for p in $$list; do \
	  $(am__strip_dir) \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f '$(DESTDIR)$(libdir)/$$f'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f "$(DESTDIR)$(libdir)/$$f"; \
	done

clean-libLTLIBRARIES:
	-test -z "$(lib_LTLIBRARIES)" || rm -f $(lib_LTLIBRARIES)
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  dir="`echo $$p | sed -e 's|/[^/]*$$||'`"; \
	  test "$$dir" != "$$p" || dir=.; \
	  echo "rm -f \"$${dir}/so_locations\""; \
	  rm -f "$${dir}/so_locations"; \
	done
libapsr.la: $(libapsr_la_OBJECTS) $(libapsr_la_DEPENDENCIES) $(EXTRA_libapsr_la_DEPENDENCIES) 
	$(LINK) -rpath $(libdir) $(libapsr_la_OBJECTS) $(libapsr_la_LIBADD) $(LIBS)
install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	test -z "$(bindir)" || $(MKDIR_P) "$(DESTDIR)$(bindir)"
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	for p in $$list; do echo "$$p $$p"; done | \
	sed 's/$(EXEEXT)$$//' | \
	while read p p1; do if test -f $$p || test -f $$p1; \
	  then echo "$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n;h' -e 's|.*|.|' \
	    -e 'p;x;s,.*/,,;s/$(EXEEXT)$$//;$(transform);s/$$/$(EXEEXT)/' | \
	sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1 } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) files[d] = files[d] " " $$1; \
	    else { print "f", $$3 "/" $$4, $$1; } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	    if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	    test -z "$$files" || { \
	    echo " $(INSTALL_PROGRAM_ENV) $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL_PROGRAM) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	    $(INSTALL_PROGRAM_ENV) $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL_PROGRAM) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	    } \
	; done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	files=`for p in $$list; do echo "$$p"; done | \
	  sed -e 'h;s,^.*/,,;s/$(EXEEXT)$$//;$(transform)' \
	      -e 's/$$/$(EXEEXT)/' `; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(bindir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(bindir)" && rm -f $$files

clean-binPROGRAMS:
	@list='$(bin_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list
apsr_dbudp$(EXEEXT): $(apsr_dbudp_OBJECTS) $(apsr_dbudp_DEPENDENCIES) $(EXTRA_apsr_dbudp_DEPENDENCIES) 
	@rm -f apsr_dbudp$(EXEEXT)
	$(LINK) $(apsr_dbudp_OBJECTS) $(apsr_dbudp_LDADD) $(LIBS)
apsr_udpdb$(EXEEXT): $(apsr_udpdb_OBJECTS) $(apsr_udpdb_DEPENDENCIES) $(EXTRA_apsr_udpdb_DEPENDENCIES) 
	@rm -f apsr_udpdb$(EXEEXT)
	$(LINK) $(apsr_udpdb_OBJECTS) $(apsr_udpdb_LDADD) $(LIBS)
apsr_udpdisk$(EXEEXT): $(apsr_udpdisk_OBJECTS) $(apsr_udpdisk_DEPENDENCIES) $(EXTRA_apsr_udpdisk_DEPENDENCIES) 
	@rm -f apsr_udpdisk$(EXEEXT)
	$(LINK) $(apsr_udpdisk_OBJECTS) $(apsr_udpdisk_LDADD) $(LIBS)
apsr_udpgenerator$(EXEEXT): $(apsr_udpgenerator_OBJECTS) $(apsr_udpgenerator_DEPENDENCIES) $(EXTRA_apsr_udpgenerator_DEPENDENCIES) 
	@rm -f apsr_udpgenerator$(EXEEXT)
	$(LINK) $(apsr_udpgenerator_OBJECTS) $(apsr_udpgenerator_LDADD) $(LIBS)
apsr_udpheader$(EXEEXT): $(apsr_udpheader_OBJECTS) $(apsr_udpheader_DEPENDENCIES) $(EXTRA_apsr_udpheader_DEPENDENCIES) 
	@rm -f apsr_udpheader$(EXEEXT)
	$(LINK) $(apsr_udpheader_OBJECTS) $(apsr_udpheader_LDADD) $(LIBS)
bat_to_utc$(EXEEXT): $(bat_to_utc_OBJECTS) $(bat_to_utc_DEPENDENCIES) $(EXTRA_bat_to_utc_DEPENDENCIES) 
	@rm -f bat_to_utc$(EXEEXT)
	$(LINK) $(bat_to_utc_OBJECTS) $(bat_to_utc_LDADD) $(LIBS)
test_boardudp$(EXEEXT): $(test_boardudp_OBJECTS) $(test_boardudp_DEPENDENCIES) $(EXTRA_test_boardudp_DEPENDENCIES) 
	@rm -f test_boardudp$(EXEEXT)
	$(LINK) $(test_boardudp_OBJECTS) $(test_boardudp_LDADD) $(LIBS)
install-dist_binSCRIPTS: $(dist_bin_SCRIPTS)
	@$(NORMAL_INSTALL)
	test -z "$(bindir)" || $(MKDIR_P) "$(DESTDIR)$(bindir)"
	@list='$(dist_bin_SCRIPTS)'; test -n "$(bindir)" || list=; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  if test -f "$$d$$p"; then echo "$$d$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n' \
	    -e 'h;s|.*|.|' \
	    -e 'p;x;s,.*/,,;$(transform)' | sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1; } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) { files[d] = files[d] " " $$1; \
	      if (++n[d] == $(am__install_max)) { \
		print "f", d, files[d]; n[d] = 0; files[d] = "" } } \
	    else { print "f", d "/" $$4, $$1 } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	     if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	     test -z "$$files" || { \
	       echo " $(INSTALL_SCRIPT) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	       $(INSTALL_SCRIPT) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	     } \
	; done

uninstall-dist_binSCRIPTS:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_bin_SCRIPTS)'; test -n "$(bindir)" || exit 0; \
	files=`for p in $$list; do echo "$$p"; done | \
	       sed -e 's,.*/,,;$(transform)'`; \
	dir='$(DESTDIR)$(bindir)'; $(am__uninstall_files_from_dir)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/apsr_dbudp.Po
include ./$(DEPDIR)/apsr_udp.Plo
include ./$(DEPDIR)/apsr_udpdb.Po
include ./$(DEPDIR)/apsr_udpdisk.Po
include ./$(DEPDIR)/apsr_udpgenerator.Po
include ./$(DEPDIR)/apsr_udpheader.Po
include ./$(DEPDIR)/bat_to_utc.Po
include ./$(DEPDIR)/test_boardudp.Po

.c.o:
	depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.o$$||'`;\
	$(COMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c -o $@ $<

.c.obj:
	depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.obj$$||'`;\
	$(COMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ `$(CYGPATH_W) '$<'` &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.c.lo:
	depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.lo$$||'`;\
	$(LTCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Plo
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES) $(PROGRAMS) $(SCRIPTS)
install-binPROGRAMS: install-libLTLIBRARIES

installdirs:
	for dir in "$(DESTDIR)$(libdir)" "$(DESTDIR)$(bindir)" "$(DESTDIR)$(bindir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-binPROGRAMS clean-generic clean-libLTLIBRARIES \
	clean-libtool mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-binPROGRAMS install-dist_binSCRIPTS \
	install-libLTLIBRARIES

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-binPROGRAMS uninstall-dist_binSCRIPTS \
	uninstall-libLTLIBRARIES

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS all all-am check check-am clean clean-binPROGRAMS \
	clean-generic clean-libLTLIBRARIES clean-libtool ctags \
	distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-binPROGRAMS \
	install-data install-data-am install-dist_binSCRIPTS \
	install-dvi install-dvi-am install-exec install-exec-am \
	install-html install-html-am install-info install-info-am \
	install-libLTLIBRARIES install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags uninstall uninstall-am uninstall-binPROGRAMS \
	uninstall-dist_binSCRIPTS uninstall-libLTLIBRARIES


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
