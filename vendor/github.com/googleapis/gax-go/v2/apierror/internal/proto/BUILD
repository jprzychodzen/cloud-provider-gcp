load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["error.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/googleapis/gax-go/v2/apierror/internal/proto",
    importpath = "github.com/googleapis/gax-go/v2/apierror/internal/proto",
    visibility = ["//vendor/github.com/googleapis/gax-go/v2/apierror:__subpackages__"],
    deps = [
        "//vendor/google.golang.org/genproto/googleapis/rpc/code:go_default_library",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect:go_default_library",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl:go_default_library",
        "//vendor/google.golang.org/protobuf/types/known/anypb:go_default_library",
    ],
)
