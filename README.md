# This Week's Rhythm

A single-file weekly planner for intermittent fasting, built on the protocols from *The Essential Guide to Intermittent Fasting for Women* by Megan Ramos — and built deliberately for imperfect humans. It plans your week around your life, adjusts without judgment, and never treats a changed day as a failed one.

Fasting hours are **rebuilding days** (when your body heals) and eating hours are **nourishing days** (when it rebuilds with food). The planner's job is to arrange them around your actual week — the dinner out, the period-hunger day, the day you were traveling and accidentally stretched longer.

Live: https://nelacc17.github.io/weekly-fast-planner/

## What it does

**Plan the week in three taps.** Pick a protocol — daily 16:8/18:6, 24h dinner-to-dinner or lunch-to-lunch, 36h, 42h, 2×48h, or 2×66h. Mark the days that need to stay easy (social dinners, hard days), and the planner places the rebuilding stretches around them, properly spaced. Don't like the layout? Ask for another.

**The plan is a suggestion, not a contract.** Tap any meal on any day to switch it on or off. Your edits *are* the plan — there are no "deviation" badges, no comparisons against what you "should" have done. A day with one meal counts as a rebuilding day, because ~23 hours without food is what it is, regardless of technicalities.

**Set your meal times once.** Breakfast, lunch, and dinner times turn the abstract plan into an actual schedule — every day shows when you'll eat, and the exported PDF becomes something you can put on the fridge.

**Export a print-friendly PDF.** One tap produces a clean A4 week table — meals bold, rebuilding slots as faint dashes, no ink-hungry dark boxes.

**A pregnancy & breastfeeding mode that stays useful.** Fasting isn't recommended during pregnancy or breastfeeding, so checking the box switches the planner to a different tool instead of a locked screen: pick when you finish dinner and how long your overnight rest is (11–13h), and it calculates your breakfast, lunch, and dinner rhythm — three nourishing meals, no grazing, nothing tighter.

**Gentle guardrails, never locks.** The only warnings are safety-shaped: back-to-back full rebuilding days that quietly merge into a 60+ hour stretch, or more than three full rebuilding days in a week. Everything else is neutral description: *"This week holds 3 rebuilding days (1 full) · 4 nourishing days · 1 easy."*

**A Guide tab for the hard moments.** Fasting fluids that never break the rhythm, training wheels for a wobbling stretch (and what *doesn't* count as one), when to stop and eat immediately, and why hungrier days — period, stress, travel — are real days, not failures.

## Philosophy

The app was shaped around one idea from the book: **progress, not perfection.** If a rebuilding day ends early, the hours still counted — pick up at the next planned meal, no make-up stretches. If a stretch runs long, enjoy it, but don't let the plan inflate to match your best days. The interface refuses to manufacture guilt: no streaks, no red marks, no failure states.

## Running it

It's one HTML file with zero build steps.

- **Locally:** open `weekly-rhythm-planner.html` in a browser.
- **GitHub Pages / your own server:** drop the file in and open it. Your plan persists in the browser's local storage on that device.
- The only external dependencies are two PDF libraries (jsPDF + AutoTable) and Google Fonts, loaded from CDNs. Everything else is inline.

Note: storage is per-place — a plan saved on one host or device doesn't sync elsewhere.

## Disclaimers

This is a personal planning tool, not medical advice. Fasting isn't appropriate for everyone — not during pregnancy or breastfeeding, not when malnourished, and only under medical supervision if you take medication for diabetes, blood pressure, or thyroid conditions. Stop any fast when you feel unwell *or uncertain*, and talk to your doctor.

Protocol structures and guidance are based on *The Essential Guide to Intermittent Fasting for Women* by Megan Ramos with Eve Mayer (2023). This project isn't affiliated with or endorsed by the author — buy the book; it's the why behind every button here.
