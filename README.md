# VCard / 51vcard.com 涉嫌欺骗性支付服务举报资料

> 本仓库汇总 VCard／51vcard.com 的公开可核验证据、举报渠道、材料清单和可复制模板，帮助受影响用户保存证据并请求有权限的机构调查。
>
> 本文只使用“涉嫌”“请求调查”等表述。区块浏览器标签、云服务关系、域名注册信息和第三方协议调用均是调查线索，不单独证明任何个人、交易所、协议、云服务商或基础设施提供方参与违法行为。

核验日期：2026-08-21（Asia/Shanghai）

## 中文说明

- 每个模板最多保留三个替换项，并以 **【REPLACE 1—3：字段说明】** 标记。每个替换项应一次性填入一整段完整事实，提交前删除 REPLACE 标记。
- 模板按受理方通常使用的语言提供，不重复制作中英两个版本。中文机构使用中文，香港机构使用繁体中文，国际机构使用英文。
- 只提交由附件或公开记录支持的事实。没有证据时，不要写“诈骗已被确认”“恶意软件”“盗号”等结论。
- 建立公开脱敏包和私密原件包。公开材料必须遮住姓名、邮箱、手机号、账户 UID、证件号和无关资产；交易哈希与链上地址通常无需遮盖。
- 不要提供密码、验证码、私钥、助记词、CVV 或远程控制权限，也不要向所谓“追回人员”支付解冻费、税费或验证费。
- 同一渠道提交一次完整举报。保存提交截图、回执、工单号和时间；有新事实时回复原工单补充，不要重复刷报。
- 中国大陆公安、香港警方和 FBI IC3 在本文中列为保留渠道。平台举报无法替代执法机关依法调取实名、服务器日志、交易所 KYC 或实施跨境冻结。

## English overview

- Each template contains no more than three replacement blocks marked **【REPLACE 1–3: field description】**. Replace each block once with a complete factual paragraph and remove the REPLACE label before submitting.
- Each script is written in the language normally used by the recipient; the templates are not duplicated in both Chinese and English.
- Submit only facts supported by attachments or public records. Do not characterize a site as confirmed fraud, phishing, malware, or account theft without evidence.
- Maintain a redacted public evidence set and a private original set. Remove names, email addresses, phone numbers, account IDs, identity documents, and unrelated balances from public evidence.
- Never share passwords, one-time codes, private keys, seed phrases, CVV data, or remote-control access. Do not pay “recovery agents,” unlock fees, taxes, or verification fees.
- Submit one complete report per channel, retain its receipt and case number, and add later evidence to the same case.
- Law-enforcement channels are listed as reserved options. Service-provider reports cannot compel identity disclosure, KYC production, or cross-border asset restraint.

## 已公开核验的本案线索 / Publicly verified case indicators

- 网站 / Website: https://www.51vcard.com/
- 官网客服邮箱 / Published support email: kf@51vcard.com
- 官网 Telegram / Published Telegram: https://t.me/VCard_CN
- 公开推广线索 / Public promotional lead: https://t.me/paleehom
- 联系线索 / Contact lead: https://t.me/Kirsch1
  - 现有证据只显示受影响用户曾联系该账号而未获回复；这不能单独证明账号持有人是经营者或实施者。
- 已发生损失的 Arbitrum 地址 / Reported loss address:
  0xd9dd4b43a223aabe12a4354cb214c13a566dfd38
- 受害交易 / Victim transaction:
  https://arbiscan.io/tx/0xfbb8115e8c139ea39fb54a75090471ab721732412c337445af7e5d8fd5f6210a
  - 2026-08-12 00:16:09（UTC+8），259.9974 USD₮0，链上状态成功。
- 地址页 / Address page:
  https://arbiscan.io/address/0xd9dd4b43a223aabe12a4354cb214c13a566dfd38
- 归集交易 / Consolidation transaction:
  https://arbiscan.io/tx/0x9bcd82cf23f7da4d12f9331cc1e9f74a19a4aed24587e7cfd54cd5b37c519466
- 后续交易 / Subsequent transaction:
  https://arbiscan.io/tx/0xc64bc14d478866cce75fce5eb5f03c34340324a2cf4b3d8289bca1232dfd73c4
- Android APK 直链 / Direct Android APK:
  https://vcard-app.oss-cn-hongkong.aliyuncs.com/Vcard.apk
- 已观察到的 App 版本 / Observed app version: V1.0.2(2020)

公开链上记录显示：上述地址在 2026-08-05 至 2026-08-12 共收到 18 笔、合计 2,570.288704 USD₮0；随后在 2026-08-13 经 Rango 调用清空。扣除 5.140577 USD₮0 后，2,565.148127 USD₮0 两秒后进入 Arbiscan 标记为“NEAR Intents: Treasury”的地址。区块浏览器标签仅作为调查线索，不能单独证明法律控制权。

