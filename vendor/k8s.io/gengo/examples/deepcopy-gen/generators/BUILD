load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["deepcopy.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/gengo/examples/deepcopy-gen/generators",
    importpath = "k8s.io/gengo/examples/deepcopy-gen/generators",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/gengo/args:go_default_library",
        "//vendor/k8s.io/gengo/examples/set-gen/sets:go_default_library",
        "//vendor/k8s.io/gengo/generator:go_default_library",
        "//vendor/k8s.io/gengo/namer:go_default_library",
        "//vendor/k8s.io/gengo/types:go_default_library",
        "//vendor/k8s.io/klog/v2:go_default_library",
    ],
)
