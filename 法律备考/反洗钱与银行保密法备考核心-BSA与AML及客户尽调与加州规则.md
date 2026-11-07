# 反洗钱与银行保密法备考核心：BSA 与 AML 及客户尽调与加州规则

> 个人学习笔记，不构成法律建议。本篇只讲银行与金融机构一侧的反洗钱合规骨架；与《银行与金融监管备考核心》的分工是：那篇画监管地图，本篇钻 BSA 一部法的内部结构——报告义务、合规计划、客户尽调三件事不要混答。

## 中文主文

### 一、先定坐标：BSA 不是一部刑法，是一套记录与报告制度

《银行保密法》（Bank Secrecy Act, BSA）的正式出处是 1970 年《货币与外国交易报告法》（Currency and Foreign Transactions Reporting Act），条文汇编于 31 U.S.C. §§ 5311–5336。31 U.S.C. § 5311 是目的条款：国会要求金融机构保存对刑事、税务与监管调查有高度利用价值的记录，并报告特定交易。理解全篇先抓住定性——BSA 的主轴不是直接禁止洗钱（洗钱罪本身在 18 U.S.C. §§ 1956、1957），而是让资金流动留下可追查的纸面轨迹，再由执法与监管沿轨迹追人。执行中枢是财政部下属的金融犯罪执法网络（Financial Crimes Enforcement Network, FinCEN），BSA 的实施规则集中在 31 C.F.R. Chapter X。

### 二、报告义务三件：CTR、SAR、FBAR 各管一段

1. **大额现金交易报告（CTR）**。授权条文是 31 U.S.C. § 5313，操作规则是 31 C.F.R. § 1010.311：金融机构对单笔、或同一营业日内合计超过 10,000 美元的现金（currency，指实物通货）存入、取出、兑换或转移，须向 FinCEN 报送 CTR；同一人多笔现金交易按合计处理、视为单笔的规则在 31 C.F.R. § 1010.313。三个易错点：门槛是「超过」10,000 美元，恰好 10,000 美元不触发；对象只限实物现金，电汇、支票与 ACH 不因此触发 CTR；为规避这一报告门槛而拆分交易，是 31 U.S.C. § 5324 单独禁止的结构化交易（structuring），本身就是犯罪，不要写成「小额分开存就没事」。
2. **可疑活动报告（SAR）**。授权条文是 31 U.S.C. § 5318(g)，银行的操作规则是 31 C.F.R. § 1020.320：银行知道、怀疑或有理由怀疑交易涉及非法来源资金、意在规避 BSA 要求、没有明显的合法目的，或意在便利犯罪活动，达到门槛即须报 SAR。银行一侧的一般门槛口径是：能识别嫌疑人时合计 5,000 美元起，不能识别嫌疑人时 25,000 美元起，内部人滥用不论金额。时限是硬数字：自初步发现之日起 30 个日历日内报送；无法识别嫌疑人时可延长，但最迟不超过初步发现后 60 日。SAR 另有两条配套规则：§ 5318(g)(2) 的安全港——依法报送 SAR 的机构就该报送免于承担责任；§ 5318(g)(1) 的保密要求——不得向交易涉及的任何人透露 SAR 的存在。
3. **外国银行与金融账户报告（FBAR）**。规则在 31 C.F.R. § 1010.350：美国人在外国金融账户中的权益合计在日历年内任一时点超过 10,000 美元，须在次年 4 月 15 日前以 FinCEN Form 114 报送，自动延期至 10 月 15 日。FBAR 是向 FinCEN 报、不是税表，但未报的民事罚款结构严厉，答题时与税务上的 Form 8938 分开写，两者门槛与对象都不同。

### 三、合规计划：§ 5318(h) 的支柱结构

