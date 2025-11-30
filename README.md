# Bluesky Posts Scraper

![banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/bsky.png)

## What is the Bluesky Posts Scraper?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.21` |
| **Last Update** | Nov 30, 2025 |

---



The Bluesky Posts Scraper is a tool specifically developed to extract post data from Bluesky, a decentralized social networking platform. It allows users to access and analyze public posts, interactions, and metadata related to user activities on Bluesky. This scraper is ideal for research, analytics, and monitoring trends on the platform.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/U9JtSIIjR6gyldBIN/1aNK9hjHBQ7Hh3mkU-account-erstellen-bluesky.jpg" alt="Bluesky Posts Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/bluesky-posts-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


## What data can the Bluesky Posts Scraper extract?

The Bluesky Posts Scraper can pull various types of data from the platform, including:

- Post content
- Post IDs
- User IDs
- Timestamps of posts
- Engagement metrics (likes, retweets, replies)
- Media URLs (images, links)

## What use cases does the Bluesky Posts Scraper have?

- 📈 Trend analysis
- 🚀 Influencer tracking
- 📊 Social media research
- 🛠 Brand monitoring

## How to use the Bluesky Posts Scraper

1. Sign up for a free account on Apify
2. Navigate to the Bluesky Posts Scraper actor
3. Input your queries
4. Click Start and wait for the results
5. Export the data in your preferred format (JSON, CSV)

## 📥 Input

To run the actor, you'll need to input a search queries. This is required.

Along with the search queries, you can also specify the following optional parameters:

- `limit` - The maximum number of posts to scrape per query. Default is 100.
- `sort` - The sorting order for the posts. Options are `latest` or `top`. Default is `latest`.
- `since` - The date from which to start scraping posts. This is useful for scraping posts from a specific date.
- `until` - The date until which to scrape posts. This is useful for scraping posts until a specific date.
- `language` - The language of the posts to scrape. This is useful for filtering posts by language.
- `proxyConfiguration` - The proxy configuration to use for the request. This is useful for avoiding IP bans.

## 📤 Output

The scraped data is stored in the default dataset associated with the actor. Here’s an example of what each item in the dataset looks like:

```json
{
  "id": "bafyreibqjfx2ejvxkd3okjtodoyqvoyk7wuberwonsakdjv4yahp2lrn4a",
  "authorId": "did:plc:pc2aiklrpzwgsiq3fuohbui4",
  "authorName": "Keri Warbis",
  "authorUsername": "keriwarbis.bsky.social",
  "authorAvatar": "https://cdn.bsky.app/img/avatar/plain/did:plc:pc2aiklrpzwgsiq3fuohbui4/bafkreihgejbtckxrsgrba7ckx6mlsofe6nzvs4t2m54y2in6edcp65tlne@jpeg",
  "text": "Bit sunburnt from yesterday’s stint in the garden.\n\nBit hungover from Eurovision.\n\nAnother day of sun and entertaining ahead.\n\nSunday roast at The Grand will be happening to round of the day.",
  "images": [
    {
      "thumb": "https://cdn.bsky.app/img/feed_thumbnail/plain/did:plc:pc2aiklrpzwgsiq3fuohbui4/bafkreiejc6jc4z47urksbwn7owoyyi4o46ufi362e52bscl4bsjrj4izyq@jpeg",
      "fullsize": "https://cdn.bsky.app/img/feed_fullsize/plain/did:plc:pc2aiklrpzwgsiq3fuohbui4/bafkreiejc6jc4z47urksbwn7owoyyi4o46ufi362e52bscl4bsjrj4izyq@jpeg",
      "alt": "",
      "aspectRatio": {
        "height": 820,
        "width": 828
      }
    }
  ],
  "link": null,
  "primaryImage": "https://cdn.bsky.app/img/feed_fullsize/plain/did:plc:pc2aiklrpzwgsiq3fuohbui4/bafkreiejc6jc4z47urksbwn7owoyyi4o46ufi362e52bscl4bsjrj4izyq@jpeg",
  "createdAt": "2024-05-12T08:36:29.345Z",
  "langs": ["en"],
  "replyCount": 0,
  "repostCount": 0,
  "likeCount": 0,
  "url": "https://bsky.app/profile/keriwarbis.bsky.social/post/3kxkwdhu77o23"
}
```

## Why use the Bluesky Posts Scraper?

- ⚡️ **Efficient** - Quickly collects comprehensive post data across Bluesky.
- 🤖 **Automated** - Automates data collection, saving time and reducing manual effort.
- 🔄 **Regular Updates** - Regularly updated to ensure compatibility with the latest Bluesky platform changes.

## FAQ

- **What is Bluesky?**
  Bluesky is a decentralized social networking platform focused on fostering open and public conversations.

- **How to find posts on Bluesky?**
  You can search directly on Bluesky using hashtags or user profiles. For automated searches, the Bluesky Posts Scraper can be used.

- **Is scraping Bluesky posts legal?**
  Scraping public information is generally legal, but it’s important to respect user privacy and adhere to the platform's terms of use.

- **How much does it cost?**
  Pricing details are available at the top of this page, or you can visit the Apify Store page for more information.

## Related Scrapers by Lexis Solutions

👉 Check out our other scrapers:

- [Facebook User Scraper](https://apify.com/lexis-solutions/facebook-user-search-scraper)
- [Facebook Views (Watch) Scraper](https://apify.com/lexis-solutions/facebook-videos-watch-scraper)
- [Bluesky Users Scraper](https://apify.com/lexis-solutions/bluesky-users-scraper)

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: Google Transparency Center