Public on-chain records show that the address received 18 USD₮0 deposits totaling 2,570.288704 between 5 and 12 August 2026 and was emptied through a Rango call on 13 August 2026. After 5.140577 USD₮0 was deducted, 2,565.148127 USD₮0 reached an address labelled by Arbiscan as “NEAR Intents: Treasury” two seconds later. Explorer labels are investigative leads, not proof of legal control.

## 通用证据编号 / Evidence index

- **E01**：提币平台完成页，显示币种、网络、扣款金额、手续费、地址、时间和参考编号。
- **E02**：完整交易哈希及区块浏览器成功页面。
- **E03**：VCard 充值页、到账承诺及当时显示的地址；若历史地址已刷新，必须如实说明没有同时期截图。
- **E04**：VCard 余额为零和账单无记录的截图或连续录屏。
- **E05**：发往 kf@51vcard.com 的邮件原件、完整邮件头、时间和投递状态。
- **E06**：Telegram 联系记录；公开前遮住无关联系人、头像和通知栏资料。
- **E07**：VCard App 版本、下载来源和官网入口截图。
- **E08**：51vcard.com 全页截图，保留地址栏、系统日期、宣传陈述、联系方式和下载按钮。
- **E09**：APK 原件、下载记录、文件哈希；没有原件时如实写明“通过官网入口安装”。
- **E10**：公开链上链接和资金路径说明。
- **E11**：举报提交截图、回执、工单号和提交时间。
- **E12**：表单要求时提供的法币折算依据，并注明汇率时间与来源。

Private originals may contain account or identity information. Never upload them to this public repository.

---

## 一、中国大陆公安／网安（保留渠道）

1. **链接**

   - 公安部网络违法犯罪信息举报网站：https://cyberpolice.mps.gov.cn/
   - 紧急或正式报案：110 或所在地县级公安机关

2. **准备的材料**

   - E01—E10 的私密原件。
   - 按时间顺序整理接触平台、取得地址、提币、链上确认、承诺到账时间届满、投诉及未回复。
   - 身份证件和账户归属证明只在公安机关正式渠道提供。
   - 不要提前删除 App、清除数据或重新安装。

3. **话术模板**

        我报案反映 51vcard.com 及其 VCard 应用涉嫌通过虚拟卡和稳定币充值服务收款后不入账。

        【REPLACE 1：交易事实完整段；一次写清提币时间和时区、提币平台、网络、总扣款、手续费、链上金额、收款地址、参考编号、交易哈希及确认状态】

        【REPLACE 2：未履约及催告完整段；一次写清到账承诺、最后核验时间、余额与账单状态、邮件或 Telegram 联系时间及回复情况】

        现有公开链上记录显示：【REPLACE 3：仅填写已有区块浏览器链接支持的资金路径摘要】。请求依法登记，固定网站、App、聊天、邮件及链上电子证据，调查实际经营主体，并向相关交易所、协议、域名注册商及云服务商发出数据保全和调证请求。

4. **必须替换**

   - REPLACE 1：交易事实段。
   - REPLACE 2：未履约及催告段。
   - REPLACE 3：已核验资金路径段。

---

## 二、OKX／实际提币平台：涉诈举报、地址标记和资料保全

1. **链接**

   - OKX 官方说明：https://www.okx.com/en-gb/help/what-should-i-do-during-or-after-a-scam
   - OKX 帮助中心：https://www.okx.com/help
   - 其他交易所用户应使用该交易所 App 内的涉诈举报或官方帮助中心。

2. **准备的材料**

   - E01、E02、E03、E04、E05、E06、E10。
   - 原始订单详情和参考编号。
   - 可以提交私密原件，但不要提供密码、验证码、私钥或助记词。

3. **话术模板**

        标题：VCard 疑似欺骗性支付服务导致链上充值未入账，请标记地址并保全资料

        我举报一笔由本人账户发出的、与疑似诈骗及疑似欺骗性支付服务有关的提币。

        【REPLACE 1：交易事实完整段；一次写清交易所、提币时间和时区、网络与代币、参考编号、总扣款、手续费、链上金额、收款地址、交易哈希及确认时间】

        【REPLACE 2：VCard 未履约完整段；一次写清地址来源、到账承诺、最后核验时间、余额与账单状态，以及邮件和其他联系渠道的时间与回复情况】

        请贵平台：
        1. 对上述收款地址进行独立风险审查，并在符合政策时添加高风险标记；
        2. 保存上述提币订单、风控、登录、设备及内部出账记录；
        3. 【REPLACE 3：如有同平台 Gas 注入或后续入金线索，写明交易哈希并请求保存关联账户、业务场景、KYC 和日志；没有则写“暂无额外平台关联线索”】
        4. 如后续资金进入贵平台控制的地址或账户，请依照适用法律、平台规则及正式调查要求采取限制措施；
        5. 提供工单编号和处理结果。

        我并不指控贵平台参与相关行为；本请求旨在风险标记、数据保全和协助调查。

4. **必须替换**

   - REPLACE 1：交易事实段。
   - REPLACE 2：未履约及催告段。
   - REPLACE 3：交易所关联线索段。

