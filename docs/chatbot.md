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
    <h1>Custom-trained AI Chatbot</h1>
    <textarea id="inputText" rows="7" cols="50" placeholder="Enter your text"></textarea><br>
    <button id="submitButton" onclick="submitText()">Submit</button>
    <h2>Response:</h2>
    <p id="response"></p>

    <script>
        function submitText() {
            let inputText = document.getElementById('inputText').value;

            fetch('https://morning-springs-03261.herokuapp.com/chatbot', {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json'
                },
                body: JSON.stringify({ input_text: inputText })
            })
            .then(response => response.json())
            .then(data => {
                document.getElementById('response').innerText = data.response;
            });
        }
    </script>
</body>
</html>
