# 📦 Docsify Docker Example

A Simple [Docsify](https://github.com/docsifyjs/docsify) running env. example repo

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/sujaykumarh/docsify-docker/build-docker)](https://github.com/sujaykumarh/docsify-docker/actions)
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/sujaykumarh/docsify/latest)](https://hub.docker.com/r/sujaykumarh/docsify)
[![Docker Pulls](https://img.shields.io/docker/pulls/sujaykumarh/docsify)](https://hub.docker.com/r/sujaykumarh/docsify)

<br>

## 📥 Download

[GitHub Registry](https://github.com/users/sujaykumarh/packages/container/package/docsify) _[preferred]_

```bash
docker pull ghcr.io/sujaykumarh/docsify:latest
```

[DockerHub](https://hub.docker.com/r/sujaykumarh/docsify)

```bash
docker pull sujaykumarh/docsify:latest
```

<br>

## 🛠️ Usage

### Example setup

Checkout repo [Example](example)

```bash
git clone https://github.com/sujaykumarh/docsify-docker-example.git
```

<br>

### Using Docker Image

### setup

```bash
# initilize docs folder using docsify
docker run --rm -v docs:/docs ghcr.io/sujaykumarh/docsify init
```

### Run

``` bash
# using docker container
docker run --rm -v docs:/docs ghcr.io/sujaykumarh/docsify serve

# or using docker-compose
docker-compose up -d
```

<br>

## 📄 License

[MIT](https://github.com/sujaykumarh/notebook/blob/main/LICENSE)  © 2022 [sujaykumarh](https://github.com/sujaykumarh)



<br>

## 📖 Resources

For more info on docsify

- Read docsify [documentation](https://docsify.js.org/#/?id=docsify)
- Find docsify source on [github](https://github.com/docsifyjs/docsify)
