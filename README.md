# Arqan Tartys Online

Interactive Kazakh physics tug-of-war for grade 10: 40 questions, nicknames, teacher-controlled teams and automatic scoring.

Run with Node.js 24: `node server.mjs`. The server contains the web assets and database schema; no dependencies are required.

For Render choose a Node web service, build `node --check server.mjs`, start `node server.mjs`, and the Free compute plan. `PORT` is provided by Render.

Free Render instances can sleep and restart. Current rooms in local SQLite are then lost; create a new room for the next lesson. Persistent hosting or an external database is required to retain rooms across instance replacements.

The server accepts `PUBLIC_ORIGIN` if a proxy does not preserve the original public scheme and host.