---

## 三、Chainabuse：公开标记已发生损失的地址

1. **链接**

   - 举报入口：https://chainabuse.com/report
   - 网络选择：Arbitrum；分类选择 Scam，没有时选择 Other。

2. **准备的材料**

   - E01—E06 的公开脱敏版和 E10。
   - 只公开已有损失交易直接支持的地址。
   - 不要公开 App 后来刷新出的地址、个人邮箱、账户 UID 或完整聊天身份资料。

3. **话术模板**

        Title: Suspected deceptive VCard payment service — on-chain deposit not credited

        This is a victim report concerning a suspected deceptive virtual-card payment service operated through 51vcard.com and the VCard application.

        【REPLACE 1: one complete transaction paragraph stating the date and time zone, amount and token, network, complete loss address, transaction hash, confirmation status, and how the address was obtained】

        【REPLACE 2: one complete evidence paragraph stating whether a contemporaneous address screenshot exists, any contemporaneous email or message, the VCard balance and ledger status, last verification date, and unanswered support contacts】

        Public on-chain records show: 【REPLACE 3: concise verified fund-flow summary supported by explorer URLs】. This report requests a public suspected-scam risk marker and independent investigation. It does not allege that any exchange, protocol, network, or infrastructure provider participated in the suspected misconduct.

4. **必须替换**

   - REPLACE 1：交易事实段。
   - REPLACE 2：证据及未履约段。
   - REPLACE 3：公开链上路径段。

---

## 四、Rango：归集交易和路由数据保全

1. **链接**

   - 官方联系页：https://rango.exchange/contact-us
   - 法律及保全邮箱：legal@rango.exchange

2. **准备的材料**

   - E02、E04、E10。
   - 受害交易、进入 Rango 的交易、Rango 输出交易和相关地址的区块浏览器链接。
   - 明确说明请求保存记录，不指控 Rango 参与涉嫌行为。

3. **话术模板**

        Subject: Preservation request regarding suspected fraud proceeds routed through Rango

        I am reporting a transaction associated with a suspected deceptive payment service and requesting preservation of records. I am not alleging that Rango participated in the suspected misconduct.

        【REPLACE 1: one complete victim-event paragraph stating the date, amount and token, network, loss address, transaction hash and explorer URL, address source, non-crediting, and unanswered support】

        The receiving address later called Rango through the following transaction:
        【REPLACE 2: Rango transaction hash, explorer URL, call time, input token and total input amount】

        The observable token transfers were:
        【REPLACE 3: exact verified outputs, fees, intermediary addresses, amounts, subsequent transaction hashes and explorer URLs】

        Please preserve all records associated with the Rango transaction, including API requests, route and quote data, request or order identifiers, integration and affiliate information, destination parameters, solver or liquidity-provider information, IP address, user agent, device information, timestamps, and support communications. Please acknowledge this preservation request, provide a case number, and identify the lawful disclosure process available to investigators.

4. **必须替换**

   - REPLACE 1：受害事件段。
   - REPLACE 2：Rango 调用段。
   - REPLACE 3：可见输出及后续路径段。

---

## 五、NEAR Intents：标记地址及意图记录保全

1. **链接**

   - 官方 Contact us 表单：https://airtable.com/appeHferup97zvJu2/pagb9PA5dhwhFcErI/form
   - 官方网站：https://intents.near.org/

2. **准备的材料**

   - E02、E04、E10。
   - Rango 归集交易、后续转账和被区块浏览器标记的地址链接。
   - 标签必须写成“区块浏览器标记”，不能写成已经证明由 NEAR 控制。

3. **话术模板**

        Subject: Preservation request concerning funds sent to an address labelled NEAR Intents: Treasury

        I request preservation and review of records concerning funds associated with a suspected deceptive payment service. I am not alleging that NEAR Intents or any NEAR entity participated in the suspected misconduct.

        【REPLACE 1: one complete victim-event paragraph stating the date, amount and token, network, loss address, transaction hash and explorer URL, address source, non-crediting, and unanswered support】

        【REPLACE 2: one complete routing paragraph stating the Rango or intermediary transaction, amount, addresses, hashes, times, and explorer URLs】

        【REPLACE 3: one complete label paragraph stating the final amount, token, address, subsequent transaction URL, explorer name, and exact public label】

        Please confirm whether the labelled address is operated by or used within NEAR Intents. If relevant records are within your control, please preserve all intent, deposit, solver, quote, route, destination, API, account, IP, device, and timestamp records associated with this transfer. Please identify the lawful disclosure channel for investigators and provide a case reference.

4. **必须替换**

   - REPLACE 1：受害事件段。
   - REPLACE 2：路由路径段。
   - REPLACE 3：最终地址及公开标签段。

---

## 六、USD₮0：代币地址风险审查

1. **链接**

   - 官方支持邮箱：support@usdt0.to
   - 官方资料：https://docs.usdt0.to/

