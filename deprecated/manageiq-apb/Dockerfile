FROM ansibleplaybookbundle/apb-base
MAINTAINER Ansible Playbook Bundle Community

LABEL "com.redhat.apb.version"="0.1.0"
LABEL "com.redhat.apb.spec"=\
"aWQ6IGI0MzI1YWVhLTA0NzktNGY4ZC1iNTAyLTE5MjJiYmFlZTEzZQpuYW1lOiBtYW5hZ2VpcS1h\
cGIKaW1hZ2U6IGFuc2libGVwbGF5Ym9va2J1bmRsZS9tYW5hZ2VpcS1hcGIKZGVzY3JpcHRpb246\
ICJNYW5hZ2VJUSBpcyBhbiBvcGVuIHNvdXJjZSBtYW5hZ2VtZW50IHBsYXRmb3JtIGZvciBIeWJy\
aWQgSVQuIgpiaW5kYWJsZTogZmFsc2UKYXN5bmM6IG9wdGlvbmFsCnBhcmFtZXRlcnM6CiAgLSBh\
cHBsaWNhdGlvbl9pbml0X2RlbGF5OgogICAgICB0aXRsZTogd2ViIGFwcCB0aW1lIGRlbGF5CiAg\
ICAgIGRlc2NyaXB0aW9uOiBUaW1lIHRvIGRlbGF5IHdlYiBhcHAgc3RhcnR1cAogICAgICB0eXBl\
OiBpbnQKICAgICAgZGVmYXVsdDogNjAKICAtIGRhdGFiYXNlX3JlZ2lvbjoKICAgICAgdGl0bGU6\
IGRhdGFiYXNlIHJlZ2lvbgogICAgICBkZXNjcmlwdGlvbjogTUlRIEluc3RhbmNlIFJlZ2lvbgog\
ICAgICB0eXBlOiBpbnQKICAgICAgZGVmYXVsdDogMQogIC0gZGF0YWJhc2Vfc2VydmljZV9uYW1l\
OgogICAgICB0aXRsZTogZGF0YWJhc2Ugc2VydmljZSBuYW1lCiAgICAgIGRlc2NyaXB0aW9uOiBT\
ZXJ2aWNlIE5hbWUgZm9yIHRoZSBkYXRhYmFzZQogICAgICB0eXBlOiBzdHJpbmcKICAgICAgZGVm\
YXVsdDogbWFuYWdlaXEtcG9zdGdyZXNxbAogIC0gbWVtY2FjaGVkX21heF9jb25uZWN0aW9uczoK\
ICAgICAgdGl0bGU6IG1heCBjb25uZWN0aW9ucwogICAgICBkZXNjcmlwdGlvbjogTWF4aW11bSBu\
dW1iZXIgb2YgY29ubmVjdGlvbnMgbWVtY2FjaGVkIHdpbGwgYWNjZXB0CiAgICAgIHR5cGU6IGlu\
dAogICAgICBkZWZhdWx0OiAxMDI0CiAgLSBtZW1jYWNoZWRfbWF4X21lbW9yeToKICAgICAgdGl0\
bGU6IG1heCBtZW1vcnkKICAgICAgZGVzY3JpcHRpb246IE1heGltdW0gbWVtb3J5IG1lbWNhY2hl\
ZCB3aWxsIHVzZSBpbiBNQgogICAgICB0eXBlOiBpbnQKICAgICAgZGVmYXVsdDogNjQKICAtIG1l\
bWNhY2hlZF9zbGFiX3BhZ2Vfc2l6ZToKICAgICAgdGl0bGU6IHNsYWIgcGFnZSBzaXplCiAgICAg\
IGRlc2NyaXB0aW9uOiBNZW1jYWNoZWQgU2xhYiBTaXplIGluIGJ5dGVzCiAgICAgIHR5cGU6IHN0\
cmluZwogICAgICBkZWZhdWx0OiAxTQogIC0gbWVtY2FjaGVkX3NlcnZpY2VfbmFtZToKICAgICAg\
dGl0bGU6IG1lbWNhY2hlZCBzZXJ2aWNlIG5hbWUKICAgICAgZGVzY3JpcHRpb246IFNlcnZpY2Ug\
bmFtZSBvZiB0aGUgbWVtY2FjaGVkIGluc3RhbmNlIHRvIHVzZQogICAgICB0eXBlOiBzdHJpbmcK\
ICAgICAgZGVmYXVsdDogbWFuYWdlaXEtbWVtY2FjaGVkCiAgLSBuYW1lc3BhY2U6CiAgICAgIHRp\
dGxlOiBuYW1lc3BhY2UKICAgICAgZGVzY3JpcHRpb246IE5hbWVzcGFjZS9Qcm9qZWN0IHRvIGRl\
cGxveSB0bwogICAgICB0eXBlOiBzdHJpbmcKICAgICAgZGVmYXVsdDogbWFuYWdlaXEtYXBiCiAg\
LSBwb3N0Z3Jlc3FsX2RhdGFiYXNlOgogICAgICB0aXRsZTogZGF0YWJhc2UgbmFtZQogICAgICBk\
ZXNjcmlwdGlvbjogcG9zdGdyZXNxbCBkYXRhYmFzZSBuYW1lCiAgICAgIHR5cGU6IHN0cmluZwog\
ICAgICBkZWZhdWx0OiB2bWRiX3Byb2R1Y3Rpb24KICAtIHBvc3RncmVzcWxfcGFzc3dvcmQ6CiAg\
ICAgIHRpdGxlOiBkYXRhYmFzZSBwYXNzd29yZAogICAgICBkZXNjcmlwdGlvbjogcG9zdGdyZXNx\
bCBkYXRhYmFzZSBwYXNzd29yZAogICAgICB0eXBlOiBzdHJpbmcKICAgICAgZGVmYXVsdDogYWRt\
aW4KICAtIHBvc3RncmVzcWxfdXNlcjoKICAgICAgdGl0bGU6IGRhdGFiYXNlIHVzZXJuYW1lCiAg\
ICAgIGRlc2NyaXB0aW9uOiBwb3N0Z3Jlc3FsIGRhdGFiYXNlIHVzZXJuYW1lCiAgICAgIHR5cGU6\
IHN0cmluZwogICAgICBkZWZhdWx0OiBhZG1pbgptZXRhZGF0YToKIGRpc3BsYXlOYW1lOiAiTWFu\
YWdlSVEgKEFQQikiCiBpbWFnZVVybDogImh0dHBzOi8vczMuYW1hem9uYXdzLmNvbS9mdXNvci8y\
MDE3ZGVtby9NYW5hZ2VJUS5wbmciCiBkb2N1bWVudGF0aW9uVXJsOiAiaHR0cHM6Ly9tYW5hZ2Vp\
cS5vcmcvZG9jcy8iCiBsb25nRGVzY3JpcHRpb246ICJNYW5hZ2VJUSBpcyBhbiBvcGVuIHNvdXJj\
ZSBtYW5hZ2VtZW50IHBsYXRmb3JtIGZvciBIeWJyaWQgSVQuIEl0IGNhbiBtYW5hZ2Ugc21hbGwg\
YW5kIGxhcmdlIGVudmlyb25tZW50cywgYW5kIHN1cHBvcnRzIG11bHRpcGxlIHRlY2hub2xvZ2ll\
cyBzdWNoIGFzIHZpcnR1YWwgbWFjaGluZXMsIHB1YmxpYyBjbG91ZHMgYW5kIGNvbnRhaW5lcnMu\
Igo="
COPY playbooks /opt/apb/actions
COPY roles /opt/ansible/roles
RUN chmod -R g=u /opt/{ansible,apb}

USER apb
