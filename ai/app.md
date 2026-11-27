# Small iOS apps as a business

How we build and sell small iPhone apps for proven gaps in the App Store, and what we learned.

> We build many small iOS apps for proven gaps in the App Store, without ads, sold only through App Store search. 14 apps built by November 2026. The lesson so far: building is not the bottleneck, distribution is.

## Before building

- Only build where competitors provably make at least about 2,000 USD a month (measured with an app-store data tool).
- Submit 2 apps a week; similar apps spaced apart, so Apple doesn't treat them as spam (guideline 4.3).
- Never use straw-man or other people's accounts to get around spam rules.

## Design rules

- Inside, the app looks like Apple's built-in apps (Settings, Reminders, Timer). If a specific Apple screen is named, rebuild exactly that one.
- Only Apple system colors through the API, never hex values. All buttons in system blue.
- Colored text only on a light tint; on full color, text is white. No thin fonts.
- Always compare side by side with real Apple apps, light and dark mode.
- Logo: one shape showing what the app does, readable at 60 px, background a full gradient in the brand color or black, never a white tile. One brand color per app, used in logo, store headlines and accents. Build three logo options and pick the best next to the five competitor logos; it may not be the palest or least readable in that row.
- Launch screen without a logo (iOS caches it, and an old logo kept appearing).
- Store images light, with a realistic iPhone frame. The first image shows the one feature a stranger gets in 5 seconds.

## Money rules (free and Pro)

- The Pro offer appears once, after the welcome screen.
- Exactly one value-based free limit that a user reaches in the first days. No nagging after that.
- Ask for reviews only with Apple's own dialog, after positive moments: 3 requests in the first month, at least 6 days apart. Never a custom "rate us 1 to 5" pre-question (forbidden by Apple, guideline 5.6.1, and filtering bad reviews is misleading).
- Revenue before reviews: don't change something for a few reviews if it costs sales.
- No data sales, no ads in apps.
- Price decisions come with a chart: revenue against churn, with the break-even point and sources.

## Quality system

- Every bug found gets an automatic check (code pattern, UI robot or design check) so it never comes back in any app.
- Before showing an app: code rules, tests and a test robot that taps everything, cancels everything and measures contrast.
- Check the real first launch: delete, install, tap through.
- Real lessons: a "restore purchases" cancel showed "your purchases were restored" (an error was swallowed); a button inside an overlay above a list did nothing; store screenshots showed an old version because the script used another simulator; a subscriber in Apple's billing grace period would have lost Pro.

## Distribution checklist before every submission

1. Which ONE feature does a stranger understand in 5 seconds? Store image 1 shows it.
2. A two-sentence description: what it does, for whom.
3. Before the one-time Pro offer, the user has already put something of their own in.
4. We used it ourselves like a customer once, first launch to purchase.
5. A second reviewer graded store images, first launch and checkout 1 to 5; anything under 4 went back.
6. No AI image shows someone else's character or brand.

Topic map (all pages): https://dlichters.com/ai/index.md