2. **准备的材料**

   - E02、E03、E04、E10。
   - 已发生损失的地址和交易；App 后来显示的新地址只通过私密官方渠道提供。
   - 如果旧地址已经清空，应明确请求历史风险标记和资料保全，不承诺可以冻结或追回。

3. **话术模板**

        Subject: Risk review request for USDt0 addresses linked to a suspected deceptive payment service

        I request an independent risk review of Arbitrum USDt0 addresses associated with the VCard service at 51vcard.com. I am not asking USDt0 to treat any allegation as proven without its own review.

        【REPLACE 1: one complete victim-event paragraph stating the date, amount, loss address, transaction hash and explorer URL, address source, non-crediting, and unanswered support】

        Public records later showed:
        【REPLACE 2: verified consolidation summary with transaction hashes and explorer URLs】

        The application later displayed a different deposit address: 【REPLACE 3: current refreshed address, submitted privately to USDt0 only; also state that its balance is not claimed as the victim's property】. Please preserve this report, review the addresses under your risk policies, apply internal risk markers where appropriate, and take any restriction action only if supported by your independent review, applicable law, and policy. Please provide a case reference.

4. **必须替换**

   - REPLACE 1：受害事件段。
   - REPLACE 2：已核验归集路径段。
   - REPLACE 3：私下提交的刷新地址及权属免责声明。

---

## 七、Vercel：主站滥用举报、下架与日志保全

1. **链接**

   - 官方滥用举报：https://vercel.com/abuse
   - 举报目标：https://51vcard.com/ 和 https://www.51vcard.com/

2. **准备的材料**

   - E01—E08 的脱敏版和 E10。
   - 51vcard.com 完整页面截图，包含地址栏、日期、充值承诺、经营及牌照宣传、联系方式和下载按钮。

3. **话术模板**

        Title: Suspected fraud and deceptive payment service at 51vcard.com

        I report 51vcard.com for suspected fraud and deceptive payment-service activity and request an independent review under Vercel's policies. I am not alleging that Vercel participates in the reported activity.

        【REPLACE 1: one complete website-evidence paragraph listing the exact claims and URLs shown on 51vcard.com, the VCard application or download links, and the dates on which the pages were captured】

        【REPLACE 2: one complete victim-event paragraph stating the date, amount and token, network, loss address, transaction hash and explorer URL, address source, confirmation status, balance and ledger status】

        【REPLACE 3: one complete support-and-continuing-risk paragraph stating contact channels and dates, response status, last verification date, and whether the application remained accessible or continued displaying a deposit address】

        Please investigate the reported deployment and account, preserve project ownership, registration, billing, deployment, access, IP, login, source-repository linkage, and change-history records, and prevent continued harm. If your review confirms a policy violation, please suspend the relevant deployment and associated abusive resources. Please provide a case number.

4. **必须替换**

   - REPLACE 1：网站及应用证据段。
   - REPLACE 2：受害交易及未入账段。
   - REPLACE 3：催告及持续风险段。

---

## 八、Alibaba Cloud：子域名、Web App 和 APK 分发

1. **链接**

   - 官方举报中心：https://www.alibabacloud.com/report
   - 官方滥用邮箱：domainabuse@service.aliyun.com
   - 已知资源：
     - https://m.51vcard.com/
     - https://webapp.51vcard.com/
     - https://vcard-app.oss-cn-hongkong.aliyuncs.com/Vcard.apk

2. **准备的材料**

   - E01—E10 的脱敏版。
   - 官网下载按钮跳转到 OSS APK 的连续录屏或截图。
   - APK 原件及文件哈希只通过官方举报渠道提交，不要在公共仓库直接分发 APK。

3. **话术模板**

        Subject: Abuse report — suspected deceptive payment service and APK distribution on Alibaba Cloud resources

        I report Alibaba Cloud resources used by the VCard service at 51vcard.com for suspected fraud and deceptive payment-service activity. I am not alleging that Alibaba Cloud participates in the reported activity.

        【REPLACE 1: one complete resource paragraph listing every reported Alibaba Cloud URL, the page that links to it, the observed application version, capture date, and how the APK was presented】

        【REPLACE 2: one complete victim-event paragraph stating the date, amount and token, network, loss address, transaction hash and explorer URL, address source, and confirmation status】

        【REPLACE 3: one complete non-delivery paragraph stating the balance and ledger status, last verification date, support channels and dates, response status, and whether the application continued operating】

        Please investigate the identified Alibaba Cloud accounts and resources, preserve account registration, billing, access, IP, object-history, upload, download, DNS, and deployment records, and restrict the resources if your independent review confirms a policy violation. Please provide a case number. This report concerns suspected deceptive collection and non-delivery; it does not claim that the APK has been technically proven to contain malware.

4. **必须替换**

   - REPLACE 1：云资源及 APK 分发证据段。
   - REPLACE 2：受害交易段。
   - REPLACE 3：未履约及持续运营段。

---

## 九、Cloud Yuqu：域名注册商滥用举报

