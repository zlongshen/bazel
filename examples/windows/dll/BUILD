cc_binary(
    name = "hellolib.dll",
    srcs = [
        "hello-library.cpp",
    ],
    linkshared = 1,
)

cc_binary(
    name = "hello",
    srcs = [
        "hello-world.cpp",
    ],
    data = [":hellolib.dll"],
)
