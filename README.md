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
| `get_birth_chart` | Calculate a Western natal birth chart (tropical zodiac, Placidus houses): Sun, Moon and Rising signs, planets in signs and houses, and the tightest major aspects. |
| `get_transits` | Show where the planets are on a given date and the tightest aspects they make to a natal birth chart (transit-to-natal aspects). |
| `get_daily_cosmic_weather` | Get the planetary atmosphere for any date (default today): Moon phase and illumination percentage, current Moon sign and element, retrograde planets, and major daily planetary aspects with resonant So |
| `check_compatibility` | Analyze multi-layered compatibility between two people using Pythagorean Life Path numerology and Western tropical Sun signs. |
| `find_healing_frequency` | Suggest Solfeggio and tuning frequencies (e.g. |
| `calculate_numerology` | Calculate Pythagorean numerology numbers (life path, expression, soul urge, karmic debt) from a full birth name and date of birth. |
| `plan_my_personal_year` | Calculate the numerology personal year for a calendar year and the personal month theme for each of its 12 months, from a date of birth. |
| `build_habit_stack` | Build a structured 30-day habit plan from a proven habit framework that fits the daily time budget (habits longer than the remaining minutes are left out and listed), phased in week by week with check-in days. |
| `check_my_chakras` | A three-question reflective chakra check that suggests which energy center to focus on, with its traditional theme, element, Solfeggio frequency, affirmation and associated crystal. |
| `find_my_crystals` | Match crystals to an intention using a short questionnaire (life focus, challenge, chakra, placement, style). |
| `search_yinyang_guides` | Search Yinyang Masters in-depth guides on habits, productivity, manifestation, crystals, chakras, astrology, numerology and sound frequencies. |
| `tuvi_chart_vn` | Lập lá số Tử Vi an sao thuần Việt đầy đủ 12 cung (Mệnh, Phụ, Phúc, Điền, Quan, Nô, Di, Tật, Tài, Tử, Phu Thê, Huynh Đệ), độ sáng chính tinh đắc miếu hãm, phụ tinh, Tuần, Triệt, Thân cư, Mệnh cư. |
| `bazi_chart` | Lập lá số Bát Tự Tứ Trụ: Can Chi 4 trụ (Năm, Tháng, Ngày, Giờ), Thập Thần, Tàng Can, Nạp Âm, Thần Sát và Thống kê Ngũ Hành vượng suy. |
| `tuvi_horoscope` | Tính vận hạn Tử Vi: Đại vận 10 năm, Lưu niên từng năm, Nguyệt vận từng tháng theo mốc ngày xem. |
| `karma_chart_read` | Luận giải Nghiệp Lực đa tầng kết hợp Tử Vi & Bát Tự: Suy ngược lá số ra nhân nghiệp đời trước, quả báo trổ trong kiếp này, thời điểm kích hoạt theo đại vận/lưu niên, và các pháp sám hối/hóa giải (Reme |
| `karma_diagnose` | Chẩn đoán căn nguyên nghiệp quả từ mô tả tự nhiên của người dùng (khó khăn tài chính, hôn nhân, sức khỏe, oan ức, việc lầm lỡ đã làm), truy nguyên nhân quả kinh điển và chỉ dẫn pháp hóa giải. |
| `decode_angel_number` | Interpret the spiritual symbolism and practical guidance behind angel numbers (111, 444, 777...), master numbers (11, 22, 33), and karmic debt numbers (13, 14, 16, 19). |
| `write_manifestation_script` | Create an intentional manifestation ritual script tailored to a specific life focus (wealth, career breakthrough, romantic love, inner peace, creative flow). |
| `build_productivity_plan` | Construct a rigorous daily productivity matrix tailored to your specific profession (software engineer, designer, product manager, healthcare, legal, accountant, teacher, entrepreneur, etc.) using pro |
| `find_guardian_angel` | Identify your lifelong Guardian Angel from the classical 72 Kabbalistic Angels (Shem HaMephorash tradition) and your Eastern Patron Bodhisattva (Bát Đại Bản Mệnh Phật) based on your birth date. |

## Notes

Results are for reflection and entertainment. They are not medical, legal or financial advice.

This repository holds listing metadata only (`server.json`, `glama.json`).
