# 医疗与公共卫生法备考核心：EMTALA、HIPAA、ACA 与加州规则

> 个人学习笔记，梳理美国急诊救治义务、健康信息隐私、平价医疗法案的合宪性与医疗支付反欺诈规则，并附加州对应制度，供备考与实务入门。不构成法律建议。

## 中文主文

### 一、先定框架：医疗法考的不是医学，是四种法律关系

美国医疗法散在很多法典里，备考时先把问题归位，答题就不会跑偏。第一是救治义务：病人已经到了急诊门口，医院能不能以没钱、没保险为由把人推走，这由 EMTALA 管。第二是信息关系：诊疗中产生的健康信息谁能看、谁能用、病人自己能不能调取，这由 HIPAA 隐私规则打底，再叠加州法。第三是覆盖与筹资：谁必须买保险、联邦能不能逼各州扩围 Medicaid，这由《平价医疗法案》（Affordable Care Act, ACA）与联邦最高法院在 NFIB 案中的判决划界。第四是支付诚信：医生把病人转给自己有利益关系的机构、或者收钱换转诊，Stark 法与联邦反回扣法用两套完全不同的责任逻辑来管。把这四条线分开，是本篇的起点。

### 二、EMTALA：到了急诊，先筛查、先稳定，再谈其他

《紧急医疗救治与积极分娩法》（Emergency Medical Treatment and Labor Act, EMTALA），条文在 42 U.S.C. § 1395dd。它本来是为制止医院「甩病人」（patient dumping）而立的：上世纪八十年代，一些医院以无力支付为由拒绝或草草转走急症患者，国会于是把救治义务写进参加联邦医疗保险（Medicare）的条件里。适用范围须记准：EMTALA 只适用于参加 Medicare 的医院的急诊部门，并不是对全美一切诊所、一切医疗机构的普遍救治命令；但实务中因为绝大多数医院都参加 Medicare，它的覆盖面非常广。

义务分三步。第一步是医学筛查检查（medical screening examination, MSE）：任何人来到急诊部门并请求检查或治疗，医院必须提供适当的筛查，由合格医务人员判断是否存在紧急医疗状况（emergency medical condition）。筛查的标准是同等对待——同一主诉的病人走同一套筛查流程，不能因保险状态、支付能力或国籍而给自费病人做一套、给无保险者做另一套。考试里常见的陷阱是把登记、验保险放在筛查之前拖延筛查，这正是 EMTALA 要禁止的。

第二步是稳定化义务：筛查发现紧急医疗状况的，医院必须在自身能力（capability）与容量（capacity）范围内提供使状况稳定（stabilize）的治疗，或者按法定条件转院。稳定并不等于治愈，而是说按医学合理判断，转运途中状况不会实质恶化。对临产者，法条另有分娩与胎盘娩出等具体要求，答题点到即可。

第三步是适当转院（appropriate transfer）的条件：未稳定的患者原则上不得转院，除非患者（或其代理人）在被告知风险后书面要求或同意，或者医生书面证明转运的医学收益大于风险；同时还要满足接收医院同意接收且有空间与人员、病历等记录随转、转运使用合格人员与设备等要求。违反 EMTALA 的后果包括民事罚款与被排除出 Medicare，患者个人也可就人身损害提起民事诉讼。注意它的定位：EMTALA 保证的是筛查与稳定的底线，不创设联邦层面的医疗事故标准，诊断对错本身仍主要由州医疗过失法判断。

### 三、HIPAA 隐私规则：PHI、最小必要与个人权利

《健康保险携带与责任法案》（HIPAA）本身范围很广，备考核心是其行政简化部分下由卫生与公众服务部（HHS）制定的隐私规则（Privacy Rule），见 45 CFR Part 164，其中 Subpart E（§ 164.500 起）是隐私规则主体。它约束的是覆盖实体（covered entities）——健康计划、医疗信息交换中心与使用电子方式传输健康信息的医疗提供者——及其业务伙伴（business associates）。

核心概念是受保护健康信息（protected health information, PHI）：与个人健康、诊疗或支付有关、能够识别个人身份的信息，纸质、口头与电子形态都在内；已去标识化（de-identified）并符合规则方法的信息则不再是 PHI。使用与披露的总原则是许可制：除规则允许或要求的情形（如为治疗、支付与医疗运营，即 treatment, payment, health care operations，以及法律要求、公共卫生等列明例外）外，使用或披露 PHI 须取得个人书面授权（authorization）。

两个高频考点要分清。其一是最小必要（minimum necessary）：覆盖实体为支付、运营等目的使用、披露或请求 PHI 时，必须作合理努力，把范围限于实现目的所必需的最小量。但这条有例外——为治疗目的的披露、向个人本人的披露、依个人授权的披露、法律要求的披露等，不适用最小必要标准，考试常拿「医生为会诊把全部病历发给接诊医生违反最小必要」来设陷阱，答案是不违反，因为治疗披露被豁免。其二是个人权利：个人有权访问（right of access）并取得自己 PHI 的副本，有权请求更正，有权获得披露记录说明，并有权要求对某些披露作限制；提供者原则上应在三十日内答复访问请求。这些是联邦底线：州法对患者更有利、更严格保护隐私的，不被 HIPAA 优先适用所排除，备考时要习惯「联邦底线加州法叠加」的双层结构。HIPAA 本身不创设私人诉权，这一点也常考——患者投诉走 HHS 民权办公室，民事与刑事罚则由政府执行，患者要索赔通常得另找州法依据。

