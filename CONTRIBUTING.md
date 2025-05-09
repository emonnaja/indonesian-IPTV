# Contributing Guide

## How to Add or Update Stream Link or Channel to a Playlist?

1. Fork this repository to Your GitHub account.
2. You can change the broadcast data or add new channels in the repository that you have forked.
3. Before make a pull request for merge, please do the following:

   - Make sure the URL you add works stably. You can check with [VLC Player](https://www.videolan.org/vlc/index.html) or [BitMovin Player](https://bitmovin.com/demos/stream-test) and watch the stream at least 3 minutes (some test streams are interrupted after 15-30 seconds or 1 minute above).
   - Make sure the channel is not blocklisted. You can check in [iptv-org.github.io](https://iptv-org.github.io/).
   - For security, make sure the URL you enter does not retrieve sensitive device or network information such as the Public IP address.
   - Make sure the URL you provide is not shortened (for example using [s.id](https://home.s.id/en) or another URL shortener).
   - Please do NOT change or alter the channel URL that is still active.

4. If everything feels safe, you can create a pull request by explaining what you changed.
5. Once the pull reuest has been accepted and merged, your changes will be available on our Content Delivery Network within 48 hours and accessible to everyone.


## How to Add New Country?

If you already have a playlist for your area (such as Malaysia, Singapore, etc.) you can follow the following steps:

1. Fork this repository to Your GitHub account.
2. Create a new file with .m3u extension in the Playlists folder with your country name (e.g. malaysia.m3u),
3. Check whether all the channels in your playlist are active or not.
4. Create a pull request by explaining what you changed.
5. Once the pull reuest has been accepted and merged, your changes will be available on our Content Delivery Network within 48 hours and accessible to everyone.