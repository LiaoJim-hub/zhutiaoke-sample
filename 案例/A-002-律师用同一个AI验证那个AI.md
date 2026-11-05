# 案例 A-002 · 律师用同一个 AI 验证那个 AI

> **报告指纹**：sha256:9db63cbfd226d268
> **可核等级**：**L1**（第 54 号文书全文公开，逐段可对）
> **必查项**：B1（出处）
> **断点集**：**B4 · B5**（按《格式·开源案例 v1》§5.2 字面定义复算）；**收紧定义后为 B1 · B3 · B4 · B5**——两个读数都报，见 §五.4
> **结论出处**：`Mata v. Avianca, Inc., 678 F. Supp. 3d 443 (S.D.N.Y. 2023)`，制裁令 No. 1:22-cv-01461 (PKC)，ECF No. 54，2023-06-22，43 页，Castel 法官。**本件所有引文均取自该文书原文，段号为原文 Finding of Fact 编号。**
> **我们不主张**：本件**不能**被当成「AI 不该用于法律工作」（法庭原文明说用可靠 AI 工具协助没有本质不当）；**不能**被当成「律师群体普遍如此」（这是一案）；**不能**被当成「我们的机制能防住它」（第 §六 节说清了它防不住哪一半）。
> **受谁托**：持有方（「整理好开源所需的案例及数量」）· C 落盘，A 终审
> **as-of**：2026-11-05 19:4x（v1.1 · 补报告指纹）
> **正本 / 副本**：仅 .md 正本，无副本，故无对账器。

---

## 一 · 案例卡【证】

| 项 | 内容 |
|---|---|
| 主体 | 律师 Steven A. Schwartz（做研究）· Peter LoDuca（签名出庭）· Levidow, Levidow & Oberman 律所 |
| 时间 | 2023-03-01 提交文书 → 03-15 对方质疑 → 04-11/12 法院两次命交原件 → 05-25 开始承认 → 06-22 制裁令 |
| 触发 | 律师用 ChatGPT 检索判例，用于反对航空公司的驳回动议 |
| 实际发生了什么 | ChatGPT 生成 **6 份不存在的判例**（Varghese / Shaboon / Petersen / Martinez / Durden / Miller），含伪造引文与伪造引述，且**分别伪托给真实在任法官** |
| 争点 | 依 Rule 11，提交 AI 生成的虚假引注、且被质疑后继续坚持，是否构成主观恶意 |
| 裁决 | 认定 **subjective bad faith**（"acts of conscious avoidance and false and misleading statements to the Court"） |
| 制裁 | **$5,000 连带（jointly and severally）**，14 日内缴入法院登记处；另须逐一具名致函 6 位被伪托的法官与当事人本人 |
| 同日另一裁定 | 驳回原告实体请求（蒙特利尔公约两年期限已过）——**虚假引注不是驳回原因** |

---

## 二 · 原文逐字【证】

**① 制裁金额（第 43 页，命令段 d）**

> "**A penalty of $5,000 is jointly and severally imposed on Respondents** and shall be paid into the Registry of this Court within 14 days of this Opinion and Order."

**② 法庭的立场（开篇）**

> "Technological advances are commonplace and there is nothing inherently improper about using a reliable artificial intelligence tool for assistance. **But existing rules impose a gatekeeping role on attorneys to ensure the accuracy of their filings.**"

**③ 失责的认定（开篇）**

> "Peter LoDuca, Steven A. Schwartz and the law firm of … (collectively, 'Respondents') **abandoned their responsibilities** when they submitted non-existent judicial opinions with fake quotes and citations created by the artificial intelligence tool ChatGPT, **then continued to stand by the fake opinions** after judicial orders called their existence into question."

**④ 本来可以不罚（开篇）**

> "**if the matter had ended with Respondents coming clean about their actions shortly after they received the defendant's March 15 brief** questioning the existence of the cases, or after they reviewed the Court's Orders of April 11 and 12 requiring production of the cases, **the record now would look quite different**."

