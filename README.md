# Dockerfile Best Practices: Specifying Ubuntu Version

This repository demonstrates a common issue and its solution in Dockerfiles: using `ubuntu:latest`.

The original `Dockerfile` uses `ubuntu:latest`, which pulls the latest version of Ubuntu.  This is problematic because updates can introduce breaking changes and inconsistencies in your build environment.  The solution `Dockerfile_fixed` demonstrates how to use a specific Ubuntu version for reproducible builds.