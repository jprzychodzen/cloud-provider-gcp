load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "binarylog.go",
        "binarylog_testutil.go",
        "env_config.go",
        "method_logger.go",
        "sink.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/internal/binarylog",
    importpath = "google.golang.org/grpc/internal/binarylog",
    visibility = ["//vendor/google.golang.org/grpc:__subpackages__"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto:go_default_library",
        "//vendor/github.com/golang/protobuf/ptypes:go_default_library",
        "//vendor/google.golang.org/grpc/binarylog/grpc_binarylog_v1:go_default_library",
        "//vendor/google.golang.org/grpc/grpclog:go_default_library",
        "//vendor/google.golang.org/grpc/internal/grpcutil:go_default_library",
        "//vendor/google.golang.org/grpc/metadata:go_default_library",
        "//vendor/google.golang.org/grpc/status:go_default_library",
    ],
)
