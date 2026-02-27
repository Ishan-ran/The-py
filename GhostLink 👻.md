**GhostLink 👻**

GhostLink is a stealth chat application concealed behind a functional, responsive educational webpage about Hydropower. To the average visitor, it appears to be a standard academic article. However, executing a specific hidden trigger reveals a real-time, Firebase-powered messaging platform complete with admin controls, media sharing, and custom visual Easter eggs.

**Features**

**The Decoy (Frontend)**

- Fully styled, responsive mock-article on "Hydropower."
- Sticky navigation, sidebars, and realistic data tables to maintain the illusion.
- Functional external links and hover states.

**The App (GhostLink Chat)**

- **Real-Time Messaging:** Powered by Firebase Firestore for instantaneous chat updates.
- **Rich Media Support:** Send text, image attachments, and record audio/voice notes directly in the chat.
- **Customization:** Upload custom chat wallpapers or profile pictures.
- **Live Indicators:** "Typing..." bubbles and read receipts (✓, ✓✓).
- **Admin "God Mode":** Dedicated dashboard for user management, allowing the admin to view all connections and delete users.

**How to Access the Secret App**

1. Scroll to the very bottom of the educational page.
1. Locate the footer button labeled **"Get Citation / Chat with AI"**.
1. **Triple-click** the button rapidly (within 400ms).
1. The screen will transition to the hidden GhostLink login portal. *(Note: A single click simply redirects to Google Gemini to maintain the facade).*

**Logins & Easter Eggs**

The app features several hardcoded login triggers that initiate custom CSS/JavaScript animations:

- **Sylus Effect:** Logging in with the username kaneshiro  and password 123456780 triggers a Tenor GIF overlay and custom text.
- **Goofy Effect:** Logging in with goofy triggers a unique, cycling flirty text animation pulled from a database of custom lines.
- **Standard Guests:** Entering any other password will auto-register a new guest account or log back into an existing one based on that string.

## **Built With**
- **HTML5 / CSS3:** Vanilla structural styling and keyframe animations.
- **JavaScript (ES6):** Frontend logic, media recording, and trigger handling.
- **Firebase v9 (Web Modular API):** Authentication, Cloud Firestore (Database), and Storage.

