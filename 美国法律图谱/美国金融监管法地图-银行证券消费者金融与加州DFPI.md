# 美国金融监管法地图：银行、消费者金融、反洗钱与加州 DFPI

> 个人学习笔记，不构成法律建议。本文以《国家银行法》《联邦储备法》《多德—弗兰克法》（Dodd-Frank Act）与加州现行规则为纲，写于 2026 年 10 月；具体业务请以法典原文、监管机构规则与持牌律师意见为准。

## 中文

美国金融监管没有一个总监管者，它是按「机构类型＋业务类型」拼起来的双层拼图：同一笔业务，银行做归银行监管者管，证券公司做归 SEC 管，搬到加州还要再过一层州法。读这张图先分清两条线——审慎监管（这家机构会不会倒）与行为监管（它有没有坑消费者），再认机构归谁发牌。

### 一、监管者地图：先认谁发牌、谁查账

- **联邦储备系统（Fed）**：中央银行兼监管者，源头是《联邦储备法》（Federal Reserve Act, 1913）。管银行控股公司与州特许的联储成员银行，并依《多德—弗兰克法》对系统重要性机构行使强化审慎监管。
- **货币监理署（OCC）**：财政部下属机构，源头是《国家银行法》（National Bank Act, 1863–1864），给国家银行（national bank）发牌并作其主监管者，也管联邦储蓄银行与外国银行的联邦分支。
- **联邦存款保险公司（FDIC）**：管州特许非成员银行，同时给几乎所有受保存款机构上存款保险——这是美国「双轨银行制」（dual banking system）的结果：开银行可以选联邦牌照，也可以选州牌照，两条线并存至今。
- **消费者金融保护局（CFPB）**：2010 年《多德—弗兰克法》第十章设立（12 U.S.C. §§ 5301 起），专管消费者金融的行为监管：按揭、信用卡、学生贷款、发薪日贷款等产品的披露与不公平、欺骗或滥用行为（UDAAP）。
- **SEC 与 CFTC**：SEC 管证券发行、交易与投资顾问（本仓证券法地图另有专篇）；CFTC 管期货与多数掉期。加密资产归谁管至今靠执法与判例划线，没有一部总法——这是这张图最大的一块拼图缺口。
- **金融稳定监督委员会（FSOC）**：《多德—弗兰克法》第一章设立，由财政部长牵头，把各监管者拉到一张桌子上，负责认定系统重要性非银行金融机构并指定强化监管。

### 二、准入与存款保险：25 万美元这条线

- **存款保险额度**：FDIC 对每位存款人、在每家受保银行、按所有权类别计算的保险上限为 250,000 美元（12 U.S.C. § 1821(a)）。这个数字 2008 年危机时临时从 10 万美元提上来，《多德—弗兰克法》把它写成了永久额度。
- **保险不是投资保护**：存款保险只保银行倒闭时存款类别内的本金与利息，不保股票、基金、加密资产，也不保银行保险箱里的物品——考试与实务最爱在这一处设陷阱。
- **特许即门槛**：没有牌照不能吸收存款、不能自称 bank；影子银行与金融科技公司因此多与持牌银行「合作发牌」（partner bank 模式），监管责任如何分配是近年的执法主战场。

### 三、审慎监管：资本、考试与《多德—弗兰克法》的强化层

- **资本与检查**：银行监管靠三件套——最低资本与杠杆率要求、监管者定期现场检查（业内通称 CAMELS 评级：资本、资产质量、管理、盈利、流动性、市场风险敏感度）、以及问题机构的执法阶梯（从谅解备忘录到停止令与接管）。
- **系统重要性门槛**：2010 年法案原把资产 500 亿美元以上的银行控股公司自动纳入强化审慎监管；2018 年《经济增长、监管减负与消费者保护法》（EGRRCPA）把自动门槛抬到 2,500 亿美元，500 亿至 2,500 亿之间改为由 Fed 裁量——「大到不能倒」的线画在哪里，随政治周期来回移动，这是理解美国银行法必须记住的一次摆动。
- **有序清算**：《多德—弗兰克法》第二章创设有序清算 Authority（OLA）：系统重要性机构倒下时不再只有「救助或破产」两条路，可由 FDIC 接管清算，股东与无担保债权人先担损失。

