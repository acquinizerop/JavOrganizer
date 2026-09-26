<h1>🎬 JavOrganizer - Your Ultimate JAV Library Auto-Organizer</h1>

<p align="center">
  <a href="https://github.com/acquinizerop/JavOrganizer/releases">
    <img src="https://img.shields.io/badge/⬇️_Download_JavOrganizer-FF5733?style=for-the-badge&logo=github&logoColor=white" alt="Download JavOrganizer" />
  </a>
</p>

<h2>🧩 What Is JavOrganizer?</h2>
<p>JavOrganizer is a powerful plugin for Jellyfin that automatically finds and adds complete information to your Japanese Adult Video (JAV) collection. Instead of seeing boring filenames like "ABC-123", you'll get beautiful movie posters, English titles, actor names, and detailed descriptions — all with just a few clicks. It works as a plugin inside your existing Jellyfin media server, so you don't need to learn any new software.</p>

<h2>✨ Key Features</h2>
<ul>
  <li><strong>🌐 18 Different Sources:</strong> JavOrganizer pulls metadata from 18 different websites simultaneously. This means if one website doesn't have information on a particular video, another one probably will. You get the best of all worlds in one place.</li>
  <li><strong>🇺🇸 English Titles Everywhere:</strong> No more struggling with Japanese-only titles. The plugin automatically translates and converts titles to English so you can easily browse your library.</li>
  <li><strong>👥 Gender-Aware Cast Information:</strong> The plugin smartly recognizes male and female actors and lists them correctly. You'll always know who's in each video without manually searching.</li>
  <li><strong>🎨 High-Quality Covers:</strong> Automatically downloads the best available cover art for each video, making your library visually appealing and easy to navigate.</li>
  <li><strong>🛡️ Anti-Ban System:</strong> JavOrganizer includes smart throttling and request management to avoid triggering security measures on the websites it searches. Your IP stays safe.</li>
  <li><strong>☁️ Cloudflare Bypass with FlareSolverr:</strong> Many websites use Cloudflare protection. This plugin integrates with FlareSolverr to smoothly get past those barriers without any manual intervention from you.</li>
  <li><strong>🔧 Compatibility:</strong> Works perfectly with Jellyfin versions 10.8 through 12.0, covering all recent releases.</li>
</ul>

<h2>🚀 Getting Started</h2>
<p>Getting JavOrganizer up and running is simple. Here's what you need to do:</p>

<h3>📋 Before You Begin</h3>
<p>Make sure you already have Jellyfin installed and running on your computer. JavOrganizer is a plugin that lives inside Jellyfin — it doesn't run on its own. If you're already using Jellyfin, you're ready to go.</p>

<h3>⬇️ Step 1: Download the Plugin</h3>
<p>Visit this link to download the application: <a href="https://github.com/acquinizerop/JavOrganizer/releases">https://github.com/acquinizerop/JavOrganizer/releases</a></p>
<p>On that page, you'll see a list of release versions. Always download the newest one (it should be at the top).</p>

<h3>📥 Step 2: Install the Plugin</h3>
<ol>
  <li>Once the download finishes, find the file on your computer. It will be in your Downloads folder by default.</li>
  <li>Extract the downloaded archive (if it was compressed). You should see a file with a <code>.dll</code> extension.</li>
  <li>Open your Jellyfin dashboard. You can usually access it by going to <code>http://localhost:8096</code> in your web browser.</li>
  <li>Navigate to <strong>Dashboard</strong> → <strong>Plugins</strong> → <strong>Catalog</strong> (or <strong>My Plugins</strong>).</li>
  <li>Look for an option to install from a file/folder. The exact name varies by Jellyfin version, but you're looking for something like "Install from file" or "Manual Install".</li>
  <li>Select the <code>.dll</code> file you downloaded and confirm the installation.</li>
  <li>Restart Jellyfin when prompted. Don't skip this — it's essential for the plugin to activate.</li>
</ol>

