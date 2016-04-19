# Alice Bot AIML Samples

This repository contains a collection of simple AIML samples that you can use as a starting point for your own Alice bots.

* **adventure.aiml:**
  Uses a combination of conversational variables and topic to simulate a classical text-adventure game. (In Italian.)
  Test this bot by looking for the “PDGT Lab Bot” in the [Pandorabots Clubhouse](https://playground.pandorabots.com/en/clubhouse/).
* **learn.aiml:**
  Acquires information from the user, both using conversational variables (that is, `<get>` and `<set>` tags) and the learning facilities supported by AIML (the `<learn>` tag).
* **that.aiml:**
  Shows how the AIML pattern matching can be extended using the conversation history, by using the `<that>` tag.
* **topic.aiml:**
  Shows how AIML categories can be put into topics and thus excluded or included based on the conversation's current topic (which works like any other conversational variable and can be set via `<set name="topic">`).
* **wildcard.aiml:**
  Exemplifies wildcard priority, the `<star>` tag, wildcard indexing and wildcard auto-splitting.
