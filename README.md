# EasyPermissionDemo
google的动态权限处理方案easypermission的demo

easypermission主要做了两件事情：
1. 对Android原生代码对权限的校验进行了封装，通过easypermission可以方便的对当前应用时候拥有权限进行判断。`EasyPermissions.hasPermissions()`
2. 对权限进行操作之后的动作进行了处理，包括弹窗提醒等，无需开发者自行处理。

不足之处：
实质上并非动态权限的处理，大部分使用场景下，仍需要开发者手动对需要使用权限的地方进行判断。
