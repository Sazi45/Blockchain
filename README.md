This project demonstrates a minimal blockchain built with Python and Flask.
Features:
- Proof-of-work mining
- Block creation
- Blockchain validation

Step 1: Run the project on Vsual Studio 2022.
You should see a CMD window show up on your screen with the following contents:
 * Serving Flask app 'node_server'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://10.210.147.52:5000
Press CTRL+C to quit
127.0.0.1 - - [29/Oct/2025 19:02:11] "GET /get_chain HTTP/1.1" 200 -
127.0.0.1 - - [29/Oct/2025 19:02:12] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [29/Oct/2025 19:02:43] "GET /mine_block HTTP/1.1" 200 -

>> This means the Flask web server (blockchain API) is running successfully on port 5000. <<

Step 2: Open Your Browser.
Go to this link:
http://127.0.0.1:5000/get_chain
You should see your blockchain displayed as JSON

Step 3: Mine a New Block
Visit:
http://127.0.0.1:5000/mine_block

