# NBA-Similarity-Index

This project is a Python-based tool that identifies NBA players most similar to a selected player, using a comprehensive set of statistical categories. It returns a similarity score out of 10 to quantify how alike each player is to the selected target.

## How It Works
The script compares a target player to all other players in the dataset using a variety of metrics. A similarity score (0 to 10) is calculated for each comparison, where 10 indicates high similarity.

## Features
The tool uses a broad spectrum of basketball statistics to evaluate player similarity, including:

- Per 100 Possessions Stats
- Advanced Analytics (e.g., PER, BPM, WS, etc.)
- Hustle Stats (deflections, contested shots, loose balls recovered, etc.)
- Play-by-Play Metrics (e.g. Position Estimate, +/-, etc.)
- Shot Type Data (pull-ups, catch & shoot, drives, etc.)
- Advanced Shooting Statistics (e.g., eFG%, TS%, shot location breakdowns)
- Per Game Stats (traditional stats like points, rebounds, assists)

## Data Sources
Data was collected from https://www.basketball-reference.com and https://www.nba.com/stats

## TODO
Add web interface

Support WNBA players

Add era-adjusted comparison mode
