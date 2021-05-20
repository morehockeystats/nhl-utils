# nhl-utils
Scraping the NHL data and handling it

This is a collection of small utils to separate them from my main project.
All kinds of programming languages may appear here, but bash and perl will likely be the most popular.

* fetch-live-game - continuously poll and download live NHL reports (json+html)

The files are stored under a created `ID/` directory, in the subdirectory named either `Final`, or in the format `P-MM:SS-E` where

 * `P` s the current period of the report 
 * `MM:SS` is the game timestamp of the report, e.g. `06:22`
 * `E` is the last event ID of the game as reported by the live JSON
