load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["gzip.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/encoding/gzip",
    importpath = "google.golang.org/grpc/encoding/gzip",
    visibility = ["//visibility:public"],
    deps = ["//vendor/google.golang.org/grpc/encoding:go_default_library"],
)
