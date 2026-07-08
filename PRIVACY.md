# Privacy Policy — InlineDoubt

Last updated: July 2026

## Overview

InlineDoubt is a Chrome Extension that allows users 
to ask inline doubts about specific lines in AI chat 
answers. The answer appears directly within the same 
page without opening new tabs or scrolling.

## Data We Collect

InlineDoubt does NOT collect any personal data.

We do not collect:
- Names, email addresses, or any identifying information
- Browsing history or web activity
- Chat content or AI conversation history
- Location data
- Payment or financial information
- Authentication credentials or passwords

## Data Storage

The only data stored by InlineDoubt is:
- Your inline doubts and AI replies
- Your optional API key (if you choose to add one)

This data is stored LOCALLY in your browser only 
using chrome.storage.local and chrome.storage.sync.
This data NEVER leaves your device to any server 
we operate. This data is NOT shared with anyone.

## How InlineDoubt Connects to AI Platforms

InlineDoubt uses fetch() calls made directly from 
within the AI platform's own page (content script).

For Claude.ai and Perplexity — the browser 
automatically attaches your existing session to 
these requests, exactly as it would for any normal 
action you take on those pages. InlineDoubt does 
not read, store, or access your session cookies 
directly — the browser handles this automatically.

For ChatGPT, Gemini, DeepSeek, Grok and Meta AI — 
InlineDoubt uses a free API key provided by the user.

## API Keys

For platforms that require an API key, InlineDoubt 
uses a free key provided by the user.

This API key is:
- Stored locally in your browser using 
  chrome.storage.sync only
- Never transmitted to any server we operate
- Only used to make direct API calls to the 
  AI platform you choose
- Never shared with any third party

## Permissions Used

| Permission | Why it is needed |
|---|---|
| storage | To save your doubts and optional API key locally in your browser only |

## Data Sharing

We do not share any data with third parties.
We do not sell any data.
We do not transfer any data outside your browser.
We have no backend server that receives your data.

## Third Party Services

When you ask a doubt, InlineDoubt sends your 
question and selected text directly to the AI 
platform you are using (Claude.ai, Gemini, etc).
This is subject to their own privacy policies:

- Claude.ai: https://www.anthropic.com/privacy
- Google Gemini: https://policies.google.com/privacy
- OpenAI ChatGPT: https://openai.com/privacy
- Perplexity: https://www.perplexity.ai/privacy
- DeepSeek: https://www.deepseek.com/privacy
- Grok: https://x.ai/privacy
- Meta AI: https://www.meta.ai/privacy

## Children's Privacy

InlineDoubt is not directed at children under 13. 
We do not knowingly collect data from children.

## Changes to This Policy

If we update this policy we will update the 
"Last updated" date at the top of this page.

## Contact

For any questions about this privacy policy, 
open an issue at:
https://github.com/Forgewhiz/InlineDoubt/issues
