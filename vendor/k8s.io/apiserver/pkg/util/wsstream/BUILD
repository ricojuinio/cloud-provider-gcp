load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "conn.go",
        "doc.go",
        "stream.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/util/wsstream",
    importpath = "k8s.io/apiserver/pkg/util/wsstream",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/net/websocket:go_default_library",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime:go_default_library",
        "//vendor/k8s.io/klog:go_default_library",
    ],
)
