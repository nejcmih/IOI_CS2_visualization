# Enhancing Strategic Thinking in Counter-Strike 2 Through Player Trends

**An interactivity and information design project by Nejc Mihelič and Vito Verdnik.**

## Mission
Proactively informing the player of other players' tendencies and their typical behavior over the course of a Counter-Strike 2 round.

## Visualizations on Offer
* **Player paths:** Visualization of player paths in a single round or a composite of multiple rounds.
* **Location heatmaps:** Statistically probable locations of players throughout the course of the round.
* Locations of the most effective flashbangs.
* Statistical tracking of AWP player movements throughout the round.
* Lurker position tracking.
* Bombsite attack success calculation and retake success chance calculation.

*Additional filtering based on team economies is available.*

## Supported Maps
* Dust 2
* Mirage
* Inferno

## How to use
It's necessary to use a web server for visualizations. The most simple way is with using a Python HTTP server, with this command in console:
* python -m http.server 8000

Then open a web browser and navigate to http://localhost:8000.

## Acknowledgements
Special thanks to **PureSkill.gg** for providing the datasets. A smaller version of the dataset is available at the following link:
[Kaggle: CS2 Gameplay Data (PureSkill.gg)](https://www.kaggle.com/datasets/billpureskillgg/cs2-2023-11-23)