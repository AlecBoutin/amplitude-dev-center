---
title: Amplitude Data Overview (Beta)
description: Get started with Amplitude Data. 
---

Welcome to Amplitude Data's documentation. These docs give you everything you need to start instrumenting your app.

--8<-- "includes/beta.md"

<div class="grid cards" markdown>

- :material-book-open-variant:{ .lg .middle } __Learn the basics__

    ---

    Get familiar with the basics of Amplitude Data.

    [:octicons-arrow-right-24: Understand the basics](#understanding-amplitude-data)

- :material-code-braces:{ .lg .middle } __Amplitude Data SDKs__

    ---

    Find the right Amplitude Data SDK for your app.

    [:octicons-arrow-right-24: See the SDKs](#sdks)
  
- :material-cogs:{ .lg .middle } __Integrations__

    ---

    Learn more about available integrations.

    [:octicons-arrow-right-24: See the integrations](#integrations)

- :material-help:{ .lg .middle } __Get more resources__

    ---

    Explore more resources for Amplitude Analytics.

    [:octicons-arrow-right-24: Resources](#more-resources)

</div>

## SDKs

Our SDKs let you easily instrument Amplitude Data in your apps.

<div class="grid-container">
  <!--android--><div class="grid-item"><a href="/data/sdks/android-ampli" class="sdk-icons"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512"><!--! Font Awesome Free 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License) Copyright 2022 Fonticons, Inc. --><path d="M420.55,301.93a24,24,0,1,1,24-24,24,24,0,0,1-24,24m-265.1,0a24,24,0,1,1,24-24,24,24,0,0,1-24,24m273.7-144.48,47.94-83a10,10,0,1,0-17.27-10h0l-48.54,84.07a301.25,301.25,0,0,0-246.56,0L116.18,64.45a10,10,0,1,0-17.27,10h0l47.94,83C64.53,202.22,8.24,285.55,0,384H576c-8.24-98.45-64.54-181.78-146.85-226.55"/></svg>Android</a></div>
  <!--ios--><div class="grid-item"><a href="/data/sdks/ios-ampli" class="sdk-icons"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M2.09 16.8h1.66V9.76H2.09m.83-.92a.9.9 0 0 0 .92-.9c0-.5-.4-.9-.92-.9a.9.9 0 0 0-.92.9c0 .5.4.9.92.9m6.33-1.78C6.46 7.06 4.7 8.96 4.7 12c0 3.06 1.76 4.96 4.55 4.96s4.55-1.9 4.55-4.96c0-3.04-1.76-4.94-4.55-4.94m0 1.44c1.71 0 2.8 1.37 2.8 3.5 0 2.15-1.09 3.5-2.8 3.5-1.71 0-2.79-1.35-2.79-3.5 0-2.13 1.08-3.5 2.79-3.5m5.25 5.61c.07 1.76 1.5 2.85 3.72 2.85 2.32 0 3.78-1.14 3.78-2.96 0-1.43-.82-2.23-2.77-2.68l-1.1-.25c-1.18-.28-1.66-.65-1.66-1.29 0-.78.73-1.33 1.81-1.33 1.1 0 1.85.55 1.93 1.44h1.63c-.04-1.69-1.43-2.83-3.55-2.83-2.08 0-3.56 1.15-3.56 2.85 0 1.37.83 2.22 2.6 2.62l1.24.29c1.21.29 1.7.68 1.7 1.38 0 .8-.8 1.37-1.96 1.37s-2.05-.57-2.15-1.46H14.5Z"/></svg>iOS</a></div>
  <!--Browser--><div class="grid-item"><a href="/data/sdks/browser-ampli" class="sdk-icons"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Free 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License) Copyright 2022 Fonticons, Inc. --><path d="M0 32v448h448V32H0zm243.8 349.4c0 43.6-25.6 63.5-62.9 63.5-33.7 0-53.2-17.4-63.2-38.5l34.3-20.7c6.6 11.7 12.6 21.6 27.1 21.6 13.8 0 22.6-5.4 22.6-26.5V237.7h42.1v143.7zm99.6 63.5c-39.1 0-64.4-18.6-76.7-43l34.3-19.8c9 14.7 20.8 25.6 41.5 25.6 17.4 0 28.6-8.7 28.6-20.8 0-14.4-11.4-19.5-30.7-28l-10.5-4.5c-30.4-12.9-50.5-29.2-50.5-63.5 0-31.6 24.1-55.6 61.6-55.6 26.8 0 46 9.3 59.8 33.7L368 290c-7.2-12.9-15-18-27.1-18-12.3 0-20.1 7.8-20.1 18 0 12.6 7.8 17.7 25.9 25.6l10.5 4.5c35.8 15.3 55.9 31 55.9 66.2 0 37.8-29.8 58.6-69.7 58.6z"/></svg>Browser</a></div>
  <!--java--><div class="grid-item"><a href="/data/sdks/jre-ampli" class="sdk-icons"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><!--! Font Awesome Free 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License) Copyright 2022 Fonticons, Inc. --><path d="M277.74 312.9c9.8-6.7 23.4-12.5 23.4-12.5s-38.7 7-77.2 10.2c-47.1 3.9-97.7 4.7-123.1 1.3-60.1-8 33-30.1 33-30.1s-36.1-2.4-80.6 19c-52.5 25.4 130 37 224.5 12.1zm-85.4-32.1c-19-42.7-83.1-80.2 0-145.8C296 53.2 242.84 0 242.84 0c21.5 84.5-75.6 110.1-110.7 162.6-23.9 35.9 11.7 74.4 60.2 118.2zm114.6-176.2c.1 0-175.2 43.8-91.5 140.2 24.7 28.4-6.5 54-6.5 54s62.7-32.4 33.9-72.9c-26.9-37.8-47.5-56.6 64.1-121.3zm-6.1 270.5a12.19 12.19 0 0 1-2 2.6c128.3-33.7 81.1-118.9 19.8-97.3a17.33 17.33 0 0 0-8.2 6.3 70.45 70.45 0 0 1 11-3c31-6.5 75.5 41.5-20.6 91.4zM348 437.4s14.5 11.9-15.9 21.2c-57.9 17.5-240.8 22.8-291.6.7-18.3-7.9 16-19 26.8-21.3 11.2-2.4 17.7-2 17.7-2-20.3-14.3-131.3 28.1-56.4 40.2C232.84 509.4 401 461.3 348 437.4zM124.44 396c-78.7 22 47.9 67.4 148.1 24.5a185.89 185.89 0 0 1-28.2-13.8c-44.7 8.5-65.4 9.1-106 4.5-33.5-3.8-13.9-15.2-13.9-15.2zm179.8 97.2c-78.7 14.8-175.8 13.1-233.3 3.6 0-.1 11.8 9.7 72.4 13.6 92.2 5.9 233.8-3.3 237.1-46.9 0 0-6.4 16.5-76.2 29.7zM260.64 353c-59.2 11.4-93.5 11.1-136.8 6.6-33.5-3.5-11.6-19.7-11.6-19.7-86.8 28.8 48.2 61.4 169.5 25.9a60.37 60.37 0 0 1-21.1-12.8z"/></svg>JRE</a></div>
  <!--node--><div class="grid-item"><a href="/data/sdks/node-ampli" class="sdk-icons"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Free 6.1.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License) Copyright 2022 Fonticons, Inc. --><path d="M224 508c-6.7 0-13.5-1.8-19.4-5.2l-61.7-36.5c-9.2-5.2-4.7-7-1.7-8 12.3-4.3 14.8-5.2 27.9-12.7 1.4-.8 3.2-.5 4.6.4l47.4 28.1c1.7 1 4.1 1 5.7 0l184.7-106.6c1.7-1 2.8-3 2.8-5V149.3c0-2.1-1.1-4-2.9-5.1L226.8 37.7c-1.7-1-4-1-5.7 0L36.6 144.3c-1.8 1-2.9 3-2.9 5.1v213.1c0 2 1.1 4 2.9 4.9l50.6 29.2c27.5 13.7 44.3-2.4 44.3-18.7V167.5c0-3 2.4-5.3 5.4-5.3h23.4c2.9 0 5.4 2.3 5.4 5.3V378c0 36.6-20 57.6-54.7 57.6-10.7 0-19.1 0-42.5-11.6l-48.4-27.9C8.1 389.2.7 376.3.7 362.4V149.3c0-13.8 7.4-26.8 19.4-33.7L204.6 9c11.7-6.6 27.2-6.6 38.8 0l184.7 106.7c12 6.9 19.4 19.8 19.4 33.7v213.1c0 13.8-7.4 26.7-19.4 33.7L243.4 502.8c-5.9 3.4-12.6 5.2-19.4 5.2zm149.1-210.1c0-39.9-27-50.5-83.7-58-57.4-7.6-63.2-11.5-63.2-24.9 0-11.1 4.9-25.9 47.4-25.9 37.9 0 51.9 8.2 57.7 33.8.5 2.4 2.7 4.2 5.2 4.2h24c1.5 0 2.9-.6 3.9-1.7s1.5-2.6 1.4-4.1c-3.7-44.1-33-64.6-92.2-64.6-52.7 0-84.1 22.2-84.1 59.5 0 40.4 31.3 51.6 81.8 56.6 60.5 5.9 65.2 14.8 65.2 26.7 0 20.6-16.6 29.4-55.5 29.4-48.9 0-59.6-12.3-63.2-36.6-.4-2.6-2.6-4.5-5.3-4.5h-23.9c-3 0-5.3 2.4-5.3 5.3 0 31.1 16.9 68.2 97.8 68.2 58.4-.1 92-23.2 92-63.4z"/></svg>Node.js</a></div>
</div>

## Integrations

These integrations help you get data in and out of Amplitude Data.

### Sources

#### Data warehouse sources 

--8<-- "includes/integration-catalog-warehouse-sources.md"

### Destinations

#### Data warehouse destinations 

--8<-- "includes/integration-catalog-warehouse-destinations.md"

#### Event streaming destinations

--8<-- "includes/integration-catalog-event-streaming-destinations.md"

### Other integrations

|Integration|Description|
|---|----------|
| [Shopify Plugin](../integrations/shopify-plugin.md)| Amplitude’s app with Shopify is a smart analytics app that automates eCommerce tracking. |
|[Receiving Cohorts from Amplitude](../integrations/sending-cohorts.md)|Sync behavioral cohorts to other partner platforms through a series of REST API calls. |

## Understanding Amplitude Data

Amplitude Data helps companies define, track, and verify their product analytics. It ensures analytics events are captured correctly and consistently across all teams and platforms,
 and enables teams to use their analytics with no need for cleanup or worrying about data integrity and trustworthiness.

For PMs, data analysts, and other data consumers, Amplitude Data provides an always up-to-date Tracking Plan for the entire company.
 It replaces ad-hoc spreadsheets and wiki pages with one centralized Tracking Plan app.
  It minimizes turnaround time with engineering when adding and changing events, and enforces taxonomy standards and conventions across all teams.

For developers, Amplitude Data provides a toolkit that simplifies and accelerates the process of instrumenting analytics across one or more products.
 It automatically generates a type-safe tracking library according to the latest spec, lints code to make sure analytics events are tracked correctly,
  and exposes a unified API that removes the need to understand the ins and outs of each analytics provider.

Amplitude Data works with popular [analytics providers](using-the-tracking-library.md#destinations) (e.g. Segment, Amplitude, Custom Destinations), and popular [developer platforms](using-the-tracking-library.md#sources), and requires no infrastructure changes to your analytics pipeline.

## More resources

- *Help Center*: [Amplitude Data](https://help.amplitude.com/hc/en-us/categories/5078631395227-Amplitude-Data-Beta-)
- *Amplitude Academy*: [Getting Started with Amplitude Data (Course)](https://academy.amplitude.com/getting-started-with-amplitude-data)
