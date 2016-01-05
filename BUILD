licenses(['notice'])

cc_library(
  name = "z",
  visibility = ['//visibility:public'],
  hdrs = glob([
    '*.h',
  ]),
  srcs = [
    "adler32.c",
    "compress.c",
    "crc32.c",
    "deflate.c",
    "gzclose.c",
    "gzlib.c",
    "gzread.c",
    "gzwrite.c",
    "infback.c",
    "inffast.c",
    "inflate.c",
    "inftrees.c",
    "trees.c",
    "uncompr.c",
    "zutil.c",
  ],
  includes = [
    ".",
  ],
)
