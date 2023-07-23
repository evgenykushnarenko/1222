<h1 align="center">
  <br>
  <a href="https://webtorrent.io"><img src="https://webtorrent.io/img/WebTorrent.png" alt="WebTorrent" width="200"></a>
  <br>
  WebTorrent
  <br>
  <br>
</h1>

<h4 align="center">The streaming torrent client. For node.js and the web.</h4>

<p align="center">
  <a href="https://discord.gg/cnXkm4Z"><img src="https://img.shields.io/discord/612575111718895616" alt="discord"></a>
  <a href="https://github.com/webtorrent/webtorrent/actions"><img src="https://img.shields.io/github/actions/workflow/status/webtorrent/webtorrent/ci.yml?branch=master" alt="ci"></a>
  <a href="https://www.npmjs.com/package/webtorrent"><img src="https://img.shields.io/npm/v/webtorrent.svg" alt="npm version"></a>
  <a href="https://www.npmjs.com/package/webtorrent"><img src="https://img.shields.io/npm/dm/webtorrent.svg" alt="npm downloads"></a>
  <a href="https://standardjs.com"><img src="https://img.shields.io/badge/code_style-standard-brightgreen.svg" alt="Standard - JavaScript Style Guide"></a>
</p>

<h5 align="center">
  Sponsored by&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://socket.dev"><img src="https://webtorrent.io/img/supporters/socket.png" alt="Socket - JavaScript open source supply chain security" height=35 valign="middle"></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://www.wormhole.app/?utm_medium=sponsorship&utm_source=webtorrent&utm_campaign=feross"><img src="https://webtorrent.io/img/supporters/wormhole.png" alt="Wormhole" height=30 valign="middle"></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://webtorrent.io/expressvpn" rel="nofollow"><img src="https://webtorrent.io/img/supporters/expressvpn.png" alt="ExpressVPN" height=30 valign="middle"></a>
</h5>
<br>

**WebTorrent** is a streaming torrent client for **node.js** and the **browser**. YEP,
THAT'S RIGHT. THE BROWSER. It's written completely in JavaScript – the language of the web
– so the same code works in both runtimes.

In node.js, this module is a simple torrent client, using TCP and UDP to talk to
other torrent clients.

In the browser, WebTorrent uses **WebRTC** (data channels) for peer-to-peer transport.
It can be used **without** browser plugins, extensions, or installations. It's Just
JavaScript&trade;. Note: WebTorrent does **not** support UDP/TCP peers in browser.

Simply include the
[`webtorrent.min.js`](https://cdn.jsdelivr.net/npm/webtorrent@latest/webtorrent.min.js) script
on your page to start fetching files over WebRTC using the BitTorrent protocol, or
`import WebTorrent from 'webtorrent'` with [browserify](http://browserify.org/) or [webpack](https://webpack.js.org/). See [demo apps
](#who-is-using-webtorrent-today) and [code examples](#usage) below.
