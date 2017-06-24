# dlScan

Quickly-made Shell tool for downloading manga chapters.

## Installation
Clone repository

    $ git clone https://github.com/savari-o/dlScan.git .

Copy dlScan to /usr/local/bin/

    $ sudo cp dlScan /usr/local/bin/

----
## Usage

    $ dlScan
    usage: dlScan manga_name scan_number

### Arguments :

* manga_name: name of the manga (can be an abbreviation)
* scan_number: number of the chapter

### Example :

    $ dlScan op 868
    Download http://cdn.japscan.com/lel/One Piece/868/01.png
    Download http://cdn.japscan.com/lel/One Piece/868/02.png
    Download http://cdn.japscan.com/lel/One Piece/868/03.png
    Download http://cdn.japscan.com/lel/One Piece/868/04.png
    Download http://cdn.japscan.com/lel/One Piece/868/05.png
    Download http://cdn.japscan.com/lel/One Piece/868/06-07.png
    Download http://cdn.japscan.com/lel/One Piece/868/08.png
    Download http://cdn.japscan.com/lel/One Piece/868/09.png
    Download http://cdn.japscan.com/lel/One Piece/868/10-11.png
    Download http://cdn.japscan.com/lel/One Piece/868/12-13.png
    Download http://cdn.japscan.com/lel/One Piece/868/14.png
    Download http://cdn.japscan.com/lel/One Piece/868/15.png
    Download http://cdn.japscan.com/lel/One Piece/868/16-17.png
    Downloaded 13 images from One Piece n°868
    $ tree
    .
    └── One\ Piece
        └── 868
            ├── 01.png
            ├── 02.png
            ├── 03.png
            ├── 04.png
            ├── 05.png
            ├── 06-07.png
            ├── 08.png
            ├── 09.png
            ├── 10-11.png
            ├── 12-13.png
            ├── 14.png
            ├── 15.png
            └── 16-17.png
    
    2 directories, 13 files