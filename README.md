# FK-yqExport
语雀知识库markdown 【目录】结构形式导出，包含图片、附件。

# 本项目只为一次性【迁移出】语雀知识库，或【定时同步】知识库到本地，想更换笔记软件的可以尽情食用 ：)
代码能用就行，不做后续维护。2023.04.28测试可运行。

# 食用指南
浏览器访问 (https://www.yuque.com/settings/tokens) 页面，新建一个读取权限的密钥，将该密钥填写到13行 X-Auth-Token 以及 202 行 token 中。

python3 FK-yqExport.py
    选择一个需要导出的数据库，然后回车。
 
# 本地目录存储示例：不包含文件夹字样及\r\n
YuqueExport\r\n
    知识库名称文件夹\r\n
        assets文件夹\r\n
        test.md\r\n
        一级文件夹\r\n
            assets文件夹\r\n
            test.md\r\n
            二级文件夹\r\n
                assets文件夹\r\n
                test.md\r\n
                。。。。。。
