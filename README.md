# Hi there, I'm  杨林森👋

**2026届前端开发工程师 (Class of 2026 Frontend Developer)**

我是一名专注于前端工程化与用户体验的开发者。我倾向于**拒绝死记硬背的八股文**，而是通过深挖真实的业务需求来驱动技术选型，并在实践中打通底层逻辑。

### 🛠️ 技术栈 (Tech Stack)

* **语言:** TypeScript (核心), JavaScript (ES6+), HTML5, CSS3/Sass
* **框架/库:** React (深入理解 Hooks 与渲染性能优化), Next.js
* **状态管理与数据流:** * Zustand (深入理解单向数据流与状态分片逻辑)
  * React Query / TanStack Query (精通服务端状态缓存、`useMutation` 自动刷新与无感静默同步)
  * Axios (精通底层实例封装、拦截器鉴权与 `FormData` 二进制文件流配置)
* **工程化:** Vite, Webpack, Git (遵循 Conventional Commits)
* **设计/UI:** Tailwind CSS, Ant Design

### 💡 核心项目 (Featured Projects)

* **[⚔️ Word Killer Admin (单词杀手后台) - 高性能中后台管理系统]** * **项目描述:** 基于 React 18 + TS 构建的单词流管理面板，对标大厂 B 端业务中常见的大数据量与复杂状态场景。
    * **技术深度 (核心亮点):**
        * **极致渲染性能:** 针对 20,000+ 条词汇数据，引入 `React Virtuoso` 实现虚拟列表滚动；配合 `useMemo` 缓存机制与自定义 `useDebounce` 防抖拦截，彻底解决长列表 DOM 节点溢出与频繁重绘导致的卡顿。
        * **算法与数据流:** 手写实现 **O(n) 时间复杂度**的扁平数据转树形结构 (List-to-Tree) 核心算法，瞬间完成万级架构节点的转换；封装通用 `treeUtils` 支持多业务线复用。
        * **架构解耦 & 乐观更新:** 大量采用 Custom Hooks (如 `useWordManager`, `useFileHandler`) 抽离底层逻辑，实现 UI 组件纯净态；在删除/修改等高频操作中引入**乐观 UI 更新 (Optimistic UI)**，配合 LocalStorage 实现无感数据持久化。
        * **数据可视化:** 接入 ECharts 绘制多维词表图表（构成比例、掌握率曲线、增量趋势），并通过 WebAPI 打通流式文件的本地上传与下载。

### ⚔️ 前端硬核实战演练 (Frontend Hardcore Training)

> **🎯 核心目标**: 备战 2026 届春招
> **💡 练习准则**: 拒绝死记硬背，全部基于真实业务需求（如游戏系统设计）推演 JavaScript/TypeScript 底层逻辑与 React 架构演进。

<details>
<summary><b>🟢 阶段一：JavaScript/TypeScript 底层逻辑突围 (进行中...)</b></summary>
<br>

- [x] **01-铁匠铺锻造功能 (Forge System)** *深入探索:* 对象方法声明、`this` 作用域穿透、默认参数、使用 `reduce` 进行高阶数据聚合、Event Loop 延迟执行机制。
- [x] **02-天网监控与封号功能 (Chat Monitor)** *深入探索:* TypeScript Interface 严格约束、基于 `filter` 与 `map` 链式调用的业务数据清洗。
- [x] **03-连击技能工厂 (Combo Skill Factory)** *深入探索:* 闭包与工厂函数模型、数组原地变异 (`push` + 展开运算符) 性能考量。
- [x] **04-排位赛匹配引擎 (Match Maker Engine)** *深入探索:* OOP 面向对象编程 (Class / constructor / static)、数组队列首位剔除 (`shift`)、TypeScript 严格元组约束 (Tuple)。

</details>

<details>
<summary><b>🔵 阶段二：React 架构与全局状态管理 (进行中...)</b></summary>
<br>

- [x] **05-装备背包系统 (React + Zustand Inventory)** *深入探索:* Zustand Store 全局状态剥离、跨组件无感知通信、UI 渲染与核心数据逻辑解耦。
- [x] **06-冒险者任务大厅 (React Quest Board)** *深入探索:* `useState` 局部状态闭环、`useEffect` 模拟网络请求与生命周期管控、父子传值。
- [x] **07-铁匠铺图纸商店 (Blacksmith Shop)** *深入探索:* **大厂标准组件设计**，`React.memo` 拦截多余渲染配合 Zustand 稳定引用 (Stable Reference)，前端数据派生计算 (Derived State)。

</details>
<details open>
<summary><b>🟣 阶段三：网络层基建与服务端状态管理 (Network & Server State)</b></summary>
<br>

- [x] **08-怪物图鉴大厅 (Bestiary Hall)** *深入探索:* Axios 底层实例封装与拦截器 (Interceptors) 核心脱壳机制、API 请求层与 UI 视图层的绝对解耦设计、RESTful 规范下的 `params` 与 `data` 严格区分、基于 Early Return 的 UI 降级策略。
- [x] **09-装备锻造台 (Forge System)** *深入探索:* 基于后端 API 契约的 TypeScript 接口逆向工程、Axios 泛型 (`<T, R>`) 深度注入以实现端到端类型安全、复杂嵌套响应结构 (`{ total, list }`) 的按需解构与映射、规避 `useEffect` 无限渲染死锁。
- [x] **10-勇者排行榜 (Leaderboard)** *深入探索:* 彻底分离“服务端状态”与“客户端状态”的架构思维、基于 `@tanstack/react-query` 的全局缓存调度中心搭建、使用 `useQuery` 替代 `useState`+`useEffect` 实现声明式数据拉取、深度解析 `queryKey` 缓存条形码机制。
- [x] **11-冒险者档案局 (Profile Bureau)** *深入探索:* 突破标准 JSON 请求模板，实战基于 `FormData` 的二进制文件流组装；深度挖掘 Axios 高级配置，挂载 `onUploadProgress` 拦截物理进度；掌握原生 DOM (`e.target.files[0]`) 提取技巧；利用 `useMutation` 结合 `invalidateQueries` 实现上传成功后的缓存强制失效与无感静默刷新。
- [ ] **12-[待解锁的下一个关卡...]**

</details>

### 📫 找到我 (Contact)
* **Email:** 3235882107@qq.com
