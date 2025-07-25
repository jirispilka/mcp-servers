## Weather MCP Server

A Model Context Protocol server providing weather data from the Open-Meteo API.

**About this MCP Server:** To understand how to connect to and utilize this MCP server, please refer to the official Model Context Protocol documentation at [mcp.apify.com](https://mcp.apify.com).

### Available Tools
- `get_weather` - Get current weather for a city.
  - `city` (string, required)
- `get_weather_by_datetime_range` - Get weather for a city between dates.
  - `city` (string, required)
  - `start_date` (string, required)
  - `end_date` (string, required)
- `get_current_datetime` - Get the current time in a timezone.
  - `timezone_name` (string, required)

### License

mcp-weather-server is licensed under the MIT License. For details, see the original repository.

## 🚩 Claim this MCP server
All credits to the original authors of <https://github.com/isdaniel/mcp_weather_server>
To claim this server, please write to [ai@apify.com](mailto:ai@apify.com).

## Documentation reference
To learn more about Apify and Actors, take a look at the following resources:
- [Apify SDK for JavaScript documentation](https://docs.apify.com/sdk/js)
- [Apify SDK for Python documentation](https://docs.apify.com/sdk/python)
- [Apify Platform documentation](https://docs.apify.com/platform)
- [Join our developer community on Discord](https://discord.com/invite/jyEM2PRvMU)
