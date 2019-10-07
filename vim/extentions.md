
## surround.vim
### link
http://weibeld.net/vim/surround-plugin.html
### surround the word
`ysw`: surround the word, and cursor go down.  
`yss`: surround the line, and cursor go down.  
and type `"`, the word was surrounded by `"`
`yss<p>`: can surround the whole line, like,  
`<p>Dolor provident amet consequatur earum</p>`
### del the surrounding
`ds`: target the surrounding, and type `"` 
can delelte the surrounding `"`,  
`dst`: delete the tag. 
### change the surrounding
`cs"/`: changes "hoge" to /hoge/.  
It's same as vim `ciw`.  

### use by V mode
select the range in v mode, type `S` to say 
the word to surround.  

### Problem
how to change this `{}` to `[]`?  
```
let songs = {
    'Stella', 'Satin Doll', 'Caravan', 'Mucho', 
    'My favorite things', 'Chance on Love',
    'To The Moon', 'Waltz', 'Willow Weep', 'Bluesette',
};
```
