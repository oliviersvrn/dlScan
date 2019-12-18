# dlScan

Warning : Not up-to-date and doesn't work at all (Website used to get image sources has completely changed)

Download your manga chapters with this tool.
Easy use with crontab, just indicate the `path` variable.

## Installation
Clone repository

    $ git clone https://github.com/savari-o/dlScan.git .

Copy dlScan to your binary folder

    $ sudo cp dlScan /usr/local/bin/

## Usage

    $ dlScan
    usage: dlScan [-c chapter] [-i] name [path]

### Example :

    $ dlScan op 868
    Downloading One Piece chapter 868 page 1 to /Users/[...]/One Piece/868/1.png ...
    Downloading One Piece chapter 868 page 2 to /Users/[...]/One Piece/868/2.png ...
    Downloading One Piece chapter 868 page 3 to /Users/[...]/One Piece/868/3.png ...
    Downloading One Piece chapter 868 page 4 to /Users/[...]/One Piece/868/4.png ...
    Downloading One Piece chapter 868 page 5 to /Users/[...]/One Piece/868/5.png ...
    Downloading One Piece chapter 868 page 6 to /Users/[...]/One Piece/868/6.png ...
    Downloading One Piece chapter 868 page 7 to /Users/[...]/One Piece/868/7.png ...
    Downloading One Piece chapter 868 page 8 to /Users/[...]/One Piece/868/8.png ...
    Downloading One Piece chapter 868 page 9 to /Users/[...]/One Piece/868/9.png ...
    Downloading One Piece chapter 868 page 10 to /Users/[...]/One Piece/868/10.png ...
    Downloading One Piece chapter 868 page 11 to /Users/[...]/One Piece/868/11.png ...
    Downloading One Piece chapter 868 page 12 to /Users/[...]/One Piece/868/12.png ...
    Downloading One Piece chapter 868 page 13 to /Users/[...]/One Piece/868/13.png ...
    $ tree
    .
    └── One\ Piece
        └── 868
            ├── 1.png
            ├── 10.png
            ├── 11.png
            ├── 12.png
            ├── 13.png
            ├── 2.png
            ├── 3.png
            ├── 4.png
            ├── 5.png
            ├── 6.png
            ├── 7.png
            ├── 8.png
            └── 9.png
    
    2 directories, 13 files
