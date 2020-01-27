# Docker Images and Plugins to support TFS in ReportPortal

`./init-repo`: Initialize the git submodules.

`./build-all`: Build the whole repository. This includes two patched versions of the `api` and `ui`service of ReportPortal (`bluefu/service-api-with-tfs`, `bluefu/service-ui-with-tfs`) and the TFS Bug Tracking System plugin as `.jar` file (see `plugin-bts-tfs/build/libs/plugin-bts-tfs-<version>-all.jar`).
