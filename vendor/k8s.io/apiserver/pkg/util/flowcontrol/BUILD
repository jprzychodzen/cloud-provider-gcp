load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "apf_context.go",
        "apf_controller.go",
        "apf_controller_debug.go",
        "apf_filter.go",
        "formatting.go",
        "rule.go",
        "watch_tracker.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/util/flowcontrol",
    importpath = "k8s.io/apiserver/pkg/util/flowcontrol",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/go-cmp/cmp:go_default_library",
        "//vendor/k8s.io/api/flowcontrol/v1beta2:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/equality:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/api/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/internalversion:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/internalversion/scheme:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/labels:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/types:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/errors:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/sets:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/wait:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/apis/flowcontrol/bootstrap:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/authentication/serviceaccount:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/authentication/user:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/endpoints/request:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/server/mux:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/apihelpers:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/flowcontrol/fairqueuing:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/flowcontrol/fairqueuing/eventclock:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/flowcontrol/fairqueuing/queueset:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/flowcontrol/format:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/flowcontrol/metrics:go_default_library",
        "//vendor/k8s.io/apiserver/pkg/util/flowcontrol/request:go_default_library",
        "//vendor/k8s.io/client-go/informers:go_default_library",
        "//vendor/k8s.io/client-go/kubernetes/typed/flowcontrol/v1beta2:go_default_library",
        "//vendor/k8s.io/client-go/listers/flowcontrol/v1beta2:go_default_library",
        "//vendor/k8s.io/client-go/tools/cache:go_default_library",
        "//vendor/k8s.io/client-go/util/workqueue:go_default_library",
        "//vendor/k8s.io/klog/v2:go_default_library",
        "//vendor/k8s.io/utils/clock:go_default_library",
    ],
)
