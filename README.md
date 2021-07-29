# Launch Buildpack

This is a Cloud Native Buildpack that allows you to provide [launch configure](https://github.com/buildpacks/spec/blob/main/buildpack.md#launchtoml-toml) to a build.

By default, it will read a `launch.toml` file in the workspace. The path to the launch configure can be overriden by setting `BP_LAUNCH_CONFIG_PATH`.
