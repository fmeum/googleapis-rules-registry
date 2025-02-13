# googleapis-rules-registry

A collection of utility modules that allow users to add support for new languages to the `googleapis` Bazel module.

## Usage

Add support for `<lang>_proto_library` targets in `googleapis` by adding a `bazel_dep` on `googleapis-<lang>`. For `<lang>_grpc_library`, use `googleapis-grpc-<lang>`.
