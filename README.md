# Podcast RSS Editor

Came across [JJYing's](https://github.com/JJYing) project for RSS Editor, decided to make some tweaks to enable users to make changes to the feed as a session object. This allows the site to be publically accessible without having to deal with saving files. 

![](https://raw.githubusercontent.com/rangedsp/Podcast-RSS-Editor/master/assets/screenshot.jpg)

# 01. Changes to project

- Removed dashboard as it was not needed for my use
- A download button to get the output of the changes in a new xml file

# 02. Usage

- Upload the xml feed to the '**Settings**' panel, you can see the content in the preview box if the upload is successful.
- There isn't any authentication or security check, but with the change, now user brings their own data, but I wouldn't recommend using it as part of your core product.

# 03. Change Log

- [August 15, 2020] Allow user to upload their own xml instead of providing it at build time.
- [Feb 3, 2019] Updated the layout compatibility.
- [Jul 27, 2017] Added ‘**Preview**’ function for episode link, image file and audio file.
- [Dec 13, 2016] Added ‘**duplicate**’ and ‘**delete**’ functions.
- [Jul 20, 2016] Added multi-language support: Simplified Chinese, Traditional Chinese, English.

# 04. Alternatives

- [Itunes podcast XML generator](http://codepen.io/jon-walstedt/pen/jsIup) by Jon Wålstedt
- [Podcast Generator](http://www.podcastgenerator.net/)
- Any Podcast hosting services.

# 05. Credits

- Some icons used are from the set [Squid Ink Line Icons](http://thesquid.ink/line-icons/)
