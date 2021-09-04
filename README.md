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

### 删除某一范围的内容

> a:around
>
> i:inner

da{：删除{}以及{}内的内容

di{: 仅删除{}内的内容

- **`daw`** to **d**elete **a** **w**ord (plus trailing whitespace)
- **`ciw`** to **c**hange **i**nner **w**ord
- **`das`** to **d**elete **a** **s**entence (**`dis`** to delete inner sentence)
- **`da"`** to delete something in double quotes including the quotes themselves (**`di"`** deletes only the content **i**nside the quotes and spares the quotes)
- **`ci"`** to change something inside double quotes
- **`dap`** to delete a paragraph
- **`dab`** **`da(`** or **`da)`** to delete a block surrounded by **`(`**
- **`daB`** **`da{`** or **`da}`** to delete a block surrounded by **`{`**
- **`dat`** to delete an HTML tag
- **`cit`** to change the contents of an HTML tag

## 跳转

w：跳一个词

b：回跳一个词

gd

gf

<kbd>Ctrl</kbd>+o: 向后跳

<kbd>Ctrl</kbd>+i: 向前跳

## 重复上一次操作

<kbd>.</kbd>

# learn vim

\- *`y`* (yank): Copy in Vim jargon

\- *`p`* (put): Paste in Vim jargon

\- *`g~`* (switch case): changes letters from lowercase to uppercase and back. alternatively, use *`gu`* to make something lowercase and *`gu`* to make something uppercase

\- *`>`* (shift right): adds indentation

\- *`<`* (shift left): Removes indentation

\- *`=`* (format code): Formats code

\- *`x`* is equivalent to *`dl`* and deletes the character under the cursor

\- *`X`* is equivalent to *`dh`* and deletes the character before the cursor

\- *`s`* is equivalent to *`ch`*, deletes the character under the cursor and puts you into Insert mode

\- *`r`* allows you to replace one single character for another. Very handy to fix typos.

\- *`~`* to switch case for a single characte

## Windows中被代替的常用快捷键

- `<CTRL-C>` no longer copies, and instead it sends you back to *Normal mode*. The command that we use in Vim for copying is far less verbose: **`y`** (for yank).
- `<CTRL-V>` no longer pastes and instead sends you into *Visual-block mode*. Again, the command we use in Vim for pasting is less verbose: Just a single **`p`** (for paste).
- `<CTRL-F>` no longer lets you search, and instead it allows you to scroll your screen one page forward. Once more, the command we use in Vim for searching is closer to your fingertips: `/{term-i-am-searching-for}`.

# AndroidStudio插件

[在Android Studio上使用IdeaVim插件_ShortChin的博客-CSDN博客](https://blog.csdn.net/ShortChin/article/details/51799901)