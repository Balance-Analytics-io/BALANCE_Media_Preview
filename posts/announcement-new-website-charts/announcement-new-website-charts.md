---
title: Announcing Launch of New Website & Charts!
description: Fast Beautiful DataViz Charts and Newsletter Service Built on SvelteKit
slug: announcement-new-website-charts
published: 2023-3-31
category: announcements
series: false
---

# Announcing Launch of New Website & Charts!

**Highlights**
- New Website & Fast Crisp Charts
- New Email Newsletter Subscription and Website Articles
- Under the Hood of the New Website: Sveltekit and D3 Charts

## Table of Contents

------------

## New Website Introduction

Welcome to the totally revamped BALANCE Website & Application!

We have been deep in the weeds working on this totally bespoke website for many months, and are very excited to finally share what's new.

{% img src="01_landing_page_welcome_shot.png" alt="landing page welcome shot" %}

Before jumping into the "why" and technicals, first a quick demo:

**Email Newsletter Subscription Service:** You are greeted with an email newsletter subscription as soon as you land on the page. We will start bringing Cardano research and analytics right to your inbox.

**Website Article Library:** If you miss an email, there will be a full library of articles to browse from the homepage. Articles will range from pool group and landscape deep dives, to development updates, education, and tutorials.

**Light and Dark Mode:** Check out the new BALANCE Dark Mode vibes, perfect to get lost in on-chain deep dives.  You can also adjust font parameters.

{% video src="02_welcome_in_dark_mode_demo.mov" %}

**Grab Articles by Category:** At the bottom of the website and articles will be article category tags to choose for certain topics of interest. You will then be taken back to the home page with the articles of interest.

**Research Articles:** We aim for highly curated data visualization, research, and analysis in our articles. At the bottom of shareable articles are calls to action to delegate, subscribe, and join our chat in the Matrix to build a community.

{% video src="walking_thru_cf_article_bottom_boxes.mov" %}

## Chart Boards

BALANCE is _way_ more than a Website, it's an Application.

- CIP-50 Chart Board
- Tool Tip
- fast and responsive charts

{% video src="cip_50_chart_welcome_dark_mode_demo.mov" %}

{% img src="avg_resulting_decen_chart.png" alt="group stake vs leverage chart" %}

{% video src="avg_resulting_decen_chart_demo.mov" %}

{% img src="group_stake_v_leverage_chart.png" alt="group stake vs leverage chart" %}

{% video src="stake_v_lev_demo_bubbles.mov" %}

{% video src="stake_v_lev_time_demo.mov" %}

## About & FAQ
- FAQ expanding boxes
- About Page
- ready for more!

{% video src="faq_demo.mov" %}

{% img src="about_page.png" alt="about page" %}

## What's Under the Hood?
- Sveltkit & D3 Charts
- Solid Foundation on rock, ready for building, versitile

### Sveltekit for the Website & Application

{% img src="svelte_kit_homepage_screenshot.png" alt="svelte kit home page screenshot" %}

Basically, [Svelte](https://svelte.dev/) is a new framework and language that has the significant advantages of a fast, clean, and crisp user experience that far out-weighs its predecessor of React and Javascript. 

From the Svelte website: 

> "Svelte is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app. Instead of using techniques like virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.” 

In layman’s terms, running Svelte at build-time compiles your code into lightweight and super simple javascript code, thus the user gets a fast experience. The heavy lifting is done at compile time instead of on-demand in browser time.

**But what is Sveltekit? Above was about Svelte**

Very observant, glad you asked. From the [Sveltekit](https://kit.svelte.dev/) Introduction:  

> “SvelteKit is a framework for rapidly developing robust, performant web applications using Svelte.” 
“Svelte renders UI components. You can compose these components and render an entire page with just Svelte, but you need more than just Svelte to write an entire app.  SvelteKit provides basic functionality like a router — which updates the UI when a link is clicked — and server-side rendering (SSR).”

In layman’s terms again, Sveltekit is the tooling and framework that lets you build a web app using Svelte (and other stuff), including the server-client side fetch and push interactions, shared memory, and full stack capabilities.

Sveltekit is a hot new language that is being adopted for good reason, but it is still very new, has poor documentation at times, and has early growing pains. So, the design decision to use Svelte was not the easy route, but we believe the right decision.

### D3.js for Beautiful Charts

{% img src="d3js_homepage_screenshot.png" alt="d3js homepage screenshot" %}

Ultimately, to make serious, professional grade charts and curated data visualizations, we needed a robust and extensive library that is compatible with Sveltekit.  That ultimately lead us to [D3](https://d3js.org/).

**What is D3 you ask?**

Well, from the D3.js website:

>“D3.js is a JavaScript library for manipulating documents based on data. D3 helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation.”

In layman’s terms, D3 is a robust and mature Javascript visualization library used by the dataviz pros, with the trade off of complexity for additional control and artistic work.  After browsing what is possible from the very creators of Sveltekit showcasing their data visualization story telling, it is _*very impressive*_ and BALANCE was sold.

It should be clear by now BALANCE is going for timeless work and the learning curve investment is worth our time for quality.



## Subscribe to the Newsletter
- Newsletter

{% img src="newsletter_subscribe.png" alt="subscribe to the newsletter" %}