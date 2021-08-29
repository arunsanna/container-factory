# BuildAh

### Prereqs

```
sudo yum -y update

sudo yum -y install \
    make \
    golang \
    glib2-devel \
    libseccomp-devel \
    git \
    bzip2 \
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