1. **链接**

   - 注册商联系页：https://www.diymysite.com/aboutus/contact.asp
   - 滥用邮箱：abuse@diymysite.com
   - 举报域名：51vcard.com

2. **准备的材料**

   - E01—E08 的脱敏版和 E10。
   - 精确 URL、域名查询结果、Vercel 与 Alibaba Cloud 举报回执。
   - 保存邮件完整头、投递证明和注册商回复，供 Verisign／ICANN 升级。

3. **话术模板**

        主题：举报 51vcard.com 涉嫌用于欺骗性支付服务并请求调查及保全注册资料

        我向 51vcard.com 的注册商举报该域名涉嫌被用于虚拟卡及稳定币充值收款后不入账的欺骗性支付服务。本举报不指控注册商参与相关行为。

        【REPLACE 1：受害交易完整段；一次写清交易时间、网络、金额与代币、损失地址、交易哈希、区块浏览器链接和确认状态】

        【REPLACE 2：未履约及催告完整段；一次写清到账承诺、最后核验日期、余额与账单状态、联系渠道和时间、回复情况及域名是否仍在运营】

        【REPLACE 3：域名证据完整段；一次写清精确举报 URL、域名查询结果、网站经营或牌照陈述，以及已取得的 Vercel／Alibaba Cloud 工单】

        请贵司：
        1. 按滥用政策调查 51vcard.com 及其注册账户；
        2. 保全注册人、代理商、付款、登录 IP、设备、域名变更、DNS 修改、验证和通信记录；
        3. 要求注册人说明完整经营主体、牌照、发卡行及未入账原因；
        4. 如独立调查确认违反适用政策或法律，请采取暂停解析、锁定或其他适当措施；
        5. 提供受理编号及调查结果。

        附件为脱敏交易证据、账户余额、客服催告和公开链上记录。

4. **必须替换**

   - REPLACE 1：受害交易段。
   - REPLACE 2：未履约及催告段。
   - REPLACE 3：域名及其他服务商证据段。

---

## 十、12321：涉诈网站举报

1. **链接**

   - 涉诈网站直接入口：https://wechat.12321.cn/cheat_site
   - 备用入口：https://12321.cn/web
   - 建议类型：金融诈骗；具体子类按页面实际选项选择。

2. **准备的材料**

   - E01—E08 的脱敏版。
   - 图片数量受限时优先：提币完成、链上成功、VCard 余额为零、充值承诺和官网页面。

3. **话术模板**

        举报 51vcard.com 及其 VCard 应用涉嫌通过虚拟卡和稳定币充值服务实施欺骗性收款。

        【REPLACE 1：交易事实完整段；一次写清日期、提币平台、网络、金额与代币、手续费、收款地址、交易哈希和确认状态】

        【REPLACE 2：未履约及催告完整段；一次写清到账承诺、最后核验日期、余额与账单状态、邮箱或 Telegram 联系时间及回复情况】

        【REPLACE 3：持续风险完整段；一次写清网站和 App 的精确 URL、最后访问时间、是否仍能登录及是否继续展示稳定币收款入口】

        请求核查网站、关联应用及实际经营主体，保存后台资料，并在查明违规后采取停止传播和风险提示措施。

4. **必须替换**

   - REPLACE 1：交易事实段。
   - REPLACE 2：未履约及催告段。
   - REPLACE 3：网站和 App 持续风险段。

---

## 十一、12321：不良手机应用举报

1. **链接**

   - 入口：https://12321.cn/web
   - 投诉类型：不良手机应用
   - 应用名称：VCard
   - 应用来源：https://www.51vcard.com/ 和 APK 直链

2. **准备的材料**

   - E01—E04、E07—E09。
   - 版本页面、官网入口、APK 下载记录和网站按钮跳转证据。

3. **话术模板**

        举报 VCard 安卓应用涉嫌通过稳定币充值页面收款后不向用户账户入账。

        【REPLACE 1：应用来源完整段；一次写清官网入口、App 版本、APK 完整 URL、下载按钮实际跳转情况、安装时间和取证日期】

        【REPLACE 2：交易事实完整段；一次写清日期、网络、金额与代币、损失地址、交易哈希、区块浏览器链接和确认状态】

        【REPLACE 3：未履约完整段；一次写清到账承诺、最后核验日期、余额与账单状态、联系渠道和回复情况，以及 App 是否继续运行】

        请求核查该应用的开发、分发、收款及后台行为，保存相关资料，并在确认违规后停止传播。本人未声称该 APK 已被技术鉴定为病毒或木马，本举报针对其涉嫌欺骗性收款及服务未交付行为。

4. **必须替换**

   - REPLACE 1：应用来源及分发证据段。
   - REPLACE 2：受害交易段。
   - REPLACE 3：未履约及持续运行段。

---

## 十二、Telegram：公开推广内容和关联账号线索

1. **链接**

   - 官方举报说明：https://telegram.org/faq?setln=en
   - 滥用邮箱：abuse@telegram.org
   - 官网公开频道：https://t.me/VCard_CN
   - 其他账号只在存在公开推广内容或可验证联系证据时提交。

