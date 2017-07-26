# market-manage
它会尽可能将所有模块区分开；每个模块都具备模板处理和静态资源处理的功能


## dealer 分销管理
负责管理整个代理体系并不负责销售和安装

## manage-service 系统管理
负责管理高阶管理员各项管理职能；比如各种系统运行参数的调整以及所有登录体系的许可

## web 项目
管理各模块共享的web资源

## payment-support-huabei
花呗支付的支持

### 注意
目前暂时将所有页面都管理与web模块，这是仅仅临时的解决方案
/web/src/main/webapp/