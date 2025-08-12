alias(
    name = "libseccomp2",
    actual = select({
        "@platforms//cpu:x86_64": "@libseccomp2-dev-deb//:libseccomp2",
        "@platforms//cpu:aarch64": "@libseccomp2-dev-deb-arm64//:libseccomp2",
        "//conditions:default": "@libseccomp2-dev-deb//:libseccomp2",
    }),
    visibility = ["//visibility:public"], 
)