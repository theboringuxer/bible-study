#Bible Study Skill

A Claude skill that turns any Bible verse or short passage into concise, easy-to-read study notes.

Give it a reference like "John 3:16", a question like "what does Proverbs 27:17 mean?", or even a paraphrase like "the verse about not worrying", and it returns the same four-part format every time.

What you get
Text (ESV): the verse in the English Standard Version
Other common renderings: the same verse in NIV and NKJV
Meaning & Application: one or two short paragraphs. It opens with who is speaking, to whom, and why, then explains the meaning and how it applies to daily life.
Related Scriptures: 2-4 cross-references, each with a short phrase naming the connection

Notes are built to be read in about a minute. No word studies, historical deep dives, or long commentary unless you ask for them.

Translations

Only three translations are supported: ESV (primary), NIV, and NKJV. You can ask for NIV or NKJV as the primary text. Requests for any other translation are declined, and one of these three is offered instead.

Accuracy
Verse wording is checked by web search every time (esv.org for ESV, Biblia or Bible Hub for NIV and NKJV). The skill never quotes from memory.
If a translation can't be confirmed, that line is left out and the notes say so. The rest is still delivered.
Each cross-reference is checked to make sure it exists and supports the stated connection.
Only the requested verse or passage is quoted. For passages longer than about 5 verses, only the key verse(s) are quoted and the rest is summarized.
Where faithful Christians read a verse differently in a significant way, the notes mention the range in one line instead of picking a side.
Installation
Keep the skill in a folder named bible-study containing SKILL.md. The folder name must match the name field in the file.
Package the folder as a .skill file (a zip of the folder) and add it in Claude's skill settings.

Optional: if you also have a scripture-accuracy skill installed, this skill will use it for citation and context checks. It works fine without it.

Usage

Just ask in plain language:

John 3:16
What does "iron sharpens iron" mean?
Study Romans 8:28-30
Explain Philippians 4:13, use NIV
Customizing

All behavior lives in SKILL.md. Common edits:

Translations: change the Translations section and the Output Format list
Length: adjust the "1-2 short paragraphs" rule under Meaning & Application
Depth: remove the "No extra sections" guideline to allow word studies or background
Notes

Scripture quotations are retrieved at request time from the sources above. ESV, NIV, and NKJV are copyrighted translations, so use of the quoted text is subject to their publishers' terms.
