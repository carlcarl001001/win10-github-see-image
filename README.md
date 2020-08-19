#### win10 解决git hub不能看图片问题

用nodepad++打开C:\Windows\System32\drivers\etc\hosts文件，

在末尾添加

/# GitHub Start 

140.82.113.3      github.com

140.82.114.20     gist.github.com
 
151.101.184.133    assets-cdn.github.com

151.101.184.133    raw.githubusercontent.com

151.101.184.133    gist.githubusercontent.com

151.101.184.133    cloud.githubusercontent.com

151.101.184.133    camo.githubusercontent.com

151.101.184.133    avatars0.githubusercontent.com

199.232.68.133     avatars0.githubusercontent.com

199.232.28.133     avatars1.githubusercontent.com

151.101.184.133    avatars1.githubusercontent.com

151.101.184.133    avatars2.githubusercontent.com

199.232.28.133     avatars2.githubusercontent.com

151.101.184.133    avatars3.githubusercontent.com

199.232.68.133     avatars3.githubusercontent.com

151.101.184.133    avatars4.githubusercontent.com

199.232.68.133     avatars4.githubusercontent.com

151.101.184.133    avatars5.githubusercontent.com

199.232.68.133     avatars5.githubusercontent.com

151.101.184.133    avatars6.githubusercontent.com

199.232.68.133     avatars6.githubusercontent.com

151.101.184.133    avatars7.githubusercontent.com

199.232.68.133     avatars7.githubusercontent.com

151.101.184.133    avatars8.githubusercontent.com

199.232.68.133     avatars8.githubusercontent.com
 
/# GitHub End

这个2020年6月9日请测有效。如果复制了上面代码（不需要重启电脑），仍然没有效，有可能是地址过期了，需要重新找新的地址。
