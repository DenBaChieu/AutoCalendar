# AutoCalendarFrontend  
A web app that uses AI to convert your schedule into a Google Calendar.  

---

## Features  
- Converts raw schedules into events using **Gemini AI + prompt engineering**  
- Lets you **review and confirm** events before adding them  
- Creates a **new calendar** in your Google account to keep events separate  
- Supports filtering input (requires headers or indicators for event data)  

---

## How It Works  
1. Paste your schedule into the app.  
2. AI extracts dates, times, and event details.  
3. Review and confirm before adding to Google Calendar.  
4. Events are added to a newly created calendar in your Google account.  

---

## Privacy & Security  
- Backend is hosted on **Render**.  
- Your credentials are only temporarily stored (up to 15 minutes).  
- We only request the Google Calendar scope:  
  `https://www.googleapis.com/auth/calendar.app.created`  
  This limits access to only the new calendar created by the app.  

[Privacy Policy](https://denbachieu.github.io/PrivacyPolicies/AutoCalendarPrivacyPolicy)  
[Terms of Service](https://denbachieu.github.io/PrivacyPolicies/AutoCalendarToS)  

---

## Tech Stack  
- **Frontend:** Vite, React, Tailwind CSS  
- **Backend:** Python (Flask), hosted on Render  
- **AI:** Gemini AI  
- **API:** Google Calendar API  
