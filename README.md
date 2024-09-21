# Regex
Notes on Regular Expression
🚀 Unlocking the Power of Regular Expressions (Regex)! 🚀

💡 What is RegEx?
• Regular expressions are patterns used to search for specific strings.
• Enclosed in / /

💼 Example:
Input: Hello World
RegEx: /Hello/
Match: Hello

🔠 Character Set []:
• Matches any of the characters/numbers inside the brackets.
💠 Example:
/[bh]at/ matches bat, hat.

🚫 Negate Character Set [^]:
• Matches any characters/numbers except the ones in brackets.
💠 Example:
/[^bh]at/ matches anything except bat, hat.

📚 Range [a-zA-Z]:
• Specifies a range of characters.
💠 Example: /player[0-9]/ matches player1, player5.

🎯 Exact Match {}:
• Specifies the exact or range of occurrences.
💠 Example:
• /[0-9]{4}/ matches exactly 4 digits like 0000, 1234.
• /[0-9]{1,5}/ matches digits of length 1 to 5.
• /[0-9]{3,}/ matches 3 or more digits.

⚙️ Meta Characters:
• \d: Matches any digit [0-9].
• \w: Matches any word character [0-9a-zA-Z_].
• \s: Matches any whitespace character.
• \t: Matches a tab character.

🔢 Quantifiers:
• *: Matches zero or more occurrences.
• +: Matches one or more occurrences.
• ?: Matches zero or one occurrence (makes preceding character optional).

📍 Anchors:
• ^: Specifies that the match must start at the beginning of the string.
• $: Specifies that the match must be at the end of the string.

💻 Regex is a powerful tool for text processing, and I love using it for efficient data handling and validation!