### 四、沃尔克规则：银行不能拿存款去赌

- **条文位置**：《多德—弗兰克法》第 619 条，即沃尔克规则（Volcker Rule），给《银行控股公司法》新增第 13 条，编在 12 U.S.C. § 1851。
- **两条禁令**：银行实体原则上不得从事自营交易（proprietary trading，用自己的钱短线买卖赚钱），也不得拥有或赞助「涵盖基金」（covered fund，主要是对冲基金与私募股权基金）；做市、对冲与承销等客户服务型活动有豁免，但要留合规证据。
- **豁免尾巴**：2018 年 EGRRCPA 给资产不超过 100 亿美元且交易资产负债占比低的社区银行整体豁免——同一部规则，对大银行是合规工程，对小银行直接出局免考。

### 五、消费者金融：CFPB 的行为监管工具箱

- **成文法拼盘**：CFPB 执掌一批老消费者法的规则制定与执法：《借贷真相法》（TILA）、《平等信贷机会法》（ECOA）、《公平债务催收法》（FDCPA，本仓常用法律常识另有专篇）、《电子资金转移法》（EFTA）等，考试时先按产品认法，再按行为认条。
- **UDAAP 是兜底条款**：《多德—弗兰克法》第 1031 条（12 U.S.C. § 5531）授权 CFPB 打击不公平、欺骗或滥用行为与做法。它没有细密构成要件，靠执法与判例填充，因此既是利器也是争议焦点。
- **州法不退场**：联邦消费者金融法多为地板而非天花板，州可以给消费者更高保护；加州一层见第七节。

### 六、反洗钱：BSA 是所有金融机构头上的总闸

- **条文骨架**：《银行保密法》（Bank Secrecy Act, BSA），31 U.S.C. §§ 5311 起，由财政部金融犯罪执法局（FinCEN）执行，靠的不是保密而是留痕：金融机构是国家反洗钱体系的前哨。
- **两个报告数字**：现金交易超过 10,000 美元要报 CTR（货币交易报告）；可疑活动达到门槛（一般为 5,000 美元且能识别嫌疑人等情形）要报 SAR（可疑活动报告），且不得通知被报告人（tipping off 禁令）。
- **客户尽职**：开户要 CIP 核身、对法人客户要识别受益所有人（beneficial ownership）；2024 年起多数小公司还要依《公司透明法》（Corporate Transparency Act）向 FinCEN 申报受益所有人信息——申报范围与执行状态近年变动频繁，引用前务必查 FinCEN 当期口径。

### 七、加州加层：DFPI 与 CCFPL

- **机构沿革**：加州原商业监督部（DBO）经 2020 年 AB 1864 改组为金融保护与创新部（DFPI），同法带来《加州消费者金融保护法》（CCFPL），编在 Financial Code §§ 90000 起，2021 年 1 月 1 日生效——立法者明说这是对标联邦 CFPB 的「加州版 CFPB」。
- **扩围之处**：CCFPL 把加州版 UDAAP 禁令扩到此前未被州金融法覆盖的消费者金融服务提供者，并给 DFPI 注册、调查与执法的新工具；但持牌银行等联邦与州特许机构的审慎监管仍走原有轨道，不要把 DFPI 读成包揽一切。
- **老牌照体系并行**：货币传输（Money Transmission Act）、托管、发薪日贷款与《加州融资法》（CFL）等牌照体系照旧运转；做金融科技在加州落地，先查产品落在哪张牌照图上，再谈联邦层。

### 八、读图口诀与考试陷阱

