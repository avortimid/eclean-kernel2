ACLOCAL_AMFLAGS = -I build-aux
AM_CXXFLAGS = -std=c++11
AM_CPPFLAGS = -I$(top_srcdir)/src

bin_PROGRAMS = eclean-kernel

eclean_kernel_SOURCES = \
	src/ek2/actions.cxx \
	src/ek2/actions.h \
	src/ek2/bootloader.cxx \
	src/ek2/bootloader.h \
	src/ek2/bootloaders/grub2.cxx \
	src/ek2/bootloaders/grub2.h \
	src/ek2/bootloaders.cxx \
	src/ek2/bootloaders.h \
	src/ek2/file.cxx \
	src/ek2/file.h \
	src/ek2/files/builddir.cxx \
	src/ek2/files/builddir.h \
	src/ek2/files/genericfile.cxx \
	src/ek2/files/genericfile.h \
	src/ek2/files/kernelfile.cxx \
	src/ek2/files/kernelfile.h \
	src/ek2/files/modulesdir.cxx \
	src/ek2/files/modulesdir.h \
	src/ek2/fileset.cxx \
	src/ek2/fileset.h \
	src/ek2/judge.cxx \
	src/ek2/judge.h \
	src/ek2/judges/cleanstale.cxx \
	src/ek2/judges/cleanstale.h \
	src/ek2/judges/keepcommonfiles.cxx \
	src/ek2/judges/keepcommonfiles.h \
	src/ek2/judges/keepnewest.cxx \
	src/ek2/judges/keepnewest.h \
	src/ek2/judges/protectrunning.cxx \
	src/ek2/judges/protectrunning.h \
	src/ek2/judges.cxx \
	src/ek2/judges.h \
	src/ek2/layout.cxx \
	src/ek2/layout.h \
	src/ek2/layouts/std.cxx \
	src/ek2/layouts/std.h \
	src/ek2/layouts.cxx \
	src/ek2/layouts.h \
	src/ek2/options.cxx \
	src/ek2/options.h \
	src/ek2/sorts.cxx \
	src/ek2/sorts.h \
	src/ek2/util/directorystream.cxx \
	src/ek2/util/directorystream.h \
	src/ek2/util/error.cxx \
	src/ek2/util/error.h \
	src/ek2/util/relativepath.cxx \
	src/ek2/util/relativepath.h \
	src/ek2/util/subprocess.cxx \
	src/ek2/util/subprocess.h \
	src/main.cxx
