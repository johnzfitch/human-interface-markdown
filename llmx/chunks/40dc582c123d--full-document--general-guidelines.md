---
chunk_index: 2052
ref: "40dc582c123d"
id: "40dc582c123dbeacbf43b2c2170a595194d8f9213d2a93efc06d8b0eebab5937"
slug: "full-document--general-guidelines"
path: "marker/1987 Apple Human Interface Guidelines - The Apple Desktop Interface/full_document.md"
kind: "markdown"
lines: [2679, 2693]
token_estimate: 787
content_sha256: "bdbc202d644c8ee25b4d73b8f0611b90d577c01a53d99d70368e00cef6197b64"
compacted: false
heading_path: ["General guidelines"]
symbol: null
address: null
asset_path: null
---

# General guidelines

Localization is the process of adapting an application to a specific locale. By making localization relatively painless, you'll ensure that international markets are available for your product in the future. You'll also allow English-speaking users in other countries to buy the U.S. English version of your software and use it, if they wish to, with their native languages. To create easily localized software, you must follow certain guidelines for the use of text, fonts, sorting, and date/time display.

- Make quoted strings that will have to be translated easy for the translator to find. No text the user sees should be in the program code itself. Storing user-visible text in resources will make translation easier.
- If your program relies on properties of the ASCII code table or uses data compression codes that assume a certain number of letters in the alphabet, remember that not all alphabets have the same numbers of characters. German, for example, has 30 characters, English 26.
- Don't assume that all languages have the same rules for punctuation, word order, and alphabetizing. In Spanish, questions both begin and end with a question mark—the beginning one being an upside-down version of the closing one. The roles of commas and periods in numbers issometimes the reverse of what you may be used to—in many countries the number 3,546.98 is rendered 3.546,98.
- D Don't let your program rely on strings having a particular length. Translation will make most strings longer.

- Laws and customs vary. The elements of addresses don't always appear in the same order. In some countries, the postal zone code precedes the name of the city, in other countries it's the reverse. Postal zone codes don't contain the same number of characters in every country, and in some countries they contain letters as well as numbers. The rules for amortizing mortgages and calculating interest rates vary from country to country—even between Canada and the United States.
- Keyboards vary from country to country. Some characters appear on some keyboards and not on others. Keystrokes that are easily performed with one hand in your own country may require two hands in another. In France and Italy, for example, typing numerals requires pressing the Shift key.
- Units of measure and standard formats for time and date differ from country to country. For example, "lines per inch" is meaningless in the metric world—that is, almost everywhere. In some countries, the 24-hour clock prevails. Such culture dependent information can be read from resources so that the application automatically works correctly in countries where those resources have been properly set up.
- Words aren't the only things that change from country to country. Telephones and mailboxes, to name just two examples often used in telecommunications programs, don't look the same in all parts of the world. Either make your graphics culturally neutral, or be prepared to create alternate graphics for various cultures.
- Mnemonic shortcuts that are valid in one language may not be valid in others. Make sure all such shortcuts are also in resources.