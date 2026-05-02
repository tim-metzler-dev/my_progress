# Day 67
Like Miyamoto Musashi said:
  "The purpose of today's training is to defeat yesterday's understanding."

## Today I learned:
  1. If you use "*" in css as selector you select every element. It is an universal selector.
  2. I'll show you the CSS hierachie:
      I. The most powerfull element is style="..."  inside HTML.
         (1,0,0,0)
     II. The second powerfull element is an ID as selector (#... {})
         (0,1,0,0)
    III. The third powerfull are classes (.class {}), attributes and things like :hover
         (0,0,1,0)
     IV. The fourth powerfull are tags (like p)
         (0,0,0,1)
      V. The "*" is the last one. It will be changed with every other selector. You write (0,0,0,0)

     You see I wrote it down as (I,II,III,IV) . This is called the cascade algorythmus and is used for CSS.
     
