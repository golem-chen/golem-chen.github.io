# CSS 文本截断

## one line

```css
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
```

## multi line

```css
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;  
  overflow: hidden;
```