31 U.S.C. § 5318(h) 要求每家金融机构建立并维持基于风险的反洗钱合规计划（AML program）。FinCEN 规则与历年考试手册把这项义务拆成可核查的支柱，银行一侧写全五件：①内部控制——把识别、监测、报告义务写进业务流程的成文政策与程序；②独立测试——由独立人员或第三方定期审计合规计划是否真在运行；③指定合规官——有专人（BSA/AML officer）负责日常执行与协调；④持续培训——对相关岗位人员做与其职责匹配的培训并留记录；⑤客户尽调——2016 年客户尽调规则（CDD Rule）补上的第五支柱，见下一节。答题陷阱是把 AML 计划写成「报了 SAR 就算合规」：计划义务与报告义务是两条线，报告做全、计划缺位，检查照样开罚。

### 四、客户尽调：CIP 管「是谁」，CDD 管「谁真正控制」

1. **客户识别计划（CIP）**。出处是《爱国者法》第 326 条，写入 31 U.S.C. § 5318(l)，银行规则在 31 C.F.R. § 1020.220：银行开户前须建立成文 CIP，取得并核验足以合理确信客户身份的信息——个人客户记姓名、出生日期、地址与身份证件号码，再以证件型或非证件型方法核验；核验不了身份，原则上不开户、不维持账户。CIP 回答的问题是「账户上写名的这个人是谁」。
2. **受益所有人（beneficial ownership）**。CDD 规则的操作条文是 31 C.F.R. § 1010.230：银行为法人实体客户（legal entity customer）开户时，须识别并核验两类自然人——所有权 prong：直接或间接持有该实体 25% 以上股权的每一名自然人（可为零至四人）；控制 prong：对该实体有重大管理控制责任的一名自然人（如首席执行官、总经理，两 prong 合计至少要落到一人）。客户须以证明书形式申报，银行核验的是申报人的身份、不是逐项审计股权真实性，但信息变化或风险事件出现时须更新。这一节与《公司透明法》（Corporate Transparency Act，31 U.S.C. § 5336）下公司向 FinCEN 直接申报受益所有人的制度是两套并行机制：一个在开户环节对银行、一个在申报环节对公司本身，近年该申报制度的适用范围经诉讼与规则调整多次变动，写作与答题一律以 FinCEN 现行指引为准，不把某一时点的申报口径写死。
3. **EDD 与持续监测**。CDD 的完整内容还有两半：理解客户关系的目的与预期活动，形成风险画像；并做持续监测——既更新客户信息，也从交易监测中发现并报告可疑交易。高风险客户（如代理行、现金密集行业、特定地域关联）适用强化尽调（enhanced due diligence, EDD）。代理行另有专门规则：31 U.S.C. § 5318(i) 要求对外国银行代理账户做尽调与强化尽调，§ 5318(j) 一线禁止与外国空壳银行维持代理关系。

### 五、OFAC 制裁合规：另一家中枢，不要与 FinCEN 混写

制裁合规与 BSA 是两条线。外国资产控制办公室（Office of Foreign Assets Control, OFAC）同属财政部，但权限来自《国际紧急经济权力法》（IEEPA，50 U.S.C. §§ 1701 起）与《与敌贸易法》等授权，执行对特定国家、政权与名单人员（SDN 名单）的封锁与禁止交易。三个备考点：①民事责任近乎严格责任——交易对方是 SDN 或被封锁人，不知情一般不免除民事责任，所以筛查义务重于主观状态；②50% 规则——被封锁人直接或间接合计持有 50% 以上权益的实体，视为被封锁人处理，哪怕实体本身不在名单上；③OFAC 2019 年发布的合规承诺框架要求基于风险的制裁合规计划，与 AML 计划在筛查、培训、测试上大量共用基础设施，但法律后果与报告去向完全不同，答题必须分开写。

### 六、加州落点

加州没有一部州版 BSA，加州落点分三层写。第一层，特许与检查：州特许银行与信用合作社由加州金融机构保护与创新部（Department of Financial Protection and Innovation, DFPI）发照与检查，但 BSA/AML 义务本身是联邦义务，州特许机构同样受 FinCEN 规则与联邦检查手册约束，检查中 DFPI 与联邦监管者分工配合。第二层，汇款业：加州《汇款法》（Money Transmission Act, Financial Code § 2000 起）对货币传输业者设州许可，持牌人仍须在 FinCEN 注册为货币服务企业（MSB）并履行联邦 AML 计划义务，州许可不替代联邦注册。第三层，执法衔接：加州总检察长与地方检察官处理州法层面的诈骗与洗钱相关州罪，联邦一侧的 SAR 与 CTR 数据仍是案件线索的主要来源。答加州题的正确顺序是：先联邦 BSA 义务，再 DFPI 的特许与州许可层，最后州执法层，不要虚构一部「加州银行保密法」。

