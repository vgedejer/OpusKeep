# OpusKeep

## Napkin Notes

### Key Features

- **Reading Goals & Challenges**
    - Reading goal quest-lines with custom quests (e.g., finish x book by y date, complete genre or series specific challenges, BookTok challenge integration)
    - Reading challenge tracker with support for different mediums (audio, graphic novels/manga/manhwa, traditional print, eBooks)
    - Genre-specific tracking and shelves with customizable buckets (e.g., fantasy to-read, romance to-read)
- **Book Management & Organization**
    - Purchased books tracker (separate from To-Read list)
    - Manually add books not in database
    - Photo recognition or ISBN/barcode scanner for easy book additions
    - Privacy controls for shelving books (select which books are public or hidden)
- **Reviews & Ratings**
    - 6-star personal review system (displayed as 5 stars globally to avoid skewing ratings)
    - Automatic shelf allocation based on ratings
- **Customization & User Experience**
    - Customizable aesthetic preferences (customizable color palettes, widget customization, multiple design options)
    - App blocker feature to encourage productivity during reading sessions

### MVP Focus

- Home Page is specifically for tracking and reading recommendations
    - Book Keeping Tab for readers to manage their books
    - Social Tab for readers to interact in their own niches
    - Settings Tab for preferences
- Mobile First - React Native
    - Built with a (Web) SaaS in mind for dual platform
- Sleek UI - I like how Fable and StoryGraph looks, but less generic looking
    - Hybrid platform - android users don’t want an Apple-esque UI on their phone
    - Prioritize uniqueness in the UX and sleekness of the UI (i really like the look and feel of Notion ironically)
- Modular Home Dashboard

### Stretch Goals and Further

- Maybe Agentic AI capabilities?
    - Look into Amazon’s AI Kindle thingy
    - Agentic AI will only “train” itself on user’s uploaded books/library (will be stored in a database)?
    - Id love to make this into a way that the AI is locally accessed so its not actually training OpenAI/Anthropic/Gemini models- but i don’t think thats possible?
- Buddy Reading capabilities (inspired by StoryGraph)
- Offer a Pro version for full algorithmic capabilities maybe? Will have to see what else to keep behind a paywall for profit
- I like the idea of hiding easter eggs in the settings (a game, a UI change → different color, style, font, etc.)
- Connect to Spotify maybe?? Or have another app like [stats.fm](http://stats.fm) to load csv data from both Spotify and Radiance
    - Use (optional) AI to make book recommendations from a user’s song library or playlist (vice versa would also be cool)
- Spotify Wrapped Type of Data Analytics
- Algorithmic Recommendations
    - Not Agentic/Gen-AI powered
    - Look into basic ML/DS algorithms for data analysis
    - Specifically to help readers move between genres
        - Manga reader wants to go into books → gets a print recommendation based on their manga interests (vice versa)
- Maybe make an entire app ecosystem? Separate apps under the same account for the following media types:
    - Scale to have a game backlog tracker
    - Letterbox’d competitor
        - Anime specific app or possibly a tab specific for anime vs film (see Instagram Following vs Favorites selection for home feed)
- Reading Comprehension Feature?
    - Help readers improve their media literacy
    - AI powered? maybe not? Maybe user created/submitted questions or worksheets
- Setup an educational version - no AI Summaries, but includes discussion boards for classroom use.
    - Basically a book club but for the classroom (helps track reading progress of each student)
        - Teacher can see the students’ progress
---
