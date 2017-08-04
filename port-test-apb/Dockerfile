FROM ansibleplaybookbundle/apb-base
# MAINTAINER {{ $MAINTAINER }}

LABEL "com.redhat.apb.version"="0.1.0"
LABEL "com.redhat.apb.spec"=\
"bmFtZTogcG9ydC10ZXN0LWFwYgppbWFnZTogZXJpa25lbHNvbi9wb3J0LXRlc3QtYXBiCmRlc2Ny\
aXB0aW9uOiB0ZXN0CmJpbmRhYmxlOiBUcnVlCmFzeW5jOiBvcHRpb25hbAptZXRhZGF0YToKICBk\
aXNwbGF5TmFtZTogUG9ydCBUZXN0IChBUEIpCnBsYW5zOgogIC0gbmFtZTogZGVmYXVsdAogICAg\
ZGVzY3JpcHRpb246IHBvcnQgdGVzdAogICAgZnJlZTogdHJ1ZQogICAgbWV0YWRhdGE6CiAgICAg\
IGRpc3BsYXlOYW1lOiBEZWZhdWx0CiAgICAgIGxvbmdEZXNjcmlwdGlvbjogcG9ydCB0ZXN0CiAg\
ICAgIGNvc3Q6ICQwLjAwCiAgICBwYXJhbWV0ZXJzOiBbXQo="

ADD playbooks /opt/apb/actions
ADD roles /opt/ansible/roles
RUN chmod -R g=u /opt/{ansible,apb}

USER apb
