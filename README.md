```
> bazel build --announce_rc :env && cat bazel-bin/env.txt
INFO: Options provided by the client:
  Inherited 'common' options: --isatty=1 --terminal_columns=178
INFO: Reading rc options for 'build' from /home/kgessner/tmp/bazel-options/.bazelrc:
  'build' options: --enable_platform_specific_config --action_env=MY_OPTION=global
INFO: Found applicable config definition build:linux in file /home/kgessner/tmp/bazel-options/.bazelrc: --action_env=MY_OPTION=linux
INFO: Analyzed target //:env (0 packages loaded, 0 targets configured).
INFO: Found 1 target...
Target //:env up-to-date:
  bazel-bin/env.txt
INFO: Elapsed time: 0.125s, Critical Path: 0.02s
INFO: 0 processes.
INFO: Build completed successfully, 1 total action
global
```
