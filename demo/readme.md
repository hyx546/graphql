# 运行mongodb

# 搭建graph-pack 的环境
 - npm i -S graphpack

 # 创建文件结构

 - src
    - db                // 数据库操作相关
        - connect.js    // 数据库操作封装
        - index.js      // DAO层
        - setting.js    // 配置
    
    - resolvers
        - index.js  
    
    - schema.graphql    // schema

- packeage.json