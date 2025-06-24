# Project Title  
**Open-Source Social Media Data Donation Tool**

## Description

Social media platforms are evolving rapidly, with users encountering a wide variety of content, including posts from creators, brands, and increasingly, AI-generated material. To understand how users engage with their feeds, we need insights into which content captures attention, how long users spend on different types of posts, and what influences their behavior. This understanding is crucial for creators, marketers, and anyone interested in the dynamics of online communities.

Currently, platform APIs provide aggregate data but do not capture individual user behaviors or the nuances of engagement with specific content types. This project aims to create an open-source browser extension that allows users to voluntarily donate their anonymized social media interaction data. The goal is to supplement platform API data with real user engagement metrics, enabling a more comprehensive analysis of how users interact with all types of content, including, but not limited to, AI-generated material.

The solution will be designed to align with our existing systems and to allow other developers to contribute to the codebase.

## Problem Statement

- **Limited insight into user engagement:** Current data collection methods do not reveal detailed, individual user behaviors or the nuances of engagement with specific types of content.
- **Need for enriched datasets:** Combining user-donated data with platform API data is essential for researchers and policymakers to understand how users interact with content, including both traditional and AI-generated posts.
- **Incentivizing data sharing:** Users are unlikely to share their data without clear benefits or incentives, necessitating innovative approaches like gamification.

## Proposed Solution

- **Open-source browser extension:** Users install the extension to donate anonymized social media interaction data.
- **Integration with existing system:** The tool will align with our current infrastructure and workflows.
- **Gamification:** Features like leaderboards will be considered to encourage voluntary participation.
- **Developer-friendly:** The codebase will be open for community contributions.

## Expected Outcomes

- **Open-source tool:** A browser extension for data donation, available for multiple platforms.
- **Enriched datasets:** User-donated data will supplement data collected from platform APIs.
- **Community engagement:** The project will be open for developer contributions and extensions.

## Tasks and Milestones

1. **Research and planning (Week 1):**
   - Review platform APIs and existing tools.
   - Define data collection scope, privacy, and consent mechanisms.
   - Review browser extension compatibility across browsers—at least Google Chrome and Safari—including how data can be collected, given differences in browser architecture and privacy mechanisms. Consider using WebExtension standards to maximize compatibility and address browser-specific privacy controls and data collection limitations.

2. **Extension development (Weeks 2–4):**
   - Build a browser extension for at least two major social media platforms compatible with both Google Chrome and Safari.
   - Implement data anonymization and user consent.
   - Ensure compatibility with our existing system.

3. **Gamification and open-source setup (Week 5):**
   - Build a browser extension for at least one major platform.
   - Design and integrate gamification features (time permitting).

4. **Documentation and handover (Week 6):**
   - Prepare codebase for open-source contribution.
   - Write clear documentation for users and developers.
   - Hand over the project to the community for ongoing development.

## Acceptance Criteria

- **Single Purpose:** The extension has a clear, single purpose: to collect and donate anonymized social media interaction data from consenting users.
- **User Consent:** The extension must obtain explicit user consent before collecting or sharing any data.
- **Data Anonymization:** All donated data is anonymized before transmission.
- **Platform Compatibility:** The extension works on at least one major browser and one major social media platform.
- **Integration:** The extension aligns with the existing system’s data collection and processing workflows.
- **Open Source:** The codebase is publicly available and allows for community contributions.
- **Documentation:** Comprehensive documentation is provided for both users and developers.
- **No Unnecessary Permissions:** The extension requests only the minimum permissions required for its stated purpose.
- **Gamification (if implemented):** Gamification features are optional but, if included, must function as described and not interfere with core data donation.

## Bounty

**10,000 INR**

## Organization

**SimPPL**

## Mentor

**Dhara Mungra**

## Additional Notes

This project builds on our ongoing work in social media intelligence and disinformation analysis. The open-source approach supports transparency, community involvement, and aligns with our broader goals of understanding user engagement with all types of content on social media platforms. AI-generated content is a relevant and important part of this landscape, but the focus remains on understanding engagement with all content modalities.
