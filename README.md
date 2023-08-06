# Seriium

## Mobile Application for Tracking TV Series

The Seriium mobile application was created during college as a project for the course **Mobile Application Programming**.

The application serves the purpose of keeping track of TV series, allowing the user to monitor where they left off with watching.

The project was developed in Android Studio, and **Java** was chosen as the programming language with **Firebase** as the database. The application incorporates knowledge of using activities, adapters, fragments, listeners, model creation, and network usage.

[![My Skills](https://skills.thijs.gg/icons?i=androidstudio,java,firebase)](https://skills.thijs.gg)

**RecyclerView** is used for listing series, seasons, and episodes. For fetching series data, **Retrofit** is used, which connects to the [EPISODATE API](https://www.episodate.com/api).

The app includes _sign-in and registration_ functionalities that work through Firebase and require email confirmation for profile verification.

---

### Once signed in, the user can:

- View their list of TV series.
- Search for TV series.
- View details of each TV series.
- Add and remove TV series from their list.
- Mark and unmark watched seasons and episodes.
- Access rich statistics.
- View their profile details.
- Modify user data for their profile.

---

### Project Setup

To run the project, you need to create your own Firebase database. Then, paste the obtained connection data into `app/build/generated/res/google-services/debug/values.xml`.
