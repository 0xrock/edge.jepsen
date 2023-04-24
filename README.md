# Jepsen Tests for Edge

FIXME

## Quickstart

Assuming you have [docker-compose](https://github.com/docker/compose) set up
already, run:

```
cd docker && bin/up
```

In another terminal, run:

```
cd docker && bin/console
```

Once console is up, run:

```
root@control:/jepsen# cd jepsen.edge && lein run test
```

## License

Copyright © 2017 Jepsen, LLC

Distributed under the Apache Public License 2.0.
