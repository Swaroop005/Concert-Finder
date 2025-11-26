🎤 Concert Finder Chatbot

An interactive AI-style concert finder chatbot built using HTML, CSS, and JavaScript.
It provides city-based concert suggestions, artist-based recommendations, and supports real-time concert data using an external API.

This project is designed with a modern UI, animated backgrounds that change according to the artist/city, and a smooth chat interface.

🌟 Features
🎯 Core Functionalities

💬 Interactive Chatbot UI

🏙️ City-based concert suggestions (Mumbai, Delhi, Bangalore)

🎵 Artist-based responses (Arijit Singh, Taylor Swift, Ed Sheeran, Dua Lipa, etc.)

🖼️ Dynamic background changes based on city/artist

🌈 Glassmorphism & gradient UI

📱 Fully responsive design

🔍 Real-time concert data support via API

🔗 Real-time Concert API Integration

To enable live concert data from your preferred API (Ticketmaster, Bandsintown, Songkick etc.), the project includes:

async function fetchConcerts(city) {
  const apiKey = "YOUR_API_KEY_HERE";  
  const url = `https://app.ticketmaster.com/discovery/v2/events.json?apikey=${apiKey}&city=${city}`;

  const response = await fetch(url);
  const data = await response.json();

  return data;
}


You can expand this to show dates, venues, artists, and ticket links.

🛠️ Technologies Used
Frontend

HTML5 → Structure of the chatbot

CSS3 → UI design, gradients, animations, glassmorphism

JavaScript → Chat logic, event handling, background switching

API (Optional)

Ticketmaster API

Bandsintown API

Songkick API

📁 Project Structure
/concert-finder-chatbot
│── index.html
│── style.css  (optional if separated)
│── script.js  (optional if separated)
│── README.md

📸 Screenshots

(Add screenshots like)

Chatbot popup

City-based backgrounds

Artist UI changes

Example:

![Chatbot Screenshot](images/chatbot.png)

🚀 How to Run

Download or clone this repository

git clone https://github.com/your-username/concert-finder-chatbot.git


Open index.html in any browser.

Chat with your Concert Buddy!

🧩 How It Works

User enters a message

JavaScript checks for keywords (city or artist)

Background + UI changes dynamically

Matching response is displayed

If enabled, API fetches live concert data

🎨 UI Features

Modern gradient theme

Floating chat button

Glass-style chatbot window

Smooth transitions

Mobile friendly

🤖 Future Enhancements

⏳ Chatbot memory (previous responses)

📍 GPS-based concert suggestions

🎟️ Ticket booking integration

🧠 AI model integration for smart responses

📅 Upcoming concerts calendar
