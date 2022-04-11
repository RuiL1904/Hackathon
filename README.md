<img align = "left" width="100" height = "100" src = "/frontend/static/favicon.png">

# TimeIt - Making event-going simple
</br>

## Disclaimer:
This project was developed during an Hackathon in which we placed **second** 🏆.

### Problem:
- Events have a lot of simultaneous performances;
- It's hard and time consuming to choose what to go to;
- The average consumer might feel overwhelmed and may be less likely to participate in events due to the tedious process.

### Solution:
- Fast, simple and reliable solution;
- Accurate and personalized;
- Relies on a user's answer to a form to create the best possible schedule.

### How it works:
- Event organizer registers the event on our website;
- The schedules' data is converted to JSON and sent to our database trough the API;
- An event ID is created and the tags for that event are stored;
- When a user wants to fill out the form, the API sends the tags back to the website;
- The user answers the form according to their preferences;
- The form asnwers are converted to JSON and sent back to the API to calculate the best schedule.

### Technologies used:
- **Frontend**: Svelte (SvelteKit);
- **Backend**: Python (FastAPI and MongoDB).
