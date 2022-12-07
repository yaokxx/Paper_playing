# Gaussian mixture model

![算法大鉴赏：高斯混合模型（Gaussian mixture model）](https://pic1.zhimg.com/v2-b6855cdc9d61672ea31e83b061c449c9_720w.jpg?source=172ae18b)

#### Modeling probability density functions for data that fit a Gaussian distribution

###### Assuming that the data is one-dimensional

![image-20221207143517462](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20221207143517462.png)

![image-20221207143522683](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20221207143522683.png)

###### Assume that the data is high-dimensional (dimension is )

![image-20221207143713161](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20221207143713161.png)

![image-20221207143717341](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20221207143717341.png)

Under the assumption that the data conforms to a Gaussian distribution, its mean and covariance matrix can be estimated by the above equation, thus completing the modeling of the probability density function of the data.

However, in most cases, the actual data distribution is not a Gaussian distribution, but may be a linear superposition of two or more Gaussian distributions, which is called Gaussian mixture distribution, and the corresponding modeling process is called Gaussian mixture model (GMM).



# Gaussian mixture model

![image-20221207143858877](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20221207143858877.png)



## Solution:  EM algorithm

![image-20221207144401263](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20221207144401263.png)