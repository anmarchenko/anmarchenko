Hi there 👋 I'm a software engineer passionate about building the best products and making real impact by solving hard problems, making sure that we solve the right problems, and [delivering shareholder value](https://www.seangoedecke.com/shareholder-value/).

Currently I work on Datadog Test Optimization product that makes your tests go brr 🏎️

### Writing
- [How we built a Ruby library that saves 50% in testing time @ Datadog](https://www.datadoghq.com/blog/engineering/ruby-test-impact-analysis/)

### What I worked on
- [Test Better, Build Better: The Betterment Approach](https://www.youtube.com/watch?v=8uuZH-V6rbo) - how Betterment tamed their CI using Datadog Test Optimization and the client library I built
- [Adventures in garbage collection](https://shopify.engineering/adventures-in-garbage-collection) - how we chased down the issue that destroyed our p99 latency at Shopify

### Where I worked
- 🐶 [Datadog](https://github.com/DataDog): I created Ruby library for Datadog Test Optimization product ([datadog-ci](https://github.com/DataDog/datadog-ci-rb)). It helps people to take their CI time from 40 minutes to 9, lift success rates from <50% to 95.4%, reduce the number of flaky tests from 3-digits-number to almost 0, and cut compute spend in half. For this library I created extremely low overhead [test impact analysis tool](https://github.com/DataDog/datadog-ci-rb/blob/main/ext/datadog_ci_native/datadog_cov.c) that enables selective test runner that deterministically skips irrelevant tests. I've also [written about test impact analysis in Ruby in depth](https://www.datadoghq.com/blog/engineering/ruby-test-impact-analysis/).
- 🛍️ [Shopify](https://github.com/Shopify): I led a team of 3 backend developers to build order management functionality for the [Shopify Bundles](https://shopify.dev/docs/apps/build/product-merchandising/bundles) app. We released the app in public beta and it is expected to be used by thousands of merchants. I also performed a deep dive on performance issues and discovered a [garbage collection](https://shopify.engineering/adventures-in-garbage-collection) problem in the main Ruby on Rails monolith that powers Shopify.
- 🚗 [SHARE NOW](https://www.share-now.com/de/en/): During the COVID-19 lockdown, I helped our engineering organization to mature and invest in building a competitive advantage for the future post-pandemic. I implemented a dynamic pricing system that increased fleet utilization by 20%, resulting in a 10% increase in profits over the holiday season. I also ensured the internal systems powering SHARE NOW were robust by rewriting the Vehicle Location Tracker, improving its maintainability and resilience.
- 🏗️ [kloeckner-i](https://github.com/kloeckner-i): I built [Part Manager](https://www.kloecknerconnect.com/part-manager/) e-commerce app, which allowed clients to manage their steel contracts online. By utilizing the tools for concurrent data import provided by the Elixir language, I achieved a 6x increase in data import speed.

### Side projects
- 🌍 [Hamster Travel](https://github.com/anmarchenko/hamster-travel) - a travel planner application.
- 🎮 [Igroteka](https://github.com/anmarchenko/igroteka) - keeping track of my gaming backlog.
