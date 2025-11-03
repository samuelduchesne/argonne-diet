# Argonne Jet-Lag Planner

A web-based planning tool for the **Argonne Anti-Jet-Lag Diet**, helping travelers minimize jet lag through strategic eating patterns.

## What is This?

The Argonne Jet-Lag Planner is a single-page web application that generates a personalized 4-day FEAST/FAST eating schedule based on your travel itinerary. By following this diet protocol in the days leading up to your trip, you can significantly reduce jet lag symptoms and adjust more quickly to your destination time zone.

## What is the Argonne Anti-Jet-Lag Diet?

The Argonne Anti-Jet-Lag Diet is a scientifically-developed protocol created by researchers at **Argonne National Laboratory** in the 1980s. The method uses alternating feast and fast days, combined with strategic caffeine timing, to help reset your body's circadian rhythm before travel.

### How It Works

The diet works by:

1. **Anchoring to destination breakfast** - Your body adjusts to the meal timing at your destination
2. **FEAST/FAST cycling** - Alternating between high-calorie and low-calorie days manipulates your metabolism
3. **Strategic caffeine timing** - Caffeine is restricted to specific windows that vary by travel direction (east vs. west)
4. **4-day preparation** - Starting four days before your destination breakfast time

### The Protocol

- **Day 1 (4 days before)**: FEAST - High-protein breakfast & lunch, high-carb dinner
- **Day 2 (3 days before)**: FAST - Light meals (salads, soups, fruits, juices)
- **Day 3 (2 days before)**: FEAST - High-protein breakfast & lunch, high-carb dinner
- **Day 4 (Travel day)**: FAST - Light meals until arrival
- **Arrival**: Break the fast with a high-protein breakfast at destination breakfast time

**Caffeine Rules:**

- Days 1-3: Only between 15:00-17:00 (local time)
- Day 4 (Eastbound): 18:00-23:00
- Day 4 (Westbound): Morning (08:00-12:00)
- No alcohol on the plane

## Features

✈️ **Automatic Schedule Generation** - Enter your trip details and get a complete 4-day plan

⏰ **Real-Time Countdown** - Live countdown to your destination breakfast (updates every second)

💾 **Plan Persistence** - Your plan is automatically saved and restored when you return to the site

🔄 **Auto-Expiration** - Saved plans automatically expire after your arrival time

🗑️ **Reset Function** - Manually clear your saved plan with the Reset button

🌍 **Global Time Zone Support** - Works with all IANA time zones

📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile

🎨 **Auto Dark/Light Theme** - Automatically matches your system preferences

♿ **Accessible** - Full keyboard navigation and screen reader support

## How to Use

1. **Visit the app**: [Your GitHub Pages URL here]
2. **Select time zones**: Choose your origin and destination time zones
3. **Enter travel times**: Input your departure and arrival date/times
4. **Set breakfast time**: Choose your preferred breakfast time at the destination (e.g., 07:30 or 08:00)
5. **Compute plan**: Click "Compute plan" to generate your personalized schedule
6. **Bookmark it**: Your plan is automatically saved - you can close the page and return anytime
7. **Follow the plan**: Start the FEAST/FAST cycle 4 days before your trip
8. **Reset when done**: After your trip, use the Reset button to clear your saved plan and start planning a new trip

### Plan Persistence

- Plans are automatically saved to your browser's localStorage
- When you return to the site, your plan is restored automatically
- Plans expire automatically after your arrival time
- Use the "Reset" button to manually clear your plan and start fresh
- Your data never leaves your browser - everything is stored locally

## Live Demo

This project is deployed as a GitHub Page and can be accessed at: [Add your GitHub Pages URL]

## Technical Details

- **Pure HTML/CSS/JavaScript** - No build process required
- **Luxon.js** - For robust date/time calculations across time zones
- **Single-page application** - Everything runs client-side
- **localStorage API** - Plans are saved locally in your browser
- **No data collection** - All calculations happen in your browser, nothing sent to any server
- **Privacy-first** - Your travel details never leave your device
- **Progressive enhancement** - Works without JavaScript for basic content

## Deployment

This app is designed to be deployed on GitHub Pages:

1. Push to the `main` branch
2. GitHub Actions automatically deploys via `.github/workflows/static.yml`
3. Site is available at `https://<username>.github.io/<repo-name>/`

## Scientific Background

The Argonne Anti-Jet-Lag Diet was developed by Dr. Charles F. Ehret and his team at Argonne National Laboratory. The research demonstrated that strategic manipulation of eating patterns, combined with light exposure and caffeine timing, can help reset circadian rhythms.

### References

- **Argonne National Laboratory** - Original research institution
- Ehret, C. F., & Scanlon, L. W. (1983). *Overcoming Jet Lag*. Berkley Books.
- [Argonne Lab News Release](https://www.anl.gov/article/how-to-beat-jet-lag)
- [Wired: The Jet Lag Diet](https://www.wired.com/story/argonne-diet-jet-lag/)
- [Anti-Jet-Lag Diet Overview](http://www.antijetlagdiet.com/)

## Disclaimer

This tool provides information based on the published Argonne Anti-Jet-Lag Diet protocol. It is not medical advice. Consult with a healthcare professional before making significant changes to your diet or if you have specific health concerns.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

See [LICENSE](LICENSE) file for details.

---

**Built for travelers, by travelers** ✈️🌍
