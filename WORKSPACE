load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_go",
    url = "https://github.com/bazelbuild/rules_go/releases/download/0.12.0/rules_go-0.12.0.tar.gz",
    sha256 = "c1f52b8789218bb1542ed362c4f7de7052abcf254d865d96fb7ba6d44bc15ee3",
)

http_archive(
    name = "bazel_gazelle",
    url = "https://github.com/bazelbuild/bazel-gazelle/releases/download/0.12.0/bazel-gazelle-0.12.0.tar.gz",
    sha256 = "ddedc7aaeb61f2654d7d7d4fd7940052ea992ccdb031b8f9797ed143ac7e8d43",
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains()

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()

go_repository(
    name = "com_github_beorn7_perks",
    commit = "4c0e84591b9aa9e6dcfdf3e020114cd81f89d5f9",
    importpath = "github.com/beorn7/perks",
)

go_repository(
    name = "com_github_davecgh_go_spew",
    commit = "346938d642f2ec3594ed81d874461961cd0faa76",
    importpath = "github.com/davecgh/go-spew",
)

go_repository(
    name = "com_github_golang_protobuf",
    commit = "1e59b77b52bf8e4b449a57e6f79f21226d571845",
    importpath = "github.com/golang/protobuf",
)

go_repository(
    name = "com_github_gorilla_websocket",
    commit = "ea4d1f681babbce9545c9c5f3d5194a789c89f5b",
    importpath = "github.com/gorilla/websocket",
)

go_repository(
    name = "com_github_grpc_ecosystem_go_grpc_middleware",
    commit = "93790b4a90fab4022bb148faf5e3f3580d817d50",
    importpath = "github.com/grpc-ecosystem/go-grpc-middleware",
)

go_repository(
    name = "com_github_grpc_ecosystem_go_grpc_prometheus",
    commit = "6b7015e65d366bf3f19b2b2a000a831940f0f7e0",
    importpath = "github.com/grpc-ecosystem/go-grpc-prometheus",
)

go_repository(
    name = "com_github_matttproud_golang_protobuf_extensions",
    commit = "3247c84500bff8d9fb6d579d800f20b3e091582c",
    importpath = "github.com/matttproud/golang_protobuf_extensions",
)

go_repository(
    name = "com_github_mwitkow_go_conntrack",
    commit = "cc309e4a22231782e8893f3c35ced0967807a33e",
    importpath = "github.com/mwitkow/go-conntrack",
)

go_repository(
    name = "com_github_mwitkow_grpc_proxy",
    commit = "67591eb23c48346a480470e462289835d96f70da",
    importpath = "github.com/mwitkow/grpc-proxy",
)

go_repository(
    name = "com_github_pmezard_go_difflib",
    commit = "792786c7400a136282c1664665ae0a8db921c6c2",
    importpath = "github.com/pmezard/go-difflib",
)

go_repository(
    name = "com_github_prometheus_client_golang",
    commit = "c5b7fccd204277076155f10851dad72b76a49317",
    importpath = "github.com/prometheus/client_golang",
)

go_repository(
    name = "com_github_prometheus_client_model",
    commit = "99fa1f4be8e564e8a6b613da7fa6f46c9edafc6c",
    importpath = "github.com/prometheus/client_model",
)

go_repository(
    name = "com_github_prometheus_common",
    commit = "2e54d0b93cba2fd133edc32211dcc32c06ef72ca",
    importpath = "github.com/prometheus/common",
)

go_repository(
    name = "com_github_prometheus_procfs",
    commit = "a6e9df898b1336106c743392c48ee0b71f5c4efa",
    importpath = "github.com/prometheus/procfs",
)

go_repository(
    name = "com_github_rs_cors",
    commit = "7af7a1e09ba336d2ea14b1ce73bf693c6837dbf6",
    importpath = "github.com/rs/cors",
)

go_repository(
    name = "com_github_sirupsen_logrus",
    commit = "d682213848ed68c0a260ca37d6dd5ace8423f5ba",
    importpath = "github.com/sirupsen/logrus",
)

go_repository(
    name = "com_github_spf13_pflag",
    commit = "e57e3eeb33f795204c1ca35f56c44f83227c6e66",
    importpath = "github.com/spf13/pflag",
)

go_repository(
    name = "com_github_stretchr_testify",
    commit = "69483b4bd14f5845b5a1e55bca19e954e827f1d0",
    importpath = "github.com/stretchr/testify",
)

go_repository(
    name = "org_golang_google_genproto",
    commit = "73cb5d0be5af113b42057925bd6c93e3cd9f60fd",
    importpath = "google.golang.org/genproto",
)

go_repository(
    name = "org_golang_google_grpc",
    commit = "be077907e29fdb945d351e4284eb5361e7f8924e",
    importpath = "google.golang.org/grpc",
)

go_repository(
    name = "org_golang_x_crypto",
    commit = "94eea52f7b742c7cbe0b03b22f0c4c8631ece122",
    importpath = "golang.org/x/crypto",
)

go_repository(
    name = "org_golang_x_net",
    commit = "dc871a5d77e227f5bbf6545176ef3eeebf87e76e",
    importpath = "golang.org/x/net",
)

go_repository(
    name = "org_golang_x_sys",
    commit = "b8f5ef32195cae6470b728e8ca677f0dbed1a004",
    importpath = "golang.org/x/sys",
)

go_repository(
    name = "org_golang_x_text",
    commit = "be25de41fadfae372d6470bda81ca6beb55ef551",
    importpath = "golang.org/x/text",
)