2. **准备的材料**

   - E04、E06、E08、E10 的脱敏版。
   - 对公开频道或推广消息使用应用内 Report；不要把“未回复私聊”单独写成违法证据。
   - 账号只作为关联线索，不得未经证实公开认定为运营者。

3. **话术模板**

        Subject: Review request — Telegram accounts associated with suspected deceptive VCard payment service

        I request review and preservation of Telegram content and account-linkage information associated with the VCard service at 51vcard.com. I am not claiming that the account holders are proven operators; I provide evidence for Telegram's independent review.

        【REPLACE 1: one complete account-evidence paragraph listing the official Telegram URL linked by 51vcard.com, each public promotional account and post URL, each contact-only account, contact dates, and the distinction between promotion evidence and non-response】

        【REPLACE 2: one complete victim-event paragraph stating the date, amount and token, network, loss address, transaction hash and explorer URL, address source, and confirmation status】

        【REPLACE 3: one complete non-delivery paragraph stating the VCard balance and ledger status, last verification date, support-response status, and continued availability of the service】. Please review public promotional content, relevant account linkages, and possible rule violations; preserve relevant records; and restrict content or accounts only if your independent review confirms a violation. Please provide a report reference if available.

4. **必须替换**

   - REPLACE 1：Telegram 账号、公开内容及联系证据段。
   - REPLACE 2：受害交易段。
   - REPLACE 3：未履约及持续运营段。

---

## 十三、香港海关：虚假服务陈述及可能涉及金钱服务的线索

1. **链接**

   - 举报邮箱：crimereport@customs.gov.hk
   - 24 小时热线：+852 2545 6182
   - 金钱服务经营者查询：https://eservices.customs.gov.hk/MSOS/wsrh/001s1?request_locale=en

2. **准备的材料**

   - E01—E10 的脱敏版。
   - 官网对香港主体、美国 MSB、资金隔离、上市母公司、金融牌照、卡组织合作、跨境转账等陈述的完整截图。
   - 若查不到完整法律实体、公司编号、发卡行或牌照号，应写“网站未公开或无法核验”，不要断言不存在。

3. **话术模板**

        主旨：舉報 VCard／51vcard.com 涉嫌虛假服務陳述及請求核查香港經營主體

        本人就 VCard／51vcard.com 涉嫌作出虛假或具誤導性的服務陳述，以及可能在未清楚披露經營主體及相關牌照的情況下提供穩定幣充值、預付卡和跨境轉賬代付服務，向香港海關提交線索並請求調查。

        【REPLACE 1：網站及香港主體證據完整段；一次寫清網站逐項陳述、香港地址及主體資料、截圖日期，以及未公開或未能核驗的法律實體名稱、公司編號、發卡行和牌照號】

        【REPLACE 2：交易及未履約完整段；一次寫清交易時間、提幣平台、網絡、金額與代幣、手續費、損失地址、交易雜湊、確認狀態、到賬承諾、核驗日期、餘額和賬單狀態】

        【REPLACE 3：聯絡及持續風險完整段；一次寫清聯絡時間和渠道、回覆情況、網站及 App 是否仍可使用和是否繼續展示收款入口】

        本人請求香港海關：
        1. 核查實際香港經營主體、公司登記、負責人及受益擁有人；
        2. 核查服務是否涉及須受規管的金錢服務，以及網站所述牌照、上市母公司、發卡合作和資金隔離是否真實；
        3. 調查收款後不入賬、客服不回覆及持續展示收款入口的行為；
        4. 保存網站、應用、聯絡賬號及收款資料，並在職權範圍內採取措施防止更多消費者受損。

4. **必须替换**

   - REPLACE 1：网站陈述及香港主体证据段。
   - REPLACE 2：交易及未履约段。
   - REPLACE 3：联系及持续风险段。

---

## 十四、香港消费者委员会：消费纠纷及退款调解

1. **链接**

   - 网上投诉：https://ecomplaint.consumer.org.hk/
   - 官方说明：https://www.consumer.org.hk/sc/complaints-and-services

2. **准备的材料**

   - E01—E08；有连续录屏和 APK 下载记录时补充。
   - 表单专用字段填写真实身份和联系方式；正文不写证件号、密码或完整金融账号。
   - 商户名称可填 VCard／51VCard，网站填 https://www.51vcard.com/；主体不明时如实注明。

3. **话术模板**

        投訴主題：VCard 收取穩定幣後未入賬且客服未作實質回覆

        本人通過 51vcard.com 提供的 VCard 服務進行穩定幣充值。

        【REPLACE 1：交易事實完整段；一次寫清交易時間、提幣平台、網絡、總扣款、手續費、鏈上金額與代幣、損失地址、參考編號、交易雜湊及確認時間】

        【REPLACE 2：未履約及催告完整段；一次寫清到賬承諾、核驗日期、餘額與賬單狀態、聯絡時間和渠道及回覆情況】

        【REPLACE 3：商戶資料及訴求完整段；一次寫清網站的香港或受監管陳述、未能核驗的實體或牌照資料，以及要求退還的金額或等值款項】。本人請求消費者委員會協助要求商戶退款、披露完整經營主體和適用牌照及發卡機構，並就充值未入賬和客服不回應作出書面解釋。

