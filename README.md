# Les Chats Hutants mutent en huant

- Nothing is right or wrong, all the citations must be turned into question.
- The questions must be in the file LANG.md where LANG is the language used.
- The structure of an entry *MUST* be
  ```
  # XXX - Title
  ```

When you add an entry in a file, you must respect the order used in the other files.

Example :

- *en.md*
  ```
  # 001 - xxxx in english (translation of the French entry #001)
  
  > …
  
  # 002 - xxxx in english (does not exist in french)
  
  > …
  
  # 003 - xxxx in english (translation of the French entry #003)
  
  > …
  ```
- *fr.md*
  ```
  # 001 - xxxx in french (translation of the English entry #001)
  
  > …
  
  # 003 - xxxx in french (translation of the English entry #003)
  
  > …
  
  # 004 - xxxx in french (does not exist in english nor in russian)
  
  > …
  ```
- *ru.md*
  ```
  # 005 - xxxx in russian (does not exist in other language)
  
> …
  
  # 006 - xxxx in russian (does not exist in other language)
  
> …
  ```

- To add an new entry in the file `en.md` add it like this one
  ```
  # 007 - xxxx in english (does not exist in other language)
  
  < …
  ```
- To translate the entry `1` in the file `ru.md` add it like this one
  ```
  # 001 - xxxx in russian (translation of the French and English entry #001)
  
  < …
  ```
