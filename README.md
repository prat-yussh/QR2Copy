# QR2Copy

QR2Copy is a web app that makes ordering prints at a Xerox (photocopy) shop simple.

## The problem

At many Xerox shops, customers send files over WhatsApp or email and the owner has to ask the same questions again and again: how many copies, which pages, color or black-and-white, one side or both. During busy hours, orders get mixed up or forgotten.

## The idea

1. The customer scans a QR code at the shop.
2. They upload a PDF and choose their print options.
3. They submit the order and get a token number.
4. The shop owner sees the order in a queue, prints it, and marks it ready.
5. The customer collects it.

No app install and no sign-up for customers. It works in a mobile browser.

## Planned features

- Customer ordering page (PDF upload, page range, copies, color, sides, paper size)
- Order token and status tracking
- Shop owner dashboard with an order queue
- Printer management
- Support for multiple shops, each with its own QR code and private data

## Tech stack

- **Backend:** Python, FastAPI
- **Database:** PostgreSQL
- **Frontend:** React, TypeScript, Tailwind CSS (planned, after the backend)

## Status

Early development. Currently setting up the project and building the backend step by step.

## Author

Pratyush, final-year BTech Computer Science student.