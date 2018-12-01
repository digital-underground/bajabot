# Add new intents
- In the nlu.md file, add the intent formatted like `## intent:intent_name`
- Under the intent, list phrases associated with the intent separated by a `-`
- Add the new intent to the `domain.yml` file
- Include the intent to a alread made story or create a new story in `data/stories.md`

# Add actions with text to an intent
- Add the action to the `/data/stories.md` file associated with the intent
- Add the action to the `domain.yml` file
- Under templates in the `domain.yml` file, add the action and the text you would like it to trigger.