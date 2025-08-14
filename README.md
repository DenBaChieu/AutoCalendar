# AutoCalendarFrontend
A website that uses AI to convert your schedule into your Google's Calendar

Privacy policy: https://denbachieu.github.io/PrivacyPolicies/AutoCalendarPrivacyPolicy

Terms of service: https://denbachieu.github.io/PrivacyPolicies/AutoCalendarToS

Using Gemini 2.5 Flash-Lite combined with prompt engineering, your input will be converted into events. You then can check the events and confirm to add it to a newly created calendar in your Google's Calendar.

You can filter out the input but make sure you still include the table's headers or any indication for what each data means.

Backend is hosted on Render. Your credentials is only temporarily stored on the backend for at most 15 minutes.

Our Google's Calendar scope is only "https://www.googleapis.com/auth/calendar.app.created" which means that we are only allowed to create a "calendar" on your Google's Calendar then add, edits, remove events on that "calendar" specifically.

This website was coded using Vite + React + Tailwind. Backend is coded in Python using Flask.
