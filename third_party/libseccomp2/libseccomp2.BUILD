cc_library(
    name = "libseccomp2",
    srcs = glob([
        "lib/*/libseccomp.so.2",
        "lib/*/libseccomp.so.2.5.1",
    ]),
    hdrs = [
        "usr/include/seccomp.h",
        "usr/include/seccomp-syscalls.h",
    ],
    includes = [
        "usr/include/",
        "usr/include/sys/",
    ],
    visibility = ["//visibility:public"],
)