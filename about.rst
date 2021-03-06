About CCHits.net, the FAQ and more
==================================

Goals
-----
CCHits.net is a site promoting and featuring `Creative Commons <http://creativecommons.org/about/licenses/>`_ licensed music and the podcasts that play them. The site was designed with more than just this in mind. Here are some of the highlights:

* Encourage and Discover Great Music
    There's a lot of great Creative Commons Licensed Music out there, and not enough people know just what you can get hold of! To help ease the burdon of this issue, there are three things that we do:
    
    * By linking directly to artist's home sites rather than to our own holding pages for artists, we ensure that the artists get maximum exposure for their own material, without having to update our site when their own information changes!
    * By linking to the source of the individual track, gives listeners a greater awareness of music sources, which hopefully should increase the exposure for sites who promote and list Creative Commons licensed music.
    * By linking to podcasts which play Creative Commons licensed music, we give listeners the opportunity to find other shows that play the music they like - ultimately giving listeners a greater fountain of great music to select from, and hopefully giving them the opportunity to discover new artists and genres to add to their personal list of favourites.

* Support Communities
    An attendor at various social groups, the original author of the code which drives cchits.net was unable to provide consistent, suitable background music for events he was involved in organising or just attending. This site was originally designed to find tracks which are generally acceptable for public play, and are available under a suitable license for public performance (which Creative Commons music should be!) By asking all submitters of music to identify the license under which the tracks are made available, as well as selecting whether tracks may not be suitable for work or family listening, it should be possible (once the code is in-place) to request from the site a suitable selection of music for playback at venues such as hackspaces, youth centres, or even just hold music for a business. Note that this site is not being created to build a re-licensing business, but instead to promote awareness of great music - there are other, better sites, that can advise and assist in the selection of Creative Commons music which are suitable for your business endeavour, but if you just want something for backing music for an hour or a whole day, this site might be (eventually!) just the thing for you.

* Create Podcasts and Improve Coding Techniques
    At the time of writing, cchits.net is the work of one person. For several months, `Jon "The Nice Guy" Spriggs <http://jon.sprig.gs/>`_ had been considering starting a podcast, however, he's not exactly known for finishing projects! By making a system which is automated enough to create a daily podcast, a weekly podcast and a monthly podcast, playing music that he likes to hear, he thought it might encourage him to stick to it - especially when there are other amazing goals (see above) which come out as a side benefit. He normally has described himself as a writer of "bad PHP code", and each project he starts improves the techniques he has learned.
    
    In this instance, CCHits.net has introduced Jon to the concept of writing an API that works, a system of remote execution of code, the generation of synthesized speech and the generation of an audio track, entirely in code! Never being shy of criticism from the community, especially where code is concerned, the code has all been released under a license which encourages reuse and requires the code is re-released under the same license.

Get Involved
------------
If you want to get involved, please contact show@cchits.net to talk about submitting tracks, creating shows and generally doing more with CCHits.net

Source
------
The source code for everything driving this site is available in the `Git Repositories <https://github.com/CCHits>`_ at Github.

Patches to either can either be e-mailed to code@cchits.net, or you can clone a repository, make your changes and then raise a merge request through the site.

Vote Adjustments
----------------
CCHits.net adjusts the votes accrued when weekly review shows and monthly chart shows are released. In both cases, this is to try and ensure that generated shows don't constantly repeat the same tracks that became popular at the start of the system.

Each time a track appears on a weekly or monthly show, it is adjusted down by 5%. No plays by external podcasts or the daily exposure show will influence the votes received by that track.

To see the shows that have played a track, you can click on the track listing for the track on any of the show listings, and it will list all the shows we know about.

Trending Data
-------------
CCHits.net monitors trending information about tracks which are being voted upon. This is done by a very simple formula - the votes for each 24 hour period is collated and multiplied by an incrementing number to correspond with the number of days the surveyed sample covers. A single vote placed on each of the 7 days in the searched period will be equivelent to 1 vote on the first day, 2 on the second, 3 on the third and so on. Each search covers 7 days.

Theme
-----
The theme is an exerpt from a track, sourced from `ccMixter <http://ccmixter.org/>`_. The Track is called `GMZ <http://ccmixter.org/files/scottaltham/19726>`_ and was created by `scottaltham <http://ccmixter.org/people/scottaltham>`_.

Not Safe for Work or Family Listening - an explanation
------------------------------------------------------
As this project was originally supposed to create audio to be used at events, I wanted to be clear about the demarkation between "Work-or-Family Safe" music, and non... so I drew up these guidelines. A track is safe for work-or-family listening if:

    * The track does not contain any swear words or derogatory words for gender, race, preference, or if it does contain them, they are hard to make out or distinguish.
    * The track does not contain any obvious direct references to drug use.
    * The track does not contain any obvious sexual references, including suggestive sounds.
    * The track does not advocate crime or gun use (which is a criminal act in some countries).

Obviously, not everyone agrees with this definition, and I don't upload every track. Some people will mark a track as being non-work-safe if it contains language they don't understand (in case it breaches one of the recommendations), or will mark a track as being work-or-family safe even if it breaches one of the above recommendations. If you disagree with how the track is marked, please feel free to contact show@cchits.net and I'll re-listen to the track, and possibly change it's flag, if I think it's appropriate.