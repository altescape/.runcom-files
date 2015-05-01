# Vim setup

This repo contains runcom and profile files for Vim, Bash etc. but is primarily for my Vim setup.

Includes colours and plugins installed with vundle.


## Vim tips

### Console window

`q:` will open a console window

---

### Fix formatting

`=` select a block of text and press `=`

---

### Marks

#### Set your marks

`ma` set a mark called `a`

`mz` set a mark called `z`

#### Jump to your marks

`` `a `` jump to mark `a`

`` `z `` jump to mark `z`

#### Jump to start of line of your marks

`'a` jump to start of line for mark `a`

`'z` jump to start of line for mark `z`

---

### Insert text on multiple lines

`Ctrl` + `v` to select a column then `shift` + `I` to enter the text. Press `Esc` shows inserted text.

---

### Copying and pasting

#### Copy word (when cursor is anywhere within word)
`yiw`

#### Paste text and replace word

`viwp`

---

### Insert linebreak without going into insert mode

By adding the following lines to the .vimrc file

```
nmap <S-Enter> O<Esc>
nmap <CR> o<Esc>
```

We can hit `shift` + `enter` whilst in normal mode.

---


