# Coding_academy_Postit
Epitech project


#Post-it App (Vue.js)
Description

A small web app to manage post-it notes, built with Vue.js.
It follows the MVVM pattern and introduces Vue basics:

-Components

-Data, methods, computed, lifecycle hooks

-Props & events

-Vue Router

-LocalStorage

-State management (Vuex/Pinia)

-API integration (bonus)

Features

-Show a list of post-it notes

-View details of a single note

-Add and delete notes

-Save data in LocalStorage

(Bonus) Save and fetch notes from an API

Setup

Requirements

Node.js (LTS)
npm (comes with Node.js)

Steps
# clone the repo
git clone git@github.com:Juste702/Coding_academy_Postit.git
cd Post-it

# install dependencies
npm install

# start dev server
npm run dev

Open http://localhost:5173


Project structure

src/
 ├── assets/       # static files
 ├── components/   # reusable components
 ├── views/        # main pages (Notes, Note)
 ├── router/       # Vue Router config
 ├── store/        # Vuex/Pinia store
 ├── App.vue       # root component
 └── main.js       # entry point

Improvements

-Use API + Vuex for remote data

-Add unit tests

-Better UI with a CSS framework

-Mobile responsive

Author

Project made for learning Vue.js.
