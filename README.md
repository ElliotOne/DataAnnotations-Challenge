# DataAnnotations Challenge (Unicode Grid Fetcher)
A solution to the Data Annotations challenge that reads a Unicode grid from an HTML table and reconstructs it in the console.

## Overview

This project, part of the Data Annotations challenge, extracts and displays a grid of Unicode characters from an HTML data source, which can be fetched from a URL or read from a local Data.html file, then processes the HTML table to reconstruct and print the Unicode character grid in the console.

---

## Features

- Fetch Unicode grid data from a live URL.
- Alternatively, read Unicode grid data from a local HTML file.
- Parse and extract grid coordinates and characters using BeautifulSoup.
- Render and print the Unicode character grid visually in the console.
- Handles invalid or missing data gracefully.

---

## Project Structure

- `fetch_unicode_grid(url)`: Fetches and processes HTML content from a URL.
- `fetch_unicode_grid_from_file(filename)`: Reads and processes HTML content from a local file.
- Output is printed as a formatted grid of Unicode characters.

---

## Output Example

```
████████░     ████████░   ██████████░    ███████░  ██░           ███░ ███░    ███░ ██░     ██░
██░     ██░ ███░     ███░ ██░          ███░    ██░ ███░   ███░   ██░    ██░  ██░   ██░     ██░
██░     ██░ ██░       ██░ ██░         ███░          ██░  █████░ ███░     ██░██░    ██░     ██░
████████░   ██░       ██░ ████████░   ██░           ███░ ██░██░ ██░       ███░     ██████████░
██░     ██░ ██░       ██░ ██░         ███░           ██░██░ ██░██░       ██░██░    ██░     ██░
██░     ██░ ███░     ███░ ██░          ███░    ██░   ████░   ████░      ██░  ██░   ██░     ██░
████████░     ████████░   ██████████░    ███████░     ██░     ██░     ███░    ███░ ██░     ██░
```

---

## How to Use

### Fetch from URL

```python
url = 'https://docs.google.com/document/d/e/2PACX-1vQGUck9HIFCyezsrBSnmENk5ieJuYwpt7YHYEzeNJkIb9OSDdx-ov2nRNReKQyey-cwJOoEKUhLmN9z/pub'
fetch_unicode_grid(URL
)
```
### Read from Local File

Make sure the local file Data.html is in the same directory as your script or notebook.

```python
fetch_unicode_grid_from_file('Data.html')
```

---

## Requirements

- Python 3.x
- requests library (for fetching from URL)
- beautifulsoup4 (for parsing HTML)

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and share.

---

### Contributions

Contributions and improvements are welcome! Feel free to fork, open issues, or submit pull requests.

