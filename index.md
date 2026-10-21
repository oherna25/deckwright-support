# Support — DuoFlash

**Last updated:** October 21, 2026

DuoFlash is a flashcard study app for iPhone Duo. This page collects
help, answers to common questions, and how to report a problem.

## Getting help

DuoFlash runs entirely on your device and has no account or network access,
so there is no in-app support chat. For help:

- Open an issue at <https://github.com/oherna25/duoFlash/issues>
- Include your iOS version, device model, and the steps to reproduce the
  problem
- For import problems, note the file format (.json, .cards, or .apkg) and,
  if possible, a sample file

Questions and feedback are welcome there too.

## Frequently asked questions

### Does DuoFlash need an account or internet connection?

No. The app works completely offline. There is no sign-in, no account, and
no network requests. All decks, cards, and study history stay on your
device.

### What import formats are supported?

JSON (native DuoFlash schema), `.cards` packages, and Anki `.apkg`
packages. The format is detected automatically when you pick a file. A
preview (deck name, card count, sample cards) is shown before importing.

### Where is my data stored?

Only on your device, in the app's local storage. It is included in your
device's standard backups (iCloud or local) according to your own device
settings. DuoFlash does not run any cloud service.

### How do I back up or share a deck?

Open a deck and use Export to save it as JSON. You can share that file or
import it on another device.

### How do I study on the cover (outer screen)?

In quiz setup, choose the outer screen, then close the phone. The current
card appears on the cover display. Cover study requires iPhone Duo.

### Does it work on a regular iPhone?

Yes for deck creation, import, and inner-screen study. Cover (outer screen)
study requires iPhone Duo.

### How do I delete my data?

Delete decks or cards inside the app at any time. Uninstalling the app
removes all locally stored data.

### Is there a subscription or in-app purchase?

No. DuoFlash is a one-time purchase with no subscriptions and no ads.

## Troubleshooting

- **Import fails or shows an error.** Check that the file is a valid
  `.json`, `.cards`, or `.apkg` file. Corrupt or unsupported files are
  rejected with a clear error message. Re-download the file and try again.
- **Cover screen stays blank.** Cover study requires iPhone Duo and the
  phone must be closed. Make sure you selected the outer screen in quiz
  setup.
- **Text is too small or too large.** DuoFlash follows Dynamic Type. Adjust
  the text size in iOS Settings → Display & Brightness → Text Size.
- **App crashes on launch.** Reinstalling the app clears local data; back up
  decks via Export first if possible.

## Reporting a bug

When reporting a bug, please include:

1. What you expected to happen and what actually happened
2. Steps to reproduce
3. Device model and iOS version
4. App version (shown in the app's About screen)
5. Whether the issue happens on the inner screen, the cover, or both

File the report at <https://github.com/oherna25/duoFlash/issues>.

## Privacy

DuoFlash collects no personal data. See the full privacy policy at
<https://oherna25.github.io/duoFlash-privacy/>.

## Contact

For anything not covered here, open an issue at
<https://github.com/oherna25/duoFlash/issues>.
path: /tmp/support-check/index.md