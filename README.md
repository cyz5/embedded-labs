# embedded-labs

嵌入式课程配套练习仓库。课程正文在 <https://cyz5.github.io/>。

仓库里**只有 14 个章节目录**，没有预建课程子目录。准备做某一节课的练习时，
在对应章下新建「技能点编号」子目录即可。

## 目录约定

```text
labs/
├── 01-c/                  # 第 1 章 C 语言深度
│   └── 1.1.1/             # 用到时再建：1.1.1 这节课的代码
├── 02-cpp/                # 第 2 章 C++（嵌入式子集）
├── 03-mcu/                # 第 3 章 MCU 硬件与底层
│   └── 3.1.2/             # 例：NVIC 练习
├── 04-rtos/               # 第 4 章 RTOS 技术栈
├── 05-linux/
├── 06-architecture/
├── 07-engineering/
├── 08-protocols/
├── 09-industry/
├── 10-safety/
├── 11-specialist/
├── 12-soft-skills/
├── 13-edge-ai/
└── 14-application/
```

子目录名就是技能点编号，与课程 URL 一一对应：

```text
课程：https://cyz5.github.io/p/1-1-1/
练习：labs/01-c/1.1.1/
```

## 开始一个练习

**本地**

```bash
git clone https://github.com/cyz5/embedded-labs.git
cd embedded-labs
mkdir labs/01-c/1.1.1
# 写代码、测试、README
git add -A
git commit -m "feat(1.1.1): 多级指针与函数指针"
git push
```

**网页端**

进入对应章节目录 → Add file → Create new file → 文件名输入 `1.1.1/README.md`，
GitHub 会自动创建 `1.1.1/` 子目录。之后再往里上传代码文件。

> Git 不跟踪空目录。新建子目录时至少放一个文件（`README.md` 或 `.gitkeep`），
> 否则 push 后仓库里看不到。

## 章节索引

| 章 | 目录 | 已上线课程 |
| --- | --- | ---: |
| 1 C 语言深度 | [`labs/01-c`](labs/01-c) | 15 |
| 2 C++（嵌入式子集） | [`labs/02-cpp`](labs/02-cpp) | 0 |
| 3 MCU 硬件与底层 | [`labs/03-mcu`](labs/03-mcu) | 89 |
| 4 RTOS 技术栈 | [`labs/04-rtos`](labs/04-rtos) | 44 |
| 5 嵌入式 Linux | [`labs/05-linux`](labs/05-linux) | 0 |
| 6 软件架构设计 | [`labs/06-architecture`](labs/06-architecture) | 0 |
| 7 工程化体系 | [`labs/07-engineering`](labs/07-engineering) | 0 |
| 8 通信协议与网络 | [`labs/08-protocols`](labs/08-protocols) | 0 |
| 9 行业应用领域 | [`labs/09-industry`](labs/09-industry) | 0 |
| 10 安全技术 | [`labs/10-safety`](labs/10-safety) | 0 |
| 11 专项能力 | [`labs/11-specialist`](labs/11-specialist) | 0 |
| 12 软技能 | [`labs/12-soft-skills`](labs/12-soft-skills) | 0 |
| 13 边缘 AI 基础 | [`labs/13-edge-ai`](labs/13-edge-ai) | 0 |
| 14 应用层业务设计 | [`labs/14-application`](labs/14-application) | 0 |

全部课程列表见 <https://cyz5.github.io/courses/>。

## 提交信息建议

```text
feat(1.1.1): 完成指针数组与函数指针练习
fix(3.1.2): 修正优先级分组测试
docs(4.2.1): 补充信号量实验记录
```

## License

代码版权归作者所有；如需开源协议，后续在仓库设置里补。
