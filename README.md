# Needs some love and attention ( August 31, 2026) #
## Please check back later...##
### What you will find here then:
* A single instance of a dockerized Traefik public facing DNS-based IP/TCP traffic director, ensuring that domains being hosted in the Traefik network will be:
  - Entire Docker-compose based single stacks, amounting to a full webserver+code, and whatever other services, such as loggers and databases needed in your specific online server stack.
  - Easily extendable - Including more domains hosted within the Traefik network.
  - Easily swappable - Replacing existing
  - Isolated and easily bootable/torn-down - Can be added, started, stopped, and removed, without any need to restart the Traefik server itself - this means that if one server-stack, reachable by Traefik - is booted, stopped, added, or removed - Traefik needs not to be rebooted.
  - Automatic SSL Certs
* Examples of Nginx/PHP/MariaDB/PostgreSQL docker containers being made available to online public access, as fully formed web-application stacks
  - Hardened for production, in terms of accommodating the security flaws in Docker Containers and host-breakout exploits.
  - Hardened for production, in terms of directive for Nginx and PHP - sensible default Nginx HTTP 400+500 settings, and performant and hardened php directive via php.ini and extended files being loaded.