### 四、ACA 与 NFIB v. Sebelius：税收权救了个人强制，支出权被划了线

《平价医疗法案》条文起点在 42 U.S.C. § 18001 起，2010 年通过，核心机制包括个人强制参保（individual mandate）、保险交易所、保费补贴与 Medicaid 扩张。它的合宪性在 National Federation of Independent Business v. Sebelius, 567 U.S. 519 (2012) 中被系统检验，结论要拆开记。

个人强制部分：首席大法官 Roberts 的意见认定，按商业条款（Commerce Clause）国会不能强迫不从事商业活动的人去购买保险——强制创造商业活动超出了规制既有商业活动的范围；必要与适当条款也不能补上这一缺口。但同一条文可被解释为一项税：未参保者向国税局缴纳的款项按金额、征收方式与功能实质就是税收，因此个人强制以国会税收权（Taxing Power）为依据得以维持。考试读法是「换个权力来源救活同一条文」，理由更换本身是考点。其后国会于 2017 年把该笔款项金额降为零，强制的实际约束随之消失，但 2012 年判决的权力分析仍是标准教材。此后 Texas v. California (2021) 又以原告缺乏起诉资格驳回了针对零金额强制的新挑战，ACA 整体存续。

Medicaid 扩张部分结论相反：ACA 原设计要求各州把 Medicaid 扩至联邦贫困线一定比例以下的人群，否则可能失去全部既有 Medicaid 拨款。法院认定这已不是附条件拨款的引导，而是胁迫（coercion）——既有拨款占州预算比重过大，州实际上没有拒绝的余地，这超出了国会支出权（Spending Power）的限度。救济方式也值得记：不是把 ACA 推倒，而是切除胁迫性的执行手段，扩张从此成为各州可自愿选择参加的项目。这与 South Dakota v. Dole 确立的「条件须与项目相关且不得胁迫」的框架一脉相承。NFIB 一案因此同时给出两条线：对个人的规制先找对权力来源，对各州的拨款条件不得以撤销全部既有资金相胁迫。

### 五、Stark 法与反回扣法：一对最容易混的支付诚信规则

医生转诊涉及两部联邦法，责任逻辑正好相反，并排记最有效。

Stark 法，即医生自我转诊法，见 42 U.S.C. § 1395nn。规则是：医生（及其直系家庭成员）与某实体存在财务关系时，不得把 Medicare（及 Medicaid 相关）患者转诊至该实体接受指定的健康服务（designated health services, DHS，如临床检验、影像、物理治疗、住院服务等），该实体也不得就此向 Medicare 申报付款，除非落入法定例外（如诊所内辅助服务、整体薪酬安排等例外，且须逐项满足例外的全部要件）。它的关键特征是严格责任（strict liability）：不需要证明医生有欺诈或牟利的故意，财务关系加转诊加申报，违规即成立，后果是拒付、退款与民事罚款。正因为无故意要件，实务合规全靠事前把安排塞进某个例外的四角之内。

联邦反回扣法（Anti-Kickback Statute, AKS），见 42 U.S.C. § 1320a-7b(b)。规则是：任何人不得明知而故意（knowingly and willfully）提供、支付、索取或收受任何报酬（remuneration），以诱导把由联邦医疗项目（Medicare、Medicaid 等）支付的物品或服务的转诊、购买或安排作为交换。它是刑事法，带故意要件，报酬可以是现金以外的任何有价值之物，司法实践中还有「一个目的」检验——只要诱导转诊是报酬的目的之一，即便同时有正当目的，也可能落入法网。法规另设若干安全港（safe harbors，见 42 CFR § 1001.952），安排完全符合安全港要件的受保护，但不符合安全港不等于自动违法，要回到故意与诱导的构成要件判断。

对照表记法：Stark 管自我转诊、民事行政、严格责任、先查例外；AKS 管向他人支付报酬换转诊、刑事、须故意、先查安全港与诱导目的。再往外一层，两者常与《虚假申报法》（False Claims Act, 31 U.S.C. § 3729 起）联动——违反 Stark 或 AKS 而申报的款项可被主张为虚假申报，这条联动线点到为止即可。州层还有各州自己的自我转诊与回扣禁令及执业伦理规则，联邦合规过关不等于州层过关。

### 六、加州层：CMIA、Knox-Keene 与 Medi-Cal

加州有三件须单独记的制度。第一是《医疗信息保密法》（Confidentiality of Medical Information Act, CMIA），见 California Civil Code § 56 起（§ 56.10 为核心披露禁令）。它比 HIPAA 覆盖面更宽：加州的医疗提供者、健康计划与承包商原则上不得披露可识别个人的医疗信息，除非患者书面授权或落入法定的强制、许可披露情形；患者对违规披露享有私人诉权与法定赔偿路径，这正好补上 HIPAA 无私人诉权的缺口。考试与实务都要双查：同一份病历的披露，先过 HIPAA，再过 CMIA，取更严者为准的思路不会错。

