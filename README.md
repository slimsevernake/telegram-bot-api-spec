# telegram-bot-api-spec

### [this is a FORK of the Original Repo](https://github.com/PaulSonOfLars/telegram-bot-api-spec)

This repo provides the necessary scripts to scrape the [telegram bot api docs] for method, types, and docstrings.

The main usecase of having this data is expected to be to generate automated libraries which follow the bot api 
documentation to the letter. Assuming the docs are correct, autogenerated libraries provide the following:
- Easy to update. Simply re-generate the code using the new JSON spec.
- Typo free. All methods/fields are guaranteed to be correct.
- No missing fields. If its in the spec, its in your code!

[telegram bot api docs]: https://core.telegram.org/bots/api