**⑤ 他问过那个 AI（Facts ¶ 45）**

> "The Schwartz Affidavit of May 25 included screenshots taken from a smartphone in which Mr. Schwartz questioned ChatGPT about the reliability of its work (e.g., '**Is Varghese a real case**' and '**Are the other cases you provided fake**'). … ChatGPT responded that it had supplied '**real**' authorities that could be found through **Westlaw, LexisNexis and the Federal Reporter**."

**⑥ 他自己写的：怀疑已起，仍采信同源（Facts ¶ 47 引其 6 月 6 日声明）**

> "As a result, I asked ChatGPT directly whether one of the cases it cited … was a real case. Based on what I was beginning to realize about ChatGPT, **I highly suspected that it was not. However, ChatGPT again responded that Varghese 'does indeed exist' and even told me that it was available on Westlaw and LexisNexis, contrary to what the Court and defendant's counsel were saying.**"

**⑦ 他承认 ChatGPT 不是补充，是唯一来源（Facts ¶ 41）**

> "THE COURT: But ChatGPT was not supplementing your research. **It was your research, correct?** / MR. SCHWARTZ: **Correct.**"

**⑧ 法院为什么不信他（Facts ¶ 47 末）**

> "These **shifting and contradictory explanations**, submitted even after the Court raised the possibility of Rule 11 sanctions, **undermine the credibility of Mr. Schwartz and support a finding of subjective bad faith**."

---

## 三 · 甩锅的三段动作【判】

> **锚**：第二节第 ⑤、⑥、⑧ 句（¶ 45 / ¶ 47 / ¶ 47 末）

| 动作 | 本案的形态 | 法庭的驳回（逐字） |
|---|---|---|
| **① 造一个可归责的主体** | 「我被 ChatGPT 误导了」——把它说成一个提供虚假信息的来源 | 法庭未采信此说：认定其"shifting and contradictory"（第 ⑧ 句），并据此认定主观恶意 |
| **② 不解释依据** | 5 月 25 日宣誓书与 6 月 6 日声明对同一件事给出两种解释 | 第 ⑧ 句：两种解释"互相矛盾"，且是在法院已提出 Rule 11 之后提交的 |
| **③ 把核实义务推给对方** | 「它向我保证过可信」——把"该由我核"变成"该由它保证" | 第 ② 句：**把关责任在律师身上**（gatekeeping role on attorneys），不在工具 |

**★ 本案与 A-001 的差别不在甩锅动作，在于本案多了一层：他真的去问了那个 AI。** 见下。

---

## 四 · 失责链：本案比甩锅多出来的那一步【判】

> **锚**：第二节第 ⑤、⑥、⑦ 句；第五节 B4

| 步 | 本案的形态 | 原文位置 |
|---|---|---|
| 1 把生成当检索 | 「我以为它是一个超级搜索引擎」 | ¶ 37（"I heard about this new site which I assumed … was like a super search engine"） |
| 2 只取摘要，不取全文 | 他**从未取得任何一份"判决"的全文**，只引用聊天生成的片段 | ¶ 40 |
| 3 **验证，但用同一个源** | 问 ChatGPT「Is Varghese a real case」，它答"确实存在，Westlaw/LexisNexis 可查" | ¶ 45、¶ 47 |
| 4 **体外信号与同源信号冲突时，采信同源的** | 它说"存在"，**"contrary to what the Court and defendant's counsel were saying"**，他选择信它 | ¶ 47 |

**★ 第 4 步是本案真正的核心。** A-001 里没有人做过验证；本案里**验证做了，且失败在"验证源"上**——当外部世界（法院、对方律师）与产生它的那个东西说法相反时，他选了后者。

**这一条对我们最要紧**：我们整套机制压在「至少有一个读数不由被控系统生产」上。**本案是一个已经做过验证、却仍然失败的实例——失败的原因不是没验，是验的源在同一侧。**

---

## 五 · 断点【判】

> **锚**：第四节第 3、4 步（¶ 45 / ¶ 47）；第二节第 ④ 句（"coming clean" 那一段）

