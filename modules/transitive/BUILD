load("@tf_modules//:def.bzl", "terraform_module")

terraform_module(
    name = "transitive",
    srcs = glob(["*.tf"]),
    module_deps = [
        "//modules/nested/directories",
        "//modules/nested/non_tf_sources"
    ],
)
