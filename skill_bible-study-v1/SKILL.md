---
name: bible-study
description: Create clear, easy-to-digest study notes for any Bible verse or short passage. Use when the user wants to understand a scripture, get study notes, explore the meaning of a verse, or see how it applies to life. Triggers include a bare reference (e.g. “John 3:16”), “what does X mean”, “study this verse”, “help me understand”, “bible study on”, “explain this scripture”, “devotional on”, or similar requests for verse understanding.
---

When asked to study or explain a Bible verse (or short passage), produce notes in this exact structure and style. Keep the tone clear, warm, and accessible. Avoid heavy academic language or long digressions. Aim for something a person can read and absorb quickly.

### Translations

Only three translations are available: ESV, NIV, and NKJV. ESV is the primary text by default. Never quote any other translation. If the user asks for one, say it isn't available and offer ESV, NIV, or NKJV instead.

### Output Format

**Text (ESV)**
Quote the verse (or short passage) using the English Standard Version.

**Other common renderings**
- NIV
- NKJV

One per line, with the translation abbreviation.

**Meaning & Application**
Start the first paragraph with one clear sentence that situates the verse (who is speaking, to whom, and in what situation), then continue directly into the core meaning and practical application. Keep the whole section to 1–2 short paragraphs. Be direct and helpful without being preachy.

**Related Scriptures**
List 2–4 relevant cross-references. Include a very brief phrase after each that captures its connection.

### Source Verification
- Verify the exact wording of the primary text and each rendering using web search. Prefer esv.org for the ESV, and Biblia or Bible Hub for the NIV and NKJV. Never quote from memory.
- If a rendering can't be confirmed, omit that line and note it. Deliver the rest of the notes.
- If the primary text can't be confirmed, say so, use the confirmed renderings instead, and ask whether to proceed.
- Confirm each cross-reference exists and says what you claim. For citation and context checks, follow the `scripture-accuracy` skill if it is available.

### Guidelines
- Quote only the exact passage requested. Never extend beyond it for “context.”
- For passages longer than about 5 verses, quote only the key verse(s) in each translation and summarize the rest in Meaning & Application.
- If the user gives a paraphrase without a reference (“the verse about not worrying”), identify the most likely verse, state the reference, and proceed. If two or more verses fit equally well, ask one short question first.
- A range (e.g. “Romans 8:28-30”) counts as a short passage. Keep the output concise.
- Where faithful Christians interpret a verse differently in significant ways, include one brief line noting the range of understanding rather than choosing a side.
- If the user requests a different primary translation from the three available, use NIV or NKJV if they pick one of those. Otherwise keep ESV.
- No extra sections (word studies, extended historical background, lengthy commentary) unless the user specifically asks for more depth.
