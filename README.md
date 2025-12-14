# limnoria-youtube
A Limnoria Plugin for fetching metadata for Youtube Links

Compatible with the YouTube Data API V3. See 
https://developers.google.com/youtube/v3/docs/

## Setup

You **MUST** provide an API key for use with this plugin, as these are required 
by current versions of the YouTube Data API. A free API key will allow for 
10,000 unique queries per day, which should be enough for most people. For 
information about obtaining an API key, see 
https://developers.google.com/youtube/registering_an_application

This plugin will only access public information, so you only need an API key. 
You don't need to worry about OAuth credentials.

Save your API key in `supybot.plugins.youtube.youtubeDataApiKey` Limnoria config
value. By default it's empty.

## Special thanks

Limnoria-Youtube is based on the Plugin at 
https://github.com/skgsergio/Limnoria-plugins/tree/master/Youtube
