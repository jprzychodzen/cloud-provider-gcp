load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "gen.go",
        "zz_generated.markerhelp.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/sigs.k8s.io/controller-tools/pkg/schemapatcher",
    importpath = "sigs.k8s.io/controller-tools/pkg/schemapatcher",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/gopkg.in/yaml.v3:go_default_library",
        "//vendor/k8s.io/apiextensions-apiserver/pkg/apis/apiextensions/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/equality:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/crd:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/crd/markers:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/genall:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/loader:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/markers:go_default_library",
        "//vendor/sigs.k8s.io/controller-tools/pkg/schemapatcher/internal/yaml:go_default_library",
        "//vendor/sigs.k8s.io/yaml:go_default_library",
    ],
)
