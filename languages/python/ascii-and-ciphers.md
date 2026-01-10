# ASCII (For Encryption)

## Why I Needed This
While working on my SentryVault project, I needed a way to encrypt and decrypt messages. To do that, I had to understand how computers handle characters.

## What ASCII Is
ASCII is a standard that assigns a number to every character.  
Computers don’t understand letters or symbols — they only understand numbers.

Examples:
- `'A'` → 65
- `'B'` → 66
- `'0'` → 48

## The Only Two Python Functions I Needed
Python makes working with ASCII simple:

- `ord()` → character to number  
  ```
  ord('A')  # 65
  ```
- `chr()` → number to character
  ```
  chr(65)  # 'A'
  ```

  ## Why This Works for Encryption
  Once a character is a number, I can apply a shift to it
  
  Example:
  
  - `'A'` → 65  
  - Shift by 2 → 67  
  - chr(67) → `'C'`
  
  This explains why "AB" becomes "CD" when shifted by 2.

  ## Important Reminder
  ASCII applies to all characters, not just letters.
  
  Example:
  
  - `'0'` → 48  
  - Shift by 5 → 53  
  - chr(53) → `'5'`
  
  I’m not doing math on numbers — I’m moving along the ASCII table.
