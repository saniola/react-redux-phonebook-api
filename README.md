# React Redux Phonebook API

A React contacts manager built with Redux Toolkit, using async thunks to fetch, add, and delete contacts through a REST API instead of local storage.

## Features

- Fetches the contact list from a remote API on load.
- Add contacts via a form validated with Formik and Yup.
- Filter/search contacts by name.
- Delete contacts from the list.
- Loading and error states are tracked in Redux and reflected in the UI.

## Stack

- React 18
- Vite
- Redux Toolkit, React Redux (async thunks)
- Axios
- Formik, Yup (form handling and validation)
- Font Awesome (icons)
- ESLint, Prettier

## Usage

```bash
npm install
npm run dev
```

Other scripts:

```bash
npm run build     # production build
npm run preview   # preview the production build
npm run lint      # run ESLint
```
