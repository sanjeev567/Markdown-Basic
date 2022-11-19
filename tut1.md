# <ins>Markdown Crash course</ins>
## * What is markdown ?
- Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004.
- Can be converted into HTML/XHTML and other formats
- It's main purpose is readability and ease of use.

## * How it works ?

![working of markdown](./markdown-flowchart.png)

## * Used for :
- It is used to create static websites, documents, notes, books, presentations, email messages, and technical documentation, readme (github).

<!-- headings -->
## 1. <ins>Headings: </ins>
```md
  # H1
  ## H2
  ### H3
  ......
  ###### H6
  ```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italic -->
## 2. <ins>Italic: </ins>
```md
  *This is* a book

  or 

  _This is_ a book
  ```
*This is* a book 

_This is_ a book

  <!-- strong -->
## 3. <ins>Strong: </ins>
```md
  **This is** is a book

  __This is__ is a book
```
  **This is** is a book

  __This is__ is a book

  <!-- Strikethrough -->
## 4. <ins>Strikethrough: </ins>
```md
  ~~This is~~ a book
```
  ~~This is~~ a book

  <!-- Horizontal line -->
## 5. <ins>Horizontal line: </ins>
first is three dashes second is three underscores
```md
  ---
  ___
```
  ---
  ___

  <!-- Block quotes -->
## 6. <ins>Block quotes: </ins>
```md
  >This is a quote
```
  >This is a quote

  <!-- Links -->
## 7. <ins>Links:</ins>
### [Link name](location of the image "shows on hover")
```md
   [click here to go google](https://google.com)

  [click here to go google](https://google.com "google")
```
  [click here to go google](https://google.com)

  [click here to go google](https://google.com "google")

  <!-- UL -->
## 7. <ins>UL:</ins>
```md
  * Item 1
  * Item 2
  * Item 3
    * Nested Item 4
    * Nested Item 5
```
  * Item 1
  * Item 2
  * Item 3
    * Nested Item 4
    * Nested Item 5

<!-- OL -->
## 7. <ins>OL:</ins>
```md
1. Item 1
2. Item 2
3. Item 3
```
1. Item 1
2. Item 2
3. Item 3

<!-- Inline code Block -->
## 8. <ins>Inline code Block:</ins>
```md
`<p>This is a paragraph </p>`
```
`<p>This is a paragraph </p>`

## 8. <ins>Images:</ins>
### ![Image name](location of image)
```md
![Markdown logo](https://markdown-here.com/img/icon256.png)
```

![Markdown logo](https://markdown-here.com/img/icon256.png)


# * <ins>Github markdown</ins>

## 1. <ins>Code Blocks </ins>

```bash
    npm install

    npm start
```


```javascript
    function(num1, num2) {
    return num1 + num2;
    }
```

```python
    def(num1, num2):
        return num1 + num2
```

## 2. <ins>Tables </ins>
```md
|Names   |  Email            |
|--------|-------------------|        
|John Doe|john@gmail.com     |
|Jane Doe|jane@gmail.com     |
```
|Names   |  Email            |
|--------|-------------------|        
|John Doe|john@gmail.com     |
|Jane Doe|jane@gmail.com     |


## 3. <ins>Task List</ins>
```md
* [X] Task 1
* [X] Task 2
* [ ] Task 3
```
* [X] Task 1
* [X] Task 2
* [ ] Task 3

## * some common use cases.
- for underlines use - `<ins>` tag
- for line break use - double enter from current line to break.

