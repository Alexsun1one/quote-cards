# Quote Cards

> A native-text-first skill for literary, philosophical, and opinion quote cards.

Quote Cards is strict about one thing: the final image should normally contain the quote as native text generated in the image itself. It is for quote cards that feel designed, not for blank backgrounds with rushed post-processing.

## Examples

<p><img src="examples/images/01-civilization-years.png" alt="Three Body quote card 1" width="100%"><br><sub>Three Body quote card 1</sub></p>
<p><img src="examples/images/02-arrogance.png" alt="Three Body quote card 2" width="100%"><br><sub>Three Body quote card 2</sub></p>
<p><img src="examples/images/03-do-not-answer.png" alt="Three Body quote card 3" width="100%"><br><sub>Three Body quote card 3</sub></p>

## What It Does

- Generate square quote cards with native Chinese text baked into the final pixels.
- Choose visual treatments for sci-fi, literary, essay, philosophical, and emotional quotes.
- Use short enough text, hierarchy, and contrast so the quote survives mobile reading.
- Only use post-overlay text when the user explicitly asks for editable templates or production correction.

## Install

Clone this repository into your local Codex skills folder:

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/Alexsun1one/quote-cards.git ~/.codex/skills/quote-cards
```

If your agent expects a nested skill directory instead of a direct clone, copy the folder that contains `SKILL.md` into its skills directory.

## Use

Example request:

```text
Use quote-cards to generate 3 native-text Chinese quote cards for 三体. Do not create blank backgrounds for later overlay unless I ask for editable templates.
```

The skill entry point is [`SKILL.md`](SKILL.md). Supporting rules live in [`references/`](references/) when this repo includes them; helper scripts live in [`scripts/`](scripts/) when available.

## Quality Bar

- The image must explain a concrete idea, not merely decorate the page.
- Chinese text should be readable at the actual publishing size.
- The output should keep a stable style system across a set while letting each image fit its topic.
- Generated examples are prompts and visual references, not fixed templates.

## WeChat

More writeups, examples, and AI workflow notes are published on my WeChat official account. This is the real QR/search card used for the account, included as a normal bitmap asset rather than a stylized fake code.

<p align="center">
  <img src="assets/wechat-official-account.png" alt="微信搜一搜：正在逐渐AI化" width="720">
</p>

## License

MIT. See [`LICENSE`](LICENSE).

## Notice

This is an original open-source skill package by Sun Wuyuan / Alexsun1one. It is not affiliated with OpenAI, GitHub, WeChat, or any referenced platform. Avoid using it to imitate protected characters, living artists, or third-party brand assets without permission.
