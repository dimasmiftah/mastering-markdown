# Mastering Markdown <!-- omit in toc -->

Table of Content
- [Text](#text)
- [List](#list)
- [Image](#image)
- [Structured Documents](#structured-documents)
- [Code](#code)
- [Extras (Only available on GitHub)](#extras-only-available-on-github)

## Text
>Text styling is super easy:
>- You put your text in between two stars `**` for make *italic text*
>- and in between four stars `****` to make it **bold**.
>- Also you can have a [link](http://google.com) with this format: `[the-text](the-url)`

## List

>You can create ordered list like this:

```
1. one
2. two 
3. three

or

1. one
2. two 
3. three
```
>both will generate same result:
1. one
1. two
1. three 
1. addition:
   1. add two spaces before number for sub-list
   2. awesome right!

>You can use `-` or `*` before your list to make bullet list
```
- I'm handsome
- I'm smart
- I'm nice
- I'm definitely narcissistic
```
>will generate:
- I'm handsome
- I'm smart
- I'm nice
- I'm definitely narcissistic

## Image
>You can add image using `![alt-text](image-link)`
```
![awesome octodex by catstello](https://octodex.github.com/images/catstello.png)
```
>will generate:

![Dimas's Avatar](https://octodex.github.com/images/catstello.png)

## Structured Documents
>Template literals `` for inline code or cancel markdown
```
`let number = 1;`
```
>will generate:

`let number = 1;`

```
`this texts will not **bold** or *italic*`
```
>will generate:

`the following text will not **bold** or *italic* `

>Use `>` before your text for quotes:

```
>Aku aku adalah anak gembala. Selalu riang serta gembira. 
> *-Dimas*
```
>will generate:

>Aku aku adalah anak gembala. Selalu riang serta gembira. Tak pernah lelah.
> *-Dimas*

>And use `#` for headings:
```
# H1 first heading
## H2 second heading
### H3 third heading
#### H4 fourth heading
##### H5 fifth heading
###### H6 sixth heading
```
>will generate:
# H1 first heading <!-- omit in toc -->
## H2 second heading <!-- omit in toc -->
### H3 third heading <!-- omit in toc -->
#### H4 fourth heading <!-- omit in toc -->
##### H5 fifth heading <!-- omit in toc -->
###### H6 sixth heading <!-- omit in toc -->

## Code
>You can put your code inside `` if it's just one line. Or you can put it inside `````` (three on top and three on the bottom) if it's multiline. 

>one line example: 
```
`let number = 1;`
```
>will generate: 

`let number = 1;`


>multiline example:

```
let number = 1;
console.log(number);
```

>You also can add the language on the opening for highlting, for example:```javascript

```javascript
let number = 1;
console.log(number);
```

## Extras (Only available on GitHub)
>You can create task list:
```
- [x] completed
- [ ] uncompleted
```
>will generate:
- [x] completed
- [ ] uncompleted

>You alo can mention someone in GitHub comment section using @ 

`Hey @BennoAlif :wave:`
>will generate:

Hey @BennoAlif :wave:

>and the last, you can add emoji!
```
:partying_face: :partying_face: :partying_face:
```
>will generate:

:partying_face: :partying_face: :partying_face:

>You can visit [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) to see the available emoji.  

# Tips
>- Use VSCode becase it provide Markdown Previewer
>- Install Markdown All in One extention in VSCode for Markdown writing shorcuts




