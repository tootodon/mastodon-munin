# mastodon-munin
## A few munin plugins for Mastodon:

* Local and total accounts
* Local and total toots

## Configuration:

Default database: *mastodon_production*

Default path for media: */home/mastodon/live/public/system*

## Installation:
(dont do that in /root)
```bash
git clone https://github.com/tootodon/mastodon-munin.git
cd mastodon-munin/
ln -s $PWD/plugins/mastodon_* /etc/munin/plugins/
ln -s $PWD/plugins-conf.d/mastodon /etc/munin/plugin-conf.d/
service munin-node restart
```
## Example
http://munin.tootodon.xyz/mastodon-day.html
