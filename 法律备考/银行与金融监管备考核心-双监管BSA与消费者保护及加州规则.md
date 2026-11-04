# 银行与金融监管备考核心：双重银行体系、BSA 与消费者保护及加州规则

> 个人学习笔记，不构成法律建议。银行监管这一块最容易错的不是概念，而是「谁管谁」：同一家银行可能同时受特许机关、存款保险人、控股公司监管者与消费者保护机构四条线约束。备考先画监管地图，再记条文：特许与分工看《国家银行法》与 12 U.S.C. 第 16 章，存款保险看 12 U.S.C. §§ 1811、1821，反洗钱看 31 U.S.C. §§ 5311 起与 FinCEN 规则，消费者保护看 12 U.S.C. § 5531。金额门槛凡规则有调整机制的，一律以现行规则为准，不死背旧数。

## 中文主文

### 一、双重银行体系（dual banking system）：特许有两扇门

美国银行可以向联邦或向州申请特许（charter），这就是双重银行体系，南北战争时期的《国家银行法》（National Bank Act, 1864）创设联邦特许之后一直如此。

- **国家银行（national bank）**：由财政部下属的货币监理署（Office of the Comptroller of the Currency, OCC）依 12 U.S.C. § 21 一带发给特许并担任主要联邦监管者；名称通常带 National 或 N.A.。国家银行依法必须加入联邦储备体系。
- **州特许银行**：由州银行监管机构（如加州 DFPI，见第七节）发给特许并参与检查；按是否加入联邦储备体系再分两路——州成员银行（state member bank）的主要联邦监管者是联邦储备体系（Federal Reserve），州非成员银行（state nonmember bank）的主要联邦监管者是 FDIC。
- **控股公司这一层**：银行控股公司（bank holding company）与储蓄贷款控股公司原则上由联邦储备体系合并监管，不论旗下银行是哪种特许——这是答题时最常漏掉的一层。
- **信用合作社（credit union）另成一路**：联邦特许与存款保险走国家信用合作社管理局（NCUA），不要与 FDIC 混写。
- **联邦优先（preemption）的边界**：国家银行原则上受联邦法与 OCC 规则支配，州法并非一概排除。Dodd-Frank 把判断标准成文化于 12 U.S.C. § 25b：回到 Barnett Bank of Marion County v. Nelson, 517 U.S. 25 (1996) 的口径——州消费者金融法若「阻止或显著干扰」国家银行行使联邦权力，才被优先排除，且须由 OCC 逐案判断。一般适用的州消费者保护法对国家银行并非自动失效，答题时不要写成「州法完全管不着」。

### 二、FDIC 与存款保险：§ 1811 立机构，§ 1821 定上限

联邦存款保险公司（Federal Deposit Insurance Corporation, FDIC）由《联邦存款保险法》设立，条文见 **12 U.S.C. § 1811**（该法汇编为 12 U.S.C. §§ 1811 起）：FDIC 一身三任——存款保险人、州非成员银行的主要联邦监管者、倒闭受保机构的接管与清算人（receiver）。

- **保险上限**：受保机构倒闭时，每位存款人在同一机构、同一所有权类别下的存款净额，保额以标准最高存款保险金额（standard maximum deposit insurance amount）为限，现行金额为 **250,000 美元**，条文见 **12 U.S.C. § 1821(a)(1)(E)**，并设有按期检视通胀调整的机制；计算细节在 12 C.F.R. Part 330。三个限定词一个都不能丢：按存款人、按机构、按所有权类别分别计算（个人账户、联名账户、信托账户、退休账户等各算一类），不是「每个账户保 25 万」。
- **保的是存款，不是投资品**：在受保银行买的股票、债券、共同基金、年金不受 FDIC 保险，这条在考试与投诉场景里都常考。
- **信用合作社的存款**由 NCUA 的 Share Insurance Fund 承保，标准上限与银行一侧平行，但机构与法源完全不同。

### 三、审慎监管的工具箱：资本、检查与执行

审慎监管（safety and soundness）不靠单一条文，靠一组工具配合：

- **资本与及时纠正措施（prompt corrective action）**：12 U.S.C. § 1831o 按资本充足程度把受保机构分档，资本越薄，监管者的强制处置越硬（限制分红、要求资本恢复计划，直到接管），目的是在资不抵债之前介入。
- **检查与评级**：三家联邦银行监管者按风险分工定期检查，业内通用的 CAMELS 评级是监管方法而非制定法，别写成法条。
- **执行权**：12 U.S.C. § 1818 给了各联邦银行监管者对受保机构及其关联方发出停止令（cease-and-desist）、课处民事罚款、移除问题高管的权力，是三家共用的执行总开关。把「谁检查」与「谁执行」分开写：保险人 FDIC 对非其主监管的机构另有后备检查与执行地位，不是只有主监管者能动手。

### 四、Dodd-Frank 与 Volcker 规则：一部危机后大法，两处高频考点

《多德—弗兰克华尔街改革与消费者保护法》（Dodd-Frank Act, Pub. L. No. 111-203, 2010）是 2008 年金融危机后的总回应。备考抓两个点：

- **Volcker 规则**：源于 Dodd-Frank 第 619 条，新增为《银行控股公司法》第 13 条，汇编于 **12 U.S.C. § 1851**。规则主体是「银行实体」（banking entity，受保存款机构、其控股公司与关联方），两项原则禁止：①自营交易（proprietary trading，以自有账户做短期自营买卖）；②持有、发起对冲基金与私募股权基金等「涵盖基金」（covered fund）的权益。承销、做市、风险缓释对冲与美国政府债券交易等属法定许可活动，实施细则由 Fed、OCC、FDIC、SEC、CFTC 五家机构分别在各自规则中落实（OCC 版如 12 C.F.R. Part 44）。考试陷阱是把 Volcker 写成「禁止一切交易」——它禁的是自营与涵盖基金，不是客户驱动的做市与承销。
- **系统重要性一侧**：金融稳定监督委员会（FSOC）的认定与 Fed 对大银行的强化审慎标准属同一部法的另一条线，本篇只提示地图位置，具体门槛数字历经 2018 年《经济增长、监管放松与消费者保护法》等后续立法调整，答题一律以现行法条为准，不写死数。

### 五、BSA 与反洗钱：31 U.S.C. §§ 5311 起

《银行保密法》（Bank Secrecy Act, BSA）汇编于 **31 U.S.C. §§ 5311–5336** 一带：§ 5311 是立法目的条款，国会要求金融机构保存记录、报告特定交易，供刑事、税务与监管调查使用。执行中枢是财政部下属的金融犯罪执法网络（FinCEN）。金融机构须依 **31 U.S.C. § 5318** 一带建立反洗钱（AML）合规程序（含客户尽职调查与受益所有人识别，规则见 31 C.F.R. Chapter X）。

