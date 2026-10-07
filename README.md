# Dusk Meta App

AI-powered SEO metadata generator for stock contributors. Drop in your images, vectors or videos and get titles, descriptions and keywords ready for the marketplaces, in batches, right on your computer.

**Platform:** Windows 10 / 11 (64-bit) 

**Website:** [Dusk Meta](https://duskmeta.motionmindx.com)

## Features

- Generates titles, descriptions and keywords for JPG, PNG, WEBP, SVG, EPS, MP4 and MOV files
- Batch processing with pause / resume and a rate-limit cooldown
- Adjustable title length, keyword count and keyword casing (lowercase, UPPERCASE, Title Case)
- Generation history with search and one-click CSV export for Adobe Stock, Shutterstock and Freepik
- Automatic updates: the app tells you when a new version is available and installs it for you

## Download and install

1. Open the **Releases** page of this repository and download the latest `Dusk-Meta-App-x.y.z.exe`.
2. Run the installer. No administrator rights are needed.
3. Launch **Dusk Meta App**.

Windows SmartScreen may show "Windows protected your PC" because the installer is not code-signed yet. Click **More info**, then **Run anyway**.

## Getting started

1. Sign in to your Dusk Meta account on the [website](https://duskmeta.motionmindx.com), open your **Profile** page and create an **App token**.
2. In the app, go to **Settings > Account & App Token**, paste the token, press **Verify**, then **Save**.
3. In **Settings > Gemini API Key Management**, add your own Gemini API key (or several).
4. Open **Generate SEO**, add your files and press **Generate SEO**.

## Credits

- Each image or vector costs **1 credit**, each video costs **5 credits**.
- Credits are only charged for files that were generated successfully.
- Unlimited plans are not charged.
- Your balance is always visible in the sidebar.

## Privacy

- Your Gemini API keys, generation history and settings are stored locally on your computer.
- Each asset is downscaled on your machine, and the downscaled copy is sent to Google's Gemini API using your own key.
- Dusk Meta's servers are only contacted to verify your app token and keep your credit balance up to date. GitHub is contacted to check for updates.

## Updates

On startup the app checks `version.json` in this repository. If a newer version exists it shows what is new, and installs it after you press **Install**. Your token, API keys and history are kept.

## About this repository

This repository hosts the released installers (see **Releases**) and `version.json`, which the app reads to detect new versions. Please do not edit `version.json` unless you are publishing a release.

## Support

saifulalomsiam2007@gmail.com

&copy; 2026 Motion Dusk. All rights reserved.