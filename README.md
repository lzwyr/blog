#项目简介：  
轻轻轻量级博客！适合java新手来做项目
<p>thx to https://github.com/KKys/blog</p>
<p>本项目是在其基础上完成的，感谢其分享。</p>
<p>在本地测试的过程中，发现其功能并不完善。提了issue，不见回复（wu~应该是工作去了）。</p>
于是学生狗决定动手修改。
 
 <P>后台：Jfinal</P>
 <P>前端：bootstrap</P>
 <P>模板引擎：FreeMaker</P>
    


#代码结构：  

                      ------java/com/blog
                                 --------------  album    （相册相关）
                                 --------------  Blog     （博客相关）
                                 --------------  comment  （评论相关）
                                 --------------  common   （配置相关）    
                                 --------------  info     （相关信息）    
                                 --------------  job      （定时器相关） 
                      ------resources
                                 --------------- config    (数据库配置)
                                 --------------- log4j     (日志配置)
                                 --------------- jobs      (定时器配置)
                      ------webapp   
                                 --------------- blog      (博客页面)
                                 --------------- common    (相关模板页面)
                                 

#TodoL：  

     1.后台照片管理（包括相册和文章），无法正确添加


