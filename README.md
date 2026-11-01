# tutor

國中、高中 AI 學科老師（也可一般聊天、翻譯）。單檔 `index.html`，純瀏覽器，直接呼叫各家 API。

- 模型：Claude（Haiku／Sonnet／Opus／Fable）、OpenAI（GPT-5.4 mini／GPT-5.5）、Gemini（3.8 Flash／4 Argon）。
- 視覺化：Markdown、KaTeX 公式、Mermaid 圖、```html 互動小圖（沙盒 iframe，不能連網、拿不到 key）。
- 幫手：選 Claude 時可呼叫 `draw_image`（Gemini 3.1 Flash Image，沒 Gemini key 改用 gpt-image-1-mini）與 `ask_expert`（Gemini 3.8 Flash／GPT-5.5 第二意見）。
- API key 由使用者自行貼上，只存在該瀏覽器的 localStorage，不進 repo。
- 線上版：https://shelly-awkward.github.io/tutor/
