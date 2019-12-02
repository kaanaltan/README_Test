# News Bias Scraper

### What?

> This Python script utilizes Beautiful Soup and Pandas libraries to scrape [Allsides Media Bias Ratings] and return a csv with the following information to classify media outlets based on their political bias:

- Name
- News Page
- Allsides Page
- Media Bias
- Agree Count
- Disagree Count
- Agreeance Ratio
- Agreeance

### Why?

> The intention of writing this script is to feed data into another script to scrape news sites with the desired classification parameters.

**Allsides Media Bias Table**

![alt text][allsides-table-gif]

[allsides-table-gif]: ./README/Images/allsides_gif.gif
[Allsides Media Bias Ratings]: https://www.allsides.com/media-bias/media-bias-ratings

# Kaan Altan - Resume

> v1.0

My resume in Python featuring a command line interface for interaction

> v2.0

Scraping mode introduced

## Usage

Command line interface allows access to specific information
> v1.0
- `-i`      Prints all content in the info dictionary
- `-n`      Prints "Name" value in the info dictionary
- `-p`      Prints "Phone" value in the info dictionary
- `-e`      Prints "Email" value in the info dictionary
- `-l`      Prints "Linkedin" value in the info dictionary
- `-f`      Prints all content in the features dictionary
- `-lsf`    Lists keys in the features dictionary (Feature titles)
- `-fid`    Prints specified feature when a feature title is passed in
- `-s`      Prints all content in the skills dictionary
- `-lss`    Lists keys in the skills dictionary (Skill titles)
- `-sid`    Prints specified skills when a skill title is passed in
> v2.0
- `-sc`     Enables scraping mode, scrapes & parses resume file passed in and uses that to display requested information

`Note: Skills are not supported in scraping mode`

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)