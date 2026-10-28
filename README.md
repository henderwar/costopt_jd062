# costopt_jd062

**校验推理成本优化顾问·流水线并行气泡比例的字段结构并列出缺失项。**

`costopt_jd062` —— 从样本里推断推理成本优化顾问·流水线并行气泡比例应有的字段集合，逐字段检查存在性与类型，缺失项单独列出

- 零依赖，Python 3.10+ 标准库即可运行
- 单文件，`costopt_jd062.py` 拷走就能用
- 不联网、不写文件

## 对应的岗位

- 目标岗位：**小米 · 初级推理成本优化顾问**
- 技能主线：推理加速、模型压缩、大模型推理
- 领域标签：大模型推理、AI基础设施
- 研究方向：推理成本优化顾问·流水线并行气泡比例

工具里的规则表就是照着上面这条岗位要求建的——每条规则都挂在技能线或领域标签上，命中时能指回具体要求。

<!-- ipos:install -->
## 安装

零依赖，Python 3.10+ 即可：

```bash
pip install henderwar-costopt_jd062
```

装完直接用命令名调用：

```bash
costopt_jd062 --help
```

也可以不用安装，直接把 `costopt_jd062.py` 拷走用——它只依赖标准库。

## 为什么需要它

字段集合从样本推断而不是写死，因此适用于没见过的推理成本优化顾问·流水线并行气泡比例结构

它遵守下面几条自己定的规矩：

1. **只报告能定位到具体位置的结论**，不做语义猜测。
2. **规则表公开**，每条命中都能对应到岗位要求的一条明示规则。
3. **输入为空或格式不对时明确报错**，不静默返回空结果。

## 用法

```bash
python costopt_jd062.py --file input.txt
python costopt_jd062.py --text "示例内容"
python costopt_jd062.py --file input.txt --json
```

加 `--json` 可以拿到机器可读的结果，便于接到流水线里。

## 已知局限

- 类型推断基于 AST，动态构造的返回值会标为无法判定。
- 不校验业务语义，只校验结构。

## 跑测试

```bash
python test_costopt_jd062.py
```

测试用独立的断言与临时数据，不污染工作目录。

## 来源与参考

- Python 标准库文档：<https://docs.python.org/3/>
- GitHub 仓库：<https://github.com/henderwar/costopt_jd062>

---

## 关于作者

henderwar 做推理成本优化顾问·流水线并行气泡比例相关的问题，方向对标小米的初级推理成本优化顾问岗位。这个工具先替你回答一个具体问题，再谈别的。

- 个人主页：<https://henderwar.github.io>
- 仓库：<https://github.com/henderwar/costopt_jd062>

## 许可

MIT，见 [LICENSE](LICENSE)。