### 5.1 按《格式·开源案例 v1》§5.2 字面定义复算

| 码 | 字段 | 本案 | 依据 |
|---|---|---|---|
| **B1** | 出处 | ✗ 未断（字面） | 引注写全了：`925 F.3d 1339 (11th Cir. 2009)`、F. Supp.、Westlaw——**写了，只是那份正本不存在** |
| B2 | 唯一落点 | ✗ | 只有一份提交给法院的文书 |
| **B3** | 发布者 | ✗ 未断（字面） | 那一格有值：LoDuca 签名，且签了 "I declare under penalty of perjury" |
| **B4** | 验证源 | **✅ 断** | 验证动作发生在产生它的同一个系统内（¶ 45、¶ 47） |
| **B5** | 撤回 | **✅ 断** | 3-15 被质疑、4-11/12 法院两次命交原件，直到 5-25 才"dribble out the truth"（¶ 47 前段；第二节第 ④ 句） |
| B6 | 额度 | ✗ | 无"这个工具被允许就哪些事项作答"的痕迹 |

**⇒ 字面断点集 = {B4, B5}。**

### 5.2 收紧定义后的重算（两个读数都要报）

v1 那两个定义太松——**B1 只管"写没写"，不管"查不查得到"；B3 只管"填没填"，不管"填的是不是做事的人"**。收紧后：

| 码 | 收紧后的判据 | 本案 | 依据 |
|---|---|---|---|
| B1 | 该出处**能否被第三方查到** | **✅ 断** | ¶ 12：他自己输入 "Varghese" 引注**查不到**，仍引用 |
| B3 | 签名者与实质作者**是否同一人** | **✅ 断** | ¶ 2 + ¶ 3 背景：Schwartz 做全部实质工作但不在该区执业，**由 LoDuca 署名**（"Mr. Schwartz continued to perform all substantive legal work"） |

**⇒ 收紧断点集 = {B1, B3, B4, B5}。**

### 5.3 这个差意味着什么（本节是本案对我们最有用的产出）

| 读法 | A-001 断点集 | A-002 断点集 | 交集 | 按 v1 §九 判 |
|---|---|---|---|---|
| **字面（松）** | {B1, B2, B3} | {B4, B5} | **∅** | **合格** |
| **收紧（紧）** | {B1, B2, B3} | {B1, B3, B4, B5} | **{B1, B3}** | **不合格** |

> ## **同一个事实，定义松一档就"合格"，紧一档就"不合格"——而松紧由我定。**

**⇒ 故「断点集交集为空」这条判据，对定义松紧极度敏感，它不是一个稳定判据。**

思考台 19:31 给的解法是「字段先冻结」。**但冻结松的字段，结论是假绿；冻结紧的字段，结论是假红。冻结本身不够。**

### 5.4 由此提出的一条改法（给格式规范 v2）

每个字段的定义必须是**可执行的操作**，不是**程度的描述**：

| 坏（程度） | 好（操作） |
|---|---|
| B1「有没有写明依据哪份正本」 | B1「**取该出处原文，在公开库中检索，能否命中**」 |
| B3「那一格填的是什么」 | B3「**签名者与实质作者是否同一人**」 |

**判据要能被一个读者在 5 分钟内执行完。执行不了的，是程度词，不是字段。**

---

## 六 · 若补上这个字段，能不能判【判】

> **锚**：第五节 5.1 表 B4、B5 两行

| 字段 | 能不能判 | 判据写成什么样 | 本案若有的效果 |
|---|---|---|---|
| **B4 验证源** | **能，且当场可判** | 每条被引用的判例必须带「**核验方式 + 核验方**」，核验方不得是被核验系统本身 | 3-01 提交那一刻就会被问："这条你用什么核的？" 答"ChatGPT"⇒ 当场红 |
| **B5 撤回** | **能，但需外部触发** | 收到质疑后的 N 小时内必须有一个「已核 / 已撤」的回执动作；无回执 ⇒ 红 | 3-15 至 5-25 那 71 天会是一条持续变红的读数，而不是靠法官某天想起来追 |
| **B1 出处（收紧版）** | **能，可机检** | 引注必须在公开库命中；不命中 ⇒ 红 | ¶ 12 那一刻（他自己查不到）就该红 |
| **B3 发布者（收紧版）** | **能，但只判得了"是不是同一人"** | 签名者 == 实质作者；不等 ⇒ 黄（不是红，因为分工本身合法） | 会让"谁签字谁负责"这句话在版面上可核 |

