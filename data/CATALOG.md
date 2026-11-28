# Catálogo de dados

Gerado automaticamente em 2026-11-28 17:53 UTC a partir de `data/manifest/`. Não edite à mão.

## Fontes

| Fonte | Status | Última tentativa | Último sucesso | Observação |
|---|---|---|---|---|
| ddragon | ok | 2026-11-28T17:49:39+00:00 | 2026-11-28T17:49:39+00:00 |  |
| esportsbench | ok | 2026-11-28T17:49:40+00:00 | 2026-11-28T17:49:40+00:00 |  |
| leaguepedia | ok | 2026-11-28T17:52:38+00:00 | 2026-11-28T17:52:38+00:00 |  |
| leaguepedia_gcd | ok | 2026-11-28T17:50:47+00:00 | 2026-11-28T17:50:47+00:00 |  |
| lolesports | ok | 2026-11-28T17:50:49+00:00 | 2026-11-28T17:50:49+00:00 |  |
| lolwiki | falhou | 2026-11-16T04:02:31+00:00 |  | Module:ChampionData/data: api.php: HTTP 403 (<html lang="en"> <head> <title>Request blocked</title> <meta name="viewport" content="width=dev… |
| meraki | ok | 2026-11-28T17:49:42+00:00 | 2026-11-28T17:49:42+00:00 |  |
| oddspapi | parcial (com erros) | 2026-11-28T17:50:12+00:00 | 2026-11-28T17:50:12+00:00 | /historical-odds od184001743462132: 404 Client Error: Not Found for url: https://api.oddspapi.io/v4/historical-odds?fixtureId=od184001743462… |
| oracles_elixir | falhou | 2026-11-28T17:49:45+00:00 | 2026-11-16T03:26:29+00:00 | 2026: download falhou, versão anterior mantida (drive-usercontent: recebeu HTML em vez de CSV ('Google Drive - Quota exceeded'); drive-uc: r… |
| pandascore | ok | 2026-11-28T17:50:09+00:00 | 2026-11-28T17:50:09+00:00 |  |
| pandaskill | ok | 2026-11-28T17:49:39+00:00 | 2026-11-28T17:49:39+00:00 |  |
| riot_gcd | ok | 2026-11-28T17:49:45+00:00 | 2026-11-28T17:49:45+00:00 |  |

## Tabelas

| View no DuckDB | Fonte/tabela | Linhas | Colunas | Partições | Período | Tamanho | Atualizada em |
|---|---|---:|---:|---|---|---:|---|
| `raw.dd_champions` | ddragon/champions | 47,243 | 35 | única | — | 0.2 MB | 2026-11-18T11:58 |
| `raw.dd_items` | ddragon/items | 107,752 | 26 | única | — | 0.3 MB | 2026-11-18T11:58 |
| `raw.ebench_matches` | esportsbench/matches | 163,653 | 6 | única | 2011-03-14 a 2026-09-30 | 1.9 MB | 2026-11-17T00:18 |
| `raw.lp_leagues` | leaguepedia/Leagues | 194 | 6 | única | — | 0.0 MB | 2026-11-16T04:18 |
| `raw.lp_matchschedule` | leaguepedia/MatchSchedule | 174,470 | 74 | 2011–2026 (16) | 2011-03-14 a 2026-12-19 | 9.5 MB | 2026-11-28T17:50 |
| `raw.lp_picksandbanss7` | leaguepedia/PicksAndBansS7 | 99,156 | 55 | 2011–2026 (16) | — | 7.3 MB | 2026-11-28T12:04 |
| `raw.lp_playerredirects` | leaguepedia/PlayerRedirects | 33,475 | 4 | única | — | 1.0 MB | 2026-11-23T21:43 |
| `raw.lp_players` | leaguepedia/Players | 20,886 | 16 | única | — | 0.7 MB | 2026-11-23T21:42 |
| `raw.lp_rosterchanges` | leaguepedia/RosterChanges | 280,735 | 24 | 2011–2026 (16) | 2011-01-01 a 2026-11-28 | 9.2 MB | 2026-11-28T17:52 |
| `raw.lp_scoreboardgames` | leaguepedia/ScoreboardGames | 138,814 | 70 | 2011–2026 (16) | 2011-06-18 a 2026-11-27 | 18.4 MB | 2026-11-28T12:03 |
| `raw.lp_scoreboardplayers` | leaguepedia/ScoreboardPlayers | 1,388,140 | 45 | 2011–2026 (16) | 2011-06-18 a 2026-11-27 | 92.9 MB | 2026-11-28T12:06 |
| `raw.lp_teamredirects` | leaguepedia/TeamRedirects | 5,827 | 4 | única | — | 0.1 MB | 2026-11-23T21:41 |
| `raw.lp_teams` | leaguepedia/Teams | 3,582 | 24 | única | — | 0.3 MB | 2026-11-23T21:41 |
| `raw.lp_tournamentplayers` | leaguepedia/TournamentPlayers | 453,133 | 12 | 2011–2026 (16) | — | 6.9 MB | 2026-11-28T17:52 |
| `raw.lp_tournamentresults` | leaguepedia/TournamentResults | 96,179 | 29 | 2011–2026 (16) | — | 4.4 MB | 2026-11-28T17:52 |
| `raw.lp_tournaments` | leaguepedia/Tournaments | 10,603 | 34 | única | — | 0.8 MB | 2026-11-28T17:50 |
| `raw.lpgcd_pages` | leaguepedia_gcd/pages | 33,233 | 5 | única | 2018-02-20 a 2026-11-27 | 0.1 MB | 2026-11-28T12:03 |
| `raw.lpgcd_snapshots` | leaguepedia_gcd/snapshots | 4,054,475 | 10 | 2018–2026 (9) | 2018-02-20 a 2026-11-27 | 3.9 MB | 2026-11-28T12:03 |
| `raw.les_leagues` | lolesports/leagues | 51 | 7 | única | — | 0.0 MB | 2026-11-16T02:15 |
| `raw.les_match_games` | lolesports/match_games | 28,100 | 10 | única | — | 0.4 MB | 2026-11-16T02:15 |
| `raw.les_schedule` | lolesports/schedule | 11,441 | 21 | única | 2024-01-13 a 2026-11-14 | 0.2 MB | 2026-11-23T13:20 |
| `raw.les_standings_matches` | lolesports/standings_matches | 33,929 | 19 | única | — | 0.4 MB | 2026-11-16T14:53 |
| `raw.les_standings_rankings` | lolesports/standings_rankings | 4,457 | 14 | única | — | 0.1 MB | 2026-11-16T04:02 |
| `raw.les_standings_raw` | lolesports/standings_raw | 514 | 3 | única | — | 0.7 MB | 2026-11-28T17:50 |
| `raw.les_team_players` | lolesports/team_players | 5,436 | 5 | única | — | 0.1 MB | 2026-11-27T12:52 |
| `raw.les_teams` | lolesports/teams | 1,587 | 7 | única | — | 0.1 MB | 2026-11-21T11:30 |
| `raw.les_tournaments` | lolesports/tournaments | 520 | 6 | única | 2011-06-18 a 2027-07-31 | 0.0 MB | 2026-11-26T12:56 |
| `raw.mk_champions` | meraki/champions | 171 | 152 | única | — | 0.7 MB | 2026-11-16T03:59 |
| `raw.mk_champions_history` | meraki/champions_history | 171 | 153 | única | 2026-11-16 a 2026-11-16 | 0.7 MB | 2026-11-16T03:59 |
| `raw.mk_items` | meraki/items | 320 | 42 | única | — | 0.1 MB | 2026-11-16T03:59 |
| `raw.mk_items_history` | meraki/items_history | 320 | 43 | única | 2026-11-16 a 2026-11-16 | 0.1 MB | 2026-11-16T03:59 |
| `raw.odds_calls` | oddspapi/calls | 40 | 5 | 2026-11 | — | 0.3 MB | 2026-11-28T17:50 |
| `raw.odds_fixtures` | oddspapi/fixtures | 14 | 14 | única | 2026-11-14 a 2026-11-30 | 0.0 MB | 2026-11-28T17:49 |
| `raw.odds_historical_odds_raw` | oddspapi/historical_odds_raw | 1 | 4 | única | 2026-11-16 a 2026-11-16 | 0.3 MB | 2026-11-16T22:25 |
| `raw.oe_matches` | oracles_elixir/matches | 1,237,800 | 165 | 2014–2026 (13) | 2014-01-14 a 2026-11-14 | 205.4 MB | 2026-11-16T02:15 |
| `raw.ps_leagues` | pandascore/leagues | 136 | 5 | única | — | 0.1 MB | 2026-11-23T13:19 |
| `raw.ps_matches_past` | pandascore/matches_past | 48,036 | 26 | única | 2014-06-01 a 2026-11-21 | 12.3 MB | 2026-11-28T12:02 |
| `raw.ps_matches_upcoming` | pandascore/matches_upcoming | 7 | 26 | única | 2026-12-05 a 2026-12-06 | 0.0 MB | 2026-11-28T12:02 |
| `raw.ps_players` | pandascore/players | 9,917 | 11 | única | — | 0.8 MB | 2026-11-23T21:49 |
| `raw.ps_series` | pandascore/series | 871 | 11 | única | — | 0.2 MB | 2026-11-23T13:19 |
| `raw.ps_state` | pandascore/state | 1 | 2 | única | — | 0.0 MB | 2026-11-16T23:01 |
| `raw.ps_team_players` | pandascore/team_players | 2,593 | 4 | única | — | 0.0 MB | 2026-11-23T21:43 |
| `raw.ps_teams` | pandascore/teams | 1,949 | 7 | única | — | 0.3 MB | 2026-11-23T21:43 |
| `raw.ps_tournaments` | pandascore/tournaments | 2,210 | 16 | única | — | 7.9 MB | 2026-11-23T21:42 |
| `raw.pskill_game_events` | pandaskill/game_events | 1,884,740 | 8 | única | — | 14.5 MB | 2026-11-17T00:18 |
| `raw.pskill_game_metadata` | pandaskill/game_metadata | 37,459 | 9 | única | 2019-09-15 a 2024-09-14 | 0.6 MB | 2026-11-17T00:17 |
| `raw.pskill_game_players_stats` | pandaskill/game_players_stats | 374,554 | 28 | única | — | 9.3 MB | 2026-11-17T00:18 |
| `raw.pskill_pscores` | pandaskill/pscores | 373,880 | 3 | única | — | 2.1 MB | 2026-11-17T00:18 |
| `raw.pskill_skill_ratings` | pandaskill/skill_ratings | 373,880 | 20 | única | — | 37.3 MB | 2026-11-17T00:18 |
| `raw.gcd_contracts` | riot_gcd/contracts | 741 | 13 | única | — | 0.0 MB | 2026-11-26T12:55 |
| `raw.gcd_contracts_history` | riot_gcd/contracts_history | 2,014 | 14 | única | 2026-11-17 a 2026-11-26 | 0.1 MB | 2026-11-26T12:55 |
| `raw.gcd_sheets` | riot_gcd/sheets | 5 | 3 | única | — | 0.0 MB | 2026-11-25T13:15 |

**Total:** 11,549,415 linhas, 453.0 MB em Parquet.
