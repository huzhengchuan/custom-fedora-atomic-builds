Tested in a fedora 25 m2.large vm, m2.small will work as well

Script to build a fedora atomic 25 image with:

* docker 1.12 (fedora-25)
* flannel (fedora-25)
* etcd (fedora-25)
* kubernetes 1.4 (kubernetes repository)

To be used with OpenStack/Magnum.

Sample image: http://test-strigazi-sharing.web.cern.ch/test-strigazi-sharing/fedora-atomic-25-k8s-1.4-docker-1.12.qcow2

./run.sh