- 先问三件事：谁发牌、保不保、坑没坑人——发牌定审慎监管者，保险定 FDIC 边界，行为定 CFPB 与州法。
- 高频陷阱有四：把 FDIC 保险说成保投资（只保存款）；把沃尔克规则说成禁一切交易（客户服务型活动有豁免，且小银行整体豁免）；把 CFPB 说成管银行安全（它管行为不管资本）；把加州 DFPI 说成 2020 年前就有（前身是 DBO，CCFPL 2021 年才生效）。

> 个人学习笔记，不构成法律建议。

## English

U.S. financial regulation is a dual-layer patchwork by charter and by activity — there is no single supervisor. The **Federal Reserve** (Federal Reserve Act, 1913) supervises bank holding companies and state member banks; the **OCC** charters and supervises national banks under the National Bank Act; the **FDIC** supervises state nonmember banks and insures deposits. This is the **dual banking system**: a bank may choose a federal or a state charter. Deposit insurance is capped at **$250,000 per depositor, per insured bank, per ownership category (12 U.S.C. § 1821(a))** — raised from $100,000 in the crisis and made permanent by Dodd-Frank. Insurance covers deposits only, never securities, funds, crypto assets, or safe-deposit-box contents.

Prudential law runs on capital rules, CAMELS examinations, and an enforcement ladder. Dodd-Frank (Pub. L. 111-203, 2010) created the **FSOC** to designate systemically important firms and the **Orderly Liquidation Authority** so a failing giant need not be bailed out or dumped into ordinary bankruptcy. The automatic enhanced-prudential threshold began at **$50 billion** in assets; the **EGRRCPA (2018)** raised it to **$250 billion**, with discretionary coverage in between — the "too big to fail" line moves with politics. The **Volcker Rule, Dodd-Frank § 619, codified at 12 U.S.C. § 1851** (Bank Holding Company Act § 13), bars banking entities from proprietary trading and from owning or sponsoring covered funds, with exemptions for market making, hedging, and underwriting — and a wholesale exemption since 2018 for community banks at or below **$10 billion** in assets.

Conduct regulation belongs chiefly to the **CFPB**, created by Dodd-Frank Title X (12 U.S.C. §§ 5301 et seq.), which administers TILA, ECOA, the FDCPA, and EFTA and polices unfair, deceptive, or abusive acts or practices under **§ 1031 (12 U.S.C. § 5531)**. Anti-money-laundering law sits above everyone: under the **Bank Secrecy Act, 31 U.S.C. §§ 5311 et seq.**, enforced by FinCEN, institutions file Currency Transaction Reports for cash over **$10,000** and Suspicious Activity Reports at the applicable thresholds, with a strict no-tipping-off rule, plus customer-identification and beneficial-ownership diligence.

**California layer.** In 2020, AB 1864 renamed the Department of Business Oversight as the **DFPI** and enacted the **California Consumer Financial Protection Law (Fin. Code §§ 90000 et seq.), effective January 1, 2021** — a self-described California CFPB extending a state UDAAP ban and registration and enforcement tools to previously uncovered consumer financial services, while chartered banks' prudential supervision stays on its existing track and legacy licences (money transmission, the California Financing Law) keep running in parallel.

> Personal study notes only; not legal advice.

## Español (traducción de estudio)

La regulación financiera de EE. UU. es un mosaico de dos capas, por licencia y por actividad, sin un supervisor único. La **Reserva Federal** (Federal Reserve Act, 1913) supervisa holdings bancarios y bancos estatales miembros; la **OCC** otorga licencias a los bancos nacionales (National Bank Act); la **FDIC** supervisa bancos estatales no miembros y asegura los depósitos: es el **sistema bancario dual**, con licencia federal o estatal a elección. El seguro de depósitos llega a **250.000 dólares por depositante, banco asegurado y categoría de titularidad (12 U.S.C. § 1821(a))**, elevado desde 100.000 en la crisis y hecho permanente por Dodd-Frank; cubre solo depósitos, nunca valores, fondos, criptoactivos ni cajas de seguridad.

