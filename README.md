## Docker Dependencies Mirrors

To ensure reliable builds and avoid Docker Hub rate limiting, this project maintains mirrors of upstream images on the GitHub Container Registry (GHCR).

These images are **unmodified mirrors** of the official upstream releases.

| Service | Source Code | Our Mirror (GHCR) | License |
| :--- | :--- | :--- | :--- |
| **Redis** | [redis/redis](https://github.com/redis/redis) | `ghcr.io/cyberrangecz/docker-dependencies-mirror/redis:6.2.6` | BSD-3-Clause |
| **Syslog-ng** | [syslog-ng/syslog-ng](https://github.com/syslog-ng/syslog-ng) | `ghcr.io/cyberrangecz/docker-dependencies-mirror/syslog-ng:latest` | GPLv2/LGPL |
| **Guacamole** | [apache/guacamole-server](https://github.com/apache/guacamole-server) | `ghcr.io/cyberrangecz/docker-dependencies-mirror/guacd:1.6.0` | Apache 2.0 |
