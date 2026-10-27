# Podcasts

This repo turns written articles (filings, blog posts, X posts and threads, and similar text) into short, two-host, podcast-style audio overviews. It also hosts them as simple web players on GitHub Pages.

**Listen:** https://rbs11.github.io/podcasts/

## Episodes

| Episode | Source | Length |
|---|---|---|
| [Anthropic S-1: key takeaways](https://rbs11.github.io/podcasts/anthropic-s1/) | Anthropic's S-1 registration statement and public commentary on X | ~21 min |
| [Thorsten Ball: how I work with agents](https://rbs11.github.io/podcasts/thorsten-ball-agents/) | Thorsten Ball's X article "How I work with Agents… as of October 2026" and replies | ~22 min |

## How it works

1. Read the source article plus related public discussion.
2. Write a conversational two-host script that covers the key takeaways, defines the main terms, and explains what a full read would add.
3. Generate speech with neural text-to-speech voices and normalize the audio with `ffmpeg`.
4. Publish an MP3 and a small HTML5 player page that supports lock-screen playback controls.

## Important notice

- **Commentary, not a copy.** Each episode is an original, transformative summary and discussion made for commentary, criticism, and education. Episodes are not reproductions of the source works.
- **No affiliation or endorsement.** This project is not affiliated with, sponsored by, or endorsed by any company, author, or publication it discusses. All trademarks and source works belong to their respective owners.
- **AI-generated audio.** The voices are synthetic text-to-speech. They do not belong to, imitate, or represent any real person, including any author discussed.
- **No advice.** Content is for general information only. It is not financial, investment, legal, or professional advice, and it may contain errors or be out of date. Check the original sources before relying on anything you hear.
- **No warranty.** Everything here is provided "as is", without warranty of any kind. The author is not liable for any loss or damage that comes from using it. See [LICENSE](LICENSE).
- **Takedown requests.** If you own rights in a source work and object to an episode, please [open an issue](https://github.com/rbs11/podcasts/issues). The episode will be reviewed and removed promptly where appropriate.

## License

- **Code** (HTML, scripts, and page templates) is under the [MIT License](LICENSE).
- **Episode audio and scripts** are under [Creative Commons Attribution-NonCommercial 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (CC BY-NC 4.0). That covers only the original commentary in them. Third-party material that is quoted or referenced stays with its owners and is not relicensed here.
