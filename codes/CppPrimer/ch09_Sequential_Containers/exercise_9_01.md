> 练习9.1：对于下面的程序任务，vector、deque和list哪种容器最为适合？解释你的选择理由。如果没有哪一种容器优于其他容器，也请解释理由。

(a) 读取固定数量的单词，将它们按照字典序插入到容器中。我们将在下一章看到，关联容器更适合这个问题。
(b) 读取未知数量的单词，总是将新单词插入到末尾。删除操作在头部进行。
(c) 从一个文件读取未知数量的整数。将这些数排序，然后将她们打印到标准输出。

---

(a) 使用list，因为很可能从中间插入数据，list的速度更快。
(b) 使用deque，因为需要在头尾插入或者删除元素，deque的速度都很快。
(c) 使用vector，没有什么很好的理由选择其他容器，就应该使用vector。
