# gittest
Testing markdown

## Below is a Blockquote
> What hereby follow is a very good blockquote.

### List
- First item
- Second item
- Third item
- Fourth item
##### classDiagram
```mermaid
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
```

### I am posting a link here
[Markdownguide](https://www.markdownguide.org/)

#### sequenceDiagram
    ```mermaid
Alice->>John: Hello John, how are you?
John-->>Alice: Great!
Alice-)John: See you later!
```

### The below word is very important
<mark>this word</mark> is very important as you can see.

### Very funny emoji :tent:
We love emojis done we :joy:

### Table 
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
