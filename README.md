<p align="center">
  <img src="https://raw.githubusercontent.com/baffuohasareb/sika-puduo-releases/main/icon-navy.png" width="120" alt="Sika Puduo logo" />
</p>

<h1 align="center">Sika Puduo</h1>
<p align="center"><em>Kept in check.</em></p>

---

## What is this?

Sika Puduo is a simple app for tracking your money. Income, expenses, budgets, savings, loans, the whole picture, all in one place.

No signing up. No linking your bank account. No "create a profile" stress. You install it, set a PIN, and start logging your money like an adult.

## Why should I trust this with my money info?

Fair question, it's your money. Here's the deal:

- **Everything stays on your phone.** There's no server sitting somewhere with your data on it, because there is no server. Period.
- **No tracking, no ads, no "anonymous analytics."** We're not watching what you spend on.
- **Locked behind your PIN or fingerprint.** Yours to open, nobody else's.
- **You can back up your own data** anytime, straight from the app, in case you switch phones or just like having receipts.

If a random app on your phone is quietly phoning home with your spending habits, it's not this one.

## Get the App

**[⬇️ Download Sika Puduo (Android)](https://github.com/baffuohasareb/sika-puduo-releases/releases/download/v1.0.0/sika-puduo-v1.0.1.apk)**

That link always points to the newest version. One tap, one file, done.

### Installing it (takes 2 minutes)

1. Tap the download link above on your phone
2. Once it's downloaded, tap the file to open it
3. Android might show a popup asking to "allow installs from this source", tap allow. This is normal, it's just how Android handles apps that aren't from the Play Store, not a red flag on the app itself.
4. Open Sika Puduo, set your PIN, and you're in

That's it. No account, no email, no verification code.

**A note on why it's not on the Play Store (yet):** getting listed there is its own whole process. For now, this is the official way to get the app, straight from the source.

### A heads-up about the Play Protect warning

When you go to install, Android might flash a message from Play Protect saying it can't verify the app or that it's not commonly downloaded. That's expected, it's just Android's way of flagging anything that isn't distributed through the Play Store, not a sign something's wrong. Tap "More details" and then "Install anyway" to continue. You're safe to proceed.

---

## For the tech-curious 🤓

Let's satisfy your curiosity. Here's the shape of it all:

- Built with **React Native / Expo**
- All your data lives in an on-device **SQLite** database, nothing leaves your phone
- PIN is salted and hashed, never stored in plain text, with lockout protection against brute-force guessing
- Screenshots and screen recording are blocked while you're in the app
- This particular build is compiled for **arm64-v8a**, which covers basically every Android phone from 2018 onward

### Verifying your download

Paranoid in a good way? Every release comes with a checksum so you can confirm the file you downloaded is exactly the file we published, byte for byte, with nothing added in transit.

**Mac/Linux:**
```
shasum -a 256 sika-puduo-vX.X.X.apk
```

**Windows (PowerShell):**
```
Get-FileHash sika-puduo-vX.X.X.apk -Algorithm SHA256
```

Match the output against the checksum for the current release below. If they're identical, you're good.

### Release Asset Integrity
- **File:** sika-puduo-v1.0.1.apk (45.47 MB)
- **SHA-256:** feb045d8793f228c5012df5b647747ff4ced557ed39d0ef4243a1e5d4c76cff6

---

## Who made this?

Hey, I'm **Baffuoh**, a software engineer based in Kumasi, Ghana. I spend most of my time building software professionally, web platforms, mobile apps, and AI-powered products, and I build personal projects like this one on the side.

Sika Puduo actually started as something just for me. I wanted a simple way to track my own money without handing my financial details to another company's servers. Once I had it working, I realized how useful it could be for other people too, so I decided to clean it up and put it out there for anyone who wants the same thing.

It's one of the things I build.

## Got a question, bug, or idea?

We're setting up a proper place for this on the website. Until then, reach out directly at hi.sikapuduo@gmail.com.

---

<p align="center"><em>Know what's up with your money, because it's <strong>your money</strong>.</em></p>
