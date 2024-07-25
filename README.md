# React + Vite Example App

## Getting started

To get the frontend running locally:

- Clone this repo
- `npm install` to install all req'd dependencies
- `npm run dev` to start the local server (this project Vite)



## Functionality overview

The example application is a social blogging site (i.e. a Medium.com clone) called "Conduit". It uses a custom API for all requests, including authentication.

**General functionality:**

- Authenticate users via JWT (login/signup pages + logout button on settings page)
- CRU* users (sign up & settings page - no deleting required)
- CRUD Articles
- CR*D Comments on articles (no updating required)
- GET and display paginated lists of articles
- Favorite articles
- Follow other users

**The general page breakdown looks like this:**

- Home page (URL: /#/ )
    - List of tags
    - List of articles pulled from either Feed, Global, or by Tag
    - Pagination for list of articles
- Sign in/Sign up pages (URL: /#/login, /#/register )
    - Use JWT (store the token in localStorage)
- Settings page (URL: /#/settings )
- Editor page to create/edit articles (URL: /#/editor, /#/editor/article-slug-here )
- Article page (URL: /#/article/article-slug-here )
    - Delete article button (only shown to article's author)
    - Render markdown from server client side
    - Comments section at bottom of page
    - Delete comment button (only shown to comment's author)
- Profile page (URL: /#/@username, /#/@username/favorites )
    - Show basic user info
    - List of articles populated from author's created articles or author's favorited articles

<br />

## Screenshots

<img width="1280" alt="Screenshot 2024-07-25 at 8 13 16 PM" src="https://github.com/user-attachments/assets/611d01e4-2d2f-4f44-9eb8-279952935a21">
<img width="1280" alt="Screenshot 2024-07-25 at 8 13 24 PM" src="https://github.com/user-attachments/assets/3139f374-c37b-4b46-9a21-0e7f7d08f57b">
<img width="1280" alt="Screenshot 2024-07-25 at 8 13 29 PM" src="https://github.com/user-attachments/assets/90a551c4-da7e-41b3-8d48-e029fa81ebf9">
<img width="1280" alt="Screenshot 2024-07-25 at 8 14 11 PM" src="https://github.com/user-attachments/assets/46080023-1ab9-4b7e-8412-93
<img width="1280" alt="Screenshot 2024-07-25 at 8 21 56 PM" src="https://github.com/user-attachments/assets/d2b1fd9d-7d05-416d-b40e-4c8a686b2bfd">

