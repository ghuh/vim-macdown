# macdown.vim

> write markdown in Vim with live-reloads in
> [MacDown](https://macdown.uranusjr.com/)

## Usage

Using this plugin requires two things:

- You are on a Mac
- You have [MacDown](https://macdown.uranusjr.com/) installed

To install `macdown.vim`, use your favorite Vim plugin manager (e.g.
[Plug](https://github.com/junegunn/vim-plug)):

```vimscript
Plug 'hashrocket/vim-macdown'
```


**On demand**:

* `<leader>p` (`\p` with default vim config)
* `:MacDownPreview` to invoke by name or in a script

Make some edits to a markdown file and then hit `<leader>p` to view a
preview in Macdown.

**On save for *.md files**:

Add the following to your `.vimrc`:

```vimscript
" execute commands on filetype save
autocmd BufWritePost *.md exec :MacDownPreview
```

### License

macdown.vim is released under the [MIT License](http://www.opensource.org/licenses/MIT).

---

### About

[![Hashrocket logo](https://hashrocket.com/hashrocket_logo.svg)](https://hashrocket.com)

macdown.vim is supported by the team at [Hashrocket, a multidisciplinary
design and development consultancy](https://hashrocket.com). If you'd like
to [work with us](https://hashrocket.com/contact-us/hire-us) or [join our
team](https://hashrocket.com/contact-us/jobs), don't hesitate to get in
touch.