4. **必须替换**

   - REPLACE 1：交易事实段。
   - REPLACE 2：未履约及催告段。
   - REPLACE 3：商户资料及退款诉求段。

---

## 十五、Verisign：.com 注册局升级举报

1. **链接**

   - DNS Abuse 表单：https://verisign.my.site.com/DNSAbuse/
   - 仅在已向 Cloud Yuqu 提交完整报告而注册商没有确认或调查时使用。

2. **准备的材料**

   - Cloud Yuqu 原始举报、完整邮件头、投递证明、回执和等待时间。
   - E01、E02、E04、E08、E10 的脱敏版。
   - Verisign 不处理退款，也不会因一般消费纠纷自动暂停域名。

3. **话术模板**

        Title: Escalated abuse report concerning 51vcard.com

        I escalate an abuse report concerning 51vcard.com, a domain registered through Cloud Yuqu LLC. The domain is used to advertise and deliver a suspected deceptive virtual-card and stablecoin payment service.

        【REPLACE 1: one complete victim-event paragraph stating the date, amount and token, network, loss address, transaction hash and explorer URL, address source, confirmation status, VCard balance and ledger status】

        【REPLACE 2: one complete continuing-risk paragraph stating the last verification date, support channels and response status, the domain's current availability, and exact website claims supported by screenshots】

        【REPLACE 3: one complete registrar-escalation paragraph stating the original report date and time, abuse email or form, delivery proof, follow-up, elapsed time, and the registrar's exact response or non-response】

        Please review the attached registrar correspondence and evidence, preserve relevant registry records, and take any mitigation action available under applicable DNS-abuse obligations and policy. This report requests investigation and does not allege that Verisign or the registrar participated in the suspected misconduct.

4. **必须替换**

   - REPLACE 1：受害事件及未入账段。
   - REPLACE 2：持续风险及网站陈述段。
   - REPLACE 3：注册商举报及未处理段。

---

## 十六、ICANN：注册商未履行滥用联系或调查义务时投诉

1. **链接**

   - 合规投诉：https://www.icann.org/compliance/complaint
   - 选择 Abuse / DNS Abuse (Registrar)。
   - 只有在已向注册商提交证据而其未维护有效联系方式、未确认或未合理调查时使用。

2. **准备的材料**

   - Cloud Yuqu 原始举报、邮件头、投递状态、全部回执和后续往来。
   - 域名注册信息及精确时间线。
   - ICANN 不裁决 VCard 是否诈骗、不追回资金，也不直接处理网站内容争议。

3. **话术模板**

        Title: Registrar failure to investigate an abuse report concerning 51vcard.com

        Cloud Yuqu LLC is the registrar of 51vcard.com and publishes abuse@diymysite.com for abuse complaints.

        【REPLACE 1: one complete registrar-contact paragraph stating the original report date and time, delivery method and proof, exact materials supplied, follow-up dates, elapsed time, and the precise failure to acknowledge or investigate】

        【REPLACE 2: one complete underlying-case paragraph stating the 51vcard.com URLs and claims, victim transaction date, amount and token, network, address, hash, confirmation status, VCard balance and ledger status, and support response】

        【REPLACE 3: one complete compliance paragraph identifying the registrar obligation believed not to have been met and attaching the relevant correspondence; do not use this block merely to disagree with a substantive registrar decision】

        I understand that ICANN does not adjudicate website-content disputes or recover funds. This complaint is limited to whether the accredited registrar fulfilled its contractual obligation to maintain an abuse contact and reasonably investigate and respond to a properly documented report. Please review the attached registrar correspondence and determine whether the registrar complied with its obligations.

4. **必须替换**

   - REPLACE 1：注册商联系及未处理段。
   - REPLACE 2：基础案件事实段。
   - REPLACE 3：具体合规问题段。

---

## 十七、香港警方网上报案（保留渠道）

1. **链接**

   - 香港警务处电子报案室：https://crp.police.gov.hk/crp001/?lang=en

2. **准备的材料**

   - E01—E10 私密原件。
   - 香港经营地址、网站陈述、联系账号、链上路径和服务商工单。
   - 在警方专用字段填写真实身份和联系方式。

