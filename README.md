## Attacker

Attacker is a golang application serve as a wraper of `metasploit` and `curl`. And it comes with the following exploit scenarios:

* apache-struts2-cve-2017-5638

* tomcat-cve-2017-12617

* apache-activemq-cve-2016-3088

* postgres-plpython (postgres external procedure call of reverse shell)

* shellshock-cve-2014-6271

* nginx insecure configuration leads to path traversal 

* tomcat-groovy-cve-2020-9484

## Build

Run `make build`

## Run

Run `make run`

## Clean

Run `make clean`

## Todo list

- [x] Containerized Metasploit (with exploit examples)
- [ ] Convert to k8s deployment yamls
