### 自我介绍 👋
*我是姚苏珂，预计 2022 年毕业*。

*我会 hadoop，python、Java，经常会有一些奇妙的想法*。

*我乐于助人，脾气很好，私以为自身有很多的闪光点。*

*我也很喜欢读书，表演，展示才艺。*

*我喜欢向大家分享一些自己的心得体会，当然我也很喜欢交朋友。*

*可以来临沂找我玩。*


*我的邮箱是 1023265839@qq.com ，欢迎给我发邮件。*

*如果你对我感兴趣可以给我发邮件，谢谢*


# 畅想
当初十分喜爱计算机，所以选择了计算机专业。过去在信工系接触到的课程很符合我对计算机专业的期待，因为我在课程中学到了很多关于计算机的知识。我觉得计算机是我喜欢的领域，它或许会成为我最擅长的领域。
# 技能树与技术偏好
（1）目前我已经具备了Java，python，dw等专业知识。对编程方面比较感兴趣。

    A JAVA     仅仅入门水平，不太行。还得继续学习。
    
    B python    仅仅入门水平，但有着较为浓厚的兴趣，想要深入学习。
    
（2）之前比较有意思的项目



    用Java计算出水仙花数
    水仙花数是指：一个三位数，其各位数字立方和等于该数本身。例如：370=33+73+00.这就说明370是一个水仙花数。
　　所以要判断一个三位数是不是水仙花数，得先取得这个三位数的的个位，十位和百位。
　　1：先取得他的百位：int BaiWei = x/100; 因为int是整形，所以不会进行四舍五入，也不会管小数点后面的数。
　　再取得十位：int ShiWei = (x-BaiWei*100)/10;先用这个数减去百位数*100，再除以10，原因同上。
　　最后取得个位数：int GeWei = x-BaiWei*100-ShiWei*10.很明显，就能得到个位数。
　　2：
　　intb = x/100;
　　int s = x/100%10;
　　int g =  x%10;
　　求立方的方法：
　　1，x = Baiwei*Baiwei*Baiwei+ShiWei*ShiWei*ShiWei+GeWei*GeWei*GeWei
　　2，Java提供求n次方的方法：java.lang.Math.pow(a, b);其表示为a的b次方。
　　最后程序：
　　第一种：

　　public class ShuiXianHuaShu {
    public static void main(String[] args) {
        int x = 0;        //定义水仙花数的个数
        for(int i=100;i<=999;i++){
            int b = i/100;        //取得百位数
            int s = (i-100*b)/10;        //取得十位数
            int g = (i-s*10-b*100);        //取得个位数
            
            if(i==g*g*g+s*s*s+b*b*b){
                x++;    //每次符合水仙花数条件，则x+1;
                System.out.print(i+" ");    //输出符合条件的数
        }
        }System.out.println();        //换行
        System.out.println("水仙花数总共有"+x+"个");    //输出水仙花数的总数
    }
}

　　第二种：

　　public class ShuiXianHuaShu {
    public static void main(String[] args) {
        int x = 0;        //定义水仙花数的个数
        for(int i=100;i<=999;i++){
            int b = i/100;        //取得百位数
            int s = i%100/10;        //取得十位数
            int g = i%10;        //取得个位数
            
            if(i==Math.pow(b, 3) + Math.pow(s, 3) + Math.pow(g, 3)){
                x++;    //每次符合水仙花数条件，则x+1;
                System.out.print(i+" ");    //输出符合条件的数
        }
        }System.out.println();        //换行
        System.out.println("水仙花数总共有"+x+"个");    //输出水仙花数的总数
    }
}


 （5）**我期待能在后续的课程中获得更多的专业知识。**
 
 
 

<!--
**piao0804/piao0804** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
