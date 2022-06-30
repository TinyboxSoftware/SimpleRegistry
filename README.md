# SimpleRegistry
a simple setup for a docker registry that includes a web-based browser and authentication.

## Todos
- [ ] Template Setup
  - [ ] Configure SSL ([self signed is fine](https://www.techrepublic.com/article/how-to-deploy-self-hosted-docker-registry-self-signed-certificates/), it will go through NGINX + a separate cert) 
  - [ ] Configure authentication (registry auth should pass through to browser)
  - [ ] Investigate [docker_auth](https://github.com/cesanta/docker_auth) for better authentication
- [ ] Documentation Setup
  - [ ] project inspiration & goals
  - [ ] SSL generation guide: if using self-signed, PLEASE make sure you have a more secure cert on top.
  - [ ] Auth management guide
  - [ ] Image storage guide (S3/Google Drive/NFS/etc)

## Credits
- [Lazybox](https://github.com/cnorlander/Lazybox) by [Corey Norlander](https://github.com/cnorlander): used for self-signed SSL certificate generation.