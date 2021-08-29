# BuildAh

### Prereqs

```
sudo yum -y update

sudo yum -y install \
    make \
    golang \
    bats \
    btrfs-progs-devel \
    device-mapper-devel \
    glib2-devel \
    gpgme-devel \
    libassuan-devel \
    libseccomp-devel \
    git \
    bzip2 \
    go-md2man \
    runc \
    skopeo-containers
```

### Installation process
```
sudo yum module enable -y container-tools:1.0
sudo yum module install -y buildah

# if above command dont work use

sudo yum -y install buildah

```