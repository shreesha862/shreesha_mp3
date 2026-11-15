# MP3 Tag Reader & Editor

A command-line application written in C to read, display, and edit ID3 metadata tags from MP3 audio files.

## Features
- Detects and parses **ID3v1** and **ID3v2 (v2.2 and v2.3)** tags.
- Displays song metadata including title, artist, album, year, genre, and comments.
- Edits existing MP3 tag fields using command-line options.
- Displays embedded album image details (type, path, and size).
- Includes a `-h` help option and error handling for missing or invalid ID3 tags.

## Tech Stack
- **Language:** C
- **Concepts:** Binary File I/O, Structures, Pointers, Command-Line Arguments

## Usage
- **Help menu:** `./mp3_tag_reader -h`
- **View tags:** `./mp3_tag_reader -v sample.mp3`
- **Edit tags:** `./mp3_tag_reader -e -t "New Title" sample.mp3`
