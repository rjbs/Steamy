# Steamy

This is terrible code, but it gets the job done, more or less.

I wrote this for my video game book club.  You tell it who's in the club and it
helps pick a game to review.  Its main job is to find games that multiple
members *own* but haven't *played*.  You can also require that it support a
given OS, and that it tell you how much the game costs, so you can pick based
on total cost for all non-owners to get the game.

The Steam API is a mess.

    steamy [long options...] USERID...
      --time INT            playtime allowed before exclusion (min.)
      --key STR             Steam API key
      --limit INT           stop listing after this many items
      --cache-duration STR  Duration for new items in cache (default is "6
                            hours")
      --linux               Require linux support
      --mac                 Require mac support
      --windows             Require windows support
      --price               fetch price data
