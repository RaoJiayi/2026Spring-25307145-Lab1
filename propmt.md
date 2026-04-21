pdfkit-sample-code-arkts-master/
├─ AppScope/                     <!-- 应用作用域的目录，存放全局配置与应用级资源 -->
│  ├─ resources/                <!-- 应用所用的资源文件的根目录 -->
│  │  └─ base/
│  │     ├─ element/             <!-- 应用全局元素资源目录（字符串、颜色等） -->
│  │     └─ media/              <!-- 应用全局媒体资源目录 -->
│  │        └─ app_icon.png     <!-- 应用图标文件，桌面显示图标 -->
│  └─ app.json5                  <!-- 应用的全局配置文件，定义包名、版本、权限 -->
├─ entry/                        <!-- 应用的工程入口模块，默认启动模块 -->
│  ├─ src/
│  │  └─ main/
│  │     ├─ ets/
│  │     │  ├─ entryability/
│  │     │  │  └─ EntryAbility.ets <!-- 入口模块的入口UIAbility文件，应用启动入口 -->
│  │     │  ├─ pages/           <!-- 模块的页面文件目录，存放ArkUI页面 -->
│  │     │  │  └─ Index.ets     <!-- 模块的首页页面文件，PDF阅读器主界面 -->
│  │     │  └─ components/      <!-- 自定义组件目录，存放PDF渲染、文件列表等可复用组件 -->
│  ├─ resources/                <!-- 模块所用的资源文件的根目录 -->
│  │  ├─ base/
│  │  │  ├─ element/             <!-- 模块所用的元素资源目录（字符串、颜色、尺寸） -->
│  │  │  └─ media/              <!-- 模块所用的媒体资源目录（图片、图标） -->
│  │  │     ├─ background.png    <!-- UIAbility的入口图标文件 -->
│  │  │     └─ startIcon.png     <!-- UIAbility组件启动页面图标 -->
│  │  ├─ profile/               <!-- 模块所用的配置目录（页面、卡片、自定义配置） -->
│  │  │  └─ main_pages.json     <!-- 模块的页面配置文件，注册所有页面路由 -->
│  │  ├─ rawfile/               <!-- 模块所用的原始文件目录，存放PDF示例文件 -->
│  │  └─ zh_CN/                 <!-- 模块的限定词目录，存放中文本地化资源 -->
│  └─ module.json5              <!-- 模块的配置文件，声明模块信息、UIAbility、权限 -->
├─ build/                        <!-- 项目构建生成的目录，存放编译输出文件 -->
│  ├─ default/
│  │  └─ outputs/
│  │     └─ default/
│  │        └─ entry-default-unsigned.hap <!-- 编译生成的应用安装包 -->
├─ oh_modules/                   <!-- 项目依赖的第三方库目录，存放PDFKit等npm包 -->
├─ images/                       <!-- 项目文档说明用的图片资源目录 -->
├─ hvigor/                       <!-- 鸿蒙构建工具Hvigor的依赖目录 -->
├─ build-profile.json5           <!-- 项目级构建配置文件，定义构建选项、ABI -->
├─ hvigorfile.ts                 <!-- Hvigor构建工具的入口脚本文件 -->
├─ oh-package.json5              <!-- 项目依赖配置文件，声明所需npm包与版本 -->
├─ oh-package-lock.json5         <!-- 依赖版本锁定文件，保证开发环境一致性 -->
├─ LICENSE                       <!-- 项目开源协议文件 -->
├─ readme_cn.md                  <!-- 项目中文说明文档 -->
└─ readme_en.md                  <!-- 项目英文说明文档 -->
