
# Markdown


## Menu Items (unorder list)
- Pizza
- Burger
- Fries

## Links
```md
[text](path)
```

Examples
```md
[Visit Google](https://www.google.com)
```

Preview
[Visit Google](https://www.google.com)


### HTML Elements
```html
- <>    open brackets 
- </>   closing bracket
- <u>   open element for underline `u` tagname
- </u>  closing block for underine element

Example
<> Text / Another Element </>

<u>Text</u>

<tagname>Text/element</tagname>
```

This _repo_ is all about **hotel** menu __items__ and <u>orders</u> *data*


### Data

Menu
```csv
id,name,price
1,pizza,75
2,burger,35
3,fries,60
```

Orders
```json
[
    {
        "orderId": 1,
        "date": "19/05/2025:10:00AM",
        "items": [
            {
                "id": 1, 
                "quantity": 2
            },
            {
                "id": 3, 
                "quantity": 1
            }
        ]
    },
    {
        "orderId": 2,
        "date": "20/05/2025:04:00AM",
        "items": [
            {
                "id": 2,
                "quantity": 4
            }
        ]
    }
]
```


###  Table Syntax
```
| Column | Second Column | Third Column |
| ---    | ---           | ---          |
| One    |  Two          |  Three       |
```

| Column | Second Column | Third Column |
| ---    | ---           | ---          |
| One    |  Two          |  Three       |


### Menu Table
| id    |   Name    |   Price   |
| ---   | ---       |   ---     |
| 1     | Pizza     | 65        |
| 2     | Burger    | 45        |
| 3     | Fries     | 25        |  

### Coding Block
`Z     a    k    e    e     r`

```
Pizza
Burger
Fries
```

---

#### Symbols
```
`   backticks
''  single quote
""  double quote
-   hyphen
_   underscore
*   start
:   colon
;   semi-columns
#   hash
|   pipe
\   backward slash
/   forward slash
```

##### Menu Items (Order list)
0. Pizza
0. Burger
0. Fries

###### Another Heading (Level 6)
---
5. Five
5. Six
5. Seven

---
