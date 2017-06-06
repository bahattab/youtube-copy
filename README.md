This is a quick hack that uses the Youtube Data API to create playlists and 
subscriptions from [Google Takeout for Youtube](https://www.google.com/settings/takeout).
The oAuth stuff and parts of calling the API is straight from Youtube's tutorial
and code samples for using their APIs.

I wrote this to transfer my playlists and subscription from one Google account 
to another.

## Prequisite

To use this, you must first 
[enable the Youtube Data API for your Google account](https://developers.google.com/youtube/v3/quickstart/go#step_1_turn_on_the_api_name)
including downloading the credential file for oAuth.  Save the credential file 
as `cs.json`.

Using Google Takeout, download your playlist and subscriptions in JSON format.

## Installing

`go get -insecure lazyhackergo.com/youtube-copy`

** Until I get https on lazyhackergo.com, please use the -insecure flag **

## Disclaimer

I wrote this specifically for my need to copy some data over so there's no
support.  Use it at your own risk, but feel free to look at the code.