第二是 Knox-Keene 法，即《Knox-Keene 医疗服务计划法》（Knox-Keene Health Care Service Plan Act），见 California Health and Safety Code § 1340 起。它是加州对健康服务计划（health care service plan，实务中即 HMO 型计划）的许可与监管法，由加州管理式医疗部（Department of Managed Health Care）执行，内容覆盖计划许可、财务偿付能力、网络与服务可及性、参保人申诉与独立医疗审查等。区分点是：加州的保险型产品由保险部按《保险法典》监管，Knox-Keene 型计划则走这部法，两条监管线不要混。

第三是 Medi-Cal：它就是加州的 Medicaid，由加州医疗保健服务部（Department of Health Care Services）管理，联邦出资、州执行的联合结构不变，只是名称、州内资格细则与管理式护理安排按加州版本运行。NFIB 案之后 Medicaid 扩张是州的选择，加州选择了扩张，Medi-Cal 覆盖面随之扩大，这条事实常被用来考「扩张自愿化」的落地效果。

### 参考依据

Emergency Medical Treatment and Labor Act, 42 U.S.C. § 1395dd；HIPAA Privacy Rule, 45 CFR Part 164（尤其 Subpart E）；Affordable Care Act, 42 U.S.C. § 18001 起；National Federation of Independent Business v. Sebelius, 567 U.S. 519 (2012)；Stark Law, 42 U.S.C. § 1395nn；Anti-Kickback Statute, 42 U.S.C. § 1320a-7b(b) 及安全港 42 CFR § 1001.952；False Claims Act, 31 U.S.C. § 3729 起；California Civil Code § 56 起（CMIA）；California Health and Safety Code § 1340 起（Knox-Keene Act）。

*声明：个人学习笔记，不构成法律、税务或医疗建议。文中法条、案例与监管规则以官方公布文本为准，具体案件请咨询执业律师。*

---

## English

- **EMTALA.** Under 42 U.S.C. § 1395dd, a hospital with an emergency department that participates in Medicare must give anyone who comes to that department an appropriate medical screening examination, stabilize any emergency medical condition within its capability, and transfer an unstabilized patient only under the statutory conditions for an appropriate transfer. It is an anti-dumping floor, not a federal malpractice code.
- **HIPAA.** The Privacy Rule at 45 CFR Part 164 governs protected health information (PHI) held by covered entities. Uses and disclosures generally need authorization unless the Rule permits them, as for treatment, payment, and health care operations. The minimum necessary standard limits many uses and requests, but it does not apply to treatment disclosures. Individuals hold a right of access to their own PHI. HIPAA creates no private right of action.
- **ACA and NFIB.** In NFIB v. Sebelius, 567 U.S. 519 (2012), the individual mandate in the Affordable Care Act (42 U.S.C. § 18001 et seq.) failed under the Commerce Clause but survived as a tax. The Medicaid expansion could not be enforced by threatening to withdraw all existing Medicaid funds; that crossed the Spending Power line from inducement into coercion, so expansion became a genuine state choice.
- **Stark versus Anti-Kickback.** The Stark Law, 42 U.S.C. § 1395nn, bars physician self-referral for designated health services where a financial relationship exists, unless an exception is fully met; it is a strict-liability, civil payment rule with no intent element. The Anti-Kickback Statute, 42 U.S.C. § 1320a-7b(b), is criminal and requires knowing and willful conduct: remuneration offered or paid to induce referrals payable by a federal health care program. Safe harbors protect arrangements that fit them exactly.
- **California.** The Confidentiality of Medical Information Act (Civil Code § 56 et seq.) is broader than HIPAA in key respects and gives patients a private remedy. The Knox-Keene Act (Health and Safety Code § 1340 et seq.) licenses and regulates health care service plans, the HMO side of California managed care. Medi-Cal is simply California's name for its joint federal-state Medicaid program, and California chose to adopt the post-NFIB expansion.

*Personal study notes; not legal, tax, or medical advice.*

## Español