- **大额现金交易报告（CTR）**：现金（currency，指实物通货）存入、取出、兑换等单笔或同一营业日合计**超过 10,000 美元**的交易，金融机构须向 FinCEN 报送 CTR，授权条文 31 U.S.C. § 5313，操作规则 **31 C.F.R. § 1010.311**（合计规则在 § 1010.313）；报送期限等程序细节以 FinCEN 现行规则为准。注意 CTR 是对「现金」的报告，电汇与支票转账不因此触发 CTR，别把一切大额转账都写成 CTR。
- **可疑活动报告（SAR）**：银行对知道、怀疑或有理由怀疑涉及非法资金、意在规避 BSA 要求、或无正当商业表象的交易，达到规则门槛即须报 SAR；银行规则见 **31 C.F.R. § 1020.320**，一般门槛口径为 5,000 美元起、内部人滥用不论金额，报送时限以现行规则为准。SAR 内容对被报告人保密，被报告人不得被告知，这是常考的程序点。
- **拆分交易（structuring）**：为规避 CTR 报告要求而故意把现金交易拆小，本身即违法，条文见 **31 U.S.C. § 5324** 与 31 C.F.R. § 1010.314——钱是干净的也一样，规避目的才是关键。
- **门槛的时效提醒**：10,000 美元一线自 BSA 早期沿用至今，未随通胀自动调整；近年有提高门槛的立法提案在审议中，但提案不是现行法，答题与实务都按现行规则写。

### 六、消费者保护：CFPB 与 UDAAP（12 U.S.C. § 5531）

Dodd-Frank 第 X 篇创设消费者金融保护局（Consumer Financial Protection Bureau, CFPB），并新造了一个比 FTC 传统 UDAP 多一个 A 的标准：

- **UDAAP**：依 **12 U.S.C. § 5531**，CFPB 可对「受覆盖者」（covered person，提供消费者金融产品或服务者及其服务商）在消费者金融交易中的不公平、欺骗或滥用行为（unfair, deceptive, or abusive acts or practices）采取行动，并可立规列明。配套禁止条款在 12 U.S.C. § 5536 一带。
- **「不公平」的法定检验（§ 5531(c)）**：行为造成或可能造成消费者重大损害、该损害无法被消费者合理避免、且损害未被对消费者或竞争的抵销利益超过——三件缺一不可，不要只写「对消费者不好」。
- **「滥用」的法定检验（§ 5531(d)）**：①实质干扰消费者理解产品条款的能力；或 ②不合理利用消费者的不理解、无法保护自身利益的状态、或对业者会为其利益行事的合理信赖。这是 Dodd-Frank 新造的概念，与 FTC 法第 5 条的 UDAP（15 U.S.C. § 45，只有 unfair 与 deceptive、无 abusive）要分清。
- **分工**：CFPB 对大型受保机构有直接检查权（资产门槛以现行法条为准），对较小机构以立规与对主监管者的协调为主；州检察长在 12 U.S.C. § 5552 一带另有执行联邦消费者金融法的通道，州法执行不因 CFPB 存在而消失。

### 七、加州一格（只作对照，不与联邦混同）

- **DFPI**：加州金融保护与创新部（Department of Financial Protection and Innovation, DFPI）由原商业监督部（Department of Business Oversight）在 2020 年随 AB 1864 改组更名而来，既管加州特许银行与信用合作社的审慎监管，也管各类持牌金融活动。
- **CCFPL**：同批立法的《加州消费者金融保护法》（California Consumer Financial Protection Law, CCFPL），条文见 **Cal. Fin. Code §§ 90000–90019**：§ 90003(a)(1) 把联邦 UDAAP 扩成「违法、不公平、欺骗或滥用」（unlawful, unfair, deceptive, or abusive），§ 90005 一带给定义；该法还授权 DFPI 把此前无人监管的部分金融业者纳入登记与监管。对州特许机构，加州的审慎规则与联邦规则叠加适用；对国家银行，先回到第一节 § 25b 的优先标准，再谈州消费者法，别把 CCFPL 直接套到国家银行身上。

### 八、易错点

1. 「双重监管」写错对象：分工按特许与成员身份定——OCC 管国家银行，Fed 管州成员银行与控股公司，FDIC 管州非成员银行并当保险人；NCUA 管信用合作社。
2. FDIC 的 250,000 美元是 12 U.S.C. § 1821(a)(1)(E) 的标准上限，按存款人、按机构、按所有权类别算，不是按账户个数算。
3. Volcker 规则（12 U.S.C. § 1851）禁自营与涵盖基金，不禁承销、做市与对冲等许可活动。
4. CTR 只管实物现金且线是「超过」10,000 美元（31 C.F.R. § 1010.311）；SAR 看可疑性而非单纯金额，且不得通知被报告人。
5. 拆分干净的钱规避报告同样违法（31 U.S.C. § 5324）：构成要件的核心是规避目的。
6. UDAP 与 UDAAP 差一个 A：abusive 只在 12 U.S.C. § 5531(d) 与加州 CCFPL 里有，FTC 法第 5 条没有。
7. 国家银行不是州法真空：12 U.S.C. § 25b 的标准是「阻止或显著干扰」，逐案判断；加州 CCFPL 的主战场是州监管对象与未监管业者。

### 九、来源说明

主要依据：National Bank Act 与 OCC 特许条文，12 U.S.C. § 21 一带；Federal Deposit Insurance Act，12 U.S.C. §§ 1811 et seq.（尤其 § 1821(a)(1)(E) 的 250,000 美元标准上限与 § 1831o 及时纠正措施、§ 1818 执行权）；12 U.S.C. § 25b 与 Barnett Bank v. Nelson, 517 U.S. 25 (1996)；Dodd-Frank Act, Pub. L. No. 111-203（第 619 条与第 X 篇），Volcker 规则 12 U.S.C. § 1851；Bank Secrecy Act，31 U.S.C. §§ 5311–5336（尤其 §§ 5313、5318、5324）与 31 C.F.R. §§ 1010.311、1010.313、1010.314、1020.320（FinCEN）；CFPB 与 UDAAP，12 U.S.C. §§ 5531、5536、5552；Cal. Fin. Code §§ 90000–90019（CCFPL，尤其 § 90003(a)(1)、§ 90005）。机构分工口径经 FDIC、CFPB 与加州 DFPI 公开材料核对；金额门槛与时限如有修订，以现行法条与规则为准。

*声明：个人学习笔记，不构成法律建议。*

---

## English

**Banking and Financial Regulation: The Dual Banking System, the BSA, and Consumer Protection**

Bank regulation exam questions are lost less on concepts than on the map: who supervises whom. One bank can answer at once to its chartering authority, its deposit insurer, its holding-company regulator, and a consumer-protection agency.

