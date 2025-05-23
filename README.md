# 🌍 Fake Name Generator API

A simple front-end-friendly JSON-based API that provides fake data like names, countries, cities, PO box addresses, emails, and user profiles. Useful for testing front-end projects or creating mock data on the fly.

---

## 📁 Data Available

This project provides the following JSON files:

- [`names.json`](./names.json) — First and last names from different parts of the world.
- [`countries.json`](./countries.json) — Countries with their ISO codes and continents.
- [`cities.json`](./cities.json) — Popular cities and their respective countries.
- [`addresses.json`](./addresses.json) — Random PO box-style addresses.
- [`emails.json`](./emails.json) — Common email domains.
- [`user_profiles.json`](./user_profiles.json) — Sample user profiles with full info.

---

## 🚀 How to Use

```js
fetch("https://jesse-fakename-api.vercel.app/names.json")
  .then(res => res.json())
  .then(data => {
    console.log(data);
  });

