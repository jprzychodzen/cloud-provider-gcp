load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["status.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/status",
    importpath = "google.golang.org/grpc/status",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/genproto/googleapis/rpc/status:go_default_library",
        "//vendor/google.golang.org/grpc/codes:go_default_library",
        "//vendor/google.golang.org/grpc/internal/status:go_default_library",
    ],
)
