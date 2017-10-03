Found on https://stackoverflow.com/questions/21820715/how-to-install-latest-version-of-git-on-centos-6-x-7-x
Answer by Joe Goggins
slightly modified, so it works on AWS CentOS 7

run

sudo bash update-git-centos.sh
source /etc/bashrc
git --version

Note: you can use another GIT Version by issuing a command like follows before you run update-git-centos.sh
export GIT_VERSION=2.14.2

the latest version of GIT can be retrieved from https://www.kernel.org/pub/software/scm/git/
