![Build WAM](https://github.com/iPlug2/iPlug2OOS/workflows/Build%20WAM/badge.svg)

This is the iPlug2 template project and an example of how to set up an iPlug2 project to build "out of source", which is desirable when you need to keep all your project dependencies synchronised with version control and build on Cloud CI/CD. It set up for "containerized development" using [VSCode](https://code.visualstudio.com/docs/devcontainers/containers) and [github codespaces](https://github.com/features/codespaces).

Instead of using the common-mac.xcconfig and common-win.xcconfig in the iPlug2 folder, it uses copies of them at the top level of the iPlug2OOS repo. This means the iPlug2 submodule itself does not have to be modified.

https://github.com/iPlug2/iPlug2/wiki/Out-of-source-builds

Containerized development is documented [here](https://docs.google.com/document/d/e/2PACX-1vT6lYZ3vtYKWAty2g6DL994IO0_pfyGctDdKfPxF6MZwOgFWENfLuVtBW9J0-KzLsfPSKKN055UnAmj/pub)
