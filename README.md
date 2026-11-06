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
| `draw_tarot_cards` | Draw tarot cards for a question using a chosen spread. |
| `get_birth_chart` | Calculate a Western natal birth chart (tropical zodiac, Placidus houses): |
| `get_transits` | Show where the planets are on a given date and the tightest aspects they make to a natal birth chart… |
| `get_daily_cosmic_weather` | Get the planetary atmosphere for any date (default today): |
| `check_compatibility` | Analyze multi-layered compatibility between two people using Pythagorean Life Path numerology and Western… |
| `find_healing_frequency` | Suggest Solfeggio and tuning frequencies (eg 528 Hz, 432 Hz) for a listening or meditation goal such as… |
| `calculate_numerology` | Calculate Pythagorean numerology numbers (life path, expression, soul urge, karmic debt) from a full birth… |
| `plan_my_personal_year` | Calculate the numerology personal year for a calendar year and the personal month theme for each of its 12… |
| `build_habit_stack` | Build a structured 30-day habit plan from a proven habit framework that fits the daily time budget (habits… |
| `check_my_chakras` | A three-question reflective chakra check that suggests which energy center to focus on, with its traditional… |
| `find_my_crystals` | Match crystals to an intention using a short questionnaire (life focus, challenge, chakra, placement, style). |
| `search_yinyang_guides` | Search Yinyang Masters in-depth guides on habits, productivity, manifestation, crystals, chakras, astrology… |
| `tuvi_chart_vn` | Lập lá số Tử Vi an sao thuần Việt đầy đủ 12 cung (Mệnh, Phụ, Phúc, Điền, Quan, Nô, Di, Tật, Tài, Tử, Phu Thê… |
| `bazi_chart` | Lập lá số Bát Tự Tứ Trụ: |
| `tuvi_horoscope` | Tính vận hạn Tử Vi: |
| `karma_chart_read` | Luận giải Nghiệp Lực đa tầng kết hợp Tử Vi & Bát Tự: |
| `karma_diagnose` | Chẩn đoán căn nguyên nghiệp quả từ mô tả tự nhiên của người dùng (khó khăn tài chính, hôn nhân, sức khỏe, oan… |
| `decode_angel_number` | Interpret the spiritual symbolism and practical guidance behind angel numbers (111, 444, 777...), master… |
| `write_manifestation_script` | Create an intentional manifestation ritual script tailored to a specific life focus (wealth, career… |
| `build_productivity_plan` | Construct a rigorous daily productivity matrix tailored to your specific profession (software engineer… |
| `find_guardian_angel` | Identify your lifelong Guardian Angel from the classical 72 Kabbalistic Angels (Shem HaMephorash tradition)… |

## Notes

Results are for reflection and entertainment. They are not medical, legal or financial advice.

This repository holds listing metadata only (`server.json`, `glama.json`).