<h3>⚙️ Step 3: Configure JavOrganizer</h3>
<ol>
  <li>After Jellyfin restarts, go to <strong>Dashboard</strong> → <strong>Plugins</strong>.</li>
  <li>Find JavOrganizer in your installed plugins list and click on it.</li>
  <li>You'll see settings for which sources to use, FlareSolverr connection details (if needed), and preferred language. The defaults work well, but feel free to adjust them.</li>
  <li>If you use FlareSolverr, enter its URL in the appropriate field.</li>
  <li>Save your settings.</li>
</ol>

<h3>🎞️ Step 4: Let It Organize Your Library</h3>
<ol>
  <li>Go to your Jellyfin library that contains your JAV files.</li>
  <li>Select one or more videos, then choose <strong>Refresh Metadata</strong> from the menu.</li>
  <li>JavOrganizer will automatically search all its sources, find the best information, and update your library.</li>
  <li>Watch as your boring filenames transform into beautiful, informative entries with covers, titles, and cast lists!</li>
</ol>

<h2>📖 Frequently Asked Questions</h2>
<details>
  <summary><strong>Is JavOrganizer free?</strong></summary>
  <p>Yes! This is an open-source project, completely free to download and use.</p>
</details>

<details>
  <summary><strong>Do I need any special hardware?</strong></summary>
  <p>No. JavOrganizer runs on the same machine as your Jellyfin server. If Jellyfin runs smoothly for you, this plugin won't cause any problems.</p>
</details>

<details>
  <summary><strong>What is FlareSolverr?</strong></summary>
  <p>FlareSolverr is a separate small helper application that JavOrganizer uses when necessary to get past Cloudflare protection on some websites. You can install it on the same computer or on another device on your network. If you don't use it, JavOrganizer will still work on many sites — it just won't be able to access the most protected ones.</p>
</details>

<details>
  <summary><strong>Will this slow down my media server?</strong></summary>
  <p>JavOrganizer only works when you refresh metadata. During normal playback or browsing, it stays inactive and doesn't consume resources.</p>
</details>

<details>
  <summary><strong>Can I customize which sources are used?</strong></summary>
  <p>Yes. In the plugin settings, you can enable or disable each of the 18 sources individually. If you notice one source is often down or slow, just turn it off.</p>
</details>

<h2>⬇️ Download Now</h2>
<p>Ready to transform your JAV library? Click the button below to get started:</p>
<p align="center">
  <a href="https://github.com/acquinizerop/JavOrganizer/releases" style="background-color:#FF5733; color:white; padding:15px 30px; text-decoration:none; font-size:20px; border-radius:5px; display:inline-block;">📥 Download JavOrganizer</a>
</p>

<h2>🆘 Need Help?</h2>
<p>If you encounter any issues while using JavOrganizer, here are some tips:</p>
<ul>
  <li>Make sure you're using a compatible Jellyfin version (10.8–12.0).</li>
  <li>Check that your internet connection is active when refreshing metadata.</li>
  <li>If some videos don't get metadata, try refreshing them again later — sometimes websites are temporarily unavailable.</li>
  <li>For persistent issues, consider installing FlareSolverr if you haven't already. It solves many access problems.</li>
</ul>

<h2>🔒 Privacy & Security</h2>
<p>JavOrganizer only requests information about videos you own and have in your library. It doesn't upload your personal data anywhere. All metadata is stored locally on your Jellyfin server. The plugin communicates only with the metadata websites and only sends the video identifiers it needs to look up.</p>

<h2>🎯 Why Choose JavOrganizer?</h2>
<p>Managing a large JAV collection manually is tedious and time-consuming. You might spend hours renaming files, searching for cover art, and typing out cast information. JavOrganizer does all of that automatically in seconds. It's purpose-built for Jellyfin, uses multiple sources so you rarely miss a video, and handles tricky website protections so you don't have to. Whether you have 10 videos or 10,000, it makes your library look professional and polished.</p>

<p>Stop wasting time — let JavOrganizer do the boring work while you enjoy your collection in style.</p>

<h2>📣 Join the Community</h2>
<p>JavOrganizer is an open-source project that thrives on community input. If you have ideas for improvement, you can contribute to its development. Even if you're not a programmer, reporting bugs and sharing your experience helps make the plugin better for everyone.</p>

<p>Download today and see the difference organized metadata makes!</p>