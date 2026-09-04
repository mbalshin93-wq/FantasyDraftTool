# FantasyDraftTool

**Status:** Private development / prototype  
**Product name:** Working title

FantasyDraftTool is a pre-launch fantasy football web application exploring draft preparation, connected-league intelligence, roster analysis, waiver/FAAB strategy, historical league analysis, and in-season decision support.

## What we're building

- League-aware rankings and projections
- ADP and market analysis
- Player research, schedule, risk, and range-of-outcomes tools
- Connected-league scoring and roster analysis
- Draft preparation and draft history intelligence
- Waiver / FAAB and roster-management tools
- Historical league and manager tendency analysis

## Yahoo Fantasy integration

Yahoo Fantasy Football is planned as the first connected-league platform.

The intended production integration uses the official Yahoo Fantasy Sports API with OAuth 2.0 and **read-only** access authorized by each user. FantasyDraftTool is intended to retrieve only the league data needed to provide league-specific analysis, such as:

- league metadata and settings
- scoring and roster configuration
- teams and managers
- standings and rosters
- draft results
- transactions and waiver activity where available
- player ownership / free-agent status
- matchups, scoreboards, and fantasy results

FantasyDraftTool will not submit roster changes, waiver claims, trades, lineup changes, or draft picks to Yahoo.

## Development stage

The application is currently being developed and tested privately. A public consumer launch may be pursued in the future if development is successful.

No production Yahoo API credentials are stored in this repository.

## Yahoo attribution

Fantasy data provided by Yahoo Fantasy where applicable.
