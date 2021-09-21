# I would really appreciate it if you know the answer and send me a message. Even a hint is extremely helpful.






# Quant
- Lasso、Ridge、OLS回归的$$R^2$$大小排序
  - 我的答案是OLS > Lasso > Ridge。OLS肯定是最大的，但是Lasso和Ridge我不知道如何判断。
  - 小胖的老师说ridge和lasso无法比较，要看原模型是什么，如果原模型中很多系数close to 0，lasso是要大一些的，因为lasso can real send this coefficient to zero。
- 估算Lasso的trace（例如200个样本，40个特征）
- 正四面体上的蚂蚁，遍历3个顶点，返回原点的期望步数？
  - Hint: Markov Chain
- 自然数n各个位数之和是38，5n是19，这个自然数是奇数还是偶数？
  - 19个2满足


- 1000!末尾有几个连续的0？
  - [100的阶乘末尾有多少个0的问题](https://blog.csdn.net/huangzhiyuan111/article/details/43304523)
  - 每出现一个2和5，就会在末尾有一个0，所以只要看，从1到1000中总共有多少个2和5就可以了，又因为5总比2少，所以，只要看1000的阶乘中有多少个约数5就可以了。同样，只有末尾是0或者5的数才会有5，所以总共只有200个数其中包含5，但是，其中有1000/25=40个数包含2个5，1000/125=8个数包含三个5，1000/625=1个数包含4个5,所以总共有200+40+8+1=249个5,所以结果里总共有249个0。


- 如何不占用额外空间交换2个数？
  - i = 2*i + j
  - j = ( i - j )/2
  - i = i - j

- 一根1cm的绳子，随机选取一点剪开，变成2段。请问长的那一段平均有多长？
  - 这题第一次做，无脑写了1/2，错的离谱。
  - 设短的一段长度为X，则长的一段长度为1-X，显然要满足$$1-X \geq X$$，则X≤1/2。X~U[0,1/2]，即随机变量满足[0, 1/2]区间上的均匀分布，积分算出EX=1/4，则长的那一段平均长度3/4
  - [随机把绳子剪开，最短一段会有多长？](https://www.jlao.net/technology/1419/)
