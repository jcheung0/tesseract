AM_CPPFLAGS += \
    -I$(top_srcdir)/src/cutil \
    -I$(top_srcdir)/src/ccutil \
    -I$(top_srcdir)/src/ccstruct \
    -I$(top_srcdir)/src/dict \
    -I$(top_srcdir)/src/viewer
    
if VISIBILITY
AM_CPPFLAGS += -DTESS_EXPORTS \
    -fvisibility=hidden -fvisibility-inlines-hidden
endif

noinst_HEADERS = \
    adaptive.h blobclass.h \
    classify.h cluster.h clusttool.h cutoffs.h \
    errorcounter.h \
    featdefs.h float2int.h fpoint.h \
    intfeaturedist.h intfeaturemap.h intfeaturespace.h \
    intfx.h intmatcher.h intproto.h kdtree.h \
    mastertrainer.h mf.h mfdefs.h mfoutline.h mfx.h \
    normfeat.h normmatch.h \
    ocrfeatures.h outfeat.h picofeat.h protos.h \
    sampleiterator.h shapeclassifier.h shapetable.h \
    tessclassifier.h trainingsample.h trainingsampleset.h

noinst_LTLIBRARIES = libtesseract_classify.la

libtesseract_classify_la_SOURCES = \
    adaptive.cpp adaptmatch.cpp blobclass.cpp \
    classify.cpp cluster.cpp clusttool.cpp cutoffs.cpp \
    errorcounter.cpp \
    featdefs.cpp float2int.cpp fpoint.cpp \
    intfeaturedist.cpp intfeaturemap.cpp intfeaturespace.cpp \
    intfx.cpp intmatcher.cpp intproto.cpp kdtree.cpp \
    mastertrainer.cpp mf.cpp mfdefs.cpp mfoutline.cpp mfx.cpp \
    normfeat.cpp normmatch.cpp \
    ocrfeatures.cpp outfeat.cpp picofeat.cpp protos.cpp \
    sampleiterator.cpp shapeclassifier.cpp shapetable.cpp \
    tessclassifier.cpp trainingsample.cpp trainingsampleset.cpp 
