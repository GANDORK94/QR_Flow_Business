# QR Flow — Digital Business Card

A mobile-first digital business card that lives behind a QR code. When someone scans it, they land on a clean, professional page with all your contact info — and one tap saves everything directly to their phone's contacts.

This card also doubles as a **live product demo for QRFlow** — it's the exact experience we sell to clients, built and used by the team selling it.

---

## Live Demo

This repo is the actual card I use as an Account Executive at QRFlow. It's not a mock or a prototype — it's live, it's linked to my QR code, and it's what I hand to prospects when I'm in the field. Every time someone scans it, they're experiencing QRFlow's product firsthand before I've said a word about it.

That's intentional. The best demo is the one that sells itself.

---

## My Thought Process

I was working as an Account Executive at QRFlow and I wanted a card that actually did something when someone scanned it. Paper cards get thrown away. Even most digital cards are just a glorified webpage with a phone number on it. I wanted the experience to feel effortless — scan, tap once, saved. Done.

I built this whole thing with Claude AI. I came in knowing exactly what I wanted the experience to feel like and just kept iterating until it worked the way I had it in my head. No coding background — just a clear picture of what a good first impression looks like and the ability to describe it until the tool got it right.

### The problem with most digital cards

Most people either hand out a paper card that goes straight in the trash, or they share a contact digitally in some clunky way — AirDrop, typing it in manually, screenshotting a LinkedIn. None of that is smooth. In sales, the handoff matters. The fewer steps between "nice to meet you" and "saved in your phone," the better.

### What I wanted to build

Something that worked like this:
1. Person scans your QR code
2. They land on a clean, professional-looking card — name, title, company, contact info
3. One button — **Save to Contacts** — and they're done

No app to download, no account to create, no friction.

### How it works

The "Save to Contacts" button generates a vCard file and downloads it instantly to their phone. Their contacts app picks it up automatically — name, phone, email, website, and photo all transfer over. The whole flow takes about 5 seconds from scan to saved.

The card is designed for mobile first since that's where 100% of QR scans happen. Dark theme, animated entrance, contact icons that are immediately recognizable.

---

## Features

- Mobile-first design with dark theme and smooth animations
- Clickable email, phone, and website links
- One-tap **Save to Contacts** — downloads a vCard with name, phone, email, website, and photo
- No app required — works in any mobile browser

---

## Built With

- HTML, CSS, JavaScript
- vCard (.vcf) generation
- Claude AI
