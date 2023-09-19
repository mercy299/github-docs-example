# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share**  code. A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to __copy and paste__ their code to replicate or research issues.

- In order to create codeblocks, you need to use three **(3)** backticks (`)  <sup> [1]</sup>
- This is not to be confused with quotations (')
- You can also specify the language on top of the code

``` html
# Simple span in a div
        <div class="hamburger" @click="toggleDiv">
            <span class="bar"></span>
            <span class="bar"></span>
            <span class="bar"></span>
        </div>

```

![Rectangle 32](https://github.com/mercy299/github-docs-example/assets/44053861/2e88b038-7a13-4a2f-9ea6-e13864fdb546)

[<sup>[2]</sup>](#references)

- Make a note of where the backtick button is located. 
- It should appear above the tab key, but it may vary based on your keyboard layout.
- Good Cloud Engineers use code blocks for both code and errors that appear in the console.

## Step 3 - Use Github Flavoured Task Lists

Githuhb extends markdown to have a list where you can check off items 

- [x] Finish step 1
- [ ] Finish step 2
- [x] Finish step 3

## Step 4 - Emojis

GFM supports emojis

| Name | ShortCode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud:| 
| Grin | `:grin:` | :grin:|


## Step 5 - how to create a table 

You can use the following markdown format to create tables
```markdown
| Name | ShortCode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud:| 
| Grin | `:grin:` | :grin:|

```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#references)

## References
- [Github flavoured markdown](https://github.github.com/gfm/)
- [GFM - Tasks Lists](https://github.github.com/gfm/#task-list-items-extension-) <sup>[1]</sup>
- [Git Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- [GFM - Tables (Extension)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
