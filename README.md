# Citizen of Nowhere open data: Elo ratings and rankings

Free, daily-updated Elo ratings for the NFL, college football, NBA, NHL, MLB, WNBA, AFL, NRL, IPL and world football, plus the Global Metro Power Rankings and 12 other rankings, from Citizen of Nowhere (https://rankings.citizenofnowhere.org), every Elo series on the method at https://rankings.citizenofnowhere.org/methodology/elo (the NFL, NBA, NHL and MLB historical series from Neil Paine's published game logs, the live seasons computed by the site): a free, maintained alternative to FiveThirtyEight's discontinued Elo ratings. Every file is a plain UTF-8 CSV with a header row, described in a Frictionless `datapackage.json`, and released under Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

Last updated: 2026-11-27. 26 datasets, 38 CSV files. The repository is rewritten each morning and commits only when a dataset changed.

| Dataset | File | Rows | As of |
|---|---|---:|---|
| [NFL Elo ratings](#nfl-elo-ratings) | `data/nfl-elo.csv` | 32 | 2026-11-26 |
| [College football Elo ratings](#college-football-elo-ratings) | `data/cfb-elo.csv` | 138 | 2026-11-26 |
| [NBA Elo ratings](#nba-elo-ratings) | `data/nba-elo.csv` | 30 | 2026-11-27 |
| [NHL Elo ratings](#nhl-elo-ratings) | `data/nhl-elo.csv` | 32 | 2026-11-26 |
| [MLB Elo ratings](#mlb-elo-ratings) | `data/mlb-elo.csv` | 30 | 2026-11-01 |
| [WNBA Elo ratings](#wnba-elo-ratings) | `data/wnba-elo.csv` | 15 | 2026-11-27 |
| [AFL Elo ratings](#afl-elo-ratings) | `data/afl-elo.csv` | 18 | 2026-09-26 |
| [NRL Elo ratings](#nrl-elo-ratings) | `data/nrl-elo.csv` | 17 | 2026-10-04 |
| [IPL Elo ratings](#ipl-elo-ratings) | `data/ipl-elo.csv` | 15 | 2026-05-31 |
| [World Club Elo](#world-club-elo) | `data/world-club-elo.csv` | 500 | 2026-11-26 |
| [British and Irish club football Elo](#british-and-irish-club-football-elo) | `data/gbi-club-elo.csv` | 188 | 2026-11-27 |
| [Football Elo ratings: men's national teams](#football-elo-ratings-mens-national-teams) | `data/football-elo-men.csv` | 256 | 2026-11-26 |
| [Football Elo ratings: women's national teams](#football-elo-ratings-womens-national-teams) | `data/football-elo-women.csv` | 222 | 2026-11-26 |
| [The Universal Index](#the-universal-index) | `data/universal-index.csv` | 431 | 2026-11-27 |
| [The Universal Index: Nations](#the-universal-index-nations) | `data/universal-nations.csv` | 1,487 | 2026-11-26 |
| [The Women's Universal Index](#the-womens-universal-index) | `data/womens-universal-index.csv` | 103 | 2026-11-27 |
| [Global Metro Power Rankings](#global-metro-power-rankings) | `data/global-metro-power-rankings.csv` | 4,319 | 2026-11-25 |
| [Country composite ranking](#country-composite-ranking) | `data/country-composite.csv` | 247 | 2026-11-25 |
| [Zone Zero Cup](#zone-zero-cup) | `data/zone-zero-cup.csv` | 227 | 2026-11-24 |
| [The Team That Wins the City](#the-team-that-wins-the-city) | `data/team-that-wins-the-city.csv` | 312 | 2026-11-14 |
| [The Last of the Marylebones: global neighbourhoods](#the-last-of-the-marylebones-global-neighbourhoods) | `data/marylebone-neighbourhoods.csv` | 141 | 2026-04-21 |
| [The Champions Ledger](#the-champions-ledger) | `data/champions-ledger.csv` | 18,645 | 2026-11-22 |
| [Elections of the world](#elections-of-the-world) | `data/elections.csv` | 2,778 | 2026-10-23 |
| [Language power](#language-power) | `data/language-power.csv` | 326 | 2026-11-01 |
| [Sporting supremacy by city](#sporting-supremacy-by-city) | `data/metro-sporting-supremacy.csv` | 211 | 2026-11-24 |
| [Fan Attention Index: the top 20](#fan-attention-index-the-top-20) | `data/fan-attention-top20.csv` | 20 | 2026-11-03 |

## Licence and use

Released by Ashwin Desikan under Creative Commons Attribution-NonCommercial 4.0 International (https://creativecommons.org/licenses/by-nc/4.0/). Attribution to Ashwin Desikan / Citizen of Nowhere is required; commercial use needs permission. Use by answer engines and for training AI models is permitted under the same terms (https://rankings.citizenofnowhere.org/ai-access). How to cite: https://rankings.citizenofnowhere.org/cite. Upstream credits named in a dataset's section travel with it.

## NFL Elo ratings

NFL Elo ratings is Citizen of Nowhere Elo rating of every NFL franchise since 1920, updated after each week's games (K 20, home advantage 65; method at https://rankings.citizenofnowhere.org/methodology/elo; historical series from Neil Paine's published game logs), a free, maintained alternative to FiveThirtyEight's discontinued NFL Elo. `data/nfl-elo.csv` holds 32 rows as of 2026-11-26, with columns `rank`, `team`, `name`, `city`, `league`, `conference`, `division`, `elo`, `season`, `season_status`, `week`, `ratings_date`, `season_start_elo`, `season_peak_elo`, `record`.

- Page: https://rankings.citizenofnowhere.org/teams/nfl
- Also: `data/nfl-elo-weekly.csv` (this season week by week), 416 rows
- Also: `data/nfl-elo-season-end.csv` (every team, every season), 2,447 rows
- Cite: Desikan, A. (2026). NFL Elo ratings (model v1.0, ratings updated 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/nfl

## College football Elo ratings

College football Elo ratings is the site's own Elo rating for every college football program, 1869 to today, with K 36, home advantage 60 and 15% regression to 1500 between seasons. `data/cfb-elo.csv` holds 138 rows as of 2026-11-26, with columns `rank`, `program`, `slug`, `elo`, `z`, `adj_z`, `season`.

- Page: https://rankings.citizenofnowhere.org/teams/cfb
- Also: `data/cfb-elo-season-end.csv` (every program, every season), 14,547 rows
- Cite: Desikan, A. (2026). College football Elo ratings (model v1.0, ratings updated 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/cfb

## NBA Elo ratings

NBA Elo ratings is Citizen of Nowhere Elo rating of every NBA (and ABA) team since 1947, with this season updated week by week from results (method at https://rankings.citizenofnowhere.org/methodology/elo; historical series from Neil Paine's published game logs). `data/nba-elo.csv` holds 30 rows as of 2026-11-27, with columns `rank`, `team`, `name`, `city`, `league`, `conference`, `division`, `elo`, `season`, `season_status`, `week`, `ratings_date`, `season_start_elo`, `season_peak_elo`, `record`.

- Page: https://rankings.citizenofnowhere.org/teams/nba
- Also: `data/nba-elo-weekly.csv` (this season week by week), 210 rows
- Also: `data/nba-elo-season-end.csv` (every team, every season), 1,847 rows
- Cite: Desikan, A. (2026). NBA Elo ratings (data as of 27 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/nba

## NHL Elo ratings

NHL Elo ratings is Citizen of Nowhere Elo rating of every NHL (and WHA) team since 1917, with this season updated week by week from results (method at https://rankings.citizenofnowhere.org/methodology/elo; historical series from Neil Paine's published game logs). `data/nhl-elo.csv` holds 32 rows as of 2026-11-26, with columns `rank`, `team`, `name`, `city`, `league`, `conference`, `division`, `elo`, `season`, `season_status`, `week`, `ratings_date`, `season_start_elo`, `season_peak_elo`, `record`.

- Page: https://rankings.citizenofnowhere.org/teams/nhl
- Also: `data/nhl-elo-weekly.csv` (this season week by week), 320 rows
- Also: `data/nhl-elo-season-end.csv` (every team, every season), 1,870 rows
- Cite: Desikan, A. (2026). NHL Elo ratings (data as of 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/nhl

## MLB Elo ratings

MLB Elo ratings is Citizen of Nowhere Elo rating of every Major League Baseball team since 1876, with the latest season updated week by week from results (method at https://rankings.citizenofnowhere.org/methodology/elo; historical series from Neil Paine's published game logs). `data/mlb-elo.csv` holds 30 rows as of 2026-11-01, with columns `rank`, `team`, `name`, `city`, `league`, `conference`, `division`, `elo`, `season`, `season_status`, `week`, `ratings_date`, `season_start_elo`, `season_peak_elo`, `record`.

- Page: https://rankings.citizenofnowhere.org/teams/mlb
- Also: `data/mlb-elo-weekly.csv` (this season week by week), 990 rows
- Also: `data/mlb-elo-season-end.csv` (every team, every season), 3,085 rows
- Cite: Desikan, A. (2026). MLB Elo ratings (data as of 1 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/mlb

## WNBA Elo ratings

WNBA Elo ratings is the site's own Elo rating of every WNBA team, as carried on the Women's Universal Index. `data/wnba-elo.csv` holds 15 rows as of 2026-11-27, with columns `rank`, `team`, `elo`, `season`, `in_season`, `days_idle`.

- Page: https://rankings.citizenofnowhere.org/teams/wnba
- Cite: Desikan, A. (2026). WNBA Elo ratings (data as of 27 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/wnba

## AFL Elo ratings

AFL Elo ratings is the site's own Elo rating of every VFL/AFL club since 1897 (K 40, travel-aware home advantage, 35% regression between seasons). `data/afl-elo.csv` holds 18 rows as of 2026-09-26, with columns `rank`, `club`, `nickname`, `slug`, `elo`, `change_last_5`.

- Page: https://rankings.citizenofnowhere.org/teams/afl
- Also: `data/afl-elo-season-end.csv` (season-end rating of every club), 1,640 rows
- Cite: Desikan, A. (2026). AFL Elo ratings (model v1-k40-hga60-100-reg35) (data as of 26 Sep 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/afl

## NRL Elo ratings

NRL Elo ratings is the site's own Elo rating of every NSWRL/ARL/NRL rugby league club since 1908 (K 40, travel-aware home advantage, 35% regression between seasons). `data/nrl-elo.csv` holds 17 rows as of 2026-10-04, with columns `rank`, `club`, `nickname`, `slug`, `elo`, `change_last_5`.

- Page: https://rankings.citizenofnowhere.org/teams/nrl
- Also: `data/nrl-elo-season-end.csv` (season-end rating of every club), 1,424 rows
- Cite: Desikan, A. (2026). NRL Elo ratings (model v1-k40-hga60-100-reg35) (data as of 4 Oct 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/nrl

## IPL Elo ratings

IPL Elo ratings is the site's own Elo rating for every Indian Premier League franchise since 2008, with each side's peak and low. `data/ipl-elo.csv` holds 15 rows as of 2026-05-31, with columns `rank`, `team`, `abbr`, `slug`, `active`, `elo`, `rating_date`, `last_season`, `change_last_season`, `peak_elo`, `peak_date`, `low_elo`, `low_date`, `games`.

- Page: https://rankings.citizenofnowhere.org/teams/ipl
- Cite: Desikan, A. (2026). IPL Elo ratings (data as of 31 May 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/teams/ipl

## World Club Elo

World Club Elo is the site's own Elo rating of the world's top 500 men's football clubs on one scale across all six confederations, with each confederation's level fitted from cross-confederation games. `data/world-club-elo.csv` holds 500 rows as of 2026-11-26, with columns `rank`, `name`, `country`, `confederation`, `rating`, `games`, `xconf_games`, `provisional`, `last_match`.

- Page: https://rankings.citizenofnowhere.org/football/world-club-elo
- Cite: Desikan, A. (2026). World Club Elo (data as of 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/football/world-club-elo

## British and Irish club football Elo

British and Irish club football Elo is the site's own Elo ranking of every men's league club in England, Scotland, Wales, Northern Ireland and Ireland on one list. `data/gbi-club-elo.csv` holds 188 rows as of 2026-11-27, with columns `rank`, `club`, `country`, `division`, `tier`, `rating`, `elo`.

- Page: https://rankings.citizenofnowhere.org/sports/great-britain-ireland
- Cite: Desikan, A. (2026). British and Irish club football Elo (data as of 27 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/sports/great-britain-ireland

## Football Elo ratings: men's national teams

Football Elo ratings: men's national teams is the site's own Elo rating of every men's national football team, computed from every international result since 1872 and updated each morning; the international hubs show it in place of the FIFA ranking. `data/football-elo-men.csv` holds 256 rows as of 2026-11-26, with columns `rank`, `nation`, `elo`, `last_game`, `days_idle`, `suspended`.

- Page: https://rankings.citizenofnowhere.org/football/international
- Cite: Desikan, A. (2026). Football Elo ratings: men's national teams (data as of 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/football/international

## Football Elo ratings: women's national teams

Football Elo ratings: women's national teams is the site's own Elo rating of every women's national football team, computed from international results and updated each morning. `data/football-elo-women.csv` holds 222 rows as of 2026-11-26, with columns `rank`, `nation`, `elo`, `last_game`, `days_idle`, `suspended`.

- Page: https://rankings.citizenofnowhere.org/football/women/international
- Cite: Desikan, A. (2026). Football Elo ratings: women's national teams (data as of 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/football/women/international

## The Universal Index

The Universal Index is a cross-sport, day-by-day leaderboard of the strongest teams in the NFL, college football, MLB, NBA, NHL, IPL and men's club football, each team's Elo placed on one common scale so a Bundesliga club and an NBA side can be compared. `data/universal-index.csv` holds 431 rows as of 2026-11-27, with columns `rank`, `team`, `league`, `team_id`, `season`, `elo`, `universal`, `z`, `rank_in_league`, `in_season`, `days_idle`.

- Page: https://rankings.citizenofnowhere.org/sports/universal
- Cite: Desikan, A. (2026). The Universal Index (data as of 27 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/sports/universal

## The Universal Index: Nations

The Universal Index: Nations is a cross-sport leaderboard of national teams that puts every nation's Elo in 17 sports (football, basketball, rugby, cricket, ice hockey, handball, volleyball, baseball and Olympic codes, men's and women's) on one comparable scale. `data/universal-nations.csv` holds 1,487 rows as of 2026-11-26, with columns `rank`, `nation`, `board`, `sport`, `gender`, `elo`, `universal`, `z`, `rank_in_board`, `days_idle`, `last_game`, `suspended`.

- Page: https://rankings.citizenofnowhere.org/sports/universal/nations
- Cite: Desikan, A. (2026). The Universal Index: Nations (data as of 26 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/sports/universal/nations

## The Women's Universal Index

The Women's Universal Index is a cross-sport leaderboard of the strongest women's teams (club football, the NWSL, WNBA, PWHL, LOVB, the Hundred and the WPL) with each team's Elo placed on one common scale. `data/womens-universal-index.csv` holds 103 rows as of 2026-11-27, with columns `rank`, `team`, `league`, `team_id`, `season`, `elo`, `universal`, `z`, `rank_in_league`, `in_season`, `days_idle`, `attribution`.

- Page: https://rankings.citizenofnowhere.org/sports/women/universal
- Credit: Rows carry their own attribution where an upstream licence asks for one: Match data: Cricsheet (cricsheet.org), ODC-BY 1.0.
- Cite: Desikan, A. (2026). The Women's Universal Index (data as of 27 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/sports/women/universal

## Global Metro Power Rankings

Global Metro Power Rankings is a composite ranking of every metropolitan area on Earth by what it has built, the sum of sixteen weighted dimensions from population and listed companies to universities, transit, skyscrapers, sport and culture. `data/global-metro-power-rankings.csv` holds 4,319 rows as of 2026-11-25, with columns `rank`, `slug`, `name`, `country`, `region`, `timezone`, `continent`, `pop`, `score`, `lat`, `lon`, `primaryCity`, `gdp`, `majorTeams`, `companies`, `marketCap`, `skyscrapers`, `metroStations`, `universities`, `countrySlug`, `primaryState`, `state2`, `state3`, `stateSlug`, `state2Slug`, `state3Slug`, `sovereignSlug`, `subCountry`, `additionalStates`.

- Page: https://rankings.citizenofnowhere.org/rankings
- Cite: Desikan, A. (2026). Global Metro Power Rankings (data as of 25 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/rankings

## Country composite ranking

Country composite ranking is every sovereign state, constituent country, territory and disputed region ranked by the combined Global Metro Power score of its metros, with its population and metro count. `data/country-composite.csv` holds 247 rows as of 2026-11-25, with columns `scoreRank`, `slug`, `name`, `parent`, `continent`, `scoreTotal`, `metroAreas`, `teams`, `pop`, `metroPop`, `metroPct`, `areaSqKm`, `popRank`, `capital`, `biggestMetro`, `mostImportantMetro`.

- Page: https://rankings.citizenofnowhere.org/countries
- Cite: Desikan, A. (2026). Country composite ranking (data as of 25 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/countries

## Zone Zero Cup

Zone Zero Cup is the site's ranking of national sporting merit, scoring every nation across fourteen sport pillars from football and cricket to athletics and winter sports, rebuilt weekly. `data/zone-zero-cup.csv` holds 227 rows as of 2026-11-24, with columns `rank`, `nation`, `slug`, `continent`, `tier`, `merit`, `merit_summer`, `rank_summer`, `merit_winter`, `rank_winter`, `merit_per_capita`, `rank_per_capita`, `major_titles`, `best_rank`, `best_rank_sport`, `top_sport`, `top_sport_points`, `suspended`, `defunct`.

- Page: https://rankings.citizenofnowhere.org/sports/zone-zero-cup
- Cite: Desikan, A. (2026). Zone Zero Cup (data as of 24 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/sports/zone-zero-cup

## The Team That Wins the City

The Team That Wins the City is the site's editorial pick of the one sports team each ranked metro is identified with, with the reasoning for every pick. `data/team-that-wins-the-city.csv` holds 312 rows as of 2026-11-14, with columns `rank`, `metro`, `sport`, `team`, `rationale`.

- Page: https://rankings.citizenofnowhere.org/top-teams
- Cite: Desikan, A. (2026). The Team That Wins the City (data as of 14 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/top-teams

## The Last of the Marylebones: global neighbourhoods

The Last of the Marylebones: global neighbourhoods is the site's list of the neighbourhoods in the world's top-ranked metros that match London's Marylebone (historic, elite residential, dense and walkable with a daily village life), and the metros that have none, with the reasoning for each. `data/marylebone-neighbourhoods.csv` holds 141 rows as of 2026-04-21, with columns `rank`, `metro`, `qualifies`, `neighborhoods`, `rationale`.

- Page: https://rankings.citizenofnowhere.org/neighborhoods
- Cite: Desikan, A. (2026). The Last of the Marylebones: global neighbourhoods (data as of 21 Apr 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/neighborhoods

## The Champions Ledger

The Champions Ledger is the site's ledger of every champion of every competition it tracks, from the World Cup and the Olympics to domestic leagues and cups, each title placed on the metro the champion played in. `data/champions-ledger.csv` holds 18,645 rows as of 2026-11-22, with columns `year`, `season`, `sport`, `competition`, `comp_slug`, `era_name`, `champion`, `canonical`, `metro`, `metro_slug`, `date_awarded`, `scope`, `scope_type`, `tier`, `is_current`.

- Page: https://rankings.citizenofnowhere.org/datasets/champions-ledger
- Also: `data/champions-titles-by-metro.csv` (titles by metro), 833 rows
- Cite: Desikan, A. (2026). The Champions Ledger (data as of 22 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/datasets/champions-ledger

## Elections of the world

Elections of the world is every general election the site covers in dozens of democracies and the European Union: date, winner or largest party, turnout, seats and the winner's share. `data/elections.csv` holds 2,778 rows as of 2026-10-23, with columns `hub_code`, `hub_name`, `series`, `election_id`, `year`, `date`, `type_or_label`, `winner_or_largest`, `turnout`, `seats_total`, `seat_share_or_vote_share_of_winner`, `freedom_label`, `url`.

- Page: https://rankings.citizenofnowhere.org/elections
- Cite: Desikan, A. (2026). Elections of the world (data as of 23 Oct 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/elections

## Language power

Language power is the site's ranking of the world's languages by the Global Metro Power of the metros where they are spoken, weighted by each metro's speaker share. `data/language-power.csv` holds 326 rows as of 2026-11-01, with columns `rank`, `language`, `slug`, `power`, `share_of_world`, `metros`, `per_million_speakers`, `metros_for_80pct`, `top_metro`, `top_metro_contribution`.

- Page: https://rankings.citizenofnowhere.org/languages/power
- Credit: Speaker shares draw on Unicode CLDR territory language data (Unicode licence) and national censuses.
- Cite: Desikan, A. (2026). Language power (data as of 1 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/languages/power

## Sporting supremacy by city

Sporting supremacy by city is the Universal Index rolled up by metro: how many weeks since 1919-08-05 each city has had a team in the cross-sport top 10, and its best week. `data/metro-sporting-supremacy.csv` holds 211 rows as of 2026-11-24, with columns `rank`, `metro`, `slug`, `country`, `weeks_top10`, `weeks_top1`, `team_weeks_top10`, `team_weeks_top25`, `share_top10`, `best_rank`, `best_week`, `best_team`, `best_league`, `best_universal`.

- Page: https://rankings.citizenofnowhere.org/sports/universal
- Cite: Desikan, A. (2026). Sporting supremacy by city (Universal Index) (data as of 24 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/sports/universal

## Fan Attention Index: the top 20

Fan Attention Index: the top 20 is the site's measure of how much attention fans pay each sports team, scored 0 to 100 across 770 teams over 2025-11 to 2026-10; this file is the public top 20 only, exactly as the page shows it without sign-in. `data/fan-attention-top20.csv` holds 20 rows as of 2026-11-03, with columns `rank`, `team`, `league`, `group`, `score`.

- Page: https://rankings.citizenofnowhere.org/fans
- Cite: Desikan, A. (2026). Fan Attention Index (data as of 3 Nov 2026). Citizen of Nowhere. https://rankings.citizenofnowhere.org/fans

## Excluded on purpose

Lists compiled by someone else (the Forbes billionaires list, the Fortune 500/1000, the FIFA/Coca-Cola World Ranking, published team valuations, the Rolling Stone 500 and the films canon) are shown on the site as pages but are never redistributed here. Cite the original publisher for those.
