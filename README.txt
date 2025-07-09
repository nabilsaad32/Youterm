# Youterm
Youterm is a lightweight, terminal-based YouTube interface written in Bash.
Script Description: youterm.sh
Youterm is a lightweight, terminal-based YouTube interface written in Bash.
It allows you to search, browse, and play YouTube videos right from your terminal using powerful tools like yt-dlp, mpv, and (optionally) fzf.
Features:
- Play any YouTube link manually

- Load the latest video from a list of channels stored in a list file

- Search YouTube by keyword, and pick results via fzf or manual ID input

- Input cleanup (trims spaces and validates IDs)
Channel List Format:
The script expects a plain file called list, containing one channel per line, like:
@veritasium
