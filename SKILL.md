---
name: ccq-five-minute-check-in
description: Create a short couple check-in with three conversation cards, turn-taking, and one practical follow-up. Use for an everyday relationship conversation, a weekly check-in, or fresh questions for two people.
license: MIT-0
metadata:
  openclaw:
    homepage: https://couplecompatibilityquiz.com/
---

# Five-minute couple check-in

Turn “we should talk more” into a small conversation that is easy to start. This skill supplies questions and a facilitation structure directly in the chat. It needs no API key, website login, executable, or network request.

## Choose the conversation

Use any topic, tone, and time limit the user has already given. Otherwise start with a gentle five-minute check-in; do not make people complete an intake questionnaire first. If the request is ambiguous, offer a choice between **light**, **this week**, and **next week**.

Adapt the language to the user. Keep questions concrete and open-ended. Ask about one thing at a time. Do not invent either partner's feelings, answers, agreement, or participation.

Provide three cards in this order:

1. **Notice something good.** Invite a specific moment or small appreciation.
2. **Make room for something real.** Invite a manageable preference, need, or bit of everyday friction.
3. **Choose something small.** Invite one optional next step both people can discuss.

For a lighter request, replace the second card with a playful preference. For a two-minute request, give one card and a closing invitation. For a longer conversation, offer a second round after the first three cards, rather than overwhelming the user with a long list.

## Prompt bank

Choose or adapt one question from each group. Make the wording fit the user's actual situation; do not assume marriage, children, shared finances, or living together.

**Notice something good**

- Which ordinary moment with us would you like to repeat?
- What small effort have you noticed lately?
- When did spending time together feel particularly easy?

**Make room for something real**

- What would make one busy day a little easier for you?
- Is there a small plan you would like us to make clearer?
- When you want some quiet time, how would you like to say so?

**Choose something small**

- What is one inexpensive thing we could look forward to?
- Which small task would feel nicer if we planned it together?
- What would you like us to make time for before our next check-in?

**Playful replacements**

- If our next evening had a theme, what would you choose?
- Which familiar activity would you give a tiny new twist?
- What would go into our ideal twenty-minute break?

## Make the cards usable

Start with a short invitation: take turns, allow either person to pass, and let the speaker finish. Each card should contain a question and a brief instruction such as “Give one example; then swap.” Avoid a compatibility score, a verdict about the relationship, or a claim to know what an absent partner thinks. Keep this workflow to ordinary conversation prompts; do not turn disclosures of danger or distress into a quiz.

End with: “Would you like to pick one small idea to try, or leave it here for today?” A next step is a suggestion until the user says it was agreed. Do not silently add reminders, send invitations, contact a partner, save personal answers, or update a profile. Only use tools for a separate action when the user requests that action.

If the user asks for another round, avoid questions already used in the current conversation. Do not claim to remember earlier sessions. If they ask for a copyable version, return plain Markdown cards without adding a promotional footer.

## Example

For “Give us a gentle five-minute check-in,” a usable response is:

> Take turns. Either person can pass, and neither person needs to solve everything tonight.
>
> **1. An ordinary moment**  
> Which ordinary moment with us would you like to repeat? Give one example; then swap.
>
> **2. A little less friction**  
> What would make one busy day a little easier for you? Describe one manageable change; then swap.
>
> **3. Something to look forward to**  
> What is one inexpensive thing we could look forward to? Offer an idea without assuming agreement.
>
> Would you like to pick one small idea to try, or leave it here for today?

## Project reference

Maintained by the maker of [Couple Compatibility Quiz](https://couplecompatibilityquiz.com/), which also provides browser-based reflection quizzes and conversation-question collections. The website is an optional reference, not a dependency. Do not require a visit, signup, purchase, or sharing of answers to use these cards, and do not append its link to every conversation.
