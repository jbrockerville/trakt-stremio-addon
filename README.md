# Trakt Sync Stremio Addon

A Stremio addon for syncing watched states and ratings with Trakt.tv.

## Features
- ✅ Mark movies/episodes as watched on Trakt
- ❌ Mark movies/episodes as unwatched
- 📅 Mark entire seasons as watched
- ⭐ Rate movies/episodes/series
- 👤 Option to show/hide username in addon name
- 🔐 OAuth authentication with Trakt
- 🌐 Web installation support

## Deployment Options

### 1. Docker (Recommended for Self-Hosting)
```bash
# Clone repository
git clone https://github.com/yourusername/trakt-sync-rating-addon.git
cd trakt-sync-rating-addon

# Copy example override file for local development
cp docker-compose.override.yml.example docker-compose.override.yml

# Edit environment variables in docker-compose.override.yml if needed

# Start with Docker Compose
docker-compose up -d
