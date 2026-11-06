# Yinyang Masters MCP

Remote MCP server for tarot, Western astrology, numerology, Vietnamese Tu Vi, Bazi and in-depth guides on habits, productivity and manifestation, from [Yinyang Masters](https://yinyangmasters.com).

- **Endpoint:** `https://mcp.yinyangmasters.com/api/mcp/claude` (streamable HTTP)
- **Auth:** none, free to use
- **Languages:** English and Vietnamese

## Connect

Claude Desktop, Cursor, Windsurf or any client that supports remote MCP servers: add a remote server with the endpoint above.

```json
{
  "mcpServers": {
    "yinyang-masters": {
      "url": "https://mcp.yinyangmasters.com/api/mcp/claude"
    }
  }
}
```

## Tools

| Tool | What it does |
|---|---|
| `draw_tarot_cards` | Draw tarot cards for a question with a chosen spread. |
| `get_birth_chart` | Western natal chart: Sun, Moon, Rising, planets and houses. |
| `get_transits` | Planet positions on a date and their tightest aspects to a natal chart. |
| `get_daily_cosmic_weather` | Moon phase and planetary atmosphere for any date. |
| `check_compatibility` | Compatibility of two people from numerology and astrology. |
| `find_healing_frequency` | Solfeggio and tuning frequencies for a listening or meditation goal. |
| `calculate_numerology` | Pythagorean numerology numbers from a full birth name and date. |
| `plan_my_personal_year` | Numerology personal year and the 12 monthly themes. |
| `build_habit_stack` | 30-day habit plan that fits your daily time budget. |
| `check_my_chakras` | Three-question reflective chakra check. |
| `find_my_crystals` | Match crystals to an intention with a short questionnaire. |
| `search_yinyang_guides` | Search in-depth guides on habits, manifestation, crystals and astrology. |
| `tuvi_chart_vn` | Vietnamese Tu Vi chart with all 12 palaces. |
| `bazi_chart` | Bazi Four Pillars chart. |
| `tuvi_horoscope` | Tu Vi 10-year, yearly and monthly cycles for a chosen date. |
| `karma_chart_read` | Multi-layer karma reading combining Tu Vi and Bazi. |
| `karma_diagnose` | Karma themes from a described life situation. |
| `decode_angel_number` | Symbolism and guidance behind angel and master numbers. |
| `write_manifestation_script` | Manifestation ritual script for a chosen life focus. |
| `build_productivity_plan` | Daily productivity plan tailored to a profession. |
| `find_guardian_angel` | Guardian Angel from the 72 angels of the Kabbalistic tradition. |

## Notes

Results are for reflection and entertainment. They are not medical, legal or financial advice.

This repository holds listing metadata only (`server.json`, `glama.json`).
