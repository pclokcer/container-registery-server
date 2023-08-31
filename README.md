# Container Registery Server

First Create Password For Login

```sh
docker run --rm --entrypoint htpasswd httpd:2 -Bbn pclokcer test > auth/htpasswd
```

[For Certs](https://letsencrypt.org/docs/certificates-for-localhost/#making-and-trusting-your-own-certificates)
