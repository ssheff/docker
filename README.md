# docker

## Get Trial Docker EE for Linux:

https://hub.docker.com/search/?q=&type=edition&offering=enterprise&operating_system=linux

It would be your 30day trial


Navigate to <your user name> -> "my content" -> "1 Month Trial | 10 Nodes" -> click on "setup"

On the right bottom corner would be your link to download and install your software, it will look like:

https://storebits.docker.com/ee/XXXXXXXXX/<sub-XXXXXXXXXXXXXXXXXXXXXXXXXX>
    

## Node Sizing and Port Requirements

* UCP - 4 core(vcpu) x 16GB Ram X 100GB free in /var/lib/ for kubelet and docker. Increase CPU and RAM as cluster grows

* DTR - 4 core(vcpu) x 16GB Ram X 250GB free in /var/lib/ for kubelet and docker. Increase CPU and RAM to improve CVE Scanning.

* Storage is dependent on if external storage for DTR is used.

* Worker - 4 core(vcpu) x 16GB Ram X 100GB free in /var/lib/ for kubelet and docker. Increase as container workload increases.

Make sure the ports are open between ALL nodes.

[Docker reqs] (https://docs.docker.com/ee/ucp/admin/install/system-requirements/)

##
