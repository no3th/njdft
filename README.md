# Introduction
The NJD FileTree (NJDFT) is a system that aims to combine concepts from PARA and GTD to create a universal filetree for archival and retrieval of data. It owes its origins to two other existing projects.  

## The Johnny Decimal System
Utilizes a unique identifier for every relevant folder using an XX.XX notation, dividing each relevant category into ten sections each following the SI decimal notation.

## The r/DataCurator Filetree
A filesystemthat developed out of a need to establish a simple standardized rule for organizing digital data.


# Our Goals
## TL;DR
A universal filetree for portable storage, building upon the principles of Johnny.Decimal. 


# Details
It is a tedious job to keep track of dozens of files in dozens of places, so it helps if you have a standardized format for storing digital information. I am a student, and this implementation is biased toward my workflow, but it is adaptable. 

The neo Johnny Decimal Filetree (NJDFT) is a system that helps you not lose yourself in the details of what file goes where, because you will know this beforehand.

## Branch: Home

The folder is titled ".Home" so copy its contents to the Home folder of your OS. We have tried to keep it close to the XDG specification, so we suggest you enforce them first.

Follow this [link](https://wiki.archlinux.org/index.php/XDG_user_directories) to learn more about XDG, and how to set it up.

## Branch: Media

This filetree is suitable for storing digital media that is not time bound or project bound like in the default NJD setup.

We distinguish between "Media" and "Entertainment" like so -
- Media - Content that is meant to complement work, and not distract you from it. Lectures, Tutorials, Documentaries etc. fit this definition.
- Entertainment - Content that is meant purely for consumption, and might end up reeling you into a blackhole of procrastination.

### Entertainment
Our suggestion is to store all of your Movies, Anime and TV Shows into a separate external drive and copy them to your machine as and when you need them so that any source of distraction is out of sight (and out of mind)

### Media 
Our folders for "Video" and "Video Playlists" are roughly derived from the YouTube space. Any help in further disambiguating these would be appreciated.


# Explanation
## Default
The [master](https://github.com/no3th/njdft/tree/master) filetree is the root of the NJDFT, and the default layout for folders that you can directly extract to the root of each partition.

## Media
The [media](https://github.com/no3th/njdft/tree/ft.media) filetree follows a layout suitable for storing entertainment and media alone.

## Home
The [home](https://github.com/no3th/njdft/tree/ft.home) filetreee closely resembles the XDG specifications, and fits into the home directory of each user on a system.


## Modifications
+ Unlike the datacurator filetree, we do not have a separate section for "Adult Content" ^1^

### Notes
1. Sorry coomers, NoFap Forever

This is a work in progress. Feel free to fork to your heart's content, and in doing so (inadvertently) establish some standards to end the confusion of file and folder organization.


# Credits
+ The [Johnny•Decimal](https://johnnydecimal.com/) blog 
+ The [r/Datacurator Filetree](https://github.com/roboyoshi/datacurator-filetree) and its repos