# `xujustinj/amazonlinux-amplify-git-lfs`

AWS Amplify does not support the beloved [Git Large File Storage (LFS)](https://git-lfs.com/) out of the box.
This custom Docker image adds Git LFS to the `Amazon Linux:2023` image used by Amplify, with minimal modifications to the Dockerfile used by AWS themselves.

To use this image:

1. navigate to **Build settings** > **Build image settings**
2. click **Edit**
3. select `Build image` in the **Build image** dropdown menu and enter the reference `xujustinj/amazonlinux-amplify-git-lfs:2023`
4. click **Save**
5. redeploy

> [Slawek Kolodziej](https://github.com/slawekkolodziej/aws-amplify-lfs) provides a similar Docker image ([`slawekkolodziej/aws-amplify-lfs`](https://hub.docker.com/r/slawekkolodziej/aws-amplify-lfs)) for `Amazon Linux:2`.
