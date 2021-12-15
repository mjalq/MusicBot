<img align="right" src="https://i.imgur.com/zrE80HY.png" height="200" width="200">

# JMusicBot

[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://github.com/jagrosh/MusicBot/releases/latest)
[![Stars](https://img.shields.io/github/stars/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/stargazers)
[![Release](https://img.shields.io/github/release/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/releases/latest)
[![License](https://img.shields.io/github/license/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/blob/master/LICENSE)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://discord.gg/0p9LSGoRLu6Pet0k)<br>
[![CircleCI](https://img.shields.io/circleci/project/github/jagrosh/MusicBot/master.svg)](https://circleci.com/gh/jagrosh/MusicBot)
[![AppVeyor](https://ci.appveyor.com/api/projects/status/gdu6nyte5psj6xfk/branch/master?svg=true)](https://ci.appveyor.com/project/jagrosh/musicbot/branch/master)
[![CodeFactor](https://www.codefactor.io/repository/github/jagrosh/musicbot/badge)](https://www.codefactor.io/repository/github/jagrosh/musicbot)

A cross-platform Discord music bot with a clean interface, and that is easy to set up and run yourself!

[![Setup](http://i.imgur.com/VvXYp5j.png)](https://jmusicbot.com/setup)

## Features
  * Easy to run (just make sure Java is installed, and run!)
  * Fast loading of songs
  * No external keys needed (besides a Discord Bot token)
  * Smooth playback
  * Server-specific setup for the "DJ" role that can moderate the music
  * Clean and beautiful menus
  * Supports many sites, including Youtube, Soundcloud, and more
  * Supports many online radio/streams
  * Supports local files
  * Playlist support (both web/youtube, and local)

## Supported sources and formats
JMusicBot supports all sources and formats supported by [lavaplayer](https://github.com/sedmelluq/lavaplayer#supported-formats):
### Sources
  * YouTube
  * SoundCloud
  * Bandcamp
  * Vimeo
  * Twitch streams
  * Local files
  * HTTP URLs
### Formats
  * MP3
  * FLAC
  * WAV
  * Matroska/WebM (AAC, Opus or Vorbis codecs)
  * MP4/M4A (AAC codec)
  * OGG streams (Opus, Vorbis and FLAC codecs)
  * AAC streams
  * Stream playlists (M3U and PLS)

## Example
![Loading Example...](https://i.imgur.com/kVtTKvS.gif)

## Setup
Please see the [Setup Page](https://jmusicbot.com/setup) to run this bot yourself!

## Questions/Suggestions/Bug Reports
**Please read the [Issues List](https://github.com/jagrosh/MusicBot/issues) before suggesting a feature**. If you have a question, need troubleshooting help, or want to brainstorm a new feature, please start a [Discussion](https://github.com/jagrosh/MusicBot/discussions). If you'd like to suggest a feature or report a reproducible bug, please open an [Issue](https://github.com/jagrosh/MusicBot/issues) on this repository. If you like this bot, be sure to add a star to the libraries that make this possible: [**JDA**](https://github.com/DV8FromTheWorld/JDA) and [**lavaplayer**](https://github.com/sedmelluq/lavaplayer)!

## Editing
This bot (and the source code here) might not be easy to edit for inexperienced programmers. The main purpose of having the source public is to show the capabilities of the libraries, to allow others to understand how the bot works, and to allow those knowledgeable about java, JDA, and Discord bot development to contribute. There are many requirements and dependencies required to edit and compile it, and there will not be support provided for people looking to make changes on their own. Instead, consider making a feature request (see the above section). If you choose to make edits, please do so in accordance with the Apache 2.0 License.



<h1>Setup Guide</h1>
                
                <h2 id="1-install-java">1️⃣ Install Java<a class="headerlink" href="#1-install-java" title="Permanent link">#</a></h2>
<ul>
<li>Instructions on how to install Java on your system: <a href="../installing-java/">Installing Java</a></li>
</ul>
<h2 id="2-download-jmusicbot">2️⃣ Download JMusicBot<a class="headerlink" href="#2-download-jmusicbot" title="Permanent link">#</a></h2>
<ul>
<li>Download the latest <strong>JMusicBot-X.Y.Z.jar</strong> (and optionally, example <strong>config.txt</strong> file) from the <a href="https://github.com/jagrosh/MusicBot/releases/latest">releases</a> page (or, get the URL from the releases page and then use wget or similar command-line tool to download).</li>
<li>Your folder should look similar to this (on desktop):<br />
<img alt="View" src="/assets/images/folder-view.png" /></li>
</ul>
<div class="admonition note">
<p class="admonition-title">Note</p>
<p>The above image is Windows, but it should look similar on all platforms  </p>
</div>
<div class="admonition warning">
<p class="admonition-title">Warning</p>
<p>Do not put this in the <em>Downloads</em> or <em>Desktop</em>. Use a folder within <em>Documents</em></p>
</div>
<h2 id="3-edit-the-config-file">3️⃣ Edit the config file<a class="headerlink" href="#3-edit-the-config-file" title="Permanent link">#</a></h2>
<ul>
<li>Fill in the config file (if you downloaded it). If you didn't download it, you will be prompted when you run for the first time. An example <code>config.txt</code> is provided below (See <a href="../getting-a-bot-token/">Getting a Bot Token</a> and <a href="../finding-your-user-id/">Finding Your User ID</a> if you need help with the config).<br />
<div class="highlight"><pre><span></span><code>token = MJHJkljflksdjfCoolTokenDudeILikeItkasdk
owner = 113156185389092864
prefix = &quot;!&quot;
</code></pre></div></li>
</ul>
<div class="admonition example">
<p class="admonition-title">Example</p>
<p>You can also copy &amp; paste a template from the <a href="../config/">Example Config</a></p>
</div>
<h2 id="4-run-jmusicbot">4️⃣ Run JMusicBot<a class="headerlink" href="#4-run-jmusicbot" title="Permanent link">#</a></h2>
<ul>
<li>Run the jar file (choose one of these options):</li>
<li>Double-click the jar file (on desktop environments), OR</li>
<li>Run <code>java -Dnogui=true -jar JMusicBot-X.Y.Z.jar</code> from the command line (replace X, Y, and Z with the release numbers), OR</li>
<li>Run <code>nohup java -Dnogui=true -jar JMusicBot-X.Y.Z.jar &amp;</code> to run in the background (Linux only)</li>
<li>Provide the requested information, if prompted.</li>
<li>Wait for the "Finished Loading" message.</li>
</ul>
<h2 id="5-add-your-bot-to-your-server">5️⃣ Add your bot to your server<a class="headerlink" href="#5-add-your-bot-to-your-server" title="Permanent link">#</a></h2>
<ul>
<li>When the bot starts, if it hasn't been added to any servers yet, it will provide you with a link in the console.</li>
<li>Alternatively, follow these instructions (with images): <a href="../adding-your-bot/">Adding Your Bot To Your Server</a></li>
</ul>
