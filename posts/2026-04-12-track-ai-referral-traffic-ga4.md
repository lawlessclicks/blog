---
title: "How to Track AI Referral Traffic in Google Analytics 4"
date: 2026-04-13
canonical_url: https://lawlessclicks.com/ai-geo-optimization-for-lawyers/track-ai-referral-traffic-law-firm-ga4/
syndicated_to:
  - https://dev.to/lawless-clicks/how-to-track-ai-referral-traffic-in-google-analytics-4-3odj
tags: [analytics, ai, seo, programming]
---
> Originally published at [lawlessclicks.com](https://lawlessclicks.com/ai-geo-optimization-for-lawyers/track-ai-referral-traffic-law-firm-ga4/). Also on [Dev.to](https://dev.to/lawless-clicks/how-to-track-ai-referral-traffic-in-google-analytics-4-3odj).

If you run a website that gets recommended by AI tools like ChatGPT, Perplexity, or Google's AI Overview, you might be missing that traffic in your analytics. Most of it gets lumped into generic "Referral" or even "Direct" buckets in GA4.

Here are three ways to fix that, from quick to thorough:

## Method 1: Quick Filter (60 seconds)

In GA4's Traffic Acquisition report, search for these source names one at a time: chatgpt, perplexity, copilot, gemini, claude, deepseek. If any show up, you're already getting AI referral traffic.

## Method 2: Custom Channel Group (Recommended)

Create a dedicated channel in GA4 using a regex pattern that matches all known AI referral domains:

chatgpt|openai|perplexity|copilot|bing.com/chat|gemini|claude|anthropic|deepseek|grok|you.com|phind|poe.com

This permanently segments AI traffic into its own channel so you can track trends over time.

## Method 3: GA4 Exploration

Build a custom Exploration with an AI-specific segment. This lets you compare how AI-referred visitors behave versus organic or direct visitors — time on site, pages per session, conversion rates.

## The Hidden Traffic Problem

Not all AI-driven visits show a recognizable referrer. When someone reads a ChatGPT recommendation and types your URL directly, that shows up as "Direct" in GA4. Tracking branded search volume alongside referral data gives you a more complete picture.

## Why This Matters

AI-referred visitors tend to convert at higher rates because they arrive with a recommendation rather than comparison-shopping. Understanding this channel helps you optimize for it.

---

*Originally published at [Lawless Clicks](https://lawlessclicks.com/ai-geo-optimization-for-lawyers/track-ai-referral-traffic-law-firm-ga4/) — we help businesses track and grow their AI visibility.*
