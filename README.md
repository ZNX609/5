# 实验五 综合性实验 学生选课系统
第五次实验报告 计G191 赵静 2019322034 
### 一、实验目的
分析学生选课系统  
使用GUI窗体及其组件设计窗体界面  
完成学生选课过程业务逻辑编程  
基于文件保存并读取数据  
处理异常  
### 二、实验要求 
#### 一、系统角色分析及其系统  
人员包含：
#### 二、要求  
1.设计GUI窗体，支持学生注册、课程新加、学生选课、学生退课、打印学生选课列表等操作。  
2.基于事件模型对业务逻辑编程，实现在界面上支持上述操作。  
3.针对操作过程中可能会出现的各种异常，做异常处理。 
4.基于输入/输出编程，支持学生、课程、教师等数据的读写操作。  
5.基于Github.com提交实验，包括实验SRC源文件夹程序、README.MD实验报告文档。  
### 三、实验过程  

### 四、核心代码  
1.利用GUI窗体定义一个密码验证程序  

     class Passwd extends JFrame implements ActionListener 
    {
	JLabel lb=new JLabel("请输入密码");
	JPasswordField txt1=new JPasswordField(25) ;
	JButton bn=new JButton("确定");
	JTextField txt2=new JTextField(25);
	Passwd(){
		setSize(300,200);
		setVisible(true);
		setTitle("密码验证");
		setDefaultCloseOperation(EXIT_ON_CLOSE);
		setLayout(new FlowLayout());
		add(lb);
		add(txt1);
		txt1.setEchoChar('*');
		add(bn);
		add(txt2);
		validate();
		bn.addActionListener(this);
	}
2.
    JCheckBox cb1=new JCheckBox("java");
		cb1.addItemListener(this);
		add(cb1);//添加单选框  
    JRadioButton b1=new JRadioButton("java:张老师");
		b1.addActionListener(this);
		add(b1);//添加复选框
### 五、实验运行截图  
![Image text](https://raw.githubusercontent.com/ZNX609/5/master/1.png)  
![Image text](https://raw.githubusercontent.com/ZNX609/5/master/2.png)





### 六、实验心得  
    通过一学期的学习
