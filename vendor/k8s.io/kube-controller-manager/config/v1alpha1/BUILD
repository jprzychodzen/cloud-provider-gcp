load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "register.go",
        "types.go",
        "zz_generated.deepcopy.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kube-controller-manager/config/v1alpha1",
    importpath = "k8s.io/kube-controller-manager/config/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/cloud-provider/config/v1alpha1:go_default_library",
        "//vendor/k8s.io/cloud-provider/controllers/service/config/v1alpha1:go_default_library",
        "//vendor/k8s.io/controller-manager/config/v1alpha1:go_default_library",
    ],
)
