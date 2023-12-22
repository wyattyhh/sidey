---
layout: post
categories: book
---

## 1.  [Refactoring: A First Example](https://memberservices.informit.com/my_account/webedition/9780135425664/html/opening.html)
## 2. [Principles in Refactoring](https://memberservices.informit.com/my_account/webedition/9780135425664/html/principles.html)
## 3. [Bad Smells in Code](https://memberservices.informit.com/my_account/webedition/9780135425664/html/smells.html)
### Mysterious Name
> When you can't think of a good name for something, it's often a sign of a deeper design malaise.
### Long Function
>The net effect is that you should be much more aggressive about **decomposing functions**. A heuristic we follow is that **whenever we feel the need to comment something, we write a function instead**. Such a function contains the code that we wanted to comment but is named after the _intention_ of the code rather than the way it works. We may do this on a group of lines or even on a single line of code. **We do this even if the method call is longer than the code it replaces** - provided the method name explains the purpose of the code. The key here is not function length but the semantic distance between what the method does and how it does it.