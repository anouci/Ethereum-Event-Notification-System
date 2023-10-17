# Ethereum Event Notification System 🛎️ 🔍

Harnessing the [Mobula API](https://developer.mobula.fi/reference/metadata-api) to monitor and notify users of Ethereum smart contract events in real-time through browser notifications.

![Ethereum/Mobula Logo](https://i.imgur.com/R07Cxmk.png)

---

## Table of Contents 📖

- [Features](#features-)
- [Usage](#usage-)
- [Dashboard Setup](#dashboard-setup-)
- [API Reference](#api-reference-)

---

## Features ✨

- **Real-time Event Monitoring:** Instant browser notifications on new Ethereum smart contract events using `push.js`.
  
- **Detailed Insights:** Dive into transaction details associated with specific events.

- **Secure and Reliable:** Empowered by Mobula API for accurate and up-to-date event tracking.

---

## Usage 💡

Input the Ethereum contract address into the dashboard interface to start monitoring its events. With the power of `push.js`, receive instant browser notifications, explore transaction details, and stay updated without missing an event!

---

## Dashboard Setup 🖥️

1. **Choose a Framework:** For ease of use, consider a JavaScript framework like [Vue.js](https://vuejs.org/). It's beginner-friendly and comes with extensive documentation.
2. **Integrate push.js:** To enable browser notifications, incorporate [push.js](https://pushjs.org/) into your project.
3. **Fetch Data:** Use the provided Mobula API endpoint to fetch Ethereum transactions. Axios is a suggested library for HTTP requests in JavaScript.
4. **Display Data & Notify:** Present the fetched data using components or tables and set up notifications using `push.js` when a new event occurs.

---

## API Reference 🌐

Our system predominantly employs the Mobula API's following endpoint:

- **Transactions List:** 
  - **Method:** GET
  - **Endpoint:** `https://api.app-mobula.com/api/1/transactions/list`
  - **Description:** Fetch all ERC20, ERC721 & normal transactions from any EVM-compatible wallets.
  
For comprehensive details on this endpoint, check out the official [Mobula API documentation](https://developer.mobula.fi/reference/gettransactionslist). Simple as that!

---

### Crafted with ❤️ leveraging [Mobula API](https://developer.mobula.fi/) and enhanced with [push.js](https://pushjs.org/).
