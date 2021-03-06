olc-tools
=========

A repository with various tools to work with Open Location Codes (also known as Plus-codes). Read more at <https://plus.codes>.

## OSM Bookmarklet

Copy the contents of bookmarklet.txt to a bookmark in your browser to enable searching for OLC on OpenStreetMap. The provided files are a smaller version of the official JS API from Google, a little bit of JS to perform the actual search and a minified version, together with a short shell script to recreate these files. For recreating these files you need to have hjsmin installed. The bookmarklet-convert.txt reads a Plus-code from the current link and searches it on OSM. The purpose of this part of the repository is to provide tools to work with OSM as much as possible instead of relying on proprietary tools to use the free OLC standard for easy navigation, as efforts to integrate OLC support officially (https://github.com/openstreetmap/openstreetmap-website/issues/1807) don't seem to go anywhere because the standard is misunderstood as a commercial fancy.

## WhenWhere

A simple PWA that runs over IPFS and can be installed for completely offline navigation using OLC. Try it out at [whenwhere.cf](https://whenwhere.cf)

## OLN

OLN is short for Open Location Network or Open Listening Network. It's a project to create a worldwide community overlay using OLC as a tagging and indexing tool together with hashtags to give people access to information that is relevant to them.