**备考提示**：锚点条号按义务分组背——报告组 § 5313 与 31 C.F.R. § 1010.311（CTR 超过 10,000 美元现金）、§ 5318(g) 与 § 1020.320（SAR 30 日、5,000／25,000 美元门槛）；计划组 § 5318(h) 五支柱；尽调组 § 5318(l) 与 § 1020.220（CIP）、§ 1010.230（受益所有人 25%＋控制人）；禁止组 § 5324（结构化）；制裁组另起一行写 OFAC 与 IEEPA。

> 声明：本文为个人学习笔记，不构成法律建议。来源：31 U.S.C. §§ 5311、5313、5318、5324、5336；31 C.F.R. §§ 1010.230、1010.311、1010.313、1010.350、1020.220、1020.320；50 U.S.C. §§ 1701 起；Cal. Fin. Code § 2000 起。

## English

The Bank Secrecy Act (BSA), enacted as the Currency and Foreign Transactions Reporting Act of 1970 and codified at 31 U.S.C. §§ 5311–5336, is a recordkeeping and reporting regime, not the money-laundering crime itself (that is 18 U.S.C. §§ 1956–1957). Section 5311 states its purpose; FinCEN administers it under 31 C.F.R. Chapter X. Three reports anchor the system. **Currency Transaction Reports**: under 31 U.S.C. § 5313 and 31 C.F.R. § 1010.311, a financial institution must report currency transactions of **more than $10,000** in one business day, aggregating multiple transactions under § 1010.313; only physical currency counts, and structuring transactions to evade the threshold is separately criminal under 31 U.S.C. § 5324. **Suspicious Activity Reports**: under 31 U.S.C. § 5318(g) and, for banks, 31 C.F.R. § 1020.320, the general thresholds are $5,000 where a suspect is identified and $25,000 where none is, with insider abuse reportable at any amount; filing is due within **30 calendar days** of initial detection, and never more than 60 days. Section 5318(g) also supplies a safe harbor for good-faith filing and a strict no-tipping-off rule. **FBAR**: under 31 C.F.R. § 1010.350, U.S. persons with foreign accounts aggregating over $10,000 must file FinCEN Form 114 by April 15, with an automatic extension to October 15.

On the program side, 31 U.S.C. § 5318(h) requires a risk-based AML program, conventionally stated in five pillars: internal controls, independent testing, a designated compliance officer, ongoing training, and customer due diligence. The Customer Identification Program required by § 5318(l) and 31 C.F.R. § 1020.220 (name, date of birth, address, identification number, verified before or promptly after account opening) answers "who is the named customer." The CDD Rule's beneficial-ownership requirement, 31 C.F.R. § 1010.230, answers "who really owns and controls it": for legal entity customers, identify every natural person owning 25% or more (the ownership prong) plus one person with significant managerial control (the control prong). CDD also requires understanding the purpose of the relationship and ongoing monitoring. OFAC sanctions compliance is a separate track: it rests on IEEPA, 50 U.S.C. §§ 1701 et seq., civil liability is essentially strict, and OFAC's 50 Percent Rule treats entities owned 50% or more in aggregate by blocked persons as blocked themselves. California has no state BSA: the DFPI charters and examines state institutions, but BSA duties remain federal, and the California Money Transmission Act (Fin. Code § 2000 et seq.) adds state licensing without displacing FinCEN registration.

*Study note only; not legal advice.*

## Español

