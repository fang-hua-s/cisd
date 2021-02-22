# package.json 相关命令说明

## build:dev

用于开发环境，以development模式打包项目文件以及第三方库；
初次运行项目时需要执行；
更新了public/register/config.js配置文件时需要重新执行；

# build:prod

用于生产环境，发布开发/测试/正式环境时自动执行；
     
# serve:register

用于开发环境启动服务，代理接口；
必须先执行build:dev命令；
修改了devServer.js的内容需要重新执行这个命令，其他情况不需要重新跑；

# element:install

element主题的初始化命令，不需要执行；

# element:build

element主题的构建命令，当修改了element-variables.scss之后需要执行此命令重新构建element的样式；
同时需要再执行build:dev命令才会在界面上生效；

# build:devTemp

用于对外提供基础工程时使用，快捷生成模板项目；
