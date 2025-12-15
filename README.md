Spotify Music Streaming Analysis
Team B03 - Kaixin Gao, Kara Liao, Rita Feng, Yanlun Li, Ahrar Karim
Executive Summary
This report is focused on combining Spotify Top 200 charts, audio features, and listening
patterns to understand factors contributing to music popularity as well as music’s longevity in
charts. A structured SQL workflow and Tableau dashboards are designed to standardize track
identifiers, eliminate duplicates, and standardize data to output an analytically useful data set.
Preliminary findings suggest that a few popular tracks across the globe account for most of the
plays, as well as that popular tracks generally have a mid-tempo, low-to-moderate, and
emotionally neutral attribute set. We also observe meaningful differences in lifecycle patterns
across regions and between explicit versus clean versions. These insights directly inform
strategic decisions on release planning, playlist positioning, and regional marketing, which are
further developed in the conclusions and future steps.
Dashboard 1
Dashboard 2
Problem Statement:
This project evaluates the relationship between audio features, platform engagement metrics,
and track popularity across multiple Spotify datasets to understand what drives streaming
success. The analysis will:
• Identify audio feature patterns (danceability, energy, valence, tempo, acousticness) that
correlate with high popularity scores and streaming counts across various tracks
spanning multiple genres.
• Compare tracks and artist popularity varies across different geographic regions in the
Spotify dataset.
• Analyze temporal trends in music characteristics by tracking how audio features and
popularity metrics have evolved over time, identifying specific patterns.
• Examine chart performance dynamics through rankings to understand streaming
velocity, chart longevity, and breakthroughs.
Motivation:
Understanding the quantifiable characteristics that drive music popularity offers actionable
insights for artists, producers, and streaming platforms to optimize content strategy and
audience engagement. With streaming revenue now dominating the music industry, data-driven
Analysis of audio features and cross-platform metrics can reveal what makes tracks resonate
with global audiences and how musical preferences evolve over time.
Conclusion
Actions:
• Promote tracks with balanced/neutral moods and mainstream pop-feature profiles,
which consistently show strong global popularity.
• Highlight globally dominant artists and cross-regional hits to maximize international
reach and playlist performance.
• Invest in artists with strong brand presence rather than increasing release frequency, as
output volume has little effect on popularity.
• Prioritize tracks with stable chart longevity for core playlists, since steady performers
anchor long-term engagement.
• Use regional insights (e.g., markets favoring local artists or high-energy music) to tailor
localized playlisting and marketing strategies.
• Identify upward-transitioning tracks (Medium→High) and promote them early to capture
rising momentum.
Risks/Limitations:
• Results may differ significantly across genres, which were not separately analyzed.
• Popularity and streaming patterns can be influenced by label promotion, catalog age, or
social media trends that are not in the dataset.
• Spotify popularity scores are partly static; monthly transitions were approximated using
streams.
• Regional data coverage varies, which may skew country-level comparisons.
• Audio features explain only part of listener behavior; cultural and contextual factors are
not captured.
Next Step:
• Perform genre-level analyses to compare popularity drivers across pop, hip-hop, EDM,
and other styles.
• Create an ML Model to predict track lifecycle stages across regions.
• Build transition matrices or Sankey diagrams to visualize tier movement patterns over
time.
• Incorporate external data (TikTok, YouTube, playlist placement) to improve hit-prediction
accuracy.