La Ley de Secreto Bancario (BSA), promulgada en 1970 y codificada en 31 U.S.C. §§ 5311–5336, es un régimen de registros e informes, no el delito de lavado en sí (18 U.S.C. §§ 1956–1957); la administra FinCEN conforme al 31 C.F.R. Chapter X. Tres informes sostienen el sistema. El **CTR** (31 U.S.C. § 5313; 31 C.F.R. § 1010.311): operaciones en efectivo físico por **más de $10,000** en un mismo día hábil, con agregación según § 1010.313; fraccionar operaciones para eludir el umbral es delito autónomo (31 U.S.C. § 5324). El **SAR** (31 U.S.C. § 5318(g); para bancos, 31 C.F.R. § 1020.320): umbral general de $5,000 con sospechoso identificado y $25,000 sin sospechoso, abuso interno sin importe mínimo, presentación dentro de **30 días naturales** desde la detección inicial (máximo 60), con puerto seguro para quien informa y prohibición de avisar al afectado. El **FBAR** (31 C.F.R. § 1010.350) cubre cuentas extranjeras que sumen más de $10,000, con vencimiento el 15 de abril y prórroga automática al 15 de octubre.

En el plano programático, 31 U.S.C. § 5318(h) exige un programa AML basado en riesgo, descrito en cinco pilares: controles internos, pruebas independientes, responsable de cumplimiento designado, formación continua y diligencia debida del cliente. El programa de identificación (CIP), § 5318(l) y 31 C.F.R. § 1020.220, responde «quién es el cliente nombrado»; la regla de beneficiarios reales, 31 C.F.R. § 1010.230, responde «quién posee y controla de verdad»: toda persona física con 25% o más de participación y una persona con control gerencial significativo. El cumplimiento de sanciones de la OFAC es una vía distinta: se apoya en la IEEPA (50 U.S.C. §§ 1701 y ss.), su responsabilidad civil es prácticamente objetiva y su regla del 50% trata como bloqueada a toda entidad participada en 50% o más, en conjunto, por personas bloqueadas. California no tiene una BSA estatal: la DFPI otorga licencias y examina, pero los deberes BSA son federales, y la Money Transmission Act (Fin. Code § 2000 y ss.) añade licencia estatal sin sustituir el registro ante FinCEN.

*Nota de estudio personal; no constituye asesoramiento jurídico.*

## 한국어（初译待校）

은행비밀법(BSA)은 1970년 제정되어 31 U.S.C. §§ 5311–5336에 수록된 기록·보고 제도이며, 자금세탁죄 자체(18 U.S.C. §§ 1956–1957)와는 구분된다. 집행 중심은 FinCEN이고 규칙은 31 C.F.R. Chapter X에 모여 있다. 보고 의무는 세 가지다. **CTR**: 31 U.S.C. § 5313과 31 C.F.R. § 1010.311에 따라, 동일 영업일에 합산 **10,000달러를 초과**하는 실물 현금 거래를 보고해야 하고(합산 규칙 § 1010.313), 임계값을 피하려고 거래를 쪼개는 구조화(structuring)는 31 U.S.C. § 5324가 별도로 금지한다. **SAR**: 31 U.S.C. § 5318(g)와 은행용 규칙 31 C.F.R. § 1020.320에 따라, 혐의자가 특정되면 합계 5,000달러부터, 특정되지 않으면 25,000달러부터, 내부자 남용은 금액과 무관하게 보고하며, 최초 발견 후 **30일 이내**(최장 60일)에 제출한다. 성실한 보고에는 면책(safe harbor)이, 관련자에게 SAR 존재를 알리는 행위에는 금지 규정이 붙는다. **FBAR**: 31 C.F.R. § 1010.350에 따라 외국 계좌 합계가 10,000달러를 초과하면 다음 해 4월 15일까지 보고하고 10월 15일까지 자동 연장된다.