**1. The dual banking system.** Banks may take a federal or a state charter. National banks are chartered and primarily supervised by the **Office of the Comptroller of the Currency (OCC)** under **12 U.S.C. § 21** et seq. (National Bank Act of 1864) and must belong to the Federal Reserve System. State-chartered banks are chartered by a state regulator: if the bank joins the Federal Reserve, the **Federal Reserve** is its primary federal regulator (state member banks); if not, the **FDIC** is (state nonmember banks). Bank holding companies are consolidated-supervised by the Federal Reserve regardless of the bank's charter. Credit unions are a separate track under the NCUA. On preemption, Dodd-Frank codified the *Barnett Bank* standard at **12 U.S.C. § 25b** (*Barnett Bank of Marion County v. Nelson*, 517 U.S. 25 (1996)): a state consumer financial law is preempted as to a national bank only if it prevents or significantly interferes with the bank's federal powers, assessed case by case by the OCC — state law is not simply switched off.

**2. The FDIC and deposit insurance.** The FDIC is established by the Federal Deposit Insurance Act, **12 U.S.C. § 1811** (the Act runs from §§ 1811 et seq.), and wears three hats: insurer, primary federal regulator of state nonmember banks, and receiver for failed insured institutions. Coverage is capped at the standard maximum deposit insurance amount — **$250,000** under **12 U.S.C. § 1821(a)(1)(E)**, computed per depositor, per institution, per ownership category (see 12 C.F.R. Part 330) — not per account. Securities, mutual funds, and annuities bought at an insured bank are not deposits and are not insured. Credit-union shares are insured in parallel by the NCUA, a different statute and fund.

**3. Prudential tools.** Prompt corrective action, **12 U.S.C. § 1831o**, grades insured institutions by capital and hardens supervisory consequences as capital thins. CAMELS ratings are supervisory method, not statute. Enforcement runs through **12 U.S.C. § 1818** (cease-and-desist orders, civil money penalties, removal), shared across the federal banking agencies; the FDIC also holds backup authority over institutions it does not primarily supervise.

**4. Dodd-Frank and the Volcker Rule.** The Dodd-Frank Act (Pub. L. No. 111-203 (2010)) answered the financial crisis. Section 619 added section 13 to the Bank Holding Company Act, codified at **12 U.S.C. § 1851**: a banking entity may not engage in proprietary trading or acquire, retain, or sponsor covered funds (hedge funds and private equity funds), while underwriting, market making, risk-mitigating hedging, and trading in U.S. government obligations remain permitted activities, implemented by five agencies (the OCC rule is at 12 C.F.R. Part 44). Do not overstate the ban as covering all trading. Systemic-importance thresholds elsewhere in the Act were later retuned (notably in 2018), so check the current statute rather than memorizing figures.

**5. The BSA.** The Bank Secrecy Act is codified at **31 U.S.C. §§ 5311–5336** (§ 5311 states its recordkeeping-and-reporting purpose) and administered by FinCEN; **31 U.S.C. § 5318** anchors anti-money-laundering programs, with detail in 31 C.F.R. Chapter X. A **Currency Transaction Report** is due for transactions in physical currency of **more than $10,000** (cash-in and cash-out aggregated per business day), authority at 31 U.S.C. § 5313, rule at **31 C.F.R. § 1010.311** (aggregation at § 1010.313); wires and checks do not trigger a CTR. A bank files a **Suspicious Activity Report** under **31 C.F.R. § 1020.320** — generally at a $5,000 threshold where the bank knows or suspects illicit funds, evasion, or no lawful apparent purpose, and for insider abuse regardless of amount; the subject must not be tipped off. Splitting cash transactions to evade the CTR line is itself a crime, **31 U.S.C. § 5324** (see also 31 C.F.R. § 1010.314), even if the money is clean — evasive purpose is the point. The $10,000 line does not auto-adjust for inflation; pending reform bills are not current law.

**6. The CFPB and UDAAP.** Title X of Dodd-Frank created the Consumer Financial Protection Bureau. Under **12 U.S.C. § 5531**, the Bureau may act against unfair, deceptive, or abusive acts or practices by covered persons (see also the prohibitions at § 5536). Unfairness has a statutory test at § 5531(c): substantial injury, not reasonably avoidable by consumers, not outweighed by countervailing benefits. Abusiveness is defined at § 5531(d): materially interfering with a consumer's ability to understand a term, or taking unreasonable advantage of a consumer's lack of understanding, inability to protect their interests, or reasonable reliance. That extra "A" is what separates federal UDAAP from the FTC Act's older UDAP standard (15 U.S.C. § 45). State attorneys general have their own enforcement channel at 12 U.S.C. § 5552.

**7. California.** The Department of Financial Protection and Innovation (DFPI) — renamed from the Department of Business Oversight in 2020 under AB 1864 — supervises state-chartered banks and credit unions and licenses much else. The California Consumer Financial Protection Law (CCFPL), **Cal. Fin. Code §§ 90000–90019**, makes it unlawful at **§ 90003(a)(1)** to engage in any unlawful, unfair, deceptive, or abusive act or practice (adding "unlawful" to the federal formula; definitions at § 90005) and lets the DFPI register previously unsupervised providers. Against national banks, start with the § 25b preemption analysis, not with the CCFPL.

**Common traps:** assigning the OCC, Fed, and FDIC the wrong charters; reading the $250,000 limit per account instead of per depositor/institution/ownership category; turning the Volcker Rule into a ban on market making; treating every large transfer as a CTR; assuming clean money cannot be structured; importing "abusive" into FTC Act section 5; treating national banks as state-law-free zones.

*Personal study notes only; not legal advice. Sources: 12 U.S.C. §§ 21, 25b, 1811 et seq., 1818, 1821(a)(1)(E), 1831o, 1851, 5531, 5536, 5552; Barnett Bank, 517 U.S. 25 (1996); Dodd-Frank Act, Pub. L. No. 111-203; 31 U.S.C. §§ 5311–5336; 31 C.F.R. §§ 1010.311, 1010.313, 1010.314, 1020.320; Cal. Fin. Code §§ 90000–90019.*

---

## Español

**Regulación bancaria y financiera: sistema bancario dual, BSA y protección del consumidor**

En regulación bancaria los exámenes se pierden menos por conceptos que por el mapa: quién supervisa a quién. Un mismo banco puede responder a la vez ante la autoridad que lo autorizó, su aseguradora de depósitos, el supervisor de su sociedad controladora y una agencia de protección al consumidor.

**1. El sistema dual.** Los bancos pueden obtener su autorización (charter) del gobierno federal o de un estado. Los bancos nacionales son autorizados y supervisados principalmente por la **Office of the Comptroller of the Currency (OCC)**, conforme al **12 U.S.C. § 21** y ss. (National Bank Act de 1864), y deben pertenecer al Sistema de la Reserva Federal. Los bancos de charter estatal son autorizados por el regulador estatal: si se incorporan a la Reserva Federal, su supervisor federal principal es la **Reserva Federal** (bancos estatales miembros); si no, es la **FDIC** (bancos estatales no miembros). Las sociedades controladoras bancarias son supervisadas de forma consolidada por la Reserva Federal, sea cual sea el charter del banco. Las cooperativas de crédito siguen una vía separada, la NCUA. En materia de prevalencia federal (preemption), Dodd-Frank codificó el estándar de *Barnett Bank* en el **12 U.S.C. § 25b** (*Barnett Bank of Marion County v. Nelson*, 517 U.S. 25 (1996)): una ley estatal de finanzas de consumo solo queda desplazada respecto de un banco nacional si impide o interfiere significativamente con sus facultades federales, con evaluación caso por caso de la OCC; la ley estatal no se apaga automáticamente.

