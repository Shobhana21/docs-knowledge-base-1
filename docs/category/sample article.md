The Playground is a private testing environment in Eddy AI Chatbot where you can interact with your chatbot and validate its responses before making them visible to users. It acts as a safe space to check answer accuracy, test different question scenarios, and preview appearance changes — all without affecting the live chatbot experience on your website.

---

## When to use the Playground

- Use the Playground **before publishing for the first time** to verify that the chatbot responds accurately based on your connected sources.
- Use it **after adding new sources** to confirm the chatbot answers questions based on the latest content.
- Use it **after changing appearance settings** to preview how the chatbot looks before pushing changes live.
- Use it **after publishing** to test ongoing changes without disrupting end users.

---

## Before you begin

- You must have [created an Eddy AI Chatbot](02-create-chatbot.md) with at least one source connected.
- Before the chatbot is published for the first time, the bot and its sources are not live on your site. The Playground is the only way to interact with the chatbot during this phase.

---

## How to test your chatbot in the Playground

1. Navigate to **AI Chatbot** (<img data-block-id="mhkg3rrw-ge5yp1-047" src="https://cdn.document360.io/860f9f88-412e-4570-8222-d5bf2f4b7dd1/Images/Documentation/Frame%201707479697.png" class="inline-icon" mediatype="img" alt="Frame image" width="auto" height="auto" dataalign="center" datadisplay="inline" data-type="media-content" fixaspectratio="false" autoaspectratio="false" shadow="no" border="no" round="no" link="" newtab="" style="width:auto;height:auto;">) in the left navigation bar and click **Customize**.
2. Navigate to the **Playground** (<span class="fa-light fa-comments"></span>) tab.
3. Type a question in the chat input field, just as a user would.
4. Review the chatbot's response.
5. Continue asking questions to test different scenarios and verify accuracy.

<img src="https://cdn.document360.io/860f9f88-412e-4570-8222-d5bf2f4b7dd1/Images/Documentation/image-1769146335286.png" class="article_image" alt="Playground interface showing a test conversation between a user and the chatbot.">

The chatbot is ready for publishing when responses meet your expectations.

---

## How the Playground behaves before and after publishing

| State | Playground behaviour |
|---|---|
| **Before first publish** | The chatbot and its sources are not live. The Playground is a fully private testing space with no impact on end users. |
| **After publishing** | New sources added are synced to the live chatbot immediately. The Playground reflects the latest sources and appearance settings, letting you preview changes before pushing them to the site. |

---

## Best practices

- **Ask questions your real users would ask** — avoid testing only with exact phrases from your documentation. Use varied, natural-language questions to identify gaps in the chatbot's knowledge.
- **Test edge cases** — ask questions the chatbot should not be able to answer and verify it responds gracefully, for example by prompting a ticket escalation.
- **Test after every major source update** — even for sources that sync automatically, validate the chatbot's answers in the Playground before assuming the update is working correctly.
- **Preview appearance changes before publishing** — save appearance or CSS changes and check the Playground first to catch any visual issues before they reach your users.
<!--
## Limits and limitations

- The Playground reflects the chatbot's current training state based on synced sources — it does not simulate every possible end-user scenario.
- Appearance changes previewed in the Playground are not applied to the live chatbot until you click **Publish**.

-->


