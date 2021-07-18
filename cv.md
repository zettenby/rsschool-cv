1. # Andrei Khatsian
2. # Contacts
   + telegram: @Zettenby
   + email: zetten.by@gmail.com
3. # About Me
   My goal is to change my current job. I'm going to become a Front-End developer and I'll do everything in my possibilities to do it.
4. # Skills
   + HTML
   + CSS
   + JS
5. # Code example ("Range Extraction" kata from codewars.com)
    
 ```
    function solution(list){
 // TODO: complete solution
  let len = list.length
  let count = 0
  let end
  var str = ""
  for(i=0; i<list.length; i++)
    {
  if (list[i] + 1 == list[i+1] && list[i+1] + 1 == list[i+2]  )
    {let start = list[i]
      while(list[i]+1 == list[i+1] )
        {
          end = list[i+1]
          i++
          count++
        }
     i = i - count 
      count++
     list.splice(i,count,start +"-"+ end)
      count = 0
    }
    }
  str = list.join()
  return str
    }
```
6. # Work
   I don't have any work experience as a programmer
7. # Education 
   I have an engineering education. I've learnt HTML, CSS and JS with w3schools tutorials.
8. # English
   I speak English at a A2 level 
