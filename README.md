# HoustonKVM packages

The dnf repository for [HoustonKVM](https://github.com/researchcookie/houstonkvm), for
EL9 and EL10 on x86_64. It needs EPEL and CRB. To install:

    sudo dnf install -y epel-release
    sudo dnf config-manager --set-enabled crb
    sudo dnf config-manager --add-repo https://researchcookie.github.io/houstonkvm-rpms/houstonkvm.repo
    sudo dnf install houstonkvm

The packages and the repository metadata are signed with
[RPM-GPG-KEY-houstonkvm](RPM-GPG-KEY-houstonkvm); dnf asks you to accept it
the first time.
