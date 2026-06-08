# Leads Tracker Chrome Extension

A lightweight Chrome Extension that allows users to save and manage useful links directly from their browser. Users can save URLs manually or instantly save the URL of the currently active tab, with all data stored locally for persistence across browser sessions.

## Features

* Save custom URLs through an input field.
* Save the URL of the currently active Chrome tab with one click.
* Persistent storage using Local Storage.
* Display saved leads as clickable links.
* Open saved links in a new tab.
* Delete all saved leads when no longer needed.
* Simple and responsive user interface.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Chrome Extension APIs
* Local Storage
* JSON (Manifest Configuration)

## How It Works

### Save a Custom Link

Enter a URL into the input field and click **SAVE INPUT**.

### Save the Current Tab

Click **SAVE TAB** to automatically save the URL of the active Chrome tab.

### View Saved Leads

All saved links are displayed in a list. Clicking a link opens it in a new browser tab.

### Delete Leads

Click **DELETE ALL** to remove all saved leads from Local Storage.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/leads-tracker-extension.git
```

2. Open Chrome and navigate to:

```
chrome://extensions
```

3. Enable **Developer Mode**.

4. Click **Load Unpacked**.

5. Select the project folder.

6. The extension is now ready to use from your Chrome toolbar.

## Project Structure

```text
├── index.html
├── index.css
├── index.js
├── manifest.json
└── assets/
```

## Key Concepts Practiced

* DOM Manipulation
* Event Handling
* Arrays and Loops
* Template Literals
* Local Storage
* JSON Parsing & Stringifying
* Chrome Tabs API
* Chrome Extension Development

## Future Enhancements

* Delete individual leads
* Edit existing leads
* Search and filter saved links
* Export/import saved leads
* Dark mode support
* Lead categorization and tags

## Screenshot

*Add a screenshot of the extension here.*

## License

This project is open source and available under the MIT License.
