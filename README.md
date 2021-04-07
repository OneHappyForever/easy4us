easy4us
=======

easytoyou.eu are a brilliant service that allows unlimited ionCube decoding for a very reasonable monthly fee. it has no
way to upload a directory, so to decode a large webapp is a slow, manual process.

this script should take care of this process for you. the usage should be clear enough.

** there is a profound lack of error checking that will likely mean very large jobs might lose the session halfway though
and require a second run. by default it will skip files present in the destination dir **

````
usage: easy2us

decode directories using easytoyou.eu

optional arguments:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        easytoyou.eu username
  -p PASSWORD, --password PASSWORD
                        easytoyou.eu password
  -s SOURCE, --source SOURCE
                        source directory
  -d DECODER, --decoder DECODER
                        decoder
  -w, --overwrite       overwrite
  -o DESTINATION, --destination DESTINATION
                        destination directory
```