# Support for DeskWright

**Last updated:** October 21, 2026

DeskWright is a flashcard study app for iPhone. It runs on any iPhone. On
iPhone Duo, the cover can show the current card while the phone is closed. This
page collects help, answers to common questions, and how to report a problem.

## Getting help

DeskWright runs entirely on your device and has no account or network access,
so there is no in-app support chat. For help:

- Open an issue at <https://github.com/oherna25/deskwright-support/issues>
- Include your iOS version, device model, and the steps to reproduce the
  problem
- For import problems, note the file format (.json, .cards, or .apkg) and,
  if possible, a sample file

Questions and feedback are welcome there too.

## Frequently asked questions

### Does DeskWright need an account or internet connection?

No. The app works completely offline. There is no sign-in, no account, and
no network requests. All decks, cards, and study history stay on your
device.

### What import formats are supported?

JSON (native DeskWright schema), `.cards` packages, and Anki `.apkg`
packages. The format is detected automatically when you pick a file. A
preview (deck name, card count, sample cards) is shown before importing.

### Where is my data stored?

Only on your device, in the app's local storage. It is included in your
device's standard backups (iCloud or local) according to your device
settings. DeskWright does not run any cloud service.

### How do I back up or share a deck?

Open a deck and use Export to save it as JSON. You can share that file or
import it on another device.

### How do I study on the cover?

On iPhone Duo, choose **Cover screen** in quiz setup, then close the phone.
The current card appears on the cover. Cover study requires iPhone Duo and
iOS 27.1.

### Does it work on a regular iPhone?

Yes. Every feature except cover study works on any iPhone that runs iOS 27.0
or later. Cover study requires iPhone Duo. The cover option is hidden on
phones without a cover display.

### How do I delete my data?

Delete decks or cards inside the app at any time. Uninstalling the app
removes all locally stored data.

### Is there a subscription or in-app purchase?

No. DeskWright is a one-time purchase with no subscriptions and no ads.

## Troubleshooting

- **Import fails or shows an error.** Check that the file is a valid
  `.json`, `.cards`, or `.apkg` file. Corrupt or unsupported files are
  rejected with a clear error message. Re-download the file and try again.
- **Cover screen stays blank.** Cover study requires iPhone Duo and the
  phone must be closed. Make sure you selected **Cover screen** in quiz
  setup.
- **Text is too small or too large.** DeskWright follows Dynamic Type. Adjust
  the text size in iOS Settings > Display & Brightness > Text Size.
- **App crashes on launch.** Reinstalling the app clears local data; back up
  decks via Export first if possible.

## Reporting a bug

When reporting a bug, please include:

1. What you expected to happen and what actually happened
2. Steps to reproduce
3. Device model and iOS version
4. App version
5. Whether the issue happens on the main screen, the cover, or both

File the report at <https://github.com/oherna25/deskwright-support/issues>.

## Privacy

DeskWright collects no personal data. See the full privacy policy at
<https://oherna25.github.io/deskwright-privacy/>.

## Contact

For anything not covered here, open an issue at
<https://github.com/oherna25/deskwright-support/issues>.
