git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    tag = "0.5.1",
)

load("@io_bazel_rules_go//go:def.bzl", "go_repositories", "go_repository")
go_repositories()

go_repository(
    name = "com_github_golang_glog",
    importpath = "github.com/golang/glog",
    commit = "23def4e6c14b4da8ac2ed8007337bc5eb5007998",
)

go_repository(
    name = "com_github_gorilla_context",
    tag = "v1.1",
    importpath = "github.com/gorilla/context",
)

go_repository(
    name = "com_github_gorilla_mux",
    tag = "v1.4.0",
    importpath = "github.com/gorilla/mux",
)