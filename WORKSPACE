workspace(name = "bazel_experiments")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name="archive_in_archive", 
    urls=
    [
        "https://github.com/carpenterjc/bazel_experiments/raw/master/archive_in_archive.zip"
    ], 
    build_file="@//:archive.BUILD",
    sha256 = "4c121f5acaaac59f438b4d726b56b5945d41657f6356084d82cc8cdf76f01a0c" 
)


http_archive(
    name="archive_in_archive_new_name", 
    urls=
    [
        "https://github.com/carpenterjc/bazel_experiments/raw/master/archive_in_archive_new_name.zip"
    ],
    build_file="@//:archive.BUILD",
    sha256 = "4c121f5acaaac59f438b4d726b56b5945d41657f6356084d82cc8cdf76f01a0c" 
)
