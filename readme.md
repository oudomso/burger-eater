# Burger-Eater

Add Your Favoite Burger And Devour them

## Installation

1. npm i 
2. node server.js
3. go to localhost:8080

```bash
pip install foobar
```

## Usage

```html
      {{#each burgers}}
          {{#unless eaten}}
          {{!-- Use Partial if False --}}
        {{> state-check devour=false}}
            {{/unless}}
      {{/each}}
```