**2. La FDIC y el seguro de depósitos.** La FDIC fue creada por la Federal Deposit Insurance Act, **12 U.S.C. § 1811** (la ley corre desde los §§ 1811 y ss.), y cumple tres funciones: aseguradora, supervisora federal principal de los bancos estatales no miembros y liquidadora (receiver) de instituciones aseguradas fallidas. La cobertura está limitada al monto máximo estándar de seguro de depósitos: **250.000 dólares** según el **12 U.S.C. § 1821(a)(1)(E)**, calculado por depositante, por institución y por categoría de titularidad (véase 12 C.F.R. parte 330), no por cuenta. Los valores, fondos mutuos y anualidades comprados en un banco asegurado no son depósitos y no están asegurados. Las participaciones en cooperativas de crédito las asegura en paralelo la NCUA, con otra ley y otro fondo.

**3. Herramientas prudenciales.** La acción correctiva pronta, **12 U.S.C. § 1831o**, clasifica a las instituciones por capital y endurece las consecuencias supervisoras a medida que el capital se reduce. Las calificaciones CAMELS son método de supervisión, no texto legal. La ejecución corre por el **12 U.S.C. § 1818** (órdenes de cese, multas civiles, remoción de directivos), compartido entre las agencias bancarias federales; la FDIC conserva además autoridad de respaldo sobre instituciones que no supervisa principalmente.

**4. Dodd-Frank y la regla Volcker.** La Dodd-Frank Act (Pub. L. No. 111-203 (2010)) respondió a la crisis financiera. Su sección 619 añadió la sección 13 a la Bank Holding Company Act, codificada en el **12 U.S.C. § 1851**: una entidad bancaria no puede dedicarse al proprietary trading ni adquirir, mantener o patrocinar fondos cubiertos (covered funds: fondos de cobertura y de capital privado), mientras que la suscripción (underwriting), la creación de mercado, la cobertura de riesgos y la negociación de obligaciones del gobierno federal siguen siendo actividades permitidas, implementadas por cinco agencias (la regla de la OCC está en 12 C.F.R. parte 44). No debe exagerarse la prohibición como si cubriera toda negociación. Los umbrales de importancia sistémica en otras partes de la ley fueron reajustados después (en particular en 2018), así que debe consultarse el texto vigente y no memorizar cifras viejas.

**5. La BSA.** La Bank Secrecy Act está codificada en **31 U.S.C. §§ 5311–5336** (el § 5311 enuncia su finalidad de registros e informes) y la administra FinCEN; el **31 U.S.C. § 5318** sustenta los programas contra el lavado de dinero, con detalle en 31 C.F.R. capítulo X. Debe presentarse un **Currency Transaction Report (CTR)** por transacciones en moneda física de **más de 10.000 dólares** (sumando entradas y salidas de efectivo por día hábil), con base en el 31 U.S.C. § 5313 y regla en **31 C.F.R. § 1010.311** (agregación en el § 1010.313); las transferencias electrónicas y los cheques no activan el CTR. El banco presenta un **Suspicious Activity Report (SAR)** conforme a **31 C.F.R. § 1020.320** — en general con umbral de 5.000 dólares cuando sabe o sospecha fondos ilícitos, evasión o ausencia de propósito lícito aparente, y por abuso de personas internas sin importar el monto — y no puede avisar al sujeto reportado. Fraccionar operaciones en efectivo para evadir el límite del CTR es en sí delito, **31 U.S.C. § 5324** (véase también 31 C.F.R. § 1010.314), aunque el dinero sea limpio: lo decisivo es el propósito evasivo. La línea de 10.000 dólares no se ajusta automáticamente por inflación; los proyectos de reforma en trámite no son ley vigente.

**6. La CFPB y el estándar UDAAP.** El Título X de Dodd-Frank creó la Consumer Financial Protection Bureau. Según el **12 U.S.C. § 5531**, la Oficina puede actuar contra actos o prácticas injustos, engañosos o abusivos (unfair, deceptive, or abusive) de las personas cubiertas (véanse también las prohibiciones del § 5536). La injusticia tiene prueba legal en el § 5531(c): perjuicio sustancial, no razonablemente evitable por los consumidores y no superado por beneficios compensatorios. El abuso se define en el § 5531(d): interferir materialmente con la capacidad del consumidor de entender una condición, o aprovecharse irrazonablemente de su falta de comprensión, de su incapacidad de proteger sus intereses o de su confianza razonable. Esa «A» adicional separa el UDAAP federal del viejo UDAP de la FTC Act (15 U.S.C. § 45). Los fiscales generales estatales tienen su propio cauce de ejecución en el 12 U.S.C. § 5552.

**7. California.** El Department of Financial Protection and Innovation (DFPI), nuevo nombre del Department of Business Oversight desde 2020 por la ley AB 1864, supervisa bancos y cooperativas de charter californiano y licencia muchas otras actividades. La California Consumer Financial Protection Law (CCFPL), **Cal. Fin. Code §§ 90000–90019**, declara ilícito en su **§ 90003(a)(1)** incurrir en cualquier acto o práctica ilegal, injusta, engañosa o abusiva (añade «ilegal» a la fórmula federal; definiciones en el § 90005) y permite a la DFPI registrar a proveedores antes no supervisados. Frente a bancos nacionales, el análisis empieza por la prevalencia del § 25b, no por la CCFPL.

**Errores frecuentes:** asignar a la OCC, la Reserva Federal y la FDIC los charters equivocados; leer el límite de 250.000 dólares por cuenta en vez de por depositante, institución y categoría; convertir la regla Volcker en prohibición de crear mercado; tratar toda transferencia grande como CTR; suponer que el dinero limpio no puede fraccionarse ilícitamente; importar lo «abusivo» a la sección 5 de la FTC Act; tratar a los bancos nacionales como zonas libres de derecho estatal.

*Notas de estudio personales; no constituye asesoría legal. Fuentes: 12 U.S.C. §§ 21, 25b, 1811 y ss., 1818, 1821(a)(1)(E), 1831o, 1851, 5531, 5536, 5552; Barnett Bank, 517 U.S. 25 (1996); Dodd-Frank Act, Pub. L. No. 111-203; 31 U.S.C. §§ 5311–5336; 31 C.F.R. §§ 1010.311, 1010.313, 1010.314, 1020.320; Cal. Fin. Code §§ 90000–90019.*

---

## 한국어 (초역, 원어민 감수 대기)

**은행·금융 규제: 이중 은행 제도, BSA, 소비자 보호**

