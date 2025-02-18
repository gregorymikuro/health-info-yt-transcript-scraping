# YouTube Health Tutorial Scraper

## Overview
This repository contains a Python script that scrapes transcripts from health-related YouTube tutorial videos. It utilizes the `youtube_transcript_api` package to extract subtitles and saves them as text files for further analysis.

## Features
- Extracts transcripts from a predefined list of YouTube videos.
- Cleans and formats transcripts into readable text.
- Saves transcripts into a `data/` directory for easy access.
- Handles errors gracefully when a transcript is unavailable.

## Prerequisites
Ensure you have Python installed (>= 3.6) and install the required package using:

```bash
pip install youtube-transcript-api
```

## Installation
Clone the repository and navigate into the directory:

```bash
git clone https://github.com/yourusername/---.git
cd ---
```

## Usage
Run the script to fetch and save transcripts:

```bash
python index.ipyb
```

## Code Explanation
The script performs the following tasks:
1. Defines a list of YouTube video URLs.
2. Extracts the video ID from each URL using regular expressions.
3. Fetches the transcript using the `YouTubeTranscriptApi`.
4. Cleans the text by concatenating transcript entries.
5. Saves the transcript to a file in the `data/` directory.

## Example Output
When executed, the script will generate text files such as:

```
data/
├── s-HThHRV4uo.txt
├── RSu1who-Bk8.txt
├── yxonJTWhBJQ.txt
...
```

Each file contains the complete transcript of the corresponding video.

## Error Handling
If a transcript is unavailable, the script prints an error message and continues processing the remaining videos.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.