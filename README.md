# imgur-downloader
Imgur downloader with aria2 support

I just edited the [imgur-album-downloader](https://github.com/alexgisby/imgur-album-downloader) script to use `aria2` if available
on the system using the [pyaria2](https://github.com/kevinxhuang/pyaria2) wrapper script.


## Command Line Usage

`python imguralbum.py [album URL] [path of the folder to save to]`

If you leave out the path to the folder it saves the files in a directory with the last part of the url.

For example - 
`python imguralbum.py http://imgur.com/a/uOOju`
This will download to a directory `u00ju` inside the current directory.

`python imguralbum.py http://imgur.com/a/uOOju /home/pi/Pictures`
This will download to the `Pictures` directory in the home directory of user `pi`.

## Python Support
Currently only supports **Python 3**

## Credits

The two original projects are
 - [https://github.com/alexgisby/imgur-album-downloader](https://github.com/alexgisby/imgur-album-downloader)
 - [https://github.com/kevinxhuang/pyaria2](https://github.com/kevinxhuang/pyaria2)

## License

imgur-downloader is licensed under the terms of the MIT License (see the file LICENSE).