1. Initialize three counters: lengthCounter, wordCounter, and vowelCounter to 0.

2. Read the first character of the sentence.

3. Repeat the following steps until the current character is a period:
   a. Increment the lengthCounter by 1.
   b. If the current character is not a space:
      i. Check if the current character is a vowel (e.g., 'a', 'e', 'i', 'o', 'u', case-insensitive).
      ii. If it is a vowel, increment the vowelCounter by 1.
   c. If the current character is a space, increment the wordCounter by 1.

4. After encountering the period:
   a. Increment the lengthCounter by 1 to account for the period at the end.
   b. Increment the wordCounter by 1 to account for the last word.
   c. Output the values of lengthCounter, wordCounter, and vowelCounter as the results.

5. End.