프로그램 측면에서는 31 U.S.C. § 5318(h)가 위험 기반 AML 프로그램을 요구하며, 관행상 다섯 기둥——내부통제, 독립적 테스트, 준법감시인 지정, 지속 교육, 고객실사(CDD)——으로 정리된다. 고객확인제도(CIP, § 5318(l) 및 31 C.F.R. § 1020.220)는 «명의상 고객이 누구인가»에 답하고, 수익적 소유자 규칙(31 C.F.R. § 1010.230)은 «누가 실제로 소유·지배하는가»에 답한다: 법인 고객에 대해 지분 25% 이상을 보유한 모든 자연인과 중대한 경영 통제권을 가진 1인을 확인해야 한다. OFAC 제재 준수는 별도 축이다: IEEPA(50 U.S.C. §§ 1701 이하)에 근거하고 민사책임은 사실상 무과실에 가까우며, 차단 대상자가 합산 50% 이상을 보유한 법인도 차단된 것으로 취급하는 50% 규칙이 적용된다. 캘리포니아에는 주(州) 차원의 BSA가 없다: DFPI가 주 인가 기관을 인가·검사하지만 BSA 의무 자체는 연방 의무이며, 송금법(Fin. Code § 2000 이하)의 주 라이선스가 FinCEN 등록을 대체하지도 않는다.

*개인 학습 노트이며 법률 자문이 아니다. (초역, 원어민 감수 대기)*

## Tiếng Việt（初译待校）

Đạo luật Bí mật Ngân hàng (BSA), ban hành năm 1970 và hệ thống hóa tại 31 U.S.C. §§ 5311–5336, là chế độ lưu trữ hồ sơ và báo cáo, không phải chính tội rửa tiền (18 U.S.C. §§ 1956–1957); cơ quan điều hành là FinCEN theo 31 C.F.R. Chapter X. Ba loại báo cáo là trụ cột. **CTR**: theo 31 U.S.C. § 5313 và 31 C.F.R. § 1010.311, phải báo cáo giao dịch tiền mặt vật lý **trên $10,000** trong cùng một ngày làm việc, cộng gộp theo § 1010.313; việc chia nhỏ giao dịch để né ngưỡng (structuring) bị cấm riêng tại 31 U.S.C. § 5324. **SAR**: theo 31 U.S.C. § 5318(g) và quy tắc cho ngân hàng 31 C.F.R. § 1020.320, ngưỡng chung là $5.000 khi xác định được nghi phạm và $25.000 khi không xác định được, lạm dụng nội bộ báo cáo ở mọi số tiền, nộp trong **30 ngày** kể từ khi phát hiện ban đầu (tối đa 60 ngày), kèm bến an toàn cho người báo cáo thiện chí và cấm tiết lộ cho người liên quan. **FBAR**: theo 31 C.F.R. § 1010.350, tài khoản nước ngoài cộng gộp trên $10.000 phải báo cáo trước 15/4, tự động gia hạn đến 15/10.

Về chương trình, 31 U.S.C. § 5318(h) yêu cầu chương trình AML theo rủi ro, thường được nêu thành năm trụ cột: kiểm soát nội bộ, kiểm tra độc lập, cán bộ tuân thủ được chỉ định, đào tạo liên tục và thẩm tra khách hàng (CDD). Chương trình nhận diện khách hàng (CIP, § 5318(l) và 31 C.F.R. § 1020.220) trả lời câu hỏi «khách hàng đứng tên là ai»; quy tắc chủ sở hữu hưởng lợi, 31 C.F.R. § 1010.230, trả lời «ai thực sự sở hữu và kiểm soát»: với khách hàng pháp nhân, xác định mọi cá nhân nắm từ 25% vốn trở lên cùng một người có quyền kiểm soát quản lý đáng kể. Tuân thủ trừng phạt của OFAC là một tuyến riêng: dựa trên IEEPA (50 U.S.C. §§ 1701 trở đi), trách nhiệm dân sự gần như tuyệt đối, và quy tắc 50% coi pháp nhân do người bị phong tỏa nắm giữ cộng gộp từ 50% trở lên cũng là bị phong tỏa. California không có BSA cấp bang: DFPI cấp phép và kiểm tra các tổ chức của bang, nhưng nghĩa vụ BSA vẫn là nghĩa vụ liên bang, và Đạo luật Chuyển tiền (Fin. Code § 2000 trở đi) chỉ thêm giấy phép bang chứ không thay thế đăng ký với FinCEN.

