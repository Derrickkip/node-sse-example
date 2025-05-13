## Server-Sent Events in Node.js
This is a real-time application built on Node.js to demonstrate Server-sent events.

###How to run
- Clone the repo
- navigate to each of the folders and install the dependencies
- Run the backend `node server.js`
- Run the frontend `npm run start`
- Use curl to add facts `curl -X POST \
 -H "Content-Type: application/json" \
 -d '{"info": "Shark teeth are embedded in the gums rather than directly affixed to the jaw, and are constantly replaced throughout life.", "source": "https://en.wikipedia.org/wiki/Shark"}'\
 -s http://localhost:3001/fact`
