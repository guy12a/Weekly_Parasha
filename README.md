# Weekly Parasha

A simple Python script that creates a docx file of this week's Parasha, in English and Hebrew, while replacing instances of יהוה with אלוקים or HaShem.

## Background

During my exchange in Canada, a group of students would meet every week to study this week's Parasha. They would print out the Parasha in Hebrew and in English from Sefaria.org - but the text included mentions of יהוה - requiring the text to be sent to Genizah, instead of being recycled. My goal was to create a very similar docx file to the one Sefaria created, but ommitting the name from the text.  

## Features

The code:
- Accesses Sefaria.org, and retrieves this week's Parasha automatically, in Hebrew and English
- Replaces every mention of יהוה in the English text with "HaShem" and in the Hebrew text with אלוקים
- Writes the resulting text into a docx file, into two columns, side by side, and saves it
