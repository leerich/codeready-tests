FROM registry.redhat.io/codeready-workspaces/stacks-python 
USER root
COPY ansible-lint-3.5.1-1.el7.noarch.rpm /tmp COPY ansible-2.8.4-1.el7.ans.noarch.rpm /tmp RUN rpm -i /tmp/ansible-2.8.4-1.el7.ans.noarch.rpm 
RUN rpm -i /tmp/ansible-lint-3.5.1-1.el7.noarch.rpm 
RUN rm -rf /tmp/*.gz && rm -rf /tmp/*.tar && rm -rf /tmp/*.rpm && rm -rf /tmp/pip-19.2.2/ && rm -rf /tmp/*.whl
