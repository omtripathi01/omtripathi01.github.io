# omtripathi01.github.io

**Om Tripathi's portfolio: https://omtripathi01.github.io/om/**

The root, https://omtripathi01.github.io/, shows the template the portfolio
is built on, with sample content.

A portfolio for a React Native and full-stack engineer, built so that a
recruiter can reach the resume, a call or a message in one tap from anywhere
on the page. One config file drives everything: the same content restyles
itself into five different worlds.

Site developed by [Om Tripathi](https://github.com/omtripathi01).

## For recruiters

- **Resume in one tap.** "Download resume" sits in the hero, the chat, the
  contact section, the footer and the phone contact bar.
- **Chat with me.** A floating chat button on every page opens a message
  thread with quick replies: "We have a role for you", "Send me your resume",
  and "Book a 15-min call". Visitors can also type a message.
- **Phone contact bar.** On phones, email, WhatsApp, call and resume stay one
  tap away while scrolling.
- **Let's talk menu.** Email (copy or open), call, WhatsApp, LinkedIn, GitHub,
  a calendar link and a contact card (vCard), from the top bar.
- **30-second version.** `?tldr=1`, or the TL;DR button, collapses the site
  into one card. The page also prints cleanly as a one-page summary.
- **Job-fit check.** Paste a job description and the site shows which of the
  listed skills match.
- **Ask-me bot.** Answers common questions (location, remote work, stack,
  experience) from a written FAQ. No AI and no network calls.

## Links for one reader

- `/?for=hr`, `/?for=dev`, `/?for=visitor`: the site skips its "who's
  visiting?" question and tailors replies and jokes to that reader.
- `/?for=remote`: opens on the remote-work section.
- `/hi/<company>/`: a page for one company, with a personal greeting and
  note, the projects that fit that role and any extra sections.

## Worlds

A switcher in the corner restyles and re-animates the same content:

- **Minimal Pro**: clean, fast and printable. The default on the template demo.
- **Astronaut**: deep space, a ringed planet in 3D and zero-gravity motion.
- **Hacker**: phosphor green, matrix rain and headings that decode
  themselves. Terminal first.
- **Mobile Dev**: the default on the portfolio. A dark phone-at-night look,
  a phone that times an app launch, app-drawer skills and a chat contact.
- **Funny**: stickers, doodles and a career level map. Same facts, more jokes.
- **Arcade**: a secret 8-bit world with a career you can play through,
  unlocked by a well-known cheat code.

Each world has its own link (`/w/<world>/`) with its own share image.

## Sections

Intro, At a glance (experience, current role, apps shipped to the stores
and core stack), About, Working remotely, Selected work, How I ship, Leading teams,
Experience, Skills, What teammates say and Contact. Projects show only the
links they have: Google Play, App Store, website, source code and a live Expo
Snack that runs in the page.

## The playful layer (opt-in)

Visitors choose how much fun they want (Off, Subtle or Chaos) from the footer.

- A "who's visiting?" question (hiring, developer, just looking) that tailors
  jokes and chat replies. No answer means "hiring".
- A roaming mascot, memes, small gifts for reaching out, confetti and
  achievements with a shareable "secrets found" card.
- Festive themes that switch on during their dates, and that any visitor
  can pick from the footer at any time: Diwali lights, Christmas lights with
  snow, New Year lights with gold sparkles, and Holi colours.
- A surprise box (footer, command menu, phone menu) that lists the games and
  the secret way into each, with a Play button for phones: an 8-bit Arcade
  world, a bug-squashing game and a terminal with hidden files.
- A command menu (Ctrl or Cmd + K) and a generated soundtrack per world
  (sound is off by default).

## Also

- English and हिन्दी toggle for headings and the ask-me bot.
- Installable as an app (PWA).
- Dev X-ray: a grid, component and frame-rate overlay for curious developers.
- Share images per world, structured data (JSON-LD) and a sitemap.
- Keyboard support, visible focus, WCAG AA contrast and reduced-motion
  support in every world.
- Fast: about 191 KB of JavaScript up front (gzip). Heavy scenes load only in
  the world that needs them.

## Built with

Next.js 16 (static export), React, Tailwind CSS 4, Motion, GSAP, Lenis, Zod
and Three.js, hosted on GitHub Pages.

## About this repository

This repository only serves the site. The site is built in a private
repository; each build arrives here as one encrypted file, `site.tar.gz.enc`,
and the workflow in this repo decrypts and publishes it. Nothing here needs
editing by hand, and changes made here are replaced by the next build.
