olc-tools
=========

A repository with various tools to work with Open Location Codes (also known as Plus-codes). Read more at <https://plus.codes>.

## OSM Bookmarklet

Copy the contents of bookmarklet.txt to a bookmark in your browser to enable searching for OLC on Open Streetmaps. The provided files are a smaller version of the official JS API from Google, a little bit of JS to perform the actual search and a minified version, together with a short shell script to recreate these files. For recreating these files you need to have hjsmin installed. The bookmarklet-convert.txt reads a Plus-code from the current link and searches it on OSM. The purpose of this part of the repository is to provide tools to work with OSM as much as possible instead of relying on proprietary tools to use the free OLC standard for easy navigation, as efforts to integrate OLC support officially (https://github.com/openstreetmap/openstreetmap-website/issues/1807) don't seem to go anywhere because the standard is misunderstood as a commercial fancy.

## WhenWhere

A simple PWA that runs over IPFS and can be installed for completely offline navigation using OLC. Try it out at [whenwhere.cf](https://whenwhere.cf)

## OLC Proximity [in progress, unfinished]

Javascript code to calculate a series of plus codes that can be used to tag and/or search posts that use OLC for location tagging. This combines the idea of going from more to less precise and to calculate a configurable border around this list of codes, from more specific to less specific and stopping when the desired amount of post has been reached, thus providing an easy way to sort posts on proximity and relevancy to a given location while adding the option to be more or less precise in the first place.
