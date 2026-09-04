# Cyrca Chronotype Test

The public landing page for [Cyrca](https://play.google.com/store/apps/details?id=com.aistudio.productivitycoach.plqmnz),
the circadian productivity coach for Android.

Visitors take the same 20-question chronotype assessment that ships inside the app —
scoring is a direct port of `ChronotypeQuizScorer.kt`, and the questions, phase windows
and narratives are extracted from the app's `biological_rules.json`. The result page shows
their chronotype, their biological day with real clock times, and links to the Play Store.

Single self-contained `index.html`. No build step, no dependencies.
