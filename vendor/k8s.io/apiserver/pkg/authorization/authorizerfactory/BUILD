load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "builtin.go",
        "delegating.go",
        "metrics.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/authorization/authorizerfactory",
    importpath = "k8s.io/apiserver/pkg/authorization/authorizerfactory",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/authentication/user:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/authorization/authorizer:go_default_library",
        "//vendor/k8s.io/apiserver/plugin/pkg/authorizer/webhook:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/authorization/v1:go_default_library",
        "//vendor/k8s.io/component-base/metrics:go_default_library",
        "//vendor/k8s.io/component-base/metrics/legacyregistry:go_default_library",
    ],
)