*Ghi chú học tập cá nhân; không phải tư vấn pháp lý. (Bản dịch sơ bộ, chờ hiệu đính)*

## हिन्दी（初译待校）

बैंक गोपनीयता अधिनियम (BSA), जो 1970 में अधिनियमित हुआ और 31 U.S.C. §§ 5311–5336 में संहिताबद्ध है, अभिलेख-रखरखाव और प्रतिवेदन की व्यवस्था है, स्वयं धन-शोधन अपराध (18 U.S.C. §§ 1956–1957) नहीं; इसका संचालन FinCEN 31 C.F.R. Chapter X के तहत करता है। तीन प्रतिवेदन इसके आधार हैं। **CTR**: 31 U.S.C. § 5313 और 31 C.F.R. § 1010.311 के तहत एक ही कारोबारी दिन में **$10,000 से अधिक** की भौतिक नकदी लेन-देन की रिपोर्ट अनिवार्य है, § 1010.313 के तहत राशियाँ जोड़ी जाती हैं; सीमा से बचने के लिए लेन-देन तोड़ना (structuring) 31 U.S.C. § 5324 के तहत अलग अपराध है। **SAR**: 31 U.S.C. § 5318(g) और बैंकों हेतु 31 C.F.R. § 1020.320 के तहत सामान्य सीमा संदिग्ध की पहचान होने पर $5,000 और न होने पर $25,000 है, आंतरिक दुरुपयोग किसी भी राशि पर रिपोर्ट योग्य है, और फाइलिंग प्रारंभिक पहचान के **30 दिनों** के भीतर (अधिकतम 60 दिन) करनी होती है; सद्भावपूर्ण फाइलिंग को सुरक्षा-कवच मिलता है और संबंधित व्यक्ति को सूचना देना वर्जित है। **FBAR**: 31 C.F.R. § 1010.350 के तहत विदेशी खातों का योग $10,000 से अधिक होने पर 15 अप्रैल तक रिपोर्ट करनी होती है, 15 अक्टूबर तक स्वतः विस्तार मिलता है।

कार्यक्रम पक्ष पर, 31 U.S.C. § 5318(h) जोखिम-आधारित AML कार्यक्रम माँगता है, जिसे प्रायः पाँच स्तंभों में कहा जाता है: आंतरिक नियंत्रण, स्वतंत्र परीक्षण, नामित अनुपालन अधिकारी, निरंतर प्रशिक्षण और ग्राहक सम्यक जाँच (CDD)। ग्राहक पहचान कार्यक्रम (CIP, § 5318(l) और 31 C.F.R. § 1020.220) «नामित ग्राहक कौन है» का उत्तर देता है; लाभकारी स्वामित्व नियम, 31 C.F.R. § 1010.230, «वास्तव में स्वामी और नियंत्रक कौन है» का: विधिक इकाई ग्राहकों के लिए 25% या अधिक हिस्सेदारी रखने वाले प्रत्येक प्राकृतिक व्यक्ति और महत्वपूर्ण प्रबंधकीय नियंत्रण रखने वाले एक व्यक्ति की पहचान करनी होती है। OFAC प्रतिबंध-अनुपालन अलग मार्ग है: यह IEEPA (50 U.S.C. §§ 1701 आदि) पर आधारित है, दीवानी दायित्व वस्तुतः कठोर है, और 50 प्रतिशत नियम के तहत अवरुद्ध व्यक्तियों द्वारा सम्मिलित रूप से 50% या अधिक स्वामित्व वाली इकाई भी अवरुद्ध मानी जाती है। California का कोई राज्य-स्तरीय BSA नहीं है: DFPI राज्य संस्थानों को चार्टर और परीक्षण करता है, किंतु BSA दायित्व संघीय ही रहते हैं, और Money Transmission Act (Fin. Code § 2000 आदि) राज्य लाइसेंस जोड़ता है, FinCEN पंजीकरण का स्थान नहीं लेता।

*व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)*
