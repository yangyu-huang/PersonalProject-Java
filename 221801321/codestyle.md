## 代码规范
### 缩进
> 一般由使用的编译器自动缩进，为四个字符数。

### 变量命名
> 变量名使用与其中文语义相近的英文单词或缩写，比如计算数目常用num、number、numbers等，字符串使用s1、s2等。

### 每行最多字符数
> 每行最多字符数不超过125个字符，超过则必须换行（即整个屏幕无法看完一整行代码）。

### 函数最大行数
> 一般不超过100行。

### 函数、类命名
> 函数名一般为首字母大写与其中文语义相近的英文单词，如Getnumbers。
> 类名一般为首字母大写与其中文语义相近的英文单词，如Person类。

### 常量
> 常量一般为全英文大写单词，如MAX_NUM。

### 空行规则
> 在函数和函数之间一般会用一行空行隔开，定义变量和具体方法实现的中间也会有空行隔开（即变量定义 空行 具体方法实现）。

### 注释规则
> 一般会在有需要添加注释说明的函数、类的前面添加注释。

### 操作符前后空格
> 一般会在操作符前后各添一个空格。

### 其他规则
> string一个字符串时，我一般会这样初始化：string s1 = "";
>对于判断的条件，有时两种形式都会写，例：if(islower(f))或if(islower(f)==1)；if(n!=0)或if(!n)。可能随意写其中的一种判断形式，没有固定写哪一种。