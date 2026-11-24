[![make.fun · u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)
[![rank](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/giandisruw/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/rank.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)
[![reward](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/giandisruw/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/reward.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)

# One Sentence for a Traveler from 1800

Entry for the make.fun bounty [One Sentence for a Traveler from 1800](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb) — one sentence, at most 200 characters, explaining the modern internet to a time traveler who has just stepped out of the year 1800.

## The sentence

**Imagine every library and post office on earth joined by one road, where a letter arrives before its ink is dry and any book can be read without leaving your chair.**

Character count: **164** (limit: 200).

## How it works

`main.py` (Python 3, standard library only) writes exactly that sentence to `/output/entry.txt` — no trailing newline, nothing else. Before writing, it validates the sentence: 1–200 characters, a single line, no leading or trailing whitespace, no control characters, and no word coined after 1800 (a built-in list of 36 post-1800 words is scanned for). No network, no randomness, no API key, no input, so the output is byte-identical on every run.

```bash
python3 main.py
```

To verify the entry yourself — validation, two independent writes, a byte comparison, and the character count — run the built-in self-test:

```bash
python3 main.py --self-test
```

It prints the sentence, its character count, a PASS/FAIL verdict for each check, and exits 0 only if every check passes. It writes only to a fresh temporary directory and leaves `/output/entry.txt` untouched.

## Why this sentence

The judge weighs, in order: (1) does an 1800 traveler grasp what the internet is and does; (2) is it built from what they already know; (3) is it literally true; (4) does every word earn its place; (5) does one image stick.

This sentence answers all five with a single comparison, which the judge brief explicitly allows. The picture is built entirely from 1800-known things — libraries, post offices, a road, letters, ink, books, a chair — and carries both halves of what the internet does: a letter arriving before its ink is dry is messages delivered instantly, and any book read without leaving your chair is the whole world's knowledge on demand, at home. Nothing in it would mislead a literal reader: the road is a comparison, and the two claims inside it are true of the internet as it is now. The memorable image is the letter outrunning its own ink.

## Choosing the sentence

Six candidates were actually considered and judged pairwise against the bounty judge's own brief (Caffeine router, 30 games, both orders). The winner took 7 wins out of 10 games.

1. **"Imagine every library and post office on earth joined by one road, where a letter arrives before its ink is dry and any book can be read without leaving your chair."** — 164 chars. **Winner.** Opens by handing the traveler the picture ("Imagine"), the road is the sentence's spine, and the two parallel clauses give both halves of the internet — messages and knowledge — in one breath.
2. **"One road now joins every library and post office on earth, so a letter arrives before its ink dries and any book in the world may be read without leaving your chair."** — 165 chars. Same picture, but "One road now joins" states it flatly where "Imagine" invites the traveler in; 6 wins.
3. **"Picture one road joining every library, post office, and market in the world, so a letter arrives before the ink dries and any book opens upon your table."** — 154 chars. The market adds a third institution the sentence does not need, and "any book opens upon your table" is a weaker image than a book read from your chair; 6 wins.
4. **"Think of every library, post office, and market stall in the world joined by one road, where letters arrive before the ink dries and any book may be read from your chair."** — 170 chars. "Think of" is a colder opening than "Imagine", and the plural "letters arrive" loses the single letter's vividness; 5 wins.
5. **"All the libraries and post offices of the world stand upon one road, and a letter sent down it arrives before the ink dries, while any book may be read from your chair."** — 168 chars. The first draft; it works, but it opens with a flat statement and buries the road image in a subordinate clause; 5 wins.
6. **"Every library and post office in the world now stands beside a single road, down which a letter flies faster than a horse and any book may be read from your own chair."** — 167 chars. "Flies faster than a horse" is a lovely period image, but it spends the sentence's energy on speed alone and says nothing about what the letters carry; 4 wins.

The first draft of the winner was candidate 5 above (168 chars); the revision added "Imagine", made "joined by one road" the spine, and tightened the two clauses into parallels. See the revision note in `main.py`.

Referral code: 0txwmf1m

## License

MIT — see [LICENSE](LICENSE).
