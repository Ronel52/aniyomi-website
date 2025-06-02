-<?xml version="1.0" encoding="utf-8"?>
<rss version="2.0" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:content="http://purl.org/rss/1.0/modules/content/">
    <channel>
        <title>Aniyomi</title>
        <link>http://localhost:4173</link>
        <description>Discover and watch anime, cartoons, series, and more â€“ easier than ever on your Android device.</description>
        <lastBuildDate>Tue, 06 May 2025 14:11:00 GMT</lastBuildDate>
        <docs>https://validator.w3.org/feed/docs/rss2.html</docs>
        <generator>https://github.com/jpmonette/feed</generator>
        <language>en</language>
        <image>
            <title>Aniyomi</title>
            <url>http://localhost:4173/img/logo.png</url>
            <link>http://localhost:4173</link>
        </image>
        <copyright>Copyright Â© 2025 Mihon App, Aniyomi App</copyright>
        <item>
            <title><![CDATA[Extensions list removed]]></title>
            <link>http://localhost:4173/news/2024-07-05-extensions-removal</link>
            <guid>http://localhost:4173/news/2024-07-05-extensions-removal</guid>
            <pubDate>Fri, 05 Jul 2024 00:00:00 GMT</pubDate>
            <description><![CDATA[Due to extenuating circumstances.]]></description>
            <content:encoded><![CDATA[<h1 id="extensions-list-removed" tabindex="-1">Extensions list removed <a class="header-anchor" href="#extensions-list-removed" aria-label="Permalink to &quot;Extensions list removed&quot;"></a></h1>
<p><strong>Dear Aniyomi Community,</strong></p>
<p>Due to extenuating circumstances, we have had to purge our list of extensions.</p>
<p>As of now, <strong>Aniyomi</strong> is transitioning to a fully bring-your-own-content model. What this means is that you can still enjoy <strong>Aniyomi</strong> for manga reading and anime watching, but you'll need to source and add your own content.</p>
<p>We strongly encourage all users to exercise caution, and avoid utilizing extensions from unknown repositories, as they may contain malware.</p>
<p>It's important to note that while existing extensions may continue to work, we cannot guarantee their functionality indefinitely.</p>
<p>Additionally, please be aware that neither our Discord server nor our GitHub repository's issues page will provide support for unofficial extensions.</p>
<p>Best regards,</p>
<!-- markdownlint-disable-next-line MD036 -->
<p><em>The Aniyomi Team</em></p>
]]></content:encoded>
        </item>
    </channel>
</rss>-
title: Getting started
titleTemplate: Guides
description: Essential information to help you get set up with Aniyomi.
---

<script setup lang="ts">
import { data as release } from "@theme/data/release.data"
</script>

# Getting started

Essential information to help you get set up with Aniyomi.

## Installation guide

### Downloading Aniyomi

1. Visit our [download](/download/) page to get the latest version of **Aniyomi**.
2. After the download is complete, open the `.apk` file.
3. Proceed with the installation process.

### Adding sources

Once **Aniyomi** is installed on your device, you can bring your own content to read from various sources:

:::: tabs
== Local source
Read or watch content stored locally on your device.

See the local source guides for instructions:
- [Manga](/docs/guides/local-manga-source/)
- [Anime](/docs/guides/local-anime-source/)

== External repositories
External repositories add additional sources to **Aniyomi**. You can add external repositories by going to <nav to="browse"> and tapping **Anime/Manga extension repos**.

Once there, you can add repositories by inputting URLs ending with `index.min.json`.

::: danger Caution
Aniyomi will not provide resources for any unofficial repositories. Beware that any third-party repositories or extensions will have full access to the app and may contain malware.
:::

Once you've added a repository, go to <nav to="extensions"> and refresh the extensions list.

You can now tap the download button next to extensions to install them.

> You may need to [enable third-party installations](/docs/faq/browse/extensions#enabling-third-party-installations).

== Manual extensions
Extensions can be manually installed through `.apk` files.

::: danger Caution
Aniyomi will not provide resources for any unofficial extensions. Beware that any third-party repositories or extensions will have full access to the app and may contain malware.
:::
::::

### Adding series to your library

After installing the desired extension, you'll find it in the **Manga/Anime Sources** tab.

Here's how you can add series to your library:

1. Select the source you'd like to browse.
2. You can use the **Popular**/**Latest** listings to browse, or you can search for the series name.
3. Once you've found the series that you want to add, tap on it for more details.
4. Press the "**Add to library**" button, and the series will be added to your Library, ready to be read/watched!

## Additional setup

### Series search options

If you want to search for series across all your sources, you can use the Global Search feature.

Follow these steps:

1. Go to the "**Browse**" section.
2. Ensure you're on the "**Sources**" tab located at the top-right corner.
3. Use the Search icon in the toolbar to find series from all available sources.

### Trouble finding a specific series?

If you encounter difficulties while searching for a specific series, consider the following points:

<!-- markdownlint-disable MD004 -->
* Double-check your spelling and try again, as some sources might use **Japanese romanized** titles instead of **English** ones.
  > Example: **Boku no Hero Academia** instead of **My Hero Academia**.

* Some sources may use different spellings or wordings for titles.
  > Example: **Bungo Stray Dogs** instead of **Bungou Stray Dogs**

  > Example: **3-gatsu no Lion** instead of **Sangatsu no Lion**.
<!-- markdownlint-enable MD004 -->
