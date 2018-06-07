# SFDC MobileSDK React Native iOS Lightning Community Wrapper
The documentation say it's not possible to put a Lightning-based community in a wrapper, but it is --

For iOS, one easy step: set `info.plist` key `SFDCOAuthLoginHost` to the Lightning community base url. Include `/s` in the URL path.

Why would you want to do this? Simple: because it allows the majority of development to be handled inside the community. This effectively allows you to build once for multiple platforms, thus further extending the viability of a React Native-based approach.