3. **话术模板**

        本人舉報 51vcard.com 及其 VCard 應用涉嫌以虛擬卡和穩定幣充值服務收款後不入賬。

        【REPLACE 1：交易及未履約完整段；一次寫清交易時間、提幣平台、網絡、金額與代幣、損失地址、交易雜湊、確認狀態、到賬承諾、核驗日期、餘額及賬單狀態】

        【REPLACE 2：經營及聯絡證據完整段；一次寫清網站的香港主體、牌照、資金隔離或發卡合作陳述，未能核驗的資料，以及聯絡時間、渠道和回覆情況】

        公開鏈上記錄顯示：【REPLACE 3：附區塊瀏覽器連結的已核驗資金路徑摘要】。

        請依法登記和調查實際經營者，固定網站、應用、域名、雲服務、交易所及鏈上路由資料，並視調查結果採取防止更多受害和資產轉移的措施。

4. **必须替换**

   - REPLACE 1：交易及未履约段。
   - REPLACE 2：经营及联系证据段。
   - REPLACE 3：已核验链上路径段。

---

## 十八、FBI IC3（保留渠道）

1. **链接**

   - 官方投诉入口：https://complaint.ic3.gov/
   - IC3 接受境外网络犯罪线索，但不保证个案回复或退款。

2. **准备的材料**

   - E01—E10 的英文说明或清晰原件。
   - 法币损失金额、时间线、域名、App、联系账号、链上地址和交易哈希。
   - 只填真实信息；不要夸大美国联系点。

3. **话术模板**

        I report a suspected deceptive virtual-card and cryptocurrency payment service operated through 51vcard.com and the VCard Android application.

        【REPLACE 1: one complete transaction paragraph stating the date and time zone, exchange, network and token, total debit, network fee, on-chain amount, loss address, exchange reference, transaction hash, explorer URL, and confirmation status】

        【REPLACE 2: one complete non-delivery paragraph stating how the address was obtained, promised crediting time, VCard balance and ledger status, last verification date, support channels and dates, and response status】

        Public on-chain records show: 【REPLACE 3: concise verified consolidation and onward-transfer summary with transaction hashes and explorer URLs】.

        I request preservation of website, application, account, exchange, routing, and blockchain records and investigation of the persons operating the service. Public blockchain labels are provided only as investigative leads and are not asserted as proof that any exchange, protocol, or infrastructure provider participated in the suspected misconduct.

4. **必须替换**

   - REPLACE 1：交易事实段。
   - REPLACE 2：未履约及联系段。
   - REPLACE 3：已核验链上路径段。

---

## 当前不建议误投的渠道 / Channels not currently supported by the evidence

- **Google Safe Browsing**：目前有涉嫌欺骗性支付服务和直链 APK 的证据，但没有证据证明页面仿冒登录、盗取凭据或 APK 含恶意代码。无技术证据时不要选择 phishing 或 malware。
- **Google Play / Apple App Store**：已观察到的官网按钮并非可定位的官方商店详情页，因此没有明确商店条目可申请下架。
- **12377**：普通网络诈骗及追损通常应走公安渠道；不要为扩大曝光重复误投无关分类。
- **HKMA**：未识别实际发卡行、储值支付工具持牌人或具体受监管机构前，难以定位合适投诉对象。
- **Visa / Mastercard**：链上稳定币充值不是银行卡交易，卡组织不能撤销链上转账。
- **Tether 错误转账找回**：本案不是单纯误转到不支持地址；是否符合恢复政策应以代币发行方的官方规则为准。
- **Trust Wallet**：合约参数中的集成字符串不能证明 Trust Wallet 控制或发起交易；应先向实际路由服务请求解释和保全。

## 建议提交顺序 / Suggested order

1. 提币交易所、Chainabuse、Rango、NEAR Intents、USD₮0。
2. Vercel、Alibaba Cloud、Cloud Yuqu、12321 网站与 App、Telegram。
3. 香港海关与香港消费者委员会。
4. Cloud Yuqu 未处理时再升级 Verisign 和 ICANN。
5. 公安、香港警方和 IC3 根据受害人决定及案件需要启用。

## 跟进记录 / Follow-up log

| 渠道 | 提交时间 | 工单号 | 使用附件 | 回复期限 | 当前状态 | 下一步 |
|---|---|---|---|---|---|---|
| 【REPLACE：渠道】 | 【REPLACE：时间】 | 【REPLACE：工单号】 | 【REPLACE：E 编号】 | 【REPLACE：日期】 | 【REPLACE：状态】 | 【REPLACE：下一步】 |

72 小时没有自动确认时，可在原工单询问是否收到；注册商在合理时间内没有实质处理时，再考虑 Verisign 或 ICANN 升级。任何要求身份材料的请求，都应通过机构的官方表单或官方域名邮箱核验后提交。

## 免责声明 / Disclaimer

本文是证据整理和举报写作资源，不构成法律意见，也不保证资金能够追回、网站必然下架或地址必然冻结。任何机构是否采取行动，取决于其独立审查、适用法律和内部政策。贡献者应仅提交可核验事实，并尊重无关个人的隐私和程序权利。

This repository is an evidence-organization and reporting resource, not legal advice. It does not guarantee recovery, takedown, or freezing. Any action remains subject to each recipient's independent review, applicable law, and policies. Contributors should publish only verifiable facts and protect the privacy and due-process rights of unrelated persons.
