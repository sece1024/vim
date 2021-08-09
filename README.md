# vim

## 模式

v：可视模式，V： 可视行模式，<kbd>Ctrl</kbd>+<kbd>v</kbd> ：可视块模式



## 插入文本

i：插入模式

### 批量插入

> 
>
> 按8，再按i，进入插入模式，输入=， 按esc进入命令模式，就会出现8个=。 这在插入分割线时非常有用，如30i+<esc>就插入了36个+组成的分割线。

## 剪切复制

y

y[n]w



# Windows中被代替的常用快捷键

- `<CTRL-C>` no longer copies, and instead it sends you back to *Normal mode*. The command that we use in Vim for copying is far less verbose: **`y`** (for yank).
- `<CTRL-V>` no longer pastes and instead sends you into *Visual-block mode*. Again, the command we use in Vim for pasting is less verbose: Just a single **`p`** (for paste).
- `<CTRL-F>` no longer lets you search, and instead it allows you to scroll your screen one page forward. Once more, the command we use in Vim for searching is closer to your fingertips: `/{term-i-am-searching-for}`.