# League-of-Legends-Match-Collector
Jupyter notebook to collect match frames from Riot using cassiopeia python wrapper library.

Not all collected data is saved, only specific data from the match frames is saved 
as *.csv and all of the match timeline is saved as as *.json. All the collected data is saved by region.

The data is saved as root_dir -->lol-matches --> region_x --> csv, raw_json, parsed.txt
where parsed.txt contains '\n' separated match ids of parsed matches
