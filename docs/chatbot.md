---
title: Chatbot
---
# Support Chatbot
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot</title>
</head>
<body>
    <h1>Chatbot</h1>
    <textarea id="input_text" rows="7" cols="50" placeholder="Enter your text"></textarea>
    <button onclick="sendText()">Send</button>
    <h2>Response</h2>
    <div id="response" style="border: 1px solid black; padding: 10px;"></div>

    <script>
        async function sendText() {
            const inputText = document.getElementById('input_text').value;
            const response = await fetch('https://infinite-stream-82211.herokuapp.com/chatbot', {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json'
                },
                body: JSON.stringify({ input_text: inputText })
            });
            const data = await response.json();
            document.getElementById('response').innerText = data.response;
        }
    </script>
</body>
</html>
