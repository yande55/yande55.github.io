# Mintybug: cutting AI cost per design chat by about 11x

Live product: https://mintybug.ai (built solo)

**What I owned:** the whole product, including how it talks to the AI.

**The problem:** creators design their story worlds by chatting with an AI. Every message in that chat re-sent the full set of world rules, about 31,000 tokens each time. A 20-message session used about 621,000 tokens, which was too slow and too expensive to run.

**My choice:** send the full rules once, when the design starts. For follow-up messages, send a shorter version instead.

**The result:** the same 20-message session now uses about 56,000 tokens, about 11 times less.
