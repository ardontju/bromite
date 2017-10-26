# 63.0.3239.15
* remove URL tracking from Google search results
* disable webRTC by default

# 63.0.3239.10
* attempt enabling API keys (didn't work)
* added StartPage search engine (closes https://github.com/bromite/bromite/issues/3)

# 63.0.3239.6
* added Bromite patch for Google search results click-tracking removal
* added x86 target CPU
* fixed red blink frame

# 63.0.3235.2
* first release with NoChromo adblocking patch
* Bromite patch: disable NTP remote suggestions
* added some Inox/Iridium/Ungoogled-Chromium patches, namely:
** DuckDuckGo search engine
** disable battery status service
** disable formatting in OmniBox
** disable GCM status checks
** use local fonts instead of fonts from Google servers
** disable updater pings
** do not enable Google integrations by default (translation, lookup, etc)
** disable the ad promo system
** do not store passwords by default
** do not fetch Google promotions
** restore classic NTP
** only keep cookies until exit
** block third-party cookies