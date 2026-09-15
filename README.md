# Who gets a bus on Shabbat

Interactive map comparing Israel's Shabbat bus licenses (traffic regulation 386א) with the
timetables actually run on Friday 29 and Saturday 30 May 2026. Static page: `index.html` plus
`map_data.json` (lines, hospitals, localities) and `vectormap.json` (OpenStreetMap / Natural
Earth basemap). Method, limits and sources are on the page itself.

Built from the `reg386a` analysis pipeline; regenerate `map_data.json` with
`python -m src.analyse.map_data` there. © OpenStreetMap contributors (ODbL); Natural Earth (public domain);
timetables: Israel Ministry of Transport GTFS; license list: Ministry of Transport FOI release, Nov 2025.
