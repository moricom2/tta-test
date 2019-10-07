FROM
USER 0
ADD ./rhel.repo /etc/yum.repos.d/
# RUN yum install -y net-tools
RUN yum install -y iputils
USER 185
ENV JAVA_OPTS_APPEND -Dfile.encoding=UTF-8
COPY ROOT.war /deployments/
