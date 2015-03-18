# My-new
My first repository on GitHub.so happy.
echo "# My-new" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/cici1989/My-new.git
git push -u origin master

# 写一些东西给 GitBook 。
# 接下来是学习 Markdown 的试验。
## 测标题，
## 测＊＊加黑＊＊ 和 ＊斜体＊ __加黑__ _斜体_ 加黑
### 出现问题，**加黑 ** *斜体* 
### 还是有问题 **加黑 **， *斜体*
(问题在于加黑，双 ** 和双 __ 都不能使里面的字加黑）
## 测引用 someone，
  >我记得那美妙的一瞬，在我的面前出现了你。
  >-普希金

（在一行的开头点 h2 和输入两个半角 ## 是一样的，空格不能前置。在 > 前可以有三格空格前置。而 # 标志符号前只能是回车。）
## 测 List ，
  1、水果
  2、蔬菜
  3、谷物
（这是有问题的，没有分行）
* 1、水果

 - 苹果
   * 红富士
   * 红蛇果
 * 橘子
   * 蜜橘
   - 沙糖桔
* 2、蔬菜
  * 白菜
   - 大白菜
   - 小白菜
  * 茄子
    ＊长茄子（必须是半角的 * 号）
       * 长茄子  （* 后面必须有空格）
       * 圆茄子 （即使往后退空格它也会自动归类到同一 list 下）

* 3、谷物
  * 大米
  * 小麦
 
在 GitBook 里面， * 和 _ 混用没有问题，但在 GitHub 中嵌套有问题。做下测试。

* 1、水果

 * 苹果
    * 红富士
    * 红蛇果
 * 橘子
    * 蜜橘
    * 沙糖桔
* 2、蔬菜
  * 白菜
    * 大白菜
    * 小白菜
  * 茄子
   
       * 长茄子  
       * 圆茄子 

* 3、谷物
  * 大米
  * 小麦
