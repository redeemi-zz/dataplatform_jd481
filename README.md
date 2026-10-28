# dataplatform_jd481

**找出数据平台工程师·GPU 故障与作业自愈里互相矛盾的两处并排列出。**

`dataplatform_jd481` —— 在同一个输入里两两比对，检测数据平台工程师·GPU 故障与作业自愈相关的矛盾表述，把冲突双方原样并排呈现

- 零依赖，Python 3.10+ 标准库即可运行
- 单文件，`dataplatform_jd481.py` 拷走就能用
- 不联网、不写文件

## 对应的岗位

- 目标岗位：**宇树科技 · 初级数据平台工程师**
- 技能主线：Spark、Flink、SQL、Kafka
- 领域标签：数据平台、MLOps
- 研究方向：数据平台工程师·GPU 故障与作业自愈

工具里的规则表就是照着上面这条岗位要求建的——每条规则都挂在技能线或领域标签上，命中时能指回具体要求。

<!-- ipos:install -->
## 安装

零依赖，Python 3.10+ 即可：

```bash
pip install redeemi-zz-dataplatform_jd481
```

装完直接用命令名调用：

```bash
dataplatform_jd481 --help
```

也可以不用安装，直接把 `dataplatform_jd481.py` 拷走用——它只依赖标准库。

## 为什么需要它

不替用户猜哪一句是本意，只把矛盾双方并排摆出来，由人决定取舍

它遵守下面几条自己定的规矩：

1. **只报告能定位到具体位置的结论**，不做语义猜测。
2. **规则表公开**，每条命中都能对应到岗位要求的一条明示规则。
3. **输入为空或格式不对时明确报错**，不静默返回空结果。

## 用法

```bash
python dataplatform_jd481.py --file input.txt
python dataplatform_jd481.py --text "示例内容"
python dataplatform_jd481.py --file input.txt --json
```

加 `--json` 可以拿到机器可读的结果，便于接到流水线里。

## 已知局限

- 一致性靠字面差异判定，语义等价但写法不同会误报。
- 不解析跨文档的引用关系。

## 跑测试

```bash
python test_dataplatform_jd481.py
```

测试用独立的断言与临时数据，不污染工作目录。

## 来源与参考

- Python 标准库文档：<https://docs.python.org/3/>
- GitHub 仓库：<https://github.com/redeemi-zz/dataplatform_jd481>

---

## 关于作者

redeemi-zz 做数据平台工程师·GPU 故障与作业自愈相关的问题，方向对标宇树科技的初级数据平台工程师岗位。这个工具先替你回答一个具体问题，再谈别的。

- 个人主页：<https://redeemi-zz.github.io>
- 仓库：<https://github.com/redeemi-zz/dataplatform_jd481>

## 许可

MIT，见 [LICENSE](LICENSE)。
