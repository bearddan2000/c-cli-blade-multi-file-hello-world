cc_library(
    name = 'lib',
    srcs = 'greeting.c',
    hdrs = 'greeting.h',
)

cc_binary(
    name = 'BladeApp',
    srcs = 'main.c',
    deps = [':lib']
)