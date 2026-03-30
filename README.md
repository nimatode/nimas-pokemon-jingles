# Nima's Pokemon Jingles

A repository of custom edited Cocoon jingle packs for various Pokémon titles. This repository covers most games from Gameboy, all the way to Nintendo Switch. 

## Quick Start

1. Use this repository template
2. Add your audio files (`.mp3`, `.ogg`, `.wav`) to the repo.
3. Update `index.json` to reference each file.
4. In Cocoon, go to **Settings → Library & Data → Jingle Repositories**
   and add your repo as `your-username/your-repo-name`.

## index.json Format

The `index.json` file at the root of the repository tells Cocoon what
jingles are available and where to find them.

```json
{
  "name": "My Jingle Pack",
  "entries": [
    {
      "game": "Super Fartio Throws",
      "file": "jingles/superfartiothrows.mp3"
    },
    {
      "game": "The Legend of Velma",
      "file": "jingles/The Legend of Velma.ogg"
    }
  ]
}
```

When creating a jingle pack, make sure you have the right to distribute
the audio files. Consider using:

- Original compositions
- Clips you created yourself
- Content with appropriate Creative Commons licenses
- Short, transformative fair-use clips (consult local laws)

Do **not** redistribute copyrighted music without permission.