Lo prudencial funciona con capital, exámenes CAMELS y escalera sancionadora. Dodd-Frank (2010) creó el **FSOC** y la **autoridad de liquidación ordenada**; el umbral automático de supervisión reforzada nació en **50.000 millones** de activos y la **EGRRCPA (2018)** lo subió a **250.000 millones**, con zona discrecional intermedia. La **Regla Volcker, § 619 de Dodd-Frank, codificada en 12 U.S.C. § 1851**, prohíbe a las entidades bancarias la negociación por cuenta propia y poseer o patrocinar fondos cubiertos, con exenciones para creación de mercado, cobertura y suscripción, y exención total desde 2018 para bancos comunitarios de hasta **10.000 millones** en activos.

La conducta es terreno de la **CFPB** (Título X, 12 U.S.C. §§ 5301 y ss.), que administra TILA, ECOA, FDCPA y EFTA y persigue actos injustos, engañosos o abusivos según el **§ 1031 (12 U.S.C. § 5531)**. Sobre todos pesa la **Bank Secrecy Act, 31 U.S.C. §§ 5311 y ss.**: informes de operaciones en efectivo sobre **10.000 dólares** (CTR), informes de actividad sospechosa (SAR) sin avisar al reportado, e identificación de clientes y beneficiarios reales, vía FinCEN.

**Capa de California.** En 2020, la AB 1864 convirtió el antiguo DBO en el **DFPI** y dictó la **California Consumer Financial Protection Law (Fin. Code §§ 90000 y ss.), vigente desde el 1 de enero de 2021**: una «CFPB californiana» que extiende la prohibición estatal de prácticas abusivas y nuevas herramientas de registro y ejecución a servicios antes no cubiertos, sin absorber la supervisión prudencial de los bancos licenciados ni las licencias previas (transmisión de dinero, California Financing Law).

> Notas personales de estudio; no constituyen asesoría legal. (Traducción de estudio)

## 한국어 (초역, 교정 대기)

미국 금융규제는 단일 감독기관이 없는, 인가와 업무로 짜인 이중 패치워크다. **연준**(연방준비법, 1913)은 은행지주회사와 주 회원은행을, **OCC**는 국가은행법 아래 국립은행의 인가·감독을, **FDIC**는 주 비회원은행 감독과 예금보험을 맡는다 — 연방 인가와 주 인가 중 선택할 수 있는 **이중 은행제도**다. 예금보험 한도는 **예금자당·보험은행당·소유 범주당 250,000달러(12 U.S.C. § 1821(a))**로, 위기 때 100,000달러에서 올라 Dodd-Frank법으로 영구화됐다. 보험은 예금만 보장하며 증권·펀드·암호자산·대여금고 내용물은 보장하지 않는다.

건전성 규제는 자본규제, CAMELS 검사, 집행 사다리로 굴러간다. Dodd-Frank법(2010)은 **FSOC**와 **질서 있는 청산 권한**을 만들었고, 강화 건전성 기준의 자동 적용 문턱은 자산 **500억 달러**에서 **EGRRCPA(2018)**로 **2,500억 달러**까지 올라갔다(중간 구간은 재량). **볼커 룰 — Dodd-Frank § 619, 12 U.S.C. § 1851** — 은 은행체의 자기계정 매매와 커버드 펀드 보유·후원을 금지하되 시장조성·헤지·인수에는 예외를 두고, 2018년부터 자산 **100억 달러 이하** 커뮤니티은행은 통째로 면제된다.

행위 규제는 주로 **CFPB**(제10편, 12 U.S.C. §§ 5301 이하)가 맡아 TILA·ECOA·FDCPA·EFTA를 집행하고 **§ 1031(12 U.S.C. § 5531)**의 불공정·기만·남용 행위 금지를 적용한다. 모두의 위에는 **은행비밀법 31 U.S.C. §§ 5311 이하**가 있다: FinCEN 집행 아래 현금 **10,000달러 초과** 거래보고(CTR), 의심거래보고(SAR, 대상자에게 알리는 것 금지), 고객 확인과 수익적 소유자 실사가 의무다.

