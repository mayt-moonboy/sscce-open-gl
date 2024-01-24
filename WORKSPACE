load(
    "@bazel_tools//tools/build_defs/repo:http.bzl",
    "http_archive",
)

glwf_version = "3.3.7"
glwf_sha256 = "fd21a5f65bcc0fc3c76e0f8865776e852de09ef6fbc3620e09ce96d2b2807e04"
http_archive(
    name = "glfw",
    build_file = "@//:external/glfw/BUILD.bazel",
    sha256 = glwf_sha256 ,
    strip_prefix = "glfw-{v}".format(v = glwf_version),
    url = "https://github.com/glfw/glfw/archive/{v}.tar.gz".format(v = glwf_version),
)