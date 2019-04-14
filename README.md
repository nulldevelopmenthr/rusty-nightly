# rusty-nightly
Ubuntu based, daily generated base images using nightly rust

This image is used as a base image for releasing projects using Rust's Rocket framework (needs nightly rust) in order to target Alpine docker images (thats why x86_64-unknown-linux-musl is set as target).

To ease up development, it will also install rustfmt.

[DockerHub](https://cloud.docker.com/u/nulldevelopment/repository/docker/nulldevelopment/rusty-nightly/tags)

Load latest: nulldevelopment/rusty-nightly:latest
Load daily: nulldevelopment/rusty-nightly:2019-04-14
