# Club Penguin Continued Gateway Server
### A Club Penguin Continued Web Socket Server

### Description
This is a Web Server front-end for Web Socket gateway connections for Club Penguin Continued clients to connect to the internal server emulator.

### Installation Prerequisites
For high-performance deployments it is recommend using **Debian Linux**. Other Linux based Operating Systems should work fine as well.

Required Packages:
- nginx (1.10.3+)

### Setup
1. Download or clone the project.
2. Run `git checkout master` and ensure you are using the `master` branch, which is for stable builds.
3. Copy `nginx.vhost` to `/etc/nginx/sites-enabled/gateway.cpcontinued.local`.