은행 규제 시험에서 틀리는 지점은 개념보다 지도입니다. 누가 누구를 감독하는가. 한 은행이 인가 기관, 예금보험자, 지주회사 감독자, 소비자 보호 기관에 동시에 답해야 할 수 있습니다.

**1. 이중 은행 제도.** 은행은 연방 인가와 주 인가를 선택할 수 있습니다. 국립은행(national bank)은 **12 U.S.C. § 21** 이하(National Bank Act, 1864)에 따라 통화감독청(OCC)이 인가하고 주로 감독하며, 연방준비제도 가입이 의무입니다. 주 인가 은행은 주 감독기관이 인가합니다. 연방준비제도에 가입하면(주 회원은행) 주된 연방 감독자는 **연방준비제도**이고, 가입하지 않으면(주 비회원은행) **FDIC**입니다. 은행지주회사는 은행의 인가 종류와 무관하게 연방준비제도가 연결 기준으로 감독합니다. 신용협동조합은 NCUA가 맡는 별도 경로입니다. 연방 우선(preemption)에서는 Dodd-Frank가 **12 U.S.C. § 25b**에 *Barnett Bank* 기준(*Barnett Bank of Marion County v. Nelson*, 517 U.S. 25 (1996))을 성문화했습니다. 주 소비자금융법은 국립은행의 연방 권한을 방해하거나 현저히 간섭할 때만, OCC가 사안별로 판단하여 우선 배제되며, 주법이 자동으로 꺼지는 것은 아닙니다.

**2. FDIC와 예금보험.** FDIC는 **12 U.S.C. § 1811**(법은 §§ 1811 이하)에서 설립되었고, 보험자, 주 비회원은행의 주된 연방 감독자, 부실 보험기관의 관재인(receiver)이라는 세 역할을 합니다. 보장 한도는 표준 최대 예금보험 금액으로 **12 U.S.C. § 1821(a)(1)(E)**에 따라 **250,000달러**이며, 계좌별이 아니라 예금자별·기관별·소유권 범주별로 계산합니다(12 C.F.R. Part 330 참조). 보험 가입 은행에서 산 증권·뮤추얼펀드·연금은 예금이 아니어서 보장되지 않습니다. 신용협동조합의 출자금은 NCUA가 별도 법과 기금으로 평행하게 보장합니다.

**3. 건전성 도구.** **12 U.S.C. § 1831o**의 신속시정조치(prompt corrective action)는 자본 수준에 따라 기관을 등급화하고 자본이 얇아질수록 감독 조치를 강화합니다. CAMELS 등급은 감독 방법이지 법문이 아닙니다. 집행은 연방 은행 감독기관들이 공유하는 **12 U.S.C. § 1818**(중지명령, 민사벌금, 임원 해임)을 통하고, FDIC는 자신이 주로 감독하지 않는 기관에 대해서도 예비 권한을 가집니다.

**4. Dodd-Frank와 Volcker 규칙.** Dodd-Frank법(Pub. L. No. 111-203 (2010))은 금융위기에 대한 답입니다. 제619조는 Bank Holding Company Act 제13조를 신설했고 **12 U.S.C. § 1851**로 성문화되었습니다. 은행 실체는 자기계산 단기 매매(proprietary trading)를 할 수 없고, 헤지펀드·사모펀드 등 covered fund의 지분을 취득·보유하거나 이를 스폰서할 수 없습니다. 반면 인수, 시장조성, 위험 완화 헤지, 미국 정부채 거래는 허용 활동으로 남고, 다섯 개 기관이 시행 규칙을 냈습니다(OCC 규칙은 12 C.F.R. Part 44). 이 금지를 모든 거래의 금지로 과장하면 안 됩니다. 같은 법의 시스템적 중요성 기준은 2018년 등 후속 입법으로 조정되었으므로 수치는 현행 법문으로 확인하십시오.

**5. BSA.** Bank Secrecy Act는 **31 U.S.C. §§ 5311–5336**에 성문화되어 있고(§ 5311이 기록·보고의 목적을 밝힘) FinCEN이 집행하며, **31 U.S.C. § 5318**이 자금세탁방지 프로그램의 근거이고 세부 사항은 31 C.F.R. Chapter X에 있습니다. 실물 통화로 **10,000달러를 초과**하는 거래(영업일 기준 현금 입출금 합산)에 대해서는 **Currency Transaction Report**를 제출해야 합니다. 근거는 31 U.S.C. § 5313, 규칙은 **31 C.F.R. § 1010.311**(합산은 § 1010.313)이며, 전신송금과 수표는 CTR을 발동하지 않습니다. 은행은 **31 C.F.R. § 1020.320**에 따라 **Suspicious Activity Report**를 제출합니다. 일반적으로 은행이 불법 자금, 보고 회피, 정당한 외관의 부재를 알거나 의심하는 5,000달러 기준이 기준이 되고, 내부자 남용은 금액과 무관하며, 보고 대상자에게 알려서는 안 됩니다. CTR 기준을 피하려고 현금 거래를 쪼개는 행위(structuring) 자체가 범죄입니다(**31 U.S.C. § 5324**, 31 C.F.R. § 1010.314 참조). 돈이 깨끗해도 마찬가지이며 회피 목적이 핵심입니다. 10,000달러 기준은 물가상승에 자동 연동되지 않고, 계류 중인 개혁안은 현행법이 아닙니다.

**6. CFPB와 UDAAP.** Dodd-Frank 제X편은 소비자금융보호국(CFPB)을 만들었습니다. **12 U.S.C. § 5531**에 따라 국은 covered person의 불공정·기망·남용 행위(unfair, deceptive, or abusive acts or practices)에 대응할 수 있습니다(금지 조항은 § 5536 참조). 불공정은 § 5531(c)의 법정 검사를 따릅니다. 실질적 손해, 소비자가 합리적으로 피할 수 없을 것, 상쇄 이익을 초과하지 않을 것입니다. 남용은 § 5531(d)가 정의합니다. 소비자가 조건을 이해하는 능력을 실질적으로 방해하거나, 소비자의 이해 부족, 자기 이익을 지킬 수 없음, 합리적 신뢰를 부당하게 이용하는 경우입니다. 이 추가된 A가 연방 UDAAP를 FTC법의 옛 UDAP(15 U.S.C. § 45)와 가릅니다. 주 법무장관은 12 U.S.C. § 5552에 별도의 집행 경로를 가집니다.

**7. 캘리포니아.** 금융보호혁신부(DFPI)는 2020년 AB 1864로 상업감독부에서 개칭되었고, 캘리포니아 인가 은행과 신용협동조합을 감독하며 그 밖의 많은 활동을 인가합니다. 캘리포니아 소비자금융보호법(CCFPL), **Cal. Fin. Code §§ 90000–90019**은 **§ 90003(a)(1)**에서 위법·불공정·기망·남용 행위를 불법으로 정하고(연방 공식에 unlawful을 추가, 정의는 § 90005), DFPI가 종전에 감독받지 않던 사업자를 등록시킬 수 있게 합니다. 국립은행에 대해서는 CCFPL이 아니라 § 25b의 우선 분석부터 시작하십시오.

