load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "cmsg.go",
        "utils.go",
        "utils_unix.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/opencontainers/runc/libcontainer/utils",
    importpath = "github.com/opencontainers/runc/libcontainer/utils",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/cyphar/filepath-securejoin:go_default_library",
        "//vendor/golang.org/x/sys/unix:go_default_library",
    ],
)
