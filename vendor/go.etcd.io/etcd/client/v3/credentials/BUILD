load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["credentials.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.etcd.io/etcd/client/v3/credentials",
    importpath = "go.etcd.io/etcd/client/v3/credentials",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/go.etcd.io/etcd/api/v3/v3rpc/rpctypes:go_default_library",
        "//vendor/google.golang.org/grpc/credentials:go_default_library",
    ],
)
