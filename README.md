# media-sorter
Modification of Nikomiko's gist to add support for HEIC

Put this script in a messy folder filled with images and video files
and run it to create a "Photos" folder with the media files sorted by months in each year.
You can also change what types of files to look for in your folder
by simply adding to or changing the following lists: `imgFormats` and `videoFormats`.
NOTE: This script can also delete duplicates (by searcing for " 2" at the end of file names) and files starting with "._".
This is disabled by default, to enable set `DELETE` flag to True
