FROM
USER 0
ADD ./rhel.repo /etc/yum.repos.d/
# RUN yum install -y net-tools
RUN yum install -y iputils
USER 185
COPY ROOT.war /deployments/
