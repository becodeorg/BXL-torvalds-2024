# BeMovies

---

**Helloooooowww !!!!**

How are you my friends ? Hope you're doing well and that you are excited for this new week !

We will be creating an app about movies ! In it, we will be able to see the latest releases, see them by genre, and search for any movie we want. We will be able to click on a movie and have some info about it, like :

- the year it was done
- Its rating
- A small description of the story
- Its genres
- Its cast

We are gonna be using the [TMDB API](https://developer.themoviedb.org/reference/intro/getting-started)

---

You can find the design [here](https://www.figma.com/file/jT6U3cABdKEUDRVTUJSbQd/BeMovies?type=design&node-id=0%3A1&mode=dev). There are several comments given instructions on it.

**ALSO :**

This will be the first "group" exercise we have. You will do it in duo (so... by groups of two).

The idea is :

- Each one will do the HTML/CSS(sass) part of it.
- Then, you'll hand over your HTML/CSS(sass) to the other one and you'll do the JS part for him/her.

- For that, create two repos with the other one being a collaborator.

This requires a good coordination between the duo to set how the html, css and js will work together.

- Before starting, analyze very carefully the project, all its requirements... do some tests together with postman and coordinate yourselves on how the html/css should look like in order to facilitate its JS integration.

- Each time an html and/or css should be changed, head over to your partner so **SHE/HE changes it**.

- Work with branches, merge them, etc.

- Why not use a trello and a SCRUM methodology ?

---

Here are the groups :

GROUP 1 : Timmy - Antoine M.
GROUP 2 : Antoine L. - Jeffrey
GROUP 3 : Eric - Anthony
GROUP 4 : Ilias - Elyes
GROUP 5 : Gurkan - Thibaut
GROUP 6 : Imad - Jessica
GROUP 7 : Chloe - Anderson
GROUP 8 : Ibrahim - Fauve
GROUP 9 : Kevin - Moncef
GROUP 10 : Maxime - Santiago
GROUP 11 : Thierry - Deria

---

**TIPS :**

---

In order to get the API key, create an account. It's free !

To generate an API key, you will have to enter several information such as name of the application (choose whatever you want), application url (put `localhost:5500`), etc.

When you have an API key, look for the `API Read Access Token`. This will be the one you will use as a Bearer authorization in your calls.

`Bearer {key}` should be included in the `Headers` as `Authorization`.

So... **_each call_** will have to be accompanied by this Bearer authorization in the Headers.

---

There are many and many endpoints in this API. You will be using only a few of them, mostly in the categories `DISCOVER`, `GENRES` and `MOVIES`

---

The REGISTER / LOGIN popup is only for practice ! No need to login or sign up for real. Just log to the console an object with the data after submitting.
