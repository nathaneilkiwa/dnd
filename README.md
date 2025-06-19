🐉 DnD API Explorer
A simple web app that lets users explore Dungeons & Dragons spells, view dragon images, and read detailed descriptions using a DnD-themed API integration.

<sub>Interface showing a spell search and dragon description card.</sub>

🧰 Features:
🔮 Search and display DnD spells with casting details

🐉 Fetch and render dragon images

📜 Display dragon descriptions, including lore and stats

🎨 Themed, responsive UI with a fantasy RPG vibe

🔁 Easy navigation between multiple spells or creatures

⚙️ How It's Made
Tech Stack:

Frontend: HTML and  JavaScript


API: DnD 5e API for spell and monster data

Image Source: [Optional dragon image API or static assets]

Implementation Highlights:

Async fetch() calls to retrieve spell and dragon data

Modular JS functions for API handling and DOM updates

Error handling for invalid queries or network issues

Dynamic rendering of spell attributes like level, school, and components

Dragon cards show name, type, image, and lore description

🚀 Optimizations:

Cached API results to minimize repeat requests

Lazy-loaded images for performance

Abstracted fetch logic for scalability (e.g., support for items, monsters)

📚 Lessons Learned:
While building this project, I learned how to:

Work with public APIs and structure requests for nested data

Handle dynamic, unpredictable API structures gracefully

Build reusable components for rendering cards and descriptions

