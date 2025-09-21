# SongSwipe
SongSwipe is an innovative playlist management app that enables users to rate songs from their Spotify playlists, highlight the tracks they truly enjoy, and generate personalized playlists. The app adds social and competitive elements, encouraging sharing, rating, and group engagement.

Target Audience

Spotify users, mainly teens and young adults, who manage large playlists and want to refine their listening experience and sharpen their musical taste.

Motivation

The idea was born from a common problem: people keep songs they “like but don’t love” in playlists. Research and user interviews showed this is widespread — there is no tool for conscious, engaging, and social filtering of personal playlists. Existing platforms like Deezer and SoundCloud also lack structured filtering or rating.

Technologies

Spotify Web API: OAuth 2.0 authentication, playlist retrieval, profile sync, recommendations, and playlist creation.

Firebase & Firestore: user management, permissions (Bronze / Premium / TopUser), saving ratings and group data.

Android: Java + XML, with advanced permissions (notifications, AlarmManager, background services).

Key Features

Login & Registration: connect with Spotify, sync playlists automatically.

SongSwipe: swipe right to keep, left to skip — inspired by Tinder.

Playlist Management: view, search, sort, and export curated playlists back to Spotify.

Groups & Competitions: join or create groups, rate songs together, compete on leaderboards.

User Profile: display synced Spotify data, update details, manage group participation (Premium+).

Notifications: alerts for invites, group activity, and new ratings.

Challenges

Spotify’s 100-track API limit → solved with pagination logic.

Playback restrictions → shifted focus to UI/UX design and gamified interaction instead of in-app streaming.

User engagement → swipe interface, group competition, and statistics for motivation.

Outcome

SongSwipe transforms playlist management from a passive activity into an interactive, fun, and social experience. It provides users with a practical tool to refine their musical taste while building stronger social connections through music.
