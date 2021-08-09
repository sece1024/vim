# vim

## 模式

v：可视模式，V： 可视行模式，<kbd>Ctrl</kbd>+<kbd>v</kbd> ：可视块模式



## 文本

### 插入模式

i

a



#### 批量插入

> 
>
> 按8，再按i，进入插入模式，输入=， 按esc进入命令模式，就会出现8个=。 这在插入分割线时非常有用，如30i+<esc>就插入了36个+组成的分割线。

### 替换

r

### 剪切复制

#### 复制

y

y[n]w

#### 剪切

x

## 删除

d

d2w: 删除两个单词

dt;: 删除";"之前的字符

d/hello: 删除“hello” 之前的字符

### 删除整行

dd 

删除光标后的内容

D

d$

### 删除然后插入

c：相当于d + i, 如c$ = d$ + i, cc = dd + i

## 跳转

gd

gf

<kbd>Ctrl</kbd>+o: 向后跳

<kbd>Ctrl</kbd>+i: 向前跳

# Windows中被代替的常用快捷键

- `<CTRL-C>` no longer copies, and instead it sends you back to *Normal mode*. The command that we use in Vim for copying is far less verbose: **`y`** (for yank).
- `<CTRL-V>` no longer pastes and instead sends you into *Visual-block mode*. Again, the command we use in Vim for pasting is less verbose: Just a single **`p`** (for paste).
- `<CTRL-F>` no longer lets you search, and instead it allows you to scroll your screen one page forward. Once more, the command we use in Vim for searching is closer to your fingertips: `/{term-i-am-searching-for}`.