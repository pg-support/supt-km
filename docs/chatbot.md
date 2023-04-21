---
title: Chatbot
---
# Support Chatbot

<!-- Chatbot UI -->
<div class="chat-container">
    <div id="chatbox" class="chatbox">
        <div class="chat-output" id="chat-output"></div>
    </div>
    <form id="chat-input-form" class="chat-input-form">
        <input type="text" id="chat-input" class="chat-input" autocomplete="off" placeholder="Type your message..." />
        <button type="submit" class="chat-submit">Send</button>
    </form>
</div>

<!-- Chatbot CSS -->
<style>
.chat-container {
    width: 100%;
    max-width: 600px;
    margin: 0 auto;
}

.chatbox {
    width: 100%;
    height: 400px;
    border: 1px solid #ccc;
    padding: 20px;
    overflow-y: scroll;
    margin-bottom: 20px;
}

.chat-output {
    font-size: 16px;
}

.chat-input-form {
    display: flex;
}

.chat-input {
    flex-grow: 1;
    padding: 10px;
    border: 1px solid #ccc;
    border-right: none;
    border-radius: 5px 0 0 5px;
}

.chat-submit {
    padding: 10px;
    background-color: #007bff;
    color: #fff;
    border: none;
    cursor: pointer;
    border-radius: 0 5px 5px 0;
}
</style>

<!-- Chatbot JavaScript -->
<script>
document.getElementById("chat-input-form").addEventListener("submit", async (e) => {
    e.preventDefault();
    const chatInput = document.getElementById("chat-input");
    const userMessage = chatInput.value.trim();

    if (userMessage.length > 0) {
        displayUserMessage(userMessage);

        const serverUrl = "https://your-flask-app.herokuapp.com/api/ask";
        const response = await fetch(serverUrl, {
            method: "POST",
            headers: { "Content-Type": "application/json" },
            body: JSON.stringify({ user_input: userMessage }),
        });

        const responseData = await response.json();
        const chatbotResponse = responseData.response;
        displayChatbotMessage(chatbotResponse);
    }

    chatInput.value = "";
    chatInput.focus();
});

function displayUserMessage(message) {
    const chatOutput = document.getElementById("chat-output");
    chatOutput.innerHTML += `<div><strong>You:</strong> ${message}</div>`;
    chatOutput.scrollTop = chatOutput.scrollHeight;
}

function displayChatbotMessage(message) {
    const chatOutput = document.getElementById("chat-output");
    chatOutput.innerHTML += `<div><strong>Chatbot:</strong> ${message}</div>`;
    chatOutput.scrollTop = chatOutput.scrollHeight;
}
</script>
