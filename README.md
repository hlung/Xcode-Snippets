# Xcode Snippets

My collection of useful Xcode code snippets! It has been a great time-saver for me so I decided to share it with everyone :)

## Using these Snippets

- Go to your Xcode user's code snippets directory, at `~/Library/Developer/Xcode/UserData/CodeSnippets`. Create folder if it doesn't exist.
- In that folder, you can either:
  * run `git init`, then `git pull https://github.com/hlung/Xcode-Snippets` to that folder (recommended, easy update), OR...
  * download ZIP of this repo, extract `.codesnippet` files to that folder
- Restart Xcode.
- Enjoy!

**Note:** Each code snippet has a unique `IDECodeSnippetIdentifier` key, which Xcode generates when I created each snippet. There's a small chance that they will collide with your existing snippets. Fingers crossed.

## Creating your own Snippets

In Xcode 4 or 5, open a workspace and toggle the right sidebar to be visible. On the bottom, there is a panel with four icons in the header. Click on the `{ }` icon to open the Code Snippets Library.

Highlight your code block and drag it to the Code Snippet panel. Make sure to match the suggested platform, language, and completion scope.
