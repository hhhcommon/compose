FROM busybox:1.31.0-uclibc
LABEL com.docker.compose.test_image=true
LABEL com.docker.compose.test_failing_image=true
# With the following label the container will be cleaned up automatically
# Must be kept in sync with LABEL_PROJECT from compose/const.py
LABEL com.docker.compose.project=composetest
RUN exit 1
