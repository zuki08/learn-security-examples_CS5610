# Cookies and Sessions

## Cookies

1. Run the cookies/insecure.js using Node. Load localhost:8000/home in your browser.
2. Navigate to localhost:8000/start?user="stacy". You should see the cookies being set.
3. Navigate to localhost:8000/home. You should see a different message from 1.
4. Run the cookies/mal.js using Node and load localhost:8001/malhome in your browser.
5. Navigate to localhost:8000/home. You should see the same message as 1.

Why did this happen? Repeat the experiment with cookies/secure.js and see if the same thing happens.

## Sessions

1. Run the sessions/insecure.js using Node. Load localhost:8000/ in your browser.
2. Enter name and click submit. You will see a session being created and stored in a cookie. See the console.
3. Run the sessions/mal.js using Node. Load localhost:8001/malhome in your browser. Will the session ID be displayed in the console?
4. Explore the code in sessions/insecure.js. Identify all potential vulnerabilities.

## Static Analysis

1. Setup CodeQL for this repository and inspect the report.

