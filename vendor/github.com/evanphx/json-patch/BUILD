load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "errors.go",
        "merge.go",
        "patch.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/evanphx/json-patch",
    importpath = "github.com/evanphx/json-patch",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/pkg/errors:go_default_library"],
)
