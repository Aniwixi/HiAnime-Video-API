# HiAnime-Video-API
HiAnime Video API provides anime data, episode information, and video player integration for developers building anime streaming websites and applications. Easily retrieve anime details and integrate episode playback using simple API endpoints.

# HiAnime Video API

HiAnime Video API provides anime data, episode information, and video player integration for developers building anime streaming websites and applications.

## ✨ Features

- 📺 Retrieve anime catalog data.
- 🔎 Find anime information using AniList IDs.
- 🎬 Retrieve individual episode information.
- ▶️ Integrate the video player into anime websites.
- 🔗 Generate episode player links using anime IDs and episode numbers.
- 🛠️ REST API integration for developers.

## 🔗 Video Player

Generate a player URL using an anime ID and an episode number.

**URL Format:**

```text
https://aniwixi.xyz/{anilist_id}/{episode_number}
```

**Example:**

```text
https://aniwixi.xyz/21/1
```

In this example:
- `21` is the AniList anime ID.
- `1` is the episode number.

Replace these values to access a different anime episode.

## 📡 API Endpoints

**Base API URL:**

```text
https://prod.api.market/v1/api-player-anime/aniwixi
```

| Method | Endpoint | Description |
|---|---|---|
| GET | `/anime` | Retrieve anime catalog data |
| GET | `/anilist/{id}` | Retrieve anime information by AniList ID |
| GET | `/anilist/{id}/ep/{num}` | Retrieve information for a specific episode |

## 📖 Documentation

For API endpoint details, request examples, and integration instructions, visit the official documentation.

**[API Documentation](https://aniwixi.xyz/anime-api-documentation/)**

## 💻 Use Cases

HiAnime Video API can be used for:

- Anime streaming websites.
- Anime catalog applications.
- Episode listing systems.
- Video player integrations.
- Custom anime-related projects.

## 🌐 API Marketplace

Explore API access and available subscription plans on API.market.

**[View API Marketplace Listing](https://api.market/seller/api-player-anime/products/aniwixi)**

## ⚠️ Important Notes

- AniList IDs are used to identify anime titles in the example endpoints.
- Episode availability and returned data may vary.
- API access may be subject to usage limits and subscription requirements.
- Ensure that your use of the API and video content complies with applicable laws and copyright requirements.

## 📄 License

Check the repository's license before using, modifying, or redistributing this project.

---

**HiAnime Video API** — Anime streaming integration made simple.