- **EMTALA.** Según 42 U.S.C. § 1395dd, todo hospital que participe en Medicare y tenga servicio de urgencias debe practicar a quien llegue un examen de detección médica (medical screening examination), estabilizar cualquier condición médica de emergencia dentro de su capacidad y trasladar a un paciente no estabilizado solo en las condiciones legales de un traslado apropiado. Es un piso contra el rechazo de pacientes, no un código federal de mala praxis.
- **HIPAA.** La Regla de Privacidad, 45 CFR Part 164, regula la información de salud protegida (PHI) en poder de las entidades cubiertas. Su uso y divulgación exigen en general autorización, salvo los supuestos permitidos, como tratamiento, pago y operaciones asistenciales. El estándar de mínimo necesario limita muchos usos, pero no se aplica a las divulgaciones para tratamiento. La persona tiene derecho de acceso a su propia PHI. HIPAA no crea acción privada.
- **ACA y NFIB.** En NFIB v. Sebelius, 567 U.S. 519 (2012), el mandato individual de la Ley de Cuidado Asequible (42 U.S.C. § 18001 y ss.) no se sostuvo por la cláusula de comercio, pero sí como impuesto. La expansión de Medicaid no podía imponerse amenazando con retirar todos los fondos existentes de Medicaid: eso convertía el incentivo en coerción bajo el poder de gasto, y la expansión pasó a ser una opción real de cada estado.
- **Stark frente a Anti-Kickback.** La Ley Stark, 42 U.S.C. § 1395nn, prohíbe la autorreferencia médica a servicios de salud designados cuando existe una relación financiera, salvo que se cumpla por completo una excepción; es una regla civil de pago, de responsabilidad objetiva, sin elemento de intención. La Ley Anti-Kickback, 42 U.S.C. § 1320a-7b(b), es penal y exige conducta consciente y voluntaria: ofrecer o pagar remuneración para inducir referencias pagaderas por un programa federal de salud. Los puertos seguros (safe harbors) protegen los arreglos que encajan exactamente en ellos.
- **California.** La Ley de Confidencialidad de la Información Médica (CMIA, Civil Code § 56 y ss.) es en puntos clave más protectora que HIPAA y otorga al paciente una vía privada de reparación. La Ley Knox-Keene (Health and Safety Code § 1340 y ss.) licencia y regula los planes de servicios de salud, el lado HMO de la atención administrada californiana. Medi-Cal es simplemente el nombre californiano de su programa Medicaid, conjunto federal y estatal, y California optó por adoptar la expansión posterior a NFIB.

*Notas personales de estudio; no constituye asesoría legal, fiscal ni médica.*

## 한국어（初译待校）

- **EMTALA.** 42 U.S.C. § 1395dd에 따라 Medicare에 참여하고 응급실이 있는 병원은 찾아온 모든 사람에게 적절한 의학적 선별검사(medical screening examination)를 해야 하고, 응급 의료 상태를 병원 능력 안에서 안정시켜야 하며, 안정되지 않은 환자는 법이 정한 적절한 전원 조건을 갖출 때만 옮길 수 있습니다. 이는 환자 거부를 막는 최저선이지 연방 의료과실법이 아닙니다.
- **HIPAA.** 45 CFR Part 164의 프라이버시 규칙은 적용 대상 기관이 보유한 보호 대상 건강정보(PHI)를 규율합니다. 사용과 공개는 원칙적으로 본인 승인이 필요하고, 치료·지불·의료 운영 등 규칙이 허용하는 경우는 예외입니다. 최소 필요(minimum necessary) 기준은 많은 사용을 제한하지만 치료 목적 공개에는 적용되지 않습니다. 본인에게는 자기 PHI에 접근할 권리가 있습니다. 다만 HIPAA 자체는 사적 소송권을 만들지 않습니다.
- **ACA와 NFIB.** NFIB v. Sebelius, 567 U.S. 519 (2012)에서 대법원은 건강보험개혁법(42 U.S.C. § 18001 이하)의 개인 의무가입을 통상조항으로는 유지할 수 없지만 세금으로는 유지할 수 있다고 했습니다. Medicaid 확대는 기존 Medicaid 기금 전부를 끊겠다고 위협하는 방식으로는 강제할 수 없습니다. 지출권한이 인정하는 유인을 넘어 강제가 되기 때문이며, 확대는 주의 진정한 선택이 되었습니다.
- **Stark와 반리베이트법의 대비.** Stark법(42 U.S.C. § 1395nn)은 금전 관계가 있는 의사의 지정 의료서비스 자기 의뢰를 금지하고, 예외를 전부 충족해야만 허용됩니다. 의도를 묻지 않는 무과실에 가까운 민사·지불 규칙입니다. 반면 연방 반리베이트법(42 U.S.C. § 1320a-7b(b))은 형사법으로, 연방 의료 프로그램이 지불하는 의뢰를 유도하려고 알면서 고의로 보수를 주고받는 행위를 처벌합니다. 안전항(safe harbor)에 정확히 맞는 arrangement는 보호받습니다.
- **캘리포니아.** 의료정보기밀법(CMIA, Civil Code § 56 이하)은 핵심 부분에서 HIPAA보다 넓게 환자를 보호하고 환자에게 사적 구제 길을 줍니다. Knox-Keene법(Health and Safety Code § 1340 이하)은 건강서비스플랜, 즉 HMO 쪽 관리의료를 허가하고 감독합니다. Medi-Cal은 캘리포니아가 자기 Medicaid 프로그램에 붙인 이름이며, 캘리포니아는 NFIB 이후의 확대를 받아들인 주입니다.

