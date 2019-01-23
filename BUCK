cxx_library(
  name = "kdtree++",
  srcs = [],
  exported_headers = glob(["kdtree++/*.hpp"]),
  visibility = ["PUBLIC"]
)

cxx_binary(
  name = "test",
  deps = [":kdtree++"],
  srcs = ["examples/test_hayne.cpp"]
)
