

# https://dev.to/thangchung/start-podman-on-wsl2-in-4-steps-3jn9

* https://opensource.com/article/21/10/podman-windows-wsl
* https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/install-containerd-on-ubuntu-22-04.html
    podman machine ls

# https://github.com/containers

podman machine init         // fedorA?
podman machine start

https://docs.podman.io/en/latest/markdown/podman-volume.1.html


Error: podman-machine-default: VM does not exist

podman info
 
wsl podman images
wsl podman run -it docker.io/library/busybox



Installing and using the buildah and skopeo commands is exactly the same process.

# skopeo


skopeo is a command line utility that performs various operations on container images and image repositories.

skopeo does not require the user to be running as root to do most of its operations.

skopeo does not require a daemon to be running to perform its operations.

skopeo can work with OCI images as well as the original Docker v2 images.

skopeo inspect docker://registry.fedoraproject.org/fedora:latest

# buildkit?
https://blog.mobyproject.org/introducing-buildkit-17e056cc5317

# containerd
https://containerd.io/


# rootless.
 ## https://rootlesscontaine.rs/getting-started/common/sysctl/
sudo sysctl --system
what are user namespaces?
https://rootlesscontaine.rs/how-it-works/userns/
https://rootlesscontaine.rs/getting-started/common/subuid/

https://github.com/containerd/nerdctl/releases/download/v0.20.0/nerdctl-0.20.0-linux-amd64.tar.gz

# distrod
https://github.com/nullpo-head/wsl-distrod
