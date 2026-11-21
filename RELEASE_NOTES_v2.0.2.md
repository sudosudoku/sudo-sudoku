# sudo sudoku v2.0.2

**Released TBD · [Download on the App Store](https://apps.apple.com/us/app/sudo-sudoku/id6779813086) · [Official website](https://sudosudoku.kaichen.dev)**

```
$ sudo sudoku --sync
> mounting ~/iCloud/sudo-sudoku ... ok
> history, rating, achievements: replicated.
```

**sudo sudoku — your root follows you to the next iPhone.**

v2.0.2 adds one thing: iCloud sync. Your progress now lives in your own private iCloud database as well as on the device, so a new iPhone, a reinstall, or a second iPhone picks up exactly where you left off.

## Your progress, everywhere you're signed in ☁️

- Game history, ELO rating, and achievements sync through your **private** iCloud database on the same Apple Account. No sudo sudoku account, no sign-up, nothing to turn on.
- A new iPhone or a reinstall gets everything back on its own after launch.
- Play on two iPhones and both stay in sync, including a puzzle you started on one and finish on the other.

## Points earned on both iPhones count 📈

- The ELO rating is now kept as a ledger of solves instead of one number, so rating earned on two iPhones adds up after syncing instead of one overwriting the other.
- A solved puzzle always wins a conflict: an older, unsolved copy on another iPhone can never roll back a solve.
- Your current rating carries over unchanged when you update.

## Still offline-first 🔒

- The game works fully offline, as before. Changes sync the next time you're online.
- Signed out of iCloud, or iCloud off for sudo sudoku? Sync simply stays off. Signing out never deletes anything on the device.
- The developer can't see your iCloud data. The App Store privacy label is still **Data Not Collected**. Details in the [Privacy Policy](PRIVACY.md).

---

**Requirements:** iOS 17.0+, iPhone only. Internet optional (iCloud sync, Game Center).
Full details in [CHANGELOG.md](CHANGELOG.md).
