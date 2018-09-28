# Mastodon-Notes
Notes and things related to installing Mastodon at https://choochoo.space

## Set-Up Guide
* [Running a Mastodon instance on Ubuntu 16.04 with Docker & nginx](https://github.com/ummjackson/mastodon-guide/blob/master/up-and-running.md)
   * [(used the instructions re: letsencrypt here](https://www.makeuseof.com/tag/social-network-set-mastodon-instance-linux/)

## Noteable Issues
* [Issue related to rebooting and wiping database by accident](https://github.com/tootsuite/mastodon/issues/1376)

## Running Mastodon
* [Docker Guide](https://github.com/tootsuite/documentation/blob/master/Running-Mastodon/Docker-Guide.md)

## Useful Commands

```shell
# For logs
docker logs mastodon_sidekiq_1

# For opening Ruby shell
docker-compose run --rm web rails c
```
