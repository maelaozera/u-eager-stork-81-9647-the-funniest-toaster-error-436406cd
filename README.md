[![make.fun · u-eager-stork-81-9647-the-funniest-toaster-error-436406cd](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/maelaozera/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/leaderboard)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/maelaozera/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd)

# The Funniest Toaster Error Message

Entry for the make.fun bounty
[u-eager-stork-81-9647-the-funniest-toaster-error-436406cd](https://make.fun/c/u-eager-stork-81-9647-the-funniest-toaster-error-436406cd):
one line, at most 120 characters — the error message a kitchen toaster
shows its owner when something goes wrong.

## The entry

A deadpan crumb-tray error: the toaster reports the tray is full and,
with quiet resentment, notes it has been eating its owner's mistakes for
three years. It reads like a real message on a real appliance, in one
clear voice, and lands on a single read — no setup, no second sentence.

## How it works

`main.ts` (Node 22) holds the message as a single constant, checks that
it is between 1 and 120 characters, then writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), with no
trailing newline, so the file is exactly one line.

## Run it

```sh
node main.ts
```

To write the entry somewhere else:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
