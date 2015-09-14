# travel_log
Organize my travel log. Edit with `org-mode`, store in Git and render via [GitHub geoJSON](https://help.github.com/articles/mapping-geojson-files-on-github/).

![travel_log demonstration](https://github.com/pepijn/travel_log/blob/master/media/demo.gif)

## Description

Turns this:
![travel_log Emacs org-mode](https://github.com/pepijn/travel_log/blob/master/media/emacs.png)

Into this:
![travel_log GitHub GeoJSON](https://github.com/pepijn/travel_log/blob/master/media/geojson_github.png)

## Usage

Check out the repository, open `travel_log.org` and run `C-c C-v C-b` to run all
the blocks. The editable travel log appears after the first two blocks have been
executed.

## Requirements

* Emacs with `org-mode`
* Ruby `>= 1.9`
* Ruby gem `geocoder`

## Inspiration

[Literate Devops with Emacs](https://www.youtube.com/watch?v=dljNabciEGg) by [Howard Abrams](https://www.youtube.com/channel/UCVHICXXtKG7rZgtC5xonNdQ)
