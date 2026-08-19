# Hebrew Translator

A simple web app for translating between English and Hebrew, with full niqqud, pronunciation, and a note on meaning and register.

Open it here: https://calebcooper2024-creator.github.io/hebrew/

The app asks for an Anthropic API key the first time you use it. That key is stored only in your own browser and is never sent anywhere except to Anthropic.

After each translation, the app double-checks the vowel points against [Nakdan](https://nakdan.dicta.org.il/), the specialist vocalizer from Dicta, an Israeli research nonprofit, and corrects itself if they disagree. Only the Hebrew sentence itself is sent to Nakdan; you can turn this off in Settings.
