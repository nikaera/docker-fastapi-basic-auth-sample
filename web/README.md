# Notes 📝

You need to `docker build` with the environment variables `$USER` and `$PASS` set in the environment variables. Otherwise, an error will occur when executing the `htpasswd` command in the [Dockerfile](https://github.com/nikaera/docker-fastapi-basic-auth-sample/blob/main/web/Dockerfile#L6).
