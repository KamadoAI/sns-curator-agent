# SNS Curator AI Agent

## 🌐 Overview

AI agent designed to search for the most relevant content based on keywords. It enables users to engage with content on X (and other SNSs) by liking, replying, retweeting, and sending DMs with charactor's comments. This innovative approach aims to generate new types of user engagement and enhance interaction on social media.

## 🌟 Product Vision

Our vision is to revolutionize user engagement on social media platforms by leveraging AI to curate and interact with content intelligently. We aim to empower users to connect with their audience more effectively and foster meaningful interactions.

## 🎯 Objectives

1. **Intelligent Content Discovery**: 
   - Utilize AI algorithms to search and identify relevant content/account based on user-defined keywords. 

2. **Enhanced User Engagement**:
   - Enable users to like, reply, retweet, and send DMs to foster deeper connections with their audience.

3. **Multi-Platform Support**:
   - Extend functionality to various social media platforms, ensuring a broad reach and versatility.

## 🚀 Getting Started

### Prerequisites

- Node.js (version >v22 recommended)
- npm/bun

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd yourproject
   ```

2. Install dependencies:
   ```bash
   bun i
   ```

3. Configure environment variables:
   - Create a `.env` file in the root directory and add your credentials:
        ```
        TWITTER_USERNAME=    # Account username
        TWITTER_PASSWORD=    # Account password
        TWITTER_EMAIL=       # Account email

        # for v2 api support
        TWITTER_API_KEY=key
        TWITTER_API_SECRET_KEY=secret
        TWITTER_ACCESS_TOKEN=token
        TWITTER_ACCESS_TOKEN_SECRET=tokensecret
        ```

### Usage

To run the scraper, execute the following command:

### Tech stack
- [agent-twitter-client](https://github.com/ai16z/agent-twitter-client)