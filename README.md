#文档说明

##代码中包含的单元测试有
- string split —— 将输入数据historyData进行分割
- build animalsData object —— 将分割后的数据处理，编程对象的形式，对象包含属性有 id，time，animals
- judge format of id —— 判断 animalsData 中所有的 id 是否题目要求
- judge format of time —— 判断 animalsData 中所有的时间是否符合题目要求，其中将年月日与时分秒分开进行判断
- judge format of animals —— 判断 animalsData 中的所有 animals 是否符合题目要求，其中将animals进行数据分割，判断 animals 中形式是否为{动物的id}，{x坐标}，{y坐标}或者为{动物的id}，{上一时刻的x坐标}，{上一时刻的y坐标}，{x坐标的变化量}，{y坐标的变化量}
- historyData has wrong —— 判断数据是否有错误
- print animals snapShot —— 输出最终结果

##如何运行测试
1. 将Jasmine测试的数据包拷贝到题目所在的文件夹中放于lib文件夹中
2. 创建了一个main_run.html的文件，将实现代码main.js与测试代码main_spec.js引入html中
3. 运行html文件在网页中进行测试