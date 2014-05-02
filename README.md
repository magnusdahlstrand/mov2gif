# mov2gif

A simple command line tool to convert video files to gifs. I created this tool so that I easily can make gifs out of Quicktime screen recordings of bugs.


#### Requirements

[ffmpeg](http://www.ffmpeg.org/) and [imagemagick](http://www.imagemagick.org/) are needed. I prefer to install them with [homebrew](http://brew.sh/):

`brew install imagemagick ffmpeg`


#### Installation

Put the `mov2gif` file in a folder that is in your path, and make sure it's executable (`chmod +x mov2gif`).


#### Usage

`mov2gif input.mov [output.gif]`

The output filename will be created based on the input filename if not sent in.


#### License

This software is licenced under the [MIT license](LICENSE).