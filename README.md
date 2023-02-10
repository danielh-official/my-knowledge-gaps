# My Knowledge Gaps

A list of all the things I have yet to learn. Perhaps someone can give me a hint?

## Obsidian Plugin Development

### How do I get an Obsidian plugin to check if another plugin is already installed?
#### Details
- I need to know in order to implement Advanced URI detection and integration with [Obsidian Things Link 2](https://github.com/danielh-official/obsidian-things-link-2).
#### Answer
> No answer yet.
### How do I get a metadata field (e.g., id)?
#### Details
- This may not be necessary for [Obsidian Things Link 2](https://github.com/danielh-official/obsidian-things-link-2), but if I can't run a command from another plugin or return the id from running the "Advanced URI: copy URI for current file" command, then I need to have some other way of reading the metadata's id field.
#### Answer
> No answer yet.
### How do I run a command from another plugin?
#### Details
- For [Obsidian Things Link 2](https://github.com/danielh-official/obsidian-things-link-2), I would like to run the "Advanced URI: copy URI for current file" command as part of my workflow of getting both the native Obsidian URL and the Advanced URI Url into the notes of the resulting Things task.
- This would speed up production, as I would be relying on the code of Advanced URI to handle things like
  - Give the note an id if one doesn't exist
  - Add the note's id to the clipboard
#### Answer
> No answer yet.
### How do I get .env to run properly?
#### Details
- I can't make .env variables work with Obsidian.
- When I reference them using process.env, they always come up blank.
- I've installed dotenv and have tried putting `dotenv.config()` in places like `main.ts`, but I'm still not able to retrieve a dotenv value.
- My other option is using a .gitignore-d JSON file, but I'd rather stick to .env if I can help it.
- The problem is happening in [Notion x Obsidian Plugin](https://github.com/danielh-official/notion-x-obsidian-plugin) mainly, though I haven't tested it with my other Obsidian plugin projects, so I can't say if the problem's native only to that specific repository or to Obsidian plugins as a whole.
#### Answer
> No answer yet.
