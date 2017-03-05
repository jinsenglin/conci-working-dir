# Install

https://concourse.ci/docker-repository.html

# Launch

```bash
docker-compose up
```

# Demo

```bash
git clone https://github.com/jinsenglin/conci-working-dir.git
cd conci-working-dir
docker-compose up

export PATH=$PATH:$PWD
cd ci/helpers
bash demo.sh
```
