# URL Shortener Backend

This is the **backend** for a URL shortening service built with **Node.js**, **Express**, and **MongoDB**.

## Description
The backend provides a RESTful API to:
- Create short URLs from long URLs.
- Handle user-defined or automatically generated shortcodes.
- Redirect short URLs to the original long URLs.
- Collect basic analytics (click counts, timestamps, referrers, etc.).
- Enforce link expiration based on a validity period.

This backend is designed to be **consumed by a frontend** or tested via Postman/cURL.

---

## Features

- **Shorten URLs** with optional custom shortcodes.
- **Redirect** short URLs to their original URLs.
- **Track usage statistics** (click counts, timestamps, referrers, location).
- **Link expiration** support.
- **Robust error handling** with descriptive JSON responses.

---

## Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- npm (comes with Node.js)

### Installation

1. Clone the repo (backend folder only):
```bash
git clone https://github.com/Ayush000000007/2201640100104.git
cd 2201640100104
