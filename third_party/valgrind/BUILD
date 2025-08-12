alias(
    name = "valgrind",
    actual = select({
        "@platforms//cpu:x86_64": "@valgrind-deb//:valgrind",
        "@platforms//cpu:aarch64": "@valgrind-deb-arm64//:valgrind",
        "//conditions:default": "@valgrind-deb//:valgrind",
    }),
    visibility = ["//visibility:public"],
)