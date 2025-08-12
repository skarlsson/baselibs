alias(
    name = "acl",
    actual = select({
        "@platforms//cpu:x86_64": "@acl-deb//:acl",
        "@platforms//cpu:aarch64": "@acl-deb-arm64//:acl",
        "//conditions:default": "@acl-deb//:acl",
    }),
    visibility = ["//visibility:public"], 
)