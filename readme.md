# 仿站电商平台项目说明文档

## 项目简介
本项目是一个基于HTML、CSS和JavaScript开发的电商平台前端项目，实现了用户登录、商品展示、个人中心等基本功能。

## 技术栈
- HTML5
- CSS3
- JavaScript
- Axios（用于HTTP请求）
- Swiper（用于轮播图展示）

## 功能模块

### 1. 首页模块
- 顶部导航栏（包含登录状态显示）
- 轮播图展示
- 商品列表入口
- 用户登录/退出功能

### 2. 商品列表模块
- 商品卡片展示
- 分页功能
  - 首页/末页跳转
  - 上一页/下一页
  - 自定义每页显示数量
  - 页码跳转
- 商品标签（热销/特惠）
- 价格显示（原价/现价）

### 3. 个人中心模块
- 用户信息展示
- 个人信息修改
  - 昵称修改
  - 年龄设置
  - 性别设置
- 密码修改入口
- 返回首页功能

### 4. 登录模块
- 用户名密码登录
- 表单验证
- 登录状态保持
- 注册入口

## 页面说明

### 1. index.html（首页）
- 头部导航居中布局
- 天蓝色主题
- 轮播图展示
- 响应式布局

### 2. list.html（商品列表）
- 商品网格布局
- 分页控制
- 返回首页按钮
- 商品卡片悬浮效果

### 3. self.html（个人中心）
- 表单布局
- 信息编辑功能
- 实时保存
- 简洁的导航设计

### 4. login.html（登录页面）
- 居中表单设计
- 响应式布局
- 友好的交互提示

## 使用说明

### 1. 首页访问
1. 打开index.html
2. 可查看轮播图
3. 点击"购买商品"进入商品列表
4. 未登录状态可点击"请登录"进行登录

### 2. 商品浏览
1. 进入商品列表页面
2. 可使用分页功能浏览所有商品
3. 可调整每页显示数量
4. 可通过页码直接跳转

### 3. 个人中心
1. 登录后可访问个人中心
2. 可修改个人信息
3. 可更改密码
4. 可随时返回首页

### 4. 登录操作
1. 输入用户名和密码
2. 点击登录按钮
3. 登录成功后自动跳转到首页
4. 可通过右上角查看登录状态

## 注意事项
1. 需要保持网络连接
2. 建议使用现代浏览器访问（Chrome、Firefox等）
3. 登录状态基于localStorage存储
4. 部分功能需要登录后才能使用

## 项目特点
1. 统一的设计风格
2. 响应式布局
3. 友好的用户交互
4. 完整的功能模块
5. 良好的代码组织

## 维护建议
1. 定期更新依赖库
2. 保持代码结构清晰
3. 注意浏览器兼容性
4. 及时处理用户反馈

## 后续优化方向
1. 添加商品搜索功能
2. 完善用户注册流程
3. 增加商品详情页
4. 添加购物车功能
5. 优化移动端适配 