# offline-form-app
here's a clean, minimal offline form that saves multiple entries by appending to the same localStorage list without overwriting previous ones:

A simple HTML + JavaScript form that works offline by saving submitted entries to the browser's `localStorage`. Each new entry is added to a persistent list that remains intact even if the browser is closed or refreshed.

## 🔧 Features

- Save form data offline using `localStorage`
- Appends new entries without overwriting previous ones
- Automatically timestamps each entry
- Mobile- and desktop-friendly
- Minimal and dependency-free

## 🚀 How It Works

1. User fills in the form and clicks "Save Offline".
2. The form data is stored in `localStorage` under the key `offlineForms`.
3. Data is preserved even if the browser is closed or internet is lost.
4. Entries can later be retrieved or synced when back online.

## 📁 Files

- `index.html` — main offline form with embedded JavaScript

## 📦 Usage

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yourusername/offline-form-app.git
