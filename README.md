# Forum

Forum is simaple BBS site based on [NodeBB](https://github.com/NodeBB/NodeBB).

# Usage

To get started with running NodeBB using Docker:

```
docker-composer up -d
```

The default port of nodebb is 4567. Also open below link to press enter the administrator username, e-mail and password.

```
http://127.0.0.1:4567
```

NodeBB will launch the setup and automatically close. Next, simply start the instance again.

```
docker start forum-nodebb
```

Your NodeBB instance will be accessible on the port you selected during setup. Check docker ps for more details.

# License

Copyright © 2016 Baafan Released under the MIT license.
