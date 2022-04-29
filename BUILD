load("@rules_python//python:defs.bzl", "py_binary")
load("@python_deps//:requirements.bzl", "requirement")
load("@python3_9//:defs.bzl", "interpreter")

py_binary(
    name = "pre-commit",
    main = "pre-commit_wrapper.py",
    srcs = ["pre-commit_wrapper.py"],
    deps = [
        requirement("pre-commit"),
    ],
)
