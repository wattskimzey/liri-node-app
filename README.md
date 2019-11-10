# LIRI NODE APP
![LIRI-NODE-APP](https://raw.githubusercontent.com/wattskimzey/liri-node-app/master/images/LIRI_LOGO.png)

## Description
LIRI is a command line program that takes in parameters and gives back data.  It can search various APIs to find this data.  It displays the results on screen as well as writes them to a log file.  

# The Nitty Gritty
LIRI is a javascript app that can ping several APIs (_Spotify, OMDB & Bands in Town_) about bands, songs and movies.  Witness the magic:
* _concert-this_ - returns venue name, location and event date for the specified artist
    * using this structure _node liri.js concert-this "artist name"_
* _spotify-this-song_ - returns the artist, song's album, song name and a Spotify preview link
    * using this structure _node liri.js spotify-this-song "song name"_
* _movie-this_ - returns movie title, Rotten Tomatoes and IMDB ratings, movie release year, actors, plot, language and production country. 
    * using this structure _node liri.js movie-this "movie name"_
* _do-what-it-says_ is a little different. it reads the input from a local text file named _random.txt_ and performs one of the above actions.
    * using this structure _node liri.js do-what-it-says_  

## NPM Dependencies
* node-spotify-api
* axios
* fs
* dotenv
* moment

## APIs
* Spotify
* OMDB
* Bands In Town

## Motivation
The motivation for this project was that it was a requirement.  If you don't do your requirements then you are taken into the center of town and flogged.  Weighing coding versus flogging... well, you get the idea.

## Results
Ideally, I'm happy with the results.  I would use this program daily if I could pry myself away from my smartphone.  

## Team Efforts
* _Idea_ - Vanderbilt Bootcamp
* _project management_ - Richard 
* _front end_ - there was no front end in the traditional sense
* _back end_ - Richard. and Google.  and Stack Overflow. and Coffee. and Excedrin Migraine
* _logo_ - Richard
* _Catering_ - Richard
* _Best Boy_ - Richard
* _Comedic Relief_ - Richard

## Individual Responsibilities.
I did it all by myself (insert evil laughter)

### Challenges
The main challenge to this assignment, which was due like a month ago, was time. Unfortunately, I have not coded a time machine.

## Improvements
_Exciting things are in store for LIRI!__
* 24 - hour wine delivery
* massage therapy
* urgent care
* LIRI Points (_can be used for gas discounts_)
* MIRI - a new friend for LIRI!
* Mortgage Discounts
* _and so much more!!_



