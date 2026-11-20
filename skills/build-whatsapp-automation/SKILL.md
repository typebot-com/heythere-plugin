---
name: build-whatsapp-automation
description: Use when building or changing a business's WhatsApp automation in Heythere, including planning who can write to its number and what each of them needs, checking what the user believes Heythere does on its own, and handing the automation back with what was tried and what was assumed.
---

Heythere's tools, their errors and its docs say what the product does. This skill holds only the method around them.

## Check each belief before building on it

The request often says what Heythere will do on its own, such as pick a contact's language. List each such claim, the user's and your own, and find the sentence of a tool's description or of the [docs](https://heythere.io/docs/llms.txt) that confirms it before the automation relies on it; quote it to the user. When none confirms it, it is an assumption; when one contradicts it, tell the user what Heythere does instead, and build on that.

## List who writes before drawing steps

Before the first step, list everyone who can reach the automation and what each needs:

- the contact who sends the message the automation expects;
- the contact who writes something else, such as a question or a greeting;
- the contact who already went through it, such as someone already registered;
- the contact who stops answering.

Each reaches an end that suits them and tells them what happens next. Decide each question once, as early as it can be decided, and let the paths share what they have in common, so a member reads the graph on the canvas at a glance.

## Brief, don't script

An agent step's instructions say what it is for, in a few short paragraphs; the model finds the how. When the user reports a habit to correct, add one sentence for it rather than a set of rules.

## Say what you checked and what you assumed

When handing back, separate what you verified, in a description, the docs, Heythere's answers or a test, from what you assumed, such as the exact text a website button fills in, so the user corrects an assumption before a customer meets it.