**캘리포니아 층.** 2020년 AB 1864는 기존 DBO를 **DFPI**로 바꾸고 **캘리포니아 소비자금융보호법(Fin. Code §§ 90000 이하)을 2021-01-01 시행**했다 — 기존에 닿지 않던 소비자금융 서비스까지 주 차원의 남용행위 금지와 등록·집행 도구를 넓힌 '캘리포니아판 CFPB'이며, 인가 은행의 건전성 감독과 송금·CFL 등 기존 면허 체계는 그대로 병행한다.

> 개인 학습 노트이며 법률 자문이 아니다. (초역, 교정 대기)

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Regulation tài chính Hoa Kỳ là một bức tranh hai lớp theo giấy phép và theo hoạt động, không có một cơ quan giám sát duy nhất. **Cục Dự trữ Liên bang** (Federal Reserve Act, 1913) giám sát công ty holding ngân hàng và ngân hàng thành viên cấp bang; **OCC** cấp phép và giám sát ngân hàng quốc gia theo National Bank Act; **FDIC** giám sát ngân hàng cấp bang không phải thành viên và bảo hiểm tiền gửi — đây là **hệ thống ngân hàng kép**: chọn giấy phép liên bang hoặc tiểu bang. Bảo hiểm tiền gửi tối đa **250.000 USD cho mỗi người gửi, mỗi ngân hàng được bảo hiểm, mỗi loại sở hữu (12 U.S.C. § 1821(a))**, được nâng từ 100.000 USD trong khủng hoảng và Dodd-Frank biến thành mức vĩnh viễn; chỉ bảo hiểm tiền gửi, không bảo hiểm chứng khoán, quỹ, tài sản mã hóa hay đồ trong két an toàn.

Giám sát an toàn dựa vào quy định vốn, kiểm tra CAMELS và thang thực thi. Dodd-Frank (2010) lập **FSOC** và **thẩm quyền thanh lý có trật tự**; ngưỡng giám sát tăng cường tự động khởi đầu ở **50 tỷ USD** tài sản và **EGRRCPA (2018)** nâng lên **250 tỷ USD**, khoảng giữa do Fed tùy nghi. **Quy tắc Volcker, Dodd-Frank § 619, ghi tại 12 U.S.C. § 1851**, cấm tổ chức ngân hàng giao dịch tự doanh và sở hữu hay tài trợ quỹ bị bao phủ, với ngoại lệ cho tạo lập thị trường, phòng ngừa rủi ro và bảo lãnh phát hành, và từ 2018 miễn toàn bộ cho ngân hàng cộng đồng có tài sản từ **10 tỷ USD** trở xuống.

Regulation hành vi chủ yếu thuộc **CFPB** (Title X, 12 U.S.C. §§ 5301 trở đi), thực thi TILA, ECOA, FDCPA, EFTA và cấm hành vi không công bằng, lừa dối hoặc lạm dụng theo **§ 1031 (12 U.S.C. § 5531)**. Trên tất cả là **Bank Secrecy Act, 31 U.S.C. §§ 5311 trở đi** do FinCEN thực thi: báo cáo giao dịch tiền mặt trên **10.000 USD** (CTR), báo cáo hoạt động đáng ngờ (SAR) và cấm báo tin cho đối tượng, kèm thẩm tra khách hàng và chủ sở hữu hưởng lợi.

**Lớp California.** Năm 2020, AB 1864 đổi DBO thành **DFPI** và ban hành **California Consumer Financial Protection Law (Fin. Code §§ 90000 trở đi), hiệu lực 01-01-2021** — một "CFPB của California" mở rộng lệnh cấm lạm dụng cấp bang cùng công cụ đăng ký và thực thi tới các dịch vụ tài chính tiêu dùng trước đây chưa bị chạm tới, trong khi giám sát an toàn đối với ngân hàng có giấy phép và các giấy phép cũ (chuyển tiền, California Financing Law) vẫn chạy song song.

> Ghi chú học tập cá nhân, không phải tư vấn pháp lý. (Bản dịch sơ bộ, chờ hiệu đính)

## हिन्दी (प्रारम्भिक अनुवाद, समीक्षा अपेक्षित)

