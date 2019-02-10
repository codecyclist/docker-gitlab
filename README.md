# Setup

## Register Runner
docker run --rm -t -i -v $(pwd)/srv/gitlab-runner-1/config:/etc/gitlab-runner gitlab/gitlab-runner register

(Use Runner tokens from gitlab Web UI)