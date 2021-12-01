a.	項目搭建說明

    1. 安裝NodeJS環境(V10.15.3)
    
    2. 安裝yarn(v1.13.0)

    3. 運行yarn install命令安裝項目依賴包
    
b.	項目使用方法

    運行：yarn start命令 (開發環境)

    打包：yarn build命令 (生產環境)

c.	項目包依賴和用途說明

d.	項目目錄和文件結構

    |—— build            打包后生成文件
    |—— node_modules     依賴包文件
    |—— public           靜態文件
    |—— src
        |—— actions      react方法文件
        |—— components   項目頁面組件文件
        |—— containers   項目頁面文件
        |—— js           js方法文件
        |—— reducers     react方法文件
        |—— stores       react方法文件
        |—— styles       CSS樣式
        |—— App.js       路由
        |—— index.js     項目运行入口
    |—— package.json     依賴包版本信息
    |—— yarn.lock        yarn安裝依賴包信息

e.	項目模塊命名說明

    |—— src
        |—— containers
            |—— Admin
                |—— Role  
                    |—— AddRole.js                         Add Role 文件
                    |—— index.js                           Role List 文件
                |—— User
                    |—— AddAndEditUser.js                  Add And Edit Role 文件
                    |—— index.js                           User List 文件
            |—— Error505       
                |—— index.js      
            |—— Home
                |—— Header.js                              Home Header 文件
                |—— HomeContent.js                         Home Route 文件
                |—— HomeTable.js                           Home Table 入口文件
                |—— index.js                               Home 入口文件
                |—— Nav.js                                 Home Navigation bar 文件
            |—— Login
                |—— index.js                               Login 文件
            |—— Master
                |—— Company
                    |—— AddCompany.js                      Add Company 文件
                    |—— index.js                           Company List 文件
                |—— Project
                    |—— AddAndEditProject.js               Add And Edit Project 文件
                    |—— index.js                           Project List 文件
            |—— NoMatch
                |—— index.js                               404 文件
            |—— Operation
                |—— Planning
                    |—— AddProject.js                      Add Project 文件
                    |—— EditPlanning.js                    Edit Planning 文件
                    |—— index.js                           Planning List 文件
            |—— Report
                |—— ManningSchedule     
                    |—— index.js                           Manning Schedule List 文件

f.	項目注意事項
