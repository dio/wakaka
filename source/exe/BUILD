package(default_visibility = ["//visibility:public"])

licenses(["notice"])  # Apache 2

load(
    "@envoy//bazel:envoy_build_system.bzl",
    "envoy_cc_binary",
)

envoy_cc_binary(
    name = "envoy",
    repository = "@envoy",
    deps = [
        "@envoy//source/exe:envoy_main_entry_lib",
    ],
)
