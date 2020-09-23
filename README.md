<div align="center">

## Beginning C\+\+ 4


</div>

### Description

This just for beginners. It shows how variables can exist in different scopes
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Richard Kennesson](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/richard-kennesson.md)
**Level**          |Beginner
**User Rating**    |3.4 (17 globes from 5 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/richard-kennesson-beginning-c-4__3-1988/archive/master.zip)





### Source Code

```
//this program shows that variables can exist
//in different scopes and can be called on
//a peice of code within that scope
#include <iostream.h>
void main()
{
  char ch = 'A';
  cout << "Tier " << ch << '\n';
  {
   char ch = 'B';
   cout << "Tier " << ch << '\n';
   {
     char ch = 'C';
     cout << "Tier " << ch << '\n';
   }
   cout << "Tier " << ch << '\n';
  }
  cout << "Tier " << ch << '\n';
}
```