- **EMTALA 세부.** 이 법은 1980년대 병원이 지불 능력 없는 응급환자를 거부하거나 서둘러 전원하던 관행(patient dumping)을 막기 위해 나왔습니다. 선별검사는 주호소가 같으면 같은 절차로 해야 하고, 등록·보험 확인을 이유로 선별검사를 늦추는 것은 금지되는 전형적인 시험 함정입니다. 안정(stabilize)은 완치가 아니라 의학적으로 합리적인 판단상 이송 중 상태가 실질적으로 악화되지 않는 상태를 뜻합니다. 안정되지 않은 환자의 전원은 환자의 서면 요청·동의나 이송 이익이 위험보다 크다는 의사의 서면 증명, 수용 병원의 동의와 공간·인력, 기록 동반, 자격 있는 인력과 장비 같은 법정 조건을 갖춰야 합니다. 위반 시 민사 과태료와 Medicare 제외가 가능하고 환자는 인신손해 소송을 낼 수 있지만, EMTALA 자체는 연방 의료과실 기준을 만들지 않습니다.
- **HIPAA 세부.** 적용 대상은 건강보험 플랜, 의료정보 교환소, 전자 방식으로 건강정보를 전송하는 의료 제공자이며, 그 업무 파트너(business associates)도 규율됩니다. PHI는 종이·구두·전자 형태를 모두 포함하고, 규칙의 방법으로 비식별화(de-identified)된 정보는 PHI가 아닙니다. 개인에게는 접근권 외에 정정 요청권, 공개 내역 설명을 받을 권리, 일부 공개 제한 요청권이 있고, 제공자는 원칙적으로 30일 이내에 접근 요청에 답해야 합니다. 환자에게 더 유리하게 더 엄격히 보호하는 주법은 HIPAA에 의해 배제되지 않으며, 불만은 HHS 민권사무국(OCR)으로 갑니다.
- **ACA 후속.** 2017년 의회는 개인 의무가입의 미가입 금액을 0달러로 낮춰 실질적 강제는 사라졌지만 2012년 판결의 권한 분석은 그대로 남았습니다. Texas v. California (2021)은 원고의 소송 자격 부족으로 0달러가 된 의무가입에 대한 새 도전을 각하했고 ACA는 존속했습니다. Medicaid 쪽 논리는 South Dakota v. Dole의 틀—조건은 프로그램과 관련돼야 하고 강제가 되어서는 안 된다—과 한 줄기입니다.
- **Stark와 AKS 세부.** 지정 의료서비스(DHS)에는 임상검사, 영상, 물리치료, 입원서비스 등이 들어가고, 재무 관계는 의사 본인뿐 아니라 직계가족의 관계도 포함합니다. 예외는 요건 전부를 충족해야 하며, 위반 시 지급 거부·환급·민사 과태료가 따릅니다. AKS에서는 의도 판단에 「하나의 목적」 검사(one purpose test)가 쓰입니다. 유도하는 것이 보수 지급 목적 중 하나이기만 해도 성립할 수 있고, remuneration은 현금 외의 가치 있는 모든 것을 포함합니다. 안전항에 맞지 않는다고 자동으로 위법이 되는 것은 아니며, Stark나 AKS 위반을 전제로 한 청구는 허위청구법(False Claims Act, 31 U.S.C. § 3729 이하)과 연동될 수 있습니다.
- **캘리포니아 세부.** CMIA의 핵심 금지 조항은 Civil Code § 56.10입니다. 감독 구별도 중요합니다. Knox-Keene 플랜은 관리의료부(Department of Managed Health Care)가 감독하고, 보험형 상품은 보험부(Department of Insurance)가 Insurance Code로 감독하니 두 선을 섞지 마십시오. Medi-Cal의 주무 부처는 보건의료서비스부(Department of Health Care Services)입니다.

*개인 학습 노트이며 법률·세무·의료 자문이 아닙니다.*

## Tiếng Việt（初译待校）

- **EMTALA.** Theo 42 U.S.C. § 1395dd, bệnh viện tham gia Medicare và có khoa cấp cứu phải khám sàng lọc y tế (medical screening examination) cho mọi người đến khoa, ổn định tình trạng cấp cứu trong khả năng của bệnh viện, và chỉ chuyển bệnh nhân chưa ổn định khi đáp ứng điều kiện chuyển viện phù hợp theo luật. Đây là mức sàn chống từ chối bệnh nhân, không phải luật liên bang về sai sót y khoa.
- **HIPAA.** Quy tắc Bảo mật tại 45 CFR Part 164 điều chỉnh thông tin sức khỏe được bảo vệ (PHI) do các thực thể thuộc diện điều chỉnh nắm giữ. Việc dùng và tiết lộ nhìn chung cần sự cho phép của cá nhân, trừ các trường hợp quy tắc cho phép như điều trị, thanh toán và vận hành chăm sóc sức khỏe. Tiêu chuẩn tối thiểu cần thiết (minimum necessary) giới hạn nhiều lần sử dụng, nhưng không áp dụng cho tiết lộ nhằm điều trị. Cá nhân có quyền truy cập PHI của chính mình. HIPAA không tạo quyền kiện tư nhân.
- **ACA và NFIB.** Trong NFIB v. Sebelius, 567 U.S. 519 (2012), nghĩa vụ mua bảo hiểm cá nhân của Đạo luật Chăm sóc Sức khỏe Giá phải chăng (42 U.S.C. § 18001 trở đi) không đứng vững theo Điều khoản Thương mại nhưng được giữ lại với tư cách một khoản thuế. Việc mở rộng Medicaid không thể bị ép bằng đe dọa rút toàn bộ ngân quỹ Medicaid hiện có; cách đó biến khuyến khích thành cưỡng ép theo Quyền Chi tiêu, nên mở rộng trở thành lựa chọn thực sự của từng bang.
- **Stark đối chiếu Anti-Kickback.** Luật Stark, 42 U.S.C. § 1395nn, cấm bác sĩ tự giới thiệu tới các dịch vụ y tế được chỉ định khi có quan hệ tài chính, trừ khi đáp ứng đầy đủ một ngoại lệ; đây là quy tắc thanh toán dân sự theo trách nhiệm nghiêm ngặt, không cần yếu tố cố ý. Ngược lại, Luật Chống lại quả, 42 U.S.C. § 1320a-7b(b), là luật hình sự, đòi hỏi hành vi biết rõ và cố ý: đưa hoặc nhận thù lao để xúi giục giới thiệu mà chương trình y tế liên bang phải trả tiền. Các bến an toàn (safe harbors) bảo vệ dàn xếp khớp đúng điều kiện của chúng.
- **California.** Đạo luật Bảo mật Thông tin Y tế (CMIA, Civil Code § 56 trở đi) ở nhiều điểm bảo vệ mạnh hơn HIPAA và cho bệnh nhân con đường khiếu kiện riêng. Luật Knox-Keene (Health and Safety Code § 1340 trở đi) cấp phép và quản lý các chương trình dịch vụ chăm sóc sức khỏe, tức phía HMO của chăm sóc có quản lý ở California. Medi-Cal đơn giản là tên California đặt cho chương trình Medicaid chung liên bang-bang của mình, và California đã chọn tham gia mở rộng sau NFIB.

