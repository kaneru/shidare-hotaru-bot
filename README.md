#Shidare-Hotaru-Bot
##or insert_your_waifu_name_twitter_bot

A small script that takes a folder as an input and twitts a random image in that folder every time you execute the script. If you combine it with cron or other task scheduler, it efectively becomes a very simple twitter image bot.

Twitter image bot that posts in my case Shidare Hotaru pictures and gifs (optionally - could be videos, too).

<img src="https://pbs.twimg.com/media/CaiN2-PUAAAsoex.jpg" alt="Shidare Hotaru" width="200">

#Links

* [original bot(see early commits) by joaquinlpereyra](https://github.com/joaquinlpereyra/twitterImgBot)
* [~~my fork for @6aka6aka_bot~~](https://github.com/johnnykernel/twitterImgBot)
* [ShidareHotaruBot itself](https://twitter.com/ShidareBot)
* [my personal twitter](https://twitter.com/6aka6aka)

#Setting it up

You'll need tweepy. If you don't have it, run:

``` pip install tweepy ```

You'll also need to modify the config file to specify your twitter authentication keys. Then modify the script to specify the source folder for your images.

#Usage

Execute it. That's it.
You probably want to set it up on your crontab (or your favorite task scheduler) too :)

This is how my crontab schedule looks like:

```ksh
0 */8 * * * python /Users/johnny/some_bots/ShidareHotaruBott/image_bot.py
```
The bot posts a picture every eight hours.
