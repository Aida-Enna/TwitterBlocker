# TwitterBlocker
Block (or mute) everyone who retweeted a particular tweet, everyone who follows a certain account, or everyone on a Twitter list.

Script originally created by the owner of [Outside the Asylum](https://outsidetheasylum.blog/twitter-blocker/).

I've simply uncompressed (unminified) it and added some comments. I may add some more features. If it breaks, I'll attempt to fix it, though my JS skills are not as good as other languages.

## How to use
(Please note that you will need to use a web browser for this, not the Twitter app)

1) First, copy [the entire script](https://raw.githubusercontent.com/Aida-Enna/TwitterBlocker/refs/heads/main/Block.js) to your clipboard (Click the link and then select all of it -> copy. You can do this easily with Ctrl + A and then Ctrl + C)
2) Go to Twitter and pull up the list of people who retweeted the tweet or who follow the account in question. Followers can be found by clicking on "followers" on that person's profile. For retweets, open the post engagements by clicking the three dots in the top right corner and "view post engagements", then click over to the "reposts" tab.
3) Go to the URL bar (where you type in stuff like www.google.com) and type "javacript:", paste the text from your clipboard, and press enter.

It takes 0.5-2 seconds per account (depends on your internet speed), so it may take a few minutes if there are a lot of accounts.

Unfortunately, Twitter is designed in a weird way that makes the script stop working if you leave the tab, so you'll need to stay there while it runs. (You can, however, go to a different window on a desktop computer and it will continue running in the background window.)

Twitter also sometimes limits the number of retweets that are shown - there's nothing I can do about that unfortunately, so it may not block every retweeter if it was a very popular tweet.

## Troubleshooting
This script is a bit finicky, so it sometimes doesn't work. If you're having trouble with it, please try the following:

- If it doesn't do anything at all, that's probably because your browser has disabled Javascipt from the URL bar. Instead, open the Javascript console and paste it there. This can generally be accessed by right-clicking anywhere on the page and selecting "Inspect" or "Inspect Element", then selecting "Console" on the sidebar that shows. Or just Google "open Javascript console in (my browser)" to find specific instructions.
- Run the script in a different browser or on a different device.
- If your language on Twitter is set to a language other than English, try changing it to English temporarily to run the script.

If none of these steps resolve the problem, it's probably because Twitter changed their interface again and broke the script. If his has happened, please [create an issue](https://github.com/Aida-Enna/TwitterBlocker/issues) and I'll try to fix it.

## More information about the script
(written by the original creator, [IsaacKing314](https://x.com/IsaacKing314))

With the changes to Twitter's API, all the old tools to let you block/mute everyone on a list of people have broken. I've written a script to partially re-create the functionality.

Likes are private now, so the only things this script can do are to block or mute everyone who retweeted a partcular tweet, everyone who follows a certain account1, or everyone on a Twitter list.

## Note
It's worth remembering that not everyone who follows an account agrees with them - but you can make your own decisions.