**흔한 오류:** OCC·연방준비제도·FDIC에 잘못된 인가를 배정하기, 250,000달러 한도를 계좌별로 읽기, Volcker 규칙을 시장조성 금지로 만들기, 큰 이체 전부를 CTR로 취급하기, 깨끗한 돈은 쪼개도 된다고 생각하기, FTC법 제5조에 abusive를 끌어오기, 국립은행을 주법이 없는 지대로 취급하기.

*개인 학습 노트이며 법률 자문이 아닙니다. 출처: 12 U.S.C. §§ 21, 25b, 1811 이하, 1818, 1821(a)(1)(E), 1831o, 1851, 5531, 5536, 5552; Barnett Bank, 517 U.S. 25 (1996); Dodd-Frank Act, Pub. L. No. 111-203; 31 U.S.C. §§ 5311–5336; 31 C.F.R. §§ 1010.311, 1010.313, 1010.314, 1020.320; Cal. Fin. Code §§ 90000–90019.*

---

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Quy định ngân hàng và tài chính: hệ thống ngân hàng kép, BSA và bảo vệ người tiêu dùng**

Câu hỏi thi về quy định ngân hàng thường mất điểm ở bản đồ giám sát hơn là ở khái niệm: ai giám sát ai. Một ngân hàng có thể cùng lúc chịu sự quản lý của cơ quan cấp phép, cơ quan bảo hiểm tiền gửi, cơ quan giám sát công ty mẹ và cơ quan bảo vệ người tiêu dùng.

**1. Hệ thống ngân hàng kép.** Ngân hàng có thể lấy giấy phép (charter) liên bang hoặc tiểu bang. Ngân hàng quốc gia (national bank) do **Office of the Comptroller of the Currency (OCC)** cấp phép và giám sát chính theo **12 U.S.C. § 21** trở đi (National Bank Act năm 1864) và bắt buộc là thành viên Hệ thống Dự trữ Liên bang. Ngân hàng có charter tiểu bang do cơ quan giám sát của bang cấp phép: nếu gia nhập Dự trữ Liên bang (state member bank) thì giám sát liên bang chính là **Federal Reserve**; nếu không (state nonmember bank) thì là **FDIC**. Công ty mẹ ngân hàng do Federal Reserve giám sát hợp nhất bất kể charter của ngân hàng con. Hợp tác xã tín dụng là đường riêng do NCUA quản. Về quyền ưu tiên liên bang (preemption), Dodd-Frank đã luật hóa chuẩn *Barnett Bank* tại **12 U.S.C. § 25b** (*Barnett Bank of Marion County v. Nelson*, 517 U.S. 25 (1996)): luật tài chính tiêu dùng của bang chỉ bị gạt đối với ngân hàng quốc gia khi nó ngăn cản hoặc can thiệp đáng kể vào quyền hạn liên bang, do OCC xét từng trường hợp — luật bang không tự động tắt.

**2. FDIC và bảo hiểm tiền gửi.** FDIC được thành lập bởi **12 U.S.C. § 1811** (đạo luật chạy từ §§ 1811 trở đi) với ba vai: bên bảo hiểm, giám sát liên bang chính của ngân hàng tiểu bang không phải thành viên, và bên tiếp quản (receiver) của tổ chức được bảo hiểm bị đổ vỡ. Mức bảo hiểm bị giới hạn ở mức tối đa tiêu chuẩn: **250.000 đô la** theo **12 U.S.C. § 1821(a)(1)(E)**, tính theo người gửi, theo tổ chức và theo loại hình sở hữu (xem 12 C.F.R. Part 330) — không phải theo từng tài khoản. Chứng khoán, quỹ tương hỗ và niên kim mua tại ngân hàng được bảo hiểm không phải tiền gửi và không được bảo hiểm. Cổ phần tại hợp tác xã tín dụng được NCUA bảo hiểm song song theo luật và quỹ khác.

**3. Công cụ thận trọng.** Biện pháp khắc phục kịp thời tại **12 U.S.C. § 1831o** xếp hạng tổ chức theo vốn và siết hậu quả giám sát khi vốn mỏng đi. Xếp hạng CAMELS là phương pháp giám sát, không phải văn bản luật. Cưỡng chế chạy qua **12 U.S.C. § 1818** (lệnh ngừng, phạt tiền dân sự, bãi nhiệm lãnh đạo) do các cơ quan ngân hàng liên bang cùng dùng; FDIC còn giữ thẩm quyền dự phòng với tổ chức mình không giám sát chính.

**4. Dodd-Frank và quy tắc Volcker.** Đạo luật Dodd-Frank (Pub. L. No. 111-203 (2010)) là đáp án sau khủng hoảng tài chính. Điều 619 thêm section 13 vào Bank Holding Company Act, được hệ thống hóa tại **12 U.S.C. § 1851**: thực thể ngân hàng không được giao dịch tự doanh (proprietary trading) và không được mua, giữ hay bảo trợ covered fund (quỹ phòng hộ và quỹ vốn tư nhân), trong khi bảo lãnh phát hành, tạo lập thị trường, phòng ngừa rủi ro giảm thiểu và giao dịch trái phiếu chính phủ Mỹ vẫn được phép, do năm cơ quan ban hành quy tắc thực thi (quy tắc OCC tại 12 C.F.R. Part 44). Đừng phóng đại lệnh cấm thành cấm mọi giao dịch. Các ngưỡng tầm quan trọng hệ thống ở phần khác của đạo luật đã được điều chỉnh sau đó (đáng chú ý vào năm 2018), nên hãy kiểm tra văn bản hiện hành thay vì học thuộc con số cũ.

**5. BSA.** Bank Secrecy Act được hệ thống hóa tại **31 U.S.C. §§ 5311–5336** (§ 5311 nêu mục đích lưu hồ sơ và báo cáo), do FinCEN quản lý; **31 U.S.C. § 5318** là nền của chương trình chống rửa tiền, chi tiết tại 31 C.F.R. Chapter X. Phải nộp **Currency Transaction Report (CTR)** cho giao dịch bằng tiền mặt vật lý **trên 10.000 đô la** (cộng dồn tiền vào và tiền ra trong một ngày làm việc), căn cứ 31 U.S.C. § 5313, quy tắc tại **31 C.F.R. § 1010.311** (cộng dồn tại § 1010.313); chuyển khoản điện tử và séc không kích hoạt CTR. Ngân hàng nộp **Suspicious Activity Report (SAR)** theo **31 C.F.R. § 1020.320** — nói chung ở ngưỡng 5.000 đô la khi ngân hàng biết hoặc nghi ngờ tiền bất hợp pháp, hành vi né tránh báo cáo hoặc giao dịch không có mục đích hợp pháp rõ ràng, và đối với lạm dụng của người nội bộ thì bất kể số tiền; không được báo cho đối tượng bị báo cáo biết. Chia nhỏ giao dịch tiền mặt để né ngưỡng CTR tự nó là tội, **31 U.S.C. § 5324** (xem thêm 31 C.F.R. § 1010.314), kể cả khi tiền sạch — mục đích né tránh mới là điểm mấu chốt. Ngưỡng 10.000 đô la không tự điều chỉnh theo lạm phát; dự luật cải cách đang chờ xử lý không phải luật hiện hành.