- **Chi tiết EMTALA.** Đạo luật này ra đời để chặn thực trạng những năm 1980, khi bệnh viện từ chối hoặc vội vã chuyển đi bệnh nhân cấp cứu không có khả năng chi trả (patient dumping). Khám sàng lọc phải theo cùng một quy trình cho cùng một triệu chứng trình bày, và việc lấy đăng ký hay kiểm tra bảo hiểm làm lý do trì hoãn sàng lọc là cái bẫy kinh điển trong thi cử bị EMTALA cấm. Ổn định (stabilize) không có nghĩa là chữa khỏi, mà là theo phán đoán y khoa hợp lý, tình trạng sẽ không xấu đi đáng kể trong quá trình vận chuyển. Việc chuyển bệnh nhân chưa ổn định phải đáp ứng điều kiện luật định: bệnh nhân yêu cầu hoặc đồng ý bằng văn bản sau khi được thông báo rủi ro, hoặc bác sĩ chứng nhận bằng văn bản lợi ích y khoa lớn hơn rủi ro; bệnh viện tiếp nhận đồng ý và có chỗ cùng nhân lực; hồ sơ đi kèm; vận chuyển bằng nhân lực và thiết bị đủ chuẩn. Vi phạm có thể dẫn tới phạt tiền dân sự và bị loại khỏi Medicare, bệnh nhân cũng có thể kiện đòi bồi thường thiệt hại cá nhân, nhưng bản thân EMTALA không tạo ra tiêu chuẩn liên bang về sai sót y khoa.
- **Chi tiết HIPAA.** Thực thể thuộc diện điều chỉnh gồm chương trình y tế, trung tâm trao đổi thông tin y tế và nhà cung cấp dịch vụ y tế truyền thông tin sức khỏe bằng phương thức điện tử, và các đối tác kinh doanh (business associates) của chúng cũng bị điều chỉnh. PHI bao gồm cả dạng giấy, lời nói và điện tử; thông tin đã khử định danh (de-identified) theo phương pháp của quy tắc thì không còn là PHI. Ngoài quyền truy cập, cá nhân còn có quyền yêu cầu đính chính, quyền nhận bản kê khai các lần tiết lộ, và quyền yêu cầu hạn chế một số tiết lộ; nhà cung cấp về nguyên tắc phải trả lời yêu cầu truy cập trong ba mươi ngày. Luật bang bảo vệ quyền riêng tư nghiêm ngặt hơn và có lợi hơn cho bệnh nhân không bị HIPAA loại trừ, và khiếu nại đi tới Văn phòng Dân quyền của HHS (OCR).
- **Diễn biến sau ACA.** Năm 2017 Quốc hội hạ khoản tiền phạt không mua bảo hiểm xuống 0, khiến tính cưỡng chế thực tế của nghĩa vụ cá nhân biến mất, nhưng phân tích về quyền lực trong phán quyết 2012 vẫn còn nguyên. Texas v. California (2021) bác thách thức mới nhắm vào nghĩa vụ đã bằng 0 vì nguyên đơn thiếu tư cách kiện, và ACA tiếp tục tồn tại. Lý luận phía Medicaid nối tiếp khuôn khổ South Dakota v. Dole: điều kiện kèm theo chi tiêu phải liên quan tới chương trình và không được thành cưỡng ép.
- **Chi tiết Stark và AKS.** Dịch vụ y tế được chỉ định (DHS) gồm xét nghiệm lâm sàng, chẩn đoán hình ảnh, vật lý trị liệu, dịch vụ nội trú, và quan hệ tài chính tính cả quan hệ của thành viên gia đình trực hệ của bác sĩ. Ngoại lệ phải đáp ứng mọi yếu tố của nó; vi phạm dẫn tới từ chối thanh toán, hoàn tiền và phạt tiền dân sự. Phía AKS, thực tiễn xét nghiệm «một mục đích» (one purpose test): chỉ cần xúi giục giới thiệu là một trong các mục đích của khoản thù lao cũng có thể cấu thành vi phạm, và remuneration gồm mọi thứ có giá trị ngoài tiền mặt. Không khớp với bến an toàn không có nghĩa là tự động vi phạm, và các khoản thanh toán dựa trên vi phạm Stark hoặc AKS có thể bị coi là khai gian theo Đạo luật Khiếu nại Gian dối (False Claims Act, 31 U.S.C. § 3729 trở đi).
- **Chi tiết California.** Điều cấm cốt lõi của CMIA là Civil Code § 56.10. Cần phân biệt cơ quan quản lý: các chương trình Knox-Keene do Sở Chăm sóc Sức khỏe Có quản lý (Department of Managed Health Care) giám sát, còn sản phẩm dạng bảo hiểm do Sở Bảo hiểm (Department of Insurance) quản theo Bộ luật Bảo hiểm — đừng lẫn hai đường này. Cơ quan điều hành Medi-Cal là Sở Dịch vụ Chăm sóc Sức khỏe (Department of Health Care Services).

