# GEMINI.md - Project Context for Outli Legal

This directory contains the legal and support documentation for the **Outli** mobile application. These are static HTML files designed to be hosted and linked from within the app or on a website.

## Directory Overview
The project is a **Non-Code Project** consisting of localized and standard legal documents and a support page.

- **App Name:** Outli
- **Primary Technologies:** HTML5, Vanilla CSS
- **Owner/Data Controller:** Nikolai Altergott (Wüstenrot, Germany)
- **Email:** support@outli.live / nikolai.altergott.na@gmail.com

## Key Architectural Points (Current)
- **Core Entity:** The app has transitioned from "Groups/Klubs" to **Activities**. Users create Activities, and others request to join them.
- **Authentication:** Users authenticate exclusively via **Sign in with Apple**. Email addresses are collected during this process.
- **Data Model:**
  - Collected data includes: Name, Email, Date of Birth (Age), Gender, and Profile Picture.
  - Public/Participant Visibility: When a user joins or creates an activity, their **Name, Age, Gender, and Profile Picture** are visible to other participants.

## Key Files
- `index.html`: **Privacy Policy**
  - GDPR-compliant privacy policy.
  - Details data collection and visibility (Name, Age, Gender, etc.).
  - Mentions third-party service providers: Google Firebase and Google Places.
- `termsofuse.html`: **Terms of Use** (Terms of Service)
  - Governs the use of the app, user-generated Activities, and community guidelines.
  - Includes a critical **Safety Disclaimer** (Section 4) regarding real-world Activities organized via the app.
  - Specifies the minimum age requirement (13+).
- `support.html`: **Support Page**
  - Provides contact information for users (email-based support).
  - Contains a brief FAQ (Account deletion, Reporting users).

## Usage
These files are intended to be served as static web pages. 
- The navigation bar in each file allows users to jump between the Privacy Policy, Terms of Use, and Support pages.
- The styling is consistent across all pages, using a clean, iOS-inspired aesthetic.

## Development Notes
- **Styles:** All CSS is internal within `<style>` tags in each HTML file.
- **Updates:** Ensure the "Last updated" date is synchronized across files when major policy changes occur.
