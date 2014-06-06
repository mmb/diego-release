FROM ubuntu
VOLUME ["/var/vcap/data/gocd_agent/pipelines/drone_test/", "/workspace"]
RUN date > /workspace/date
RUN apt-get -y install tree
RUN tree /workspace