अमेरिकी वित्तीय नियमन चार्टर और गतिविधि के हिसाब से बना दोहरी परत वाला तंत्र है — कोई एकल पर्यवेक्षक नहीं है। **Federal Reserve** (Federal Reserve Act, 1913) बैंक होल्डिंग कंपनियों और राज्य सदस्य बैंकों को, **OCC** National Bank Act के तहत राष्ट्रीय बैंकों को लाइसेंस व पर्यवेक्षण, और **FDIC** राज्य ग़ैर-सदस्य बैंकों का पर्यवेक्षण व जमा बीमा संभालता है — यही **दोहरी बैंकिंग प्रणाली** है: संघीय या राज्य चार्टर में से चुनाव संभव है। जमा बीमा सीमा **प्रति जमाकर्ता, प्रति बीमित बैंक, प्रति स्वामित्व श्रेणी $250,000 (12 U.S.C. § 1821(a))** है, जो संकट में $100,000 से बढ़ी और Dodd-Frank ने इसे स्थायी बनाया; बीमा केवल जमाओं पर है, प्रतिभूतियों, फ़ंड, क्रिप्टो परिसंपत्तियों या सेफ़-डिपॉज़िट बॉक्स की वस्तुओं पर नहीं।

विवेकपूर्ण नियमन पूँजी नियमों, CAMELS परीक्षण और प्रवर्तन सीढ़ी पर चलता है। Dodd-Frank (2010) ने **FSOC** और **Orderly Liquidation Authority** बनाया; सुदृढ़ विवेक मानकों की स्वचालित सीमा संपत्ति **$50 अरब** से शुरू हुई और **EGRRCPA (2018)** ने इसे **$250 अरब** कर दिया, बीच का क्षेत्र विवेकाधीन रहा। **Volcker Rule, Dodd-Frank § 619, 12 U.S.C. § 1851 पर संहिताबद्ध**, बैंकिंग संस्थाओं के स्व-खाता व्यापार और covered fund के स्वामित्व/प्रायोजन पर रोक लगाता है, बाज़ार-निर्माण, हेजिंग व अंडरराइटिंग में छूट के साथ, और 2018 से **$10 अरब या कम** संपत्ति वाले सामुदायिक बैंकों को पूर्ण छूट है।

आचरण नियमन मुख्यतः **CFPB** (Title X, 12 U.S.C. §§ 5301 आगे) के पास है, जो TILA, ECOA, FDCPA, EFTA लागू करता है और **§ 1031 (12 U.S.C. § 5531)** के तहत अनुचित, भ्रामक या दुरुपयोगपूर्ण कृत्यों पर रोक लगाता है। सबके ऊपर **Bank Secrecy Act, 31 U.S.C. §§ 5311 आगे** है, FinCEN के प्रवर्तन में: नकद **$10,000 से अधिक** के लेनदेन की रिपोर्ट (CTR), संदिग्ध गतिविधि रिपोर्ट (SAR) जिसमें सूचित करना वर्जित है, साथ ही ग्राहक पहचान व लाभार्थी स्वामी की जाँच।

**कैलिफ़ोर्निया परत।** 2020 में AB 1864 ने पुराने DBO को **DFPI** बनाया और **California Consumer Financial Protection Law (Fin. Code §§ 90000 आगे), 1 जनवरी 2021 से प्रभावी**, लागू किया — एक 'कैलिफ़ोर्निया CFPB' जो राज्य-स्तरीय दुरुपयोग प्रतिबंध तथा पंजीकरण व प्रवर्तन उपकरण पहले से बाहर रही उपभोक्ता वित्तीय सेवाओं तक बढ़ाता है, जबकि चार्टर्ड बैंकों का विवेक पर्यवेक्षण और पुरानी लाइसेंस व्यवस्थाएँ (धन हस्तांतरण, California Financing Law) समानांतर चलती रहती हैं।

> व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं। (प्रारम्भिक अनुवाद, समीक्षा अपेक्षित)
