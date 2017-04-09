# mastodon-munin
A few munin plugins for Mastodon:

* Local and total accounts
* Local and total toots

Installation: (dont do that in /root)
```bash
git clone https://github.com/0xa/mastodon-munin.git
cd mastodon-munin/
ln -s $PWD/plugins/mastodon_{accounts,local_accounts,statuses,local_statuses} /etc/munin/plugins/
ln -s $PWD/plugins-conf.d/mastodon /etc/munin/plugin-conf.d/
service munin-node restart
```

There's also a plugin that count ⚧ in bios, but I'm not sure everyone wants it or I want everyone to use it,
so just add it if you want, or with another search. There are may fun things to do.
