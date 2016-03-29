# natie-music

a repeating music player that let's you jam to your own tune.  

each column represents a domain of pitch, and each row is played left to right on repeat.

## Specifications
this app is written in front-end javascript and hosted on github pages.  

note that the main branch (production branch) is `gh-pages`.

## Installation
`clone` the repository

## Usage
in terminal, start a simple HTTP server using `python -m SimpleHTTPServer`.  

Or, if the the `npm` package `http-server` is installed, just run `http-server`.  
go to `localhost:8000` or the port specified by the console output.

## URL redirect setup
github pages supports a custom domain by putting one in a CNAME file committed to the root directory. For example, http://www.natie.com/natie-music would be the content of the file.  
see instructions here: https://help.github.com/articles/quick-start-setting-up-a-custom-domain/  
then set up DNS on the domain manager (GoDaddy) to reroute. the settings i suggest are  
NAME = `www`  
TYPE = `CNAME`  
TTL = `1h`  
DATA = `natielabs.github.io`