*Ghi chú học tập cá nhân, không phải tư vấn pháp lý, thuế hay y tế.*

## हिन्दी（初译待校）

- **EMTALA.** 42 U.S.C. § 1395dd के तहत Medicare में भाग लेने वाले और आपात विभाग रखने वाले अस्पताल को वहाँ आने वाले हर व्यक्ति की उचित चिकित्सीय जाँच (medical screening examination) करनी होती है, आपात चिकित्सीय स्थिति को अपनी क्षमता के भीतर स्थिर करना होता है, और अस्थिर मरीज़ को केवल कानून की उचित स्थानांतरण शर्तों पर ही भेजा जा सकता है। यह मरीज़ को ठुकराने के विरुद्ध न्यूनतम सुरक्षा है, संघीय चिकित्सा-लापरवाही संहिता नहीं।
- **HIPAA.** 45 CFR Part 164 का Privacy Rule आच्छादित संस्थाओं के पास मौजूद संरक्षित स्वास्थ्य-सूचना (PHI) को नियंत्रित करता है। इसका उपयोग और प्रकटीकरण सामान्यतः व्यक्ति के प्राधिकरण से होता है, सिवाय नियम द्वारा अनुमत स्थितियों के — जैसे उपचार, भुगतान और स्वास्थ्य-देखभाल संचालन। न्यूनतम आवश्यक (minimum necessary) मानदंड कई उपयोगों को सीमित करता है, किंतु उपचार के लिए किए गए प्रकटीकरण पर लागू नहीं होता। व्यक्ति को अपनी PHI तक पहुँच का अधिकार है। HIPAA स्वयं कोई निजी वाद-अधिकार नहीं बनाता।
- **ACA और NFIB.** NFIB v. Sebelius, 567 U.S. 519 (2012) में सर्वोच्च न्यायालय ने Affordable Care Act (42 U.S.C. § 18001 आगे) के व्यक्तिगत अधिदेश को वाणिज्य खंड के तहत नहीं, किंतु कर के रूप में बनाए रखा। Medicaid विस्तार को मौजूदा समस्त Medicaid निधि रोकने की धमकी से लागू नहीं किया जा सकता था; यह व्यय-शक्ति की प्रोत्साहन सीमा पार करके बाध्यता बन जाता, इसलिए विस्तार राज्यों का वास्तविक विकल्प बन गया।
- **Stark बनाम Anti-Kickback.** Stark Law, 42 U.S.C. § 1395nn, वित्तीय संबंध होने पर चिकित्सक द्वारा निर्दिष्ट स्वास्थ्य-सेवाओं के लिए स्व-रेफ़रल रोकता है, जब तक कोई अपवाद पूरी तरह पूरा न हो; यह आशय-रहित, कठोर दायित्व वाली नागरिक भुगतान-नियम व्यवस्था है। इसके विपरीत Anti-Kickback Statute, 42 U.S.C. § 1320a-7b(b), आपराधिक है और जानबूझकर व स्वेच्छा से किया गया आचरण माँगता है: संघीय स्वास्थ्य कार्यक्रम द्वारा देय रेफ़रल प्रेरित करने के लिए पारिश्रमिक देना या लेना। Safe harbor में ठीक बैठने वाली व्यवस्थाएँ संरक्षित हैं।
- **California.** Confidentiality of Medical Information Act (CMIA, Civil Code § 56 आगे) कई बिंदुओं पर HIPAA से अधिक व्यापक सुरक्षा देता है और मरीज़ को निजी उपचार का रास्ता देता है। Knox-Keene Act (Health and Safety Code § 1340 आगे) स्वास्थ्य-सेवा योजनाओं, अर्थात California प्रबंधित देखभाल के HMO पक्ष, को लाइसेंस और नियंत्रित करता है। Medi-Cal California के अपने Medicaid कार्यक्रम का ही नाम है, और California ने NFIB के बाद का विस्तार अपनाया।

