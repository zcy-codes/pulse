> [!IMPORTANT]
> This is not the official gadgetbridge, if you are looking to install gadgetbridge, do so [here](https://gadgetbridge.org)  

<div align="center">

# Pulse

**A Garmin-only wearable companion with a modern ui.**

*by [zach](https://zachy.cc) · `cc.zachy.pulse`*

A fork of gadgetbridge redesigned to look more modern, with a primarily blue and black color scheme

</div>

---

## What is Pulse?

Pulse is a focused fork of [Gadgetbridge](https://codeberg.org/Freeyourgadget/Gadgetbridge) that pairs with **Garmin** watches and reskins the whole app to have a simpler, more accented UI.

The base gadgetbridge is still here, its just been fully redesigned, I haven't added any new compatibility, and I don't plan on it, as that's not my expertise

## Highlights

- **Today** — an animated stats ring, customizable tiles that fill with your progress, and a personalised greeting.
- **Goal celebration & streaks** — confetti and a notification when you hit a goal; tap the flame for a full streak calendar. Optional "any goal counts" streak mode.
- **Health tab** — a customizable grid of metric cards (heart rate, body energy, stress, SpO₂, HRV, respiration…) each with a 7-day mini chart.
- **Sleep tab** — a sleep score, last-night stage hypnogram, nap detection, and a 7-night trend.
- **Fitness** — browse recorded workouts and, detailed charts.
- **Week in Review** — an animated weekly review with a summary of your week
- **Achievements** — unlockable badges you can share as cards.
- **Home-screen widgets** — full + compact steps widgets with a refresh button, plus a Quick Settings tile.
- **Make it yours** — Light / Dark / System, and accent colours (Neon Blue, Violet, Coral, Mint, Pink).
- **Weather** — fetches local weather (Open-Meteo) and pushes it to your watch for supported models.
(The internet permission currently isn't optional, even though the weather fetching is, this will be fixed in the next update)
See [`app/src/main/res/xml/changelog_master.xml`](app/src/main/res/xml/changelog_master.xml) for the full, version-by-version history.

## Aesthetic

Near-black UI, neon-blue accents, [Unbounded](https://fonts.google.com/specimen/Unbounded) + [Satoshi](https://www.fontshare.com/fonts/satoshi) type.

## Building

Uses the standard Gadgetbridge Gradle setup. Pulse ships as the `mainline` flavour:

```bash
./gradlew :app:assembleMainlineDebug
```

The APK lands in `app/build/outputs/apk/mainline/debug/`.

## Privacy

Like Gadgetbridge, Pulse keeps **everything on your device**. There are no accounts, no analytics, and no data ever leaves your phone except to talk to your watch (and, optionally, to fetch weather).

## Credits & licence

Pulse is built on the excellent work of the [**Gadgetbridge**](https://codeberg.org/Freeyourgadget/Gadgetbridge) project and the entire Garmin device stack it provides. Huge thanks to all of its contributors.

Pulse is licensed under the **GNU Affero General Public License v3.0** (AGPLv3), the same as Gadgetbridge. See [`LICENSE`](LICENSE). As a fork, the source stays open — if you distribute a build, you must make the corresponding source available under the same terms.

> Pulse is an independent, unofficial fork. It is not affiliated with or endorsed by Gadgetbridge, Garmin, or any wearable vendor.
</content>
