# Demystifying Speed Tooling (Google I/O ’19)

https://www.youtube.com/watch?v=mLjxXPHuIJo

## Foundations

### 1. Benchmark with PageSpeed Insights

* still the best starting point for everyone

### 2. Iterate with Lighthouse via Devtools > Audits

* now with stack packs - tailored advice to your stack (e.g. Wordpress)

### 3. Track your field data with the CrUX Dashboard

* Google Data Studio report built on CrUX data

### 4. Understand key speed metrics

FCP, FID, TTI + new metrics in development:

* layout stability: https://gist.github.com/skobes/2f296da1b0a88cc785a4bf10a42bca07 (origin trial, too)
* largest contentful paint

## Taxonomy of speed tooling

![taxonomy of speed tooling](taxonomy.jpg)

## Plumbing

### Budgets

* Docs - https://developers.google.com/web/tools/lighthouse/audits/budgets

* Budget calculator - https://perf-budget-calculator.firebaseapp.com/

### Devtools > Performance

* Devtools > Performance Docs - https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/

### Custom metrics

* Element timing - https://developers.chrome.com/origintrials/#/view_trial/3954160472831295489 (origin trial)

