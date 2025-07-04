---
seoDescription: Get step-by-step answers from ChatGPT and improve response logic with zero-shot chain of thought prompting.
type: rule
title: Do you get ChatGPT to "think step by step"?
uri: get-chatgpt-to-answer-step-by-step
authors:
  - title: Ulysses Maclaren
    url: https://www.ssw.com.au/people/ulysses-maclaren
created: 2023-04-12T14:06:25.338Z
guid: 6ca8f268-322f-47a0-813d-7e8a0d54c08b
---

By getting ChatGPT to think through its answers step by step, you can receive more logical and coherent responses that break down complex topics or tasks into easily understandable components. This is especially useful for mathematical questions.

<!--endintro-->

Request that ChatGPT thinks through its answer with you. It's similar to telling a maths student to "show their working".

* Add the magic phrase "Let's think step by step"
* This is known as Zero shot chain of thought prompting
* If you're unsure about a ChatGPT correction, ask "I'm not sure if XYZ is right? Can you explain it to me?". It might correct itself if it's wrong
* Ask "Why do you believe that?", "Can you explain why do you think that?", "Can you give me steps on how you got here?", etc. to get an explanation for the AI's reasoning

![Figure: Bad Example - It got the answer wrong](don-t-think.png)

![Figure: Good Example - By getting it to think step by step, it got the answer right](think.png)

::: greybox
**Note:** When you’re using any of the new “reasoning” or “thinking” models—such as OpenAI’s o-series (o1, o3, o4, etc), Google’s Gemini “thinking” variants, and similar - you generally don’t need to add “Let’s think step by step”. These models already run an internal chain-of-thought before replying. Use that phrase only when you actually want the reasoning printed, otherwise it just adds tokens and makes the answer wordier.
:::