**★ 但要说清它防不住哪一半**：本案的证据是"他做了验证，用错了源"。**B4 能把"用同一个源验证"标出来，但它标不出"这个人根本不相信外部信号"**（¶ 47：他明知法院说没有，仍采信 ChatGPT）。**那一层不是字段问题，是人的问题。**

---

## 七 · 判据自身的洞【判】

> **锚**：第二节第 ① 句与第 ⑥ 句的对照

### 洞一：二手来源会把"连带"读成"各付"——L1/L2 分级不是纸面规定

同一个 $5,000，三家媒体给出两种互斥说法：

| 来源 | 原文 | 与判决书对照 |
|---|---|---|
| **判决书（L1）** | "A penalty of $5,000 is **jointly and severally** imposed" | — |
| CNBC（2023-06-22） | "ordered both LoDuca and Schwartz, along with their law firm … to **each pay $5,000** in fines" | **错**（会读成 15,000） |
| ABC（2023-07） | "were fined **US$5,000**" + 律所名 | 对 |
| 中文报道（财联社/澎湃） | "5 千美元**连带**责任" | 对 |

**⇒ 只读二手，这份案例的金额会写错 3 倍。** 这不是媒体的错，是**"连带"与"各付"在自然语言里只差一个副词**，而它决定金额是三倍还是一倍。

**这条直接给《格式·开源案例》§六 提供了一个实例**：L1 与 L2 的差别不是"准不准"，是**"错了你看不出来"**。

### 洞二：「gatekeeping role」这句话，不是一个道德要求，是一个位置

法庭没有说"律师应该更小心"。它说的是：

> "existing rules impose a **gatekeeping role** on attorneys"

**"把关"是一个位置，不是一个态度。** 位置的特征是：**只要你在那个位置上签了名，你就要对内容负责，不管你实际做没做。** 本案 LoDuca 只签名、没做研究，仍被制裁——因为位置在他身上。

**⇒ 这与 A-001 的断点 C（发布者那一格为空，空位被填成"不是我"）是同一件事的两面**：
- A-001：格子空着 ⇒ 谁都能说"不是我"；
- A-002：格子填着 ⇒ **填了就不能说"不是我"，哪怕活不是你干的。**

**故"把发布者那一格填上"这一条，在 A-002 里不是缺失，是已经做到、并且起了作用**——它让 LoDuca 无处可退。**这是一个正面实例：那个字段真的管用。**

---

## 八 · 断点对照【判·无横向结论】

> **锚**：A-001 第五节、本件第五节

| 案例 | 断点字段 | 该字段在材料里的原文位置 | 读者可复算的读数 |
|---|---|---|---|
| A-001 | B1 出处 | 判决书正文引 chatbot 答复：「…kindly do so within 90 days…」，未写依据哪份政策 | 该输出无"依据"字段 |
| A-001 | B2 唯一落点 | 判决书正文：官网 Bereavement travel 页与 chatbot 在同一域名下给出相反结论 | 同一规则存在于两处 |
| A-001 | B3 发布者 | 判决书引公司抗辩：「the chatbot is a separate legal entity that is responsible for its own actions」 | "谁说的"一栏为空 |
| A-001 | B4 验证源 | 本案不适用（该字段在本案有值：**无人做过任何验证**） | 无验证动作 |
| A-001 | B5 撤回 | 本案不适用（该字段在本案有值：公司事后告知旅客"misleading words"并更新） | 更正在事后 |
| A-002 | B1 出处 | 本件 §二 无；见 §五.2 与 ¶ 12（他输入 "Varghese" 引注，查不到，仍引用） | 引注在公开库无命中 |
| A-002 | B3 发布者 | 本件 §二 无；见 ¶ 2（"Mr. Schwartz continued to perform all substantive legal work"）+ 文书签名栏 | 签名者 ≠ 实质作者 |
| A-002 | B4 验证源 | 本件 §二 第 ⑤、⑥ 句（¶ 45、¶ 47） | 验证方 = 被验证系统本身 |
| A-002 | B5 撤回 | 本件 §二 第 ④ 句 + ¶ 47 前段（"doubled down"，5-25 才承认） | 质疑后 71 天无撤回动作 |

