# `akilli/php`

`akilli/base` based PHP image.

Uses the `app` user that is created in the `akilli/base` image. It is configured with `opcache.revalidate_freq = 0`, which is not suitable for development (see the `etc/snippets/php.conf` in the `akilli/nginx` repository for one of several possibilities to adjust this setting for development).

You can use [`docker-compose.yml`](https://github.com/akilli/docker/blob/master/php/docker-compose.yml) as a starting point for your configuration.