**6. CFPB và UDAAP.** Title X của Dodd-Frank lập ra Consumer Financial Protection Bureau. Theo **12 U.S.C. § 5531**, Cục có thể xử lý hành vi không công bằng, lừa dối hoặc lạm dụng (unfair, deceptive, or abusive) của covered person (xem thêm các điều cấm tại § 5536). Tính không công bằng có kiểm tra luật định tại § 5531(c): thiệt hại đáng kể, người tiêu dùng không thể tránh một cách hợp lý, và không bị vượt qua bởi lợi ích đối trọng. Tính lạm dụng được định nghĩa tại § 5531(d): cản trở đáng kể khả năng hiểu điều khoản của người tiêu dùng, hoặc lợi dụng một cách vô lý sự thiếu hiểu biết, sự không thể tự bảo vệ lợi ích, hay sự tin cậy hợp lý của người tiêu dùng. Chữ «A» thêm vào này phân biệt UDAAP liên bang với chuẩn UDAP cũ của FTC Act (15 U.S.C. § 45). Tổng chưởng lý bang có kênh cưỡng chế riêng tại 12 U.S.C. § 5552.

**7. California.** Department of Financial Protection and Innovation (DFPI) — đổi tên từ Department of Business Oversight vào năm 2020 theo AB 1864 — giám sát ngân hàng và hợp tác xã tín dụng có charter California và cấp phép nhiều hoạt động khác. California Consumer Financial Protection Law (CCFPL), **Cal. Fin. Code §§ 90000–90019**, tại **§ 90003(a)(1)** cấm mọi hành vi bất hợp pháp, không công bằng, lừa dối hoặc lạm dụng (thêm «bất hợp pháp» vào công thức liên bang; định nghĩa tại § 90005) và cho phép DFPI đăng ký các nhà cung cấp trước đây chưa bị giám sát. Với ngân hàng quốc gia, hãy bắt đầu bằng phân tích ưu tiên § 25b, không phải bằng CCFPL.

**Lỗi thường gặp:** gán nhầm charter cho OCC, Federal Reserve và FDIC; đọc giới hạn 250.000 đô la theo từng tài khoản thay vì theo người gửi, tổ chức và loại sở hữu; biến quy tắc Volcker thành lệnh cấm tạo lập thị trường; coi mọi khoản chuyển lớn đều là CTR; cho rằng tiền sạch thì chia nhỏ cũng không sao; đưa «abusive» vào section 5 của FTC Act; coi ngân hàng quốc gia là vùng trắng luật bang.

*Ghi chú học tập cá nhân, không phải tư vấn pháp lý. Nguồn: 12 U.S.C. §§ 21, 25b, 1811 trở đi, 1818, 1821(a)(1)(E), 1831o, 1851, 5531, 5536, 5552; Barnett Bank, 517 U.S. 25 (1996); Dodd-Frank Act, Pub. L. No. 111-203; 31 U.S.C. §§ 5311–5336; 31 C.F.R. §§ 1010.311, 1010.313, 1010.314, 1020.320; Cal. Fin. Code §§ 90000–90019.*

---

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**बैंकिंग और वित्तीय विनियमन: दोहरी बैंकिंग प्रणाली, BSA और उपभोक्ता संरक्षण**

बैंक विनियमन के परीक्षा प्रश्न अवधारणाओं से ज़्यादा नक्शे पर ग़लत होते हैं: कौन किसकी निगरानी करता है। एक ही बैंक एक साथ अपने चार्टर देने वाले प्राधिकरण, अपने जमा बीमाकर्ता, अपनी धारक-कंपनी नियामक और उपभोक्ता-संरक्षण एजेंसी के प्रति उत्तरदायी हो सकता है।

**1. दोहरी बैंकिंग प्रणाली।** बैंक संघीय या राज्य चार्टर ले सकते हैं। राष्ट्रीय बैंक (national bank) को **Office of the Comptroller of the Currency (OCC)** **12 U.S.C. § 21** आदि (National Bank Act, 1864) के तहत चार्टर देती है और मुख्य रूप से उसकी निगरानी करती है; ऐसे बैंकों का Federal Reserve System का सदस्य होना अनिवार्य है। राज्य-चार्टर बैंक राज्य नियामक से चार्टर लेते हैं: यदि वे Federal Reserve में शामिल हों (state member bank) तो उनका मुख्य संघीय नियामक **Federal Reserve** है; यदि न हों (state nonmember bank) तो **FDIC** है। बैंक धारक कंपनियों की समेकित निगरानी Federal Reserve करती है, चाहे बैंक का चार्टर कोई भी हो। क्रेडिट यूनियन NCUA के अधीन अलग मार्ग हैं। संघीय पूर्वाधिकार (preemption) पर Dodd-Frank ने **12 U.S.C. § 25b** में *Barnett Bank* मानक (*Barnett Bank of Marion County v. Nelson*, 517 U.S. 25 (1996)) संहिताबद्ध किया: राज्य उपभोक्ता-वित्त कानून राष्ट्रीय बैंक के मामले में तभी विस्थापित होता है जब वह बैंक की संघीय शक्तियों को रोके या उनमें सार्थक हस्तक्षेप करे, और यह निर्णय OCC मामले-दर-मामले करती है — राज्य कानून अपने आप बंद नहीं हो जाता।

**2. FDIC और जमा बीमा।** FDIC की स्थापना **12 U.S.C. § 1811** से होती है (अधिनियम §§ 1811 आदि से चलता है) और इसके तीन काम हैं: बीमाकर्ता, राज्य गैर-सदस्य बैंकों का मुख्य संघीय नियामक, और विफल बीमित संस्थानों का रिसीवर। बीमा सीमा मानक अधिकतम जमा बीमा राशि तक है — **12 U.S.C. § 1821(a)(1)(E)** के तहत **250,000 डॉलर**, जो प्रति जमाकर्ता, प्रति संस्थान, प्रति स्वामित्व श्रेणी गिनी जाती है (12 C.F.R. Part 330 देखें) — प्रति खाता नहीं। बीमित बैंक से खरीदे गए शेयर, म्यूचुअल फंड और वार्षिकियाँ जमा नहीं हैं और बीमित नहीं हैं। क्रेडिट यूनियनों के शेयरों का बीमा NCUA समानांतर रूप से, अलग कानून और अलग कोष से करती है।

