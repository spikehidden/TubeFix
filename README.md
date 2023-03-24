# TubeFix
 A simple PHP script to fix PeerTube embeds for Discord & Co.
 
 ----------------------------
## What is the use in this?
 Discord and Twitter doesn't treat links to Videos to Peertube instances as such because Peertube doesn't show the correct meta and oembed Info that would be needed for that.\
 My Peertube Fixer fixes that problem and "repairs" the link so it does embed the actual video like you can see below.\

<details>
<summary>Screenshots</summary>
<details>
<summary>Without Fix</summary>

![Without Tubefix](/images/screenshot1.png)
        
</details>
<details>
<summary>With Fix</summary>

![With Tubefix](/images/fixed.png)

</details>
</details>

## How to use?
 Simply just add the URL you want to "fix".\
 For example if we want to embed "https://cliptube.org/w/d6ZiUHJRxpjoZKSeetjSXe" in discord correctly so it does play the actual video we just put it behind the hostname like I do with my own "tubefix.de". The result would be "https://tubefix.de/https://cliptube.org/w/d6ZiUHJRxpjoZKSeetjSXe" which will then be shown correctly as a video in Discord.

 It is already ready to got and doesn't need any configuration but you can do so in the config.php

## Why not Open Source?
 Why should I?\
 There is an open instance (tubefix.de) everyone can use without any charge.\
 But if I notice that there will be a high enough interest I might publish it under an Open Source License.