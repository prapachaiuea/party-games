# Party Games

The one link to send friends before game night. A small menu page that links out to seven browser party games — pick one, tap it, everyone's in.

**Live:** https://prapachaiuea.github.io/party-games/

| Game | What it is |
|---|---|
| [Insider](https://github.com/prapachaiuea/insider-game) | Hidden-identity party game — everyone shares a secret word except one bluffer. |
| [Wavelength](https://github.com/prapachaiuea/wavelength-game) | Cooperative mind-reading — one player sees a hidden target, everyone else tunes in together. |
| [Quiplash](https://github.com/prapachaiuea/quiplash-game) | Comedy answer battle — same prompt, two answers, the group votes on the funnier one. |
| [Fibbing It](https://github.com/prapachaiuea/fibbing-it-game) | One true answer, everyone else writes a convincing lie — spot the truth. |
| [Trivia Murder Party](https://github.com/prapachaiuea/trivia-murder-party-game) | Answer trivia to stay safe, or answer wrong and gamble your life in a reflex trial. |
| [Werewolf](https://github.com/prapachaiuea/werewolf-game) | Wolves hunt in secret each night, the village votes out a suspect each day — survive till dawn or catch them first. |
| [Sounds Fishy](https://github.com/prapachaiuea/sounds-fishy-game) | Weird-but-true trivia bluffing — one player knows the real answer, everyone else lies, and the questioner has to catch every liar without hitting the truth. |

## How it works

This page is intentionally simple: static HTML/CSS, no JavaScript, no Firebase, no build step. It doesn't run any game itself — each card is a plain link out to that game's own site, which is a separate, independently deployed project. Adding, removing, or reordering games here never touches the games themselves.

## Project structure

```
index.html    seven linked cards, one per game
styles.css    all styling — colors are pulled from each game's own real accent color
```

## Deployment

Static site on GitHub Pages, served directly from `main`. No setup beyond enabling Pages (Settings → Pages → Deploy from branch → `main` / root).
