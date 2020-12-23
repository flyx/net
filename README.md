# Go Networking Fork

This is a fork of [Go Networking](https://github.com/golang/net).
It augments the HTML parser with `ParseOptionCustomElements`, an API to register non-standard element names with the parser.
This API can be used to parse HTML files augmented with non-standard elements, e.g. for embedding some kind of metalanguage.
It is mainly used by [askew](https://github.com/flyx/askew) to parse its component and site definitions.

All other code is not touched and should not be used.
It is merely kept around to facilitate updates from upstream.
