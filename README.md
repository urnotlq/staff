# staff
An on-machine test demo

## 项目需求

1、 请新建一个网页文件staff.html，写出如下样式部局，注意部门名称后面的加号和减号同时只能显示一个。

​		选中部门1、部门2、员工小八、员工小九时页面的选中情况及结果如下：

<img src="doc\demo.jpg" alt="默认样式" style="zoom: 67%;" />	<img src="doc\demo2.jpg" alt="选中结果" style="zoom: 67%;" />

2、 部门后面的符号“+/-”，点击+号时，展开员工列表，点击-号时，隐藏员工列表。加号或减号同时只能显示一个。

3、 当选择部门前面的复选框时，部门下的员工复选框全选，当反选部门时，部门下的员工全部反选。

4、 当选择部门员工时，如果部门员工全选，则对应部门也选中，如果部门员工没有全选时，对应部门为未选中状态。

5、 选中部门或者员工时，选中的部门和员工数据需以```json```形式展示在页面底部。如选中部门1、部门2，员工小八，员工小九时，显示：{“department”:[1,2],”user”:[8,9]}。

6、 部门1、部门2、部门3对应的部门id分别为1、2、3。

7、 员工小一、小二、小三、小四、小五、小六、小七、小八，小九分别对应的员工id为1、2、3、4、5、6、7、8、9。

## 项目结果

使用```Vue```框架编写。仅修改```inputArr```数据源即可扩展选项、升级开发。主要代码写在"`/src/views/staff.vue`"文件中。

## 项目启动


### Project setup

```
yarn install
```

#### Compiles and hot-reloads for development

```
yarn serve
```

#### Compiles and minifies for production

```
yarn build
```

#### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).