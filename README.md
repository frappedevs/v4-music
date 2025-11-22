# v4-music

## What is this?
This repository contains the in-game music playlists for V4, all organized in JSON format.

When a new server launches, it automatically fetches these playlists and converts them into Luau dictionaries, which are used by the game's music system.

## Can I contribute?
Absolutely! We don't always have time to keep the playlists up to date with current music trends. If there's a track you love and think would be a great fit for V4, feel free to open an issue or submit a pull request.

## Naming Conventions
Playlists are grouped by genre and identified by numbers:
- **One** – Dance/EDM  
- **Two** – Punk, rock, hip-hop, and similar styles  
- **Three** – Lo-fi  
- **Four** – A nostalgic collection from the early days of V4
- **Five** – A winter-limited playlist

If a music you want to add does not fit in those categories, write us an issue and we'll see what to do!

## How to Contribute

### Submitting a Pull Request
1. Fork this repository.
2. Create a new branch: `git checkout -b [Branch Name]`
3. Add your track(s) to the appropriate JSON file under the corresponding playlist.
4. Commit your changes: `git commit -m "Added [Track Name] to playlist [One/Two/Three/Four]"`
5. Push to your fork: `git push origin [Branch Name]`
6. Open a pull request with a short description of the changes and why you think the track fits the playlist.

### Submitting an Issue
If you're not comfortable with Git or JSON, you can also:
1. Open a new issue.
2. Include the song title, artist, and a short description of why you think it belongs in the game.
3. (Optional) Suggest which playlist it should go in.

## License
MIT License.
