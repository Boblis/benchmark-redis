### 使用 redis benchmark 工具, 测试 10 20 50 100 200 1k 5k 字节 value 大小，redis get set 性能

![通过benchark-redis 测试reids get,set性能](img/img.png)


### 统计平均key 的内存占用

###### 63114 个key value的大小为 10 字节

key的平均大小如下：通过命令 memeory stats 可以获取

![value 为10 字节下，key的平均大小](img/img_1.png)

###### 63091 个key，value大小为 20字节

key的平均大小如下：通过命令 memory stats 可以获取

![value 为20字节下，key的平均大小](img/img_2.png)

###### 63092 个 key，value大小为 50 字节

key的平均大小如下：通过命令memory stats 可以获取

![value 为 50字节，key平均大小](img/img_3.png)

###### 63301 个 key，value大小为 100 字节

key的平均大小如下：通过命令memory stats 可以获取

![value 为 100字节，key平均大小](img/img_4.png)

###### 63166 个 key，value大小为 200 字节

key的平均大小如下：通过命令memory stats 可以获取

![value 为 200字节，key平均大小](img/img_5.png)

###### 63187 个 key，value大小为 1k 字节

key的平均大小如下：通过命令memory stats 可以获取

![value 为 2k 字节，key平均大小](img/img_6.png)

###### 63065 个 key，value大小为 5k 字节

key的平均大小如下：通过命令memory stats 可以获取

![value 为 5k 字节，key平均大小](img/img_7.png)