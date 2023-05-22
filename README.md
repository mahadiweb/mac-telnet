# mac-telnet
Mac Telnet
### Main source [Link](https://github.com/haakonnessjoen/MAC-Telnet/)


## Install Command
##### Centos
`sudo yum install https://www.ngtech.co.il/repo/centos/7/x86_64/mactelnet-client-0.4.4-2.el7.centos.x86_64.rpm`
##### Ubuntu
`sudo apt-get install  mactelnet-client`

### Basic Command
* Help:
`mactelnet -h`

* Get available mac-telnet devices:
`mactelnet -l`

* Connect using mac address:
`mactelnet c0:a3:36:f9:5f:ac`

* `-u` for username And `-p` for password

* For quiet mac-telnet:
`-q`
