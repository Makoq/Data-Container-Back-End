## Project setup
```
npm install
```

## Project start
```
npm start
```

## File Structure

```
├─app.js          //node入口
├─api.doc         //api说明
├─dataStorage.js  //数据上传下载业务代码
├─.gitignore      //git忽略配置
├─dataTemplate    //数据模板设计相关说明
├─notebook        //开发笔记
├─README          //说明
├─package-lock.json
├─package.json    //依赖项
├─public          //静态资源
├─config          //配置项
|  ├─config.js    //基本配置文件，包括数据库、python环境等
├─dataStorage     //数据资源在容器中持久化拷贝的文件夹
├─develop_backup  //开发笔记
|  ├─dataTemplate //数据模板设计相关说明
|  ├─notebook     //开发笔记
├─lib             //依赖项
|  ├─data         //基本配置文件，包括数据库、python环境等
|  |   ├─templateIdOfVisualSolution.js  //两种可视化方法的数据模板id(在门户中的数据模板)，写死的id 
|  ├─encode       //加密
|  |   ├─encode.js //加密方法 
|  ├─SAGA         //SAGA模型软件程序
|  ├─saga_tools   //SAGA模型功能模块项json记录
|  ├─visual       //可视化
|  |   ├─shp.py   //shp数据可视化
|  |   ├─tiff.py  //tiff数据可视化
|  ├─mongodb.js   //mongodb连接配置
├─model           //数据模型
|  ├─dataList.js     //数据项
|  ├─instances.js    //服务条目项
|  ├─workSpace.js    //工作空间
|  ├─user.js         //用户
|  ├─runRecord.js    //运行记录（待完善，task）
├─processing_result           //数据处理、表达结果存储
├─router             //路由
|  ├─router.js       //路由配置
├─service            //业务处理
|  ├─instances.js    //服务条目相关（重要）
|  ├─processing.js   //处理、表达相关业务（重要）
|  ├─transition.js   //数据文件、处理、表达结果通过中转服务器转发（重要）
|  ├─systemStateRouter.js   //系统服务状态
|  ├─workSpace.js    //工作空间
|  ├─user.js         //用户登录相关
|  ├─method.js       //抽象出结合测试数据的实例，和通用方法（待完善）
|  ├─dataStorage.js  //数据上传下载
|  ├─geoProblems.js  //参与式平台相关
|  ├─index.js        //接入saga（废）
├─service_migration_tep           //数据迁移暂时存储，迁移完成后自动删
├─snapShotCache                   //数据截图暂时存储
├─temp                            //零时存储文件夹
├─test                            //测试文件存储
├─upload_ogms                     //上传
├─upload_processing               //处理、表达脚本在容器中持久化拷贝的文件夹
├─urlFile                         //url下载数据存储
├─utils                           //工具方法
|  ├─utils.js                     
├─visualTestData                  //可视化测试数据

```
 ## Dependencies

```json
 "dependencies": {
    "archiver": "^3.1.1",
    "async": "^3.2.0",
    "axios": "^0.19.2",
    "bluebird": "^3.7.2",
    "body-parser": "^1.19.0",
    "compressing": "^1.5.0",
    "connect-mongo": "^3.2.0",
    "cputilization": "^1.0.0",
    "crypto-js": "^4.0.0",
    "express": "^4.17.1",
    "express-session": "^1.17.1",
    "file-type": "^16.0.1",
    "form-data": "^3.0.0",
    "formidable": "^1.2.1",
    "get-folder-size": "^2.0.1",
    "jsdom": "^16.2.2",
    "mongoose": "^5.8.1",
    "node-stream-zip": "^1.12.0",
    "node-uuid": "^1.4.8",
    "public-ip": "^4.0.2",
    "read-blob": "^1.1.2",
    "resolve-from": "^5.0.0",
    "semver": "^6.3.0",
    "silly-datetime": "^0.1.2",
    "socket.io": "^2.3.0",
    "unzip": "^0.1.11",
    "uuid": "^3.3.3",
    "ws": "^7.4.1",
    "xml": "^1.0.1",
    "xml-js": "^1.6.11",
    "xml2js": "^0.4.22",
    "zlib": "^1.0.5"
  }

```
## Node Vsersion

    v10.15.3
## DataBase

    MongoDB
