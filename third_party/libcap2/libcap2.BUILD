cc_library(
    name = "libcap2",
    srcs = glob([
        "usr/lib/*/libcap.a",
        "usr/lib/libcap.a",
        "usr/lib/*/libcap.so",
    ]),
    hdrs = [
        "usr/include/sys/capability.h",
    ],
    includes = [
        "usr/include/",
        "usr/include/sys/",
    ],
    visibility = ["//visibility:public"],
    alwayslink = True,
)