# CEF Source Pack
----

## About this Pack

This CEF Source Pack maps CEF fields from events in the Common Event Format into a Common and CEF schema.  To see the effects of the pack one needs to show internal fields and look for __schema and __cef.  It is intended to be used in conjuction with destination packs supporting schemas.

## Deployment

1. Install this pack
2. Apply the Pack to the Source where CEF logs are coming in.  Navigate to the Source, select Processing Settings > Pre-Processing and select the Pack as the pipeline.  

This pack has been tested against Common Event Format (CEF) events received by Cribl Stream via a Syslog source.

## Release Notes

### Version 1.0.0 - 2024-01-26

Initial Release Supporting Common Event Format logs.


## Contributing to the Pack

To contribute to the Pack, please connect with Dan Schmitz on [Cribl Community Slack](https://cribl-community.slack.com/). You can suggest new features or offer to collaborate.

## Contact

The author of this pack is Dan Schmitz and can be contacted at <dschmitz@cribl.io>.


## License

This Pack uses the following license: [`Apache 2.0`](https://github.com/criblio/appscope/blob/master/LICENSE).