# Prime releases

Builds of Prime for Apple silicon Macs. Prime updates itself from this repository: it reads
`latest.json`, downloads the parts listed there, checks each part's SHA-256, joins them into
`Prime-for-Mac.zip` and installs it when Prime restarts.

To install by hand, download the parts of the newest version in `versions/` and join them:

    cat Prime-for-Mac.zip.part* > Prime-for-Mac.zip
