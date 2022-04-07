# vite构建相关配置和插件

## 1、目录结构

```text
├── config              // 构建基本配置
	├── define.ts           // 项目构建时间
	├── path.ts							// 解析路径
	├── proxy.ts            // 本地请求代理
└── plugins                //构建插件
	├── auto-import.ts     // 自动导入
	├── html.ts            //html插件(注入变量，压缩代码等)
	├── iconify.ts         //iconify图标插件
	├── mock.ts            //mock插件
	├── visualizer.ts      //构建的依赖大小占比分析插件
	├── vue.ts             //vue相关vite插件
	└── windicss.ts        //css框架插件
```
