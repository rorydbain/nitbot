# nitbot

Are you nostalgic for traditional bespoke code reviews? Do you miss fighting over tabs, spaces or line lengths? Great, add nit-bot to your repo now. It is significantly faster than Cursor, Devin, CodeRabbit and other AI code reviewers.

![nitbot requesting changes](images/changes.png)

## What it does

- Reports "Mixed spaces and tabs" on repos with no tabs.
- Posts "Not idiomatic" with nothing else.
- Posts "This feels bad" with no reason.
- Asks you to rename `i` to `index`, then back to `i`.
- Requests changes, then approves when you reply "ok".

## Pricing

|            | Free        | Pro            | Enterprise            |
| ---------- | ----------- | -------------- | --------------------- |
| Nits / day | 3           | Unlimited      | Contact us for more   |
| Severity   | nit         | NIT            | NIT (blocking)        |

## Install

```
npm i -g nitbot
nitbot review
```

It prints one nit and exits 1.
