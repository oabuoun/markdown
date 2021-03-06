# Markdown Cheat Sheet 

Based on [The Markdown Guide](https://www.markdownguide.org) and [Markdown for Dummies](https://medium.com/@taylorhxu/markdown-for-dummies-a24e982b8e85)

For more information: visit [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax)

---

**Syntax Wanted: Heading - H1**

# Heading - H1

**Code:**

```markdown
# Heading - H1
```

---

**Syntax Wanted: Heading - H2**

## Heading - H2

**Code:**

```markdown
# Heading - H2
```

---

**Syntax Wanted: Heading - H3**

### Heading - H3

**Code:**

```markdown
# Heading - H3
```

---

**Syntax Wanted: Bold Text**

**bold text**

**Code:**

```markdown
**bold text**
```

---

**Syntax Wanted: Italicized Text**

*italicized text*

**Code:**

```markdown
*italicized text*

```

---

**Syntax Wanted: Blockquote**

> blockquote

**Code:**

```markdown
> blockquote

```

---

**Syntax Wanted: Ordered List **

1. First item
2. Second item
3. Third item

**Code:**

```markdown
1. First item
2. Second item
3. Third item
```

---

**Syntax Wanted: Unordered List**

- First item
- Second item
- Third item

**Code:**

```markdown
- First item
- Second item
- Third item
```

---

**Syntax Wanted: code block**

`code block`

**Code:**

```markdown
`code block`

```

**Syntax Wanted: Code-Based Code Blocks**
 ```javascript
 var s = “JavaScript syntax highlighting”;
 alert(s);
 ```
 ```python
 s = “Python syntax highlighting”
 print s
 ```
 ```
 No language indicated, so no syntax highlighting. 
 But let’s throw in a <b>tag</b>.
 ```
var s = “JavaScript syntax highlighting”;
alert(s);
s = “Python syntax highlighting”
print s
No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let’s throw in a tag.

**Code:**
```
 ```javascript
 var s = “JavaScript syntax highlighting”;
 alert(s);
 ```
 ```python
 s = “Python syntax highlighting”
 print s
 ```
 ```
 No language indicated, so no syntax highlighting. 
 But let’s throw in a <b>tag</b>.
 ```
var s = “JavaScript syntax highlighting”;
alert(s);
s = “Python syntax highlighting”
print s
No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let’s throw in a tag.

```

---

**Syntax Wanted: Horizontal Rule**

---

**Code:**

```markdown
---

```

---

**Syntax Wanted: Link**

[title](https://www.example.com)

**Code:**

```markdown
[title](https://www.example.com)

```

---

**Syntax Wanted: Image**

![alt text](image.jpg)

**Code:**

```markdown
![alt text](image.jpg)

```

---

**Syntax Wanted: Table**

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

**Code:**

```markdown
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```

---

**Syntax Wanted: Fenced Code Block**

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

**Code:**

```markdown
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
```

---

**Syntax Wanted: Footnote**

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

**Code:**

```markdown
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

```

---

**Syntax Wanted: Heading ID**

### My Great Heading {#custom-id}

**Code:**

```markdown
### My Great Heading {#custom-id}

```

---

**Syntax Wanted: Definition List**

term
: definition

**Code:**

```markdown
term
: definition
```

---

**Syntax Wanted: Strikethrough**

~~The world is flat.~~

**Code:**

```markdown
~~The world is flat.~~
```

---

**Syntax Wanted: Task List**

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

**Code:**

```markdown
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```
