练习18.11：为什么what函数不应该抛出异常？

---

如果what抛出异常，那么在异常处理代码里就不应该调用what了，而这和what函数的初衷相违背。