- **EMTALA विवरण.** यह कानून 1980 के दशक की उस प्रथा को रोकने के लिए आया जिसमें अस्पताल भुगतान-असमर्थ आपात मरीज़ों को ठुकरा देते या जल्दबाज़ी में स्थानांतरित कर देते थे (patient dumping)। Screening एक ही शिकायत पर एक ही प्रक्रिया से होनी चाहिए, और पंजीकरण या बीमा-जाँच के बहाने screening में देरी करना EMTALA द्वारा निषिद्ध क्लासिक परीक्षा-जाल है। स्थिर करना (stabilize) का अर्थ इलाज पूरा होना नहीं, बल्कि यह है कि चिकित्सकीय युक्तियुक्त निर्णय से स्थानांतरण के दौरान स्थिति सार्थक रूप से नहीं बिगड़ेगी। अस्थिर मरीज़ का स्थानांतरण वैधानिक शर्तों पर ही होगा: जोखिम बताए जाने के बाद मरीज़ का लिखित अनुरोध या सहमति, या चिकित्सक का लिखित प्रमाणन कि चिकित्सकीय लाभ जोखिम से अधिक है; प्राप्त करने वाले अस्पताल की सहमति तथा स्थान व कार्मिक; रिकॉर्ड साथ जाना; योग्य कार्मिक व उपकरण से परिवहन। उल्लंघन पर नागरिक जुर्माना और Medicare से निष्कासन संभव है, और मरीज़ व्यक्तिगत क्षति का मुकदमा कर सकता है, किंतु EMTALA स्वयं संघीय चिकित्सा-लापरवाही मानक नहीं बनाता।
- **HIPAA विवरण.** Covered entities में स्वास्थ्य योजनाएँ, health care clearinghouse और इलेक्ट्रॉनिक रूप से स्वास्थ्य-सूचना भेजने वाले प्रदाता आते हैं, और उनके business associates भी नियंत्रित होते हैं। PHI काग़ज़ी, मौखिक और इलेक्ट्रॉनिक तीनों रूपों में होती है; नियम की विधि से de-identified की गई सूचना PHI नहीं रहती। पहुँच के अधिकार के अलावा व्यक्ति को संशोधन का अनुरोध करने, प्रकटीकरणों का हिसाब (accounting) पाने और कुछ प्रकटीकरणों पर रोक का अनुरोध करने के अधिकार हैं; प्रदाता को सिद्धांततः तीस दिनों के भीतर पहुँच-अनुरोध का उत्तर देना होता है। मरीज़ के लिए अधिक अनुकूल, अधिक कठोर राज्य कानून HIPAA से बाहर नहीं होते, और शिकायतें HHS के Office for Civil Rights (OCR) के पास जाती हैं।
- **ACA के बाद.** 2017 में कांग्रेस ने व्यक्तिगत अधिदेश की राशि शून्य कर दी, जिससे उसकी व्यावहारिक बाध्यता समाप्त हो गई, किंतु 2012 निर्णय का शक्ति-विश्लेषण बना रहा। Texas v. California (2021) ने शून्य-राशि वाले अधिदेश के विरुद्ध नई चुनौती को वादी की standing की कमी से खारिज किया और ACA बचा रहा। Medicaid पक्ष का तर्क South Dakota v. Dole के ढाँचे से जुड़ता है — खर्च की शर्तें कार्यक्रम से संबंधित हों और बाध्यता न बनें।
- **Stark और AKS विवरण.** Designated health services (DHS) में नैदानिक प्रयोगशाला, imaging, physical therapy, inpatient services आदि आते हैं, और वित्तीय संबंध में चिकित्सक के तत्काल परिवार के सदस्यों का संबंध भी गिना जाता है। अपवाद की हर शर्त पूरी होनी चाहिए; उल्लंघन पर भुगतान अस्वीकृति, वापसी और नागरिक जुर्माना लगता है। AKS पक्ष में 'one purpose' परीक्षण चलता है: यदि रेफ़रल प्रेरित करना पारिश्रमिक के उद्देश्यों में से एक भी हो तो उल्लंघन बन सकता है, और remuneration में नकदी के अलावा हर मूल्यवान वस्तु आती है। Safe harbor में न बैठना स्वतः उल्लंघन नहीं है, और Stark या AKS उल्लंघन पर आधारित दावे False Claims Act, 31 U.S.C. § 3729 आगे से जुड़ सकते हैं।
- **California विवरण.** CMIA का मूल निषेध-प्रावधान Civil Code § 56.10 है। नियामक भेद भी महत्वपूर्ण है: Knox-Keene योजनाओं की देखरेख Department of Managed Health Care करता है, जबकि बीमा-प्रकार के उत्पाद Department of Insurance के अंतर्गत Insurance Code से नियंत्रित होते हैं — दोनों रेखाएँ न मिलाएँ। Medi-Cal का संचालन Department of Health Care Services करता है।

*व्यक्तिगत अध्ययन नोट; कानूनी, कर या चिकित्सा सलाह नहीं।*
