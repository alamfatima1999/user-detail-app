# user-detail-app
### Stage 1

You're going to build a web app using create-react-app and react-router.

Using the user data from the randomUser API, you will render a list of 10 users.

1. Each user's name will be displayed on the list.
2. Clicking on a user's name routes you to the corresponding user detail page, which consists of the user's photo, name, email address, state, and country.

**Data to display on the User Detail Page:**
- Photo
- Name
- Email
- Location (state & country)

**API URL:** `https://randomuser.me/api/`
**Query Param:** `results=10`

**Additional:** 
Consider how you can optimize the code.


### Stage 2

- Implement state management.
- Fetch the set of users only once. No network call when we move between pages.
- Add a button on the details page to mark a user as a favorite.
- On the home page, highlight favorite users with special CSS.


