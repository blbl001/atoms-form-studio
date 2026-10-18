# Atoms Form Studio

一个可运行的 Atoms Demo：用自然语言描述需求，生成可交互的 Landing Page，并在同一工作区中继续修改、保存项目和查看版本。

## 在线演示

- Demo：https://47.103.20.160:8443/
- 测试账号：`cjcjcj`
- 测试密码：`123456789`
- （也可以自行注册）

## 功能

- 自然语言生成 Landing Page
- Hero、导航、关于、地址和会员注册模块
- 对话记录与连续修改
- 多项目创建和切换
- localStorage 持久化
- 版本历史和恢复
- 预览、独立窗口、全屏和手机尺寸
- Schema 查看与复制

## 技术栈

React 18、TypeScript、Vite、lucide-react。

## 本地运行

```bash
npm install
npm run dev
```

生产构建：

```bash
npm run build
npm run preview
```

## 设计说明

Demo 使用结构化 Landing Schema 驱动 React 组件渲染。自然语言输入先转换为受控的页面配置，再由预览组件渲染，保证输出稳定并便于继续扩展。项目数据和版本快照暂存于浏览器 localStorage，无需后端即可完成完整交互闭环。

## 提交信息

- 姓名：陈杰
- 应聘岗位：测试工程师
- GitHub：blbl001/atoms-form-studio
