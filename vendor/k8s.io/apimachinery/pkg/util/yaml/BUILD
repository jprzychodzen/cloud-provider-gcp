load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["decoder.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/util/yaml",
    importpath = "k8s.io/apimachinery/pkg/util/yaml",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/util/json:go_default_library",
        "//vendor/sigs.k8s.io/yaml:go_default_library",
    ],
)
