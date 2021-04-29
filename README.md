# Somewhere-2
Next-generation personal information management system and desktop environment.

# Design

It might be a tag-centered, purely file-based, self-contained multi-media application for the following reasons:

1. Tag navigation is after all the key
2. It's not ideal to devise more complicated data-based based solutions because it's too complicated: a single CSV is able to keep all the index; Also, not all files in a given folder is tagged, and we must allow folders
3. A tag based navigation is inherently incompatible with traaditional path based navigation in other applications, so it must provide all daily functionalities for most purposes

We will use a Grid view this time, and instead of just searching by tag, we will allow (like MTG Library) a more advanced filter function (e.g. based on file types, dates, etc.) to allow selecting files by criteria (for exporting purpose etc.) - the app will be free and the implementation should be as straightforward as possible so it's easier to maintain.
