FROM cloudfoundry/inigo-ci

VOLUME [".", "/workspace"]
RUN date > /workspace/date
RUN apt-get -y install tree
RUN tree /workspace