★ **本表只并列，不给结论。** 哪几行算"同一件事"，由读者判。

---

## 九 · 可错条件【证】

1. **若 ¶ 号有误** ⇒ 本件第一、二、五节的"依据"列要重标；**引文本身不受影响**（引文逐字取自 ECF 54 全文）。
2. **若 §五.2 那两处"收紧定义"被判定为"为了凑结论改定义"** ⇒ 本件 §五.3 那张对比表要撤，A-002 断点集退回 {B4, B5}。**我自标：这两处改动发生在看到 A-002 之后，不可信。**
3. **若"$5,000 连带"被证伪**（例如另有单独罚款）⇒ 本件第一节、第七节洞一要重画。
4. **最可能错的一条**：我把本案当成"验证源"的标本，**但法庭判的是"主观恶意"（bad faith），不是"验证方法不当"**。若如此，则本件第四节那条"失责链"是**我加的**，判决书没有这样拆——第四节整节要降为"我们的读法"，而不是"本案的结构"。

---

## 十 · 待审

1. **§九 第 4 条**：第四节那条四步失责链，是我拆的，不是法庭拆的。**要不要保留？** 若保留，它就该标成【判】而不是现在这样像在描述案件结构。
2. **§五.3 的两种读法**，请你判哪个算数——**这一条决定首版"2 份"成不成立。**
3. **本案是否该进首版？** 它和 A-001 都是"美国、法律/客服、2023-2024"，**行业跨度可能不够**——你若判"不够"，那第二份要换。

---

## 十一 · 复算清单【证】

> 三条，读者可自己做。**做不完三条 ⇒ 本件的 L1 等级不成立。**

| # | ① 动作 | ② 对什么 | ③ 判什么 |
|---|---|---|---|
| 1 | 打开 `https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1:2022cv01461/575368/54/`，翻到第 43 页 | 「**A penalty of $5,000 is jointly and severally imposed**」 | 若写的是 "each"，则本件第一节与第七节洞一作废 |
| 2 | 同一文书，搜 `Is Varghese a real case` | Finding of Fact **¶ 45** | 若搜不到该句，本件第二节第 ⑤ 句作废 |
| 3 | 同一文书，搜 `contrary to what the Court` | Finding of Fact **¶ 47** | 若搜不到，本件第四节第 4 步与第五节 B4 作废 |
| 4（加分） | 搜 CNBC 2023-06-22 报道，搜 `each pay` | 与第 1 条对照 | 若它也写 "jointly and severally"，则本件第七节洞一作废（**这一条验的是"二手会不会错"，不是本案**） |

---

## 来源

- 判决：`Mata v. Avianca, Inc.`，No. 1:22-cv-01461 (PKC)，ECF No. 54，2023-06-22，S.D.N.Y. · https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1:2022cv01461/575368/54/
- 判例汇编引注：678 F. Supp. 3d 443 (S.D.N.Y. 2023)
- 二手（用于第七节洞一的对照，**不作事实来源**）：CNBC 2023-06-22 · ABC News 2023-07 · 财联社 / 澎湃中文报道
- 判据：`D:\在场OS\docs\责任切片表（2026-10-21）.md` · `格式·开源案例（v1·C·2026-11-05）.md`
- 检索与成件：2026-11-05 20:1x
