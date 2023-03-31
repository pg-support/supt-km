---
title: Chatbot
---

## Support Chatbot

<div>
  <input type="text" id="userQuestion" placeholder="Ask your question..." style="width: 100%;">
  <button id="submitQuestion">Submit</button>
  <textarea id="botResponse" readonly style="width: 100%; height: 200px;"></textarea>
</div>

<script>
const userQuestion = document.getElementById("userQuestion");
const submitQuestion = document.getElementById("submitQuestion");
const botResponse = document.getElementById("botResponse");

submitQuestion.addEventListener("click", async () => {
  const question = userQuestion.value;
  const response = await fetchChatGPT(question);
  botResponse.value = response;
});

async function fetchChatGPT(prompt) {
  const apiKey = "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";
  const response = await fetch("https://api.openai.com/v1/engines/davinci-codex/completions", {
    method: "POST",
    headers: {
      "Content-Type": "application/json",
      "Authorization": `Bearer ${apiKey}`
    },
    body: JSON.stringify({
      prompt: prompt,
      max_tokens: 100
    })
  });
  const data = await response.json();
  return data.choices[0].text;
}
</script>
