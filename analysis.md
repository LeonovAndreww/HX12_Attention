# Analysis

## Layer 3, Head 7

This head looks for the same words and punctuations in the sentence. If some word is appeared, this head will try to find the next one that is the same or has a similar meaning (e.g. "quick" and "fast", "and" and ",", "red" and "yellow")

Example Sentences:
- The quick brown [MASK] jumps over the brown fast dog. 
- This [MASK] sells yellow, red, black and white shirts.

## Layer 4, Head 6

This head looks exactly at the previous word and doesn't care about anything else.

Example Sentences:
- The quick brown [MASK] jumps over the brown fast dog. 
- This [MASK] sells yellow, red, black and white shirts.

