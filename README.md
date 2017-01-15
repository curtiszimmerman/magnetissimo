# Magnetissimo [![StackShare](http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](http://stackshare.io/sergiotapia/magnetissimo)

Web application that indexes all popular torrent sites, and saves it to the local database.

![alt tag](http://i.imgur.com/meqeZrc.png)

# Heads up: REWRITE IN PROGRESS!

See here for more details: https://www.reddit.com/r/magnetissimo/comments/5km57y/im_rewriting_magnetissimo_so_it_no_longer_has/

Goals:

* Crawl multiple index sites for torrents and magnet links.
* Run without ceremony. No pointless configuration needed.
* High performance, leveraging Elixir's GenServer and Erlang's BEAM VM.
* Unit tested for correctness.

# Community

Want to talk about Magnetissimo or suggest features? We have an official subreddit!

[http://reddit.com/r/magnetissimo](http://reddit.com/r/magnetissimo)

# Parser List

Magnetissimo currently fetches torrents from the following sites:

- [x] EZTV (thanks to @agustif)
- [x] Demonoid
- [x] Isohunt
- [x] LimeTorrents
- [x] ThePirateBay
- [x] TorrentDownloads
- [x] 1337x
- [ ] https://torrentproject.se
- [ ] https://rarbg.to/torrents.php
- [ ] https://www.torlock.com/
- [ ] http://www.seedpeer.eu/
- [ ] http://sectorrent.com/
- [ ] http://www.torrenthound.com/
- [ ] http://piratepublic.com
- [ ] bitsnoop.com
- [ ] extratorrent.cc
- [ ] linuxtracker.org
- [ ] monova.org
- [ ] newtorrents.info
- [ ] torrentbit.net
- [ ] torrentfunk.com
- [ ] torrentreactor.com
- [ ] torrents.net
- [ ] yourbittorrent.com

# Usage Guide

Please check the Wiki pages for instructions on how to run Magnetissimo.

* [Running it locally](https://github.com/sergiotapia/magnetissimo/wiki/Usage:-Local)
* [Running it on Heroku](https://github.com/sergiotapia/magnetissimo/wiki/Usage:-Heroku)
* Running it on a VPS (to-do)