**3. विवेकपूर्ण उपकरण।** **12 U.S.C. § 1831o** का prompt corrective action संस्थानों को पूँजी के अनुसार वर्गीकृत करता है और पूँजी घटने पर पर्यवेक्षी परिणाम कठोर करता है। CAMELS रेटिंग पर्यवेक्षण की पद्धति है, कानून नहीं। प्रवर्तन **12 U.S.C. § 1818** (रोक आदेश, नागरिक धन-दंड, अधिकारियों को हटाना) से चलता है, जिसे सभी संघीय बैंकिंग एजेंसियाँ साझा करती हैं; FDIC के पास उन संस्थानों पर भी आरक्षित अधिकार है जिनकी वह मुख्य निगरानी नहीं करती।

**4. Dodd-Frank और Volcker नियम।** Dodd-Frank Act (Pub. L. No. 111-203 (2010)) वित्तीय संकट का उत्तर था। इसकी धारा 619 ने Bank Holding Company Act में section 13 जोड़ा, जो **12 U.S.C. § 1851** में संहिताबद्ध है: कोई बैंकिंग इकाई proprietary trading नहीं कर सकती और covered fund (हेज फंड और निजी इक्विटी फंड) में स्वामित्व हित प्राप्त, धारित या प्रायोजित नहीं कर सकती, जबकि underwriting, market making, जोखिम-घटाने वाली hedging और अमेरिकी सरकारी बांडों का व्यापार अनुमत गतिविधियाँ बनी रहती हैं, जिन्हें पाँच एजेंसियों के नियम लागू करते हैं (OCC का नियम 12 C.F.R. Part 44 में है)। इस प्रतिबंध को सारी ट्रेडिंग पर प्रतिबंध न बना दें। अधिनियम के अन्य भागों की प्रणालीगत-महत्व सीमाएँ बाद में (विशेष रूप से 2018 में) समायोजित हुईं, इसलिए पुराने आँकड़े याद करने के बजाय वर्तमान पाठ देखें।

**5. BSA।** Bank Secrecy Act **31 U.S.C. §§ 5311–5336** में संहिताबद्ध है (§ 5311 इसका अभिलेख व रिपोर्टिंग उद्देश्य बताता है) और इसका प्रशासन FinCEN करती है; **31 U.S.C. § 5318** धन-शोधन-रोधी कार्यक्रमों का आधार है, विवरण 31 C.F.R. Chapter X में है। भौतिक मुद्रा में **10,000 डॉलर से अधिक** के लेनदेन (एक व्यावसायिक दिन में नकद-आगमन और नकद-निर्गमन मिलाकर) के लिए **Currency Transaction Report** देना होता है; प्राधिकार 31 U.S.C. § 5313, नियम **31 C.F.R. § 1010.311** (संकलन § 1010.313); तार अंतरण और चेक CTR को सक्रिय नहीं करते। बैंक **31 C.F.R. § 1020.320** के तहत **Suspicious Activity Report** दाखिल करता है — सामान्यतः 5,000 डॉलर की सीमा पर, जब बैंक को अवैध धन, रिपोर्टिंग से बचाव, या स्पष्ट वैध उद्देश्य के अभाव का ज्ञान या संदेह हो, और आंतरिक दुरुपयोग में राशि निरपेक्ष — और रिपोर्ट किए गए व्यक्ति को सूचना नहीं दी जा सकती। CTR सीमा से बचने के लिए नकद लेनदेन को तोड़ना (structuring) स्वयं अपराध है, **31 U.S.C. § 5324** (31 C.F.R. § 1010.314 भी देखें), भले ही धन साफ़ हो — बचाव का उद्देश्य ही निर्णायक है। 10,000 डॉलर की रेखा मुद्रास्फीति से स्वतः समायोजित नहीं होती; लंबित सुधार विधेयक वर्तमान कानून नहीं हैं।

**6. CFPB और UDAAP।** Dodd-Frank के Title X ने Consumer Financial Protection Bureau बनाया। **12 U.S.C. § 5531** के तहत ब्यूरो covered person के अनुचित, भ्रामक या अपमानजनक (unfair, deceptive, or abusive) कृत्यों पर कार्रवाई कर सकती है (§ 5536 के निषेध भी देखें)। अनुचितता की वैधानिक कसौटी § 5531(c) में है: सार्थक हानि, जिसे उपभोक्ता यथोचित रूप से टाल न सके, और जो प्रतिसंतुलन लाभों से अधिक न हो। अपमानजनकता § 5531(d) में परिभाषित है: उपभोक्ता की किसी शर्त को समझने की क्षमता में सार्थक हस्तक्षेप, या उसकी समझ की कमी, अपने हितों की रक्षा की असमर्थता, या यथोचित विश्वास का अनुचित लाभ उठाना। यही अतिरिक्त «A» संघीय UDAAP को FTC Act के पुराने UDAP (15 U.S.C. § 45) से अलग करता है। राज्य अटॉर्नी जनरलों के पास 12 U.S.C. § 5552 में अपना प्रवर्तन मार्ग है।

**7. California।** Department of Financial Protection and Innovation (DFPI) — 2020 में AB 1864 के तहत Department of Business Oversight का नया नाम — California-चार्टर बैंकों और क्रेडिट यूनियनों की निगरानी करती है और कई अन्य गतिविधियों का लाइसेंस देती है। California Consumer Financial Protection Law (CCFPL), **Cal. Fin. Code §§ 90000–90019**, अपने **§ 90003(a)(1)** में किसी भी अवैध, अनुचित, भ्रामक या अपमानजनक कृत्य को गैरकानूनी ठहराती है (संघीय सूत्र में «unlawful» जोड़कर; परिभाषाएँ § 90005 में) और DFPI को पहले अनियमित प्रदाताओं का पंजीकरण करने देती है। राष्ट्रीय बैंकों के मामले में शुरुआत CCFPL से नहीं, § 25b के पूर्वाधिकार विश्लेषण से करें।

**आम गलतियाँ:** OCC, Federal Reserve और FDIC को ग़लत चार्टर सौंपना; 250,000 डॉलर की सीमा प्रति खाता पढ़ना, जबकि वह प्रति जमाकर्ता, संस्थान और स्वामित्व श्रेणी है; Volcker नियम को market making पर प्रतिबंध बना देना; हर बड़े अंतरण को CTR मानना; यह मानना कि साफ़ धन को तोड़ा नहीं जा सकता; FTC Act की धारा 5 में «abusive» घुसाना; राष्ट्रीय बैंकों को राज्य-कानून-मुक्त क्षेत्र मानना।

*व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं। स्रोत: 12 U.S.C. §§ 21, 25b, 1811 आदि, 1818, 1821(a)(1)(E), 1831o, 1851, 5531, 5536, 5552; Barnett Bank, 517 U.S. 25 (1996); Dodd-Frank Act, Pub. L. No. 111-203; 31 U.S.C. §§ 5311–5336; 31 C.F.R. §§ 1010.311, 1010.313, 1010.314, 1020.320; Cal. Fin. Code §§ 90000–90019.*
