---?image=images/newsMain.jpg&size=auto 70%
## Android Dev News #2 11.2018

---
## Kotlin 1.3
- Inline Class |
- Contracts |
- Couritnes |
- @JvmStatic i @JvmField w interfejsach |
- Annotation class może zawierać deklaracje klas |
- random(), ifEmpty() i ifBlank() - nowe extensions dla kolekcji |
https://kotlinlang.org/docs/reference/whatsnew13.html

+++

### Kotlin 1.3 Inline Class
```kotlin
inline class Password(val text: String)

val pwd = Password("tajne")
formatString(pwd.text)

// decompiled
String pwd = Password.constructor-impl("tajne");
this.formatString(pwd);
```
---

## Architecture components

+++

### Room 2.1
- Możliwość zwrócenia Completable, Single, Maybe jako typ funkcji @Insert, @Delete itd. |
- Możliwość zwrócenia Observable z @Query |
- Wsparcie dla FTS3 i FTS4 |
- Wsparcie dla widoków bazodanowych |

+++

### Navigation
- Nowy AppBarConfiguration umożliwiający połączenie navigation z Toolbar, CollapsingToolbar i ActionBar |
- Można podawać argumenty dla początkowego fragmentu |
- Możliwość wykorzystania nowych znaków specjalnych w schemacie deeplinka |
- Wsparcie dla Shared element transition
