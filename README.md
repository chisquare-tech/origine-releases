# Origine releases

Public download files for Origine Private Cloud. This repository holds release assets only; it has no source code.

- **The `origine` CLI:** releases tagged `cli/v<version>`, with an archive for each platform (`origine_v<version>_<os>_<arch>.tar.gz`) and `checksums.txt`.
- **Each Origine release:** releases tagged `v<version>`, with the OpenTofu module for Linode Kubernetes Engine (`origine-tofu-lke-<version>.tar.gz`) and `checksums.txt`.

Check a download against its release's `checksums.txt` (`shasum -a 256 -c`). The container images and the Helm chart are on GitHub Container Registry (`ghcr.io/chisquare-tech`). See https://origine.app/docs for how to install.
