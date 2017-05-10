# 主体内容

## 插件目录结构

1. 支付插件存储于/modules/checkout目录下，我们创建了一个yijiesppay的目录这个目录定义了一个插件名称，在这个目录下我们定义了一个module.yijiesppay.php的文件，这个文件的格式是按照Interspire Shopping Cart系统的要求定义的，要求是module.xxx.php这里xxx为插件名称和我们定义的哪个目录名一致。
1. 在/modules/checkout/yijiesppay目录下我们还定义了images、lang两个目录image主要存放了本插件使用到的一些图片；lang目录中主要存放了我们的语言支持文件

## 代码组织

主要代码存放于module.yijiesppay.php文件中我们定义了CHECKOUT_YIJIESPPAY类这个类继承于系统原有的ISC_CHECKOUT_PROVIDER类。关于本类的方法请详细阅读代码中的注释。
