# 政府合同与联邦采购备考核心：FAR、合同争议法与竞标抗议

> 个人学习笔记，不构成法律建议。联邦采购这一块考点集中在三件事：合同怎么授予（FAR 与竞争规则）、授予有问题找谁抗议（GAO 或联邦索赔法院）、履行出了争议怎么索赔（Contract Disputes Act）。三条线各有自己的期限与门槛，备考时最忌混用——GAO 的 10 天、索赔的 90 天与 12 个月，答错一个整个题就偏了。本文数字与期限凡现行法条有调整空间的，均注明以现行法条为准。

## 中文主文

### 一、骨架：FAR 与竞争规则

联邦政府采购的基本法框架由两部制定法加一部规章组成：武装力量采购走 10 U.S.C. 的采购编，非军事机构走 41 U.S.C. 第 33 章等规定；统一操作规则是 **Federal Acquisition Regulation（联邦采购条例，FAR），编在 48 C.F.R. Chapter 1**，由国防部、总务管理局（GSA）与 NASA 联合发布，各机构可以另发补充规章（如国防部的 DFARS，48 C.F.R. Chapter 2）。

FAR 的部（Part）号是备考地图：Part 6 讲竞争要求，Part 12 讲商业产品的简化采购，Part 14 是密封投标（sealed bidding），Part 15 是谈判采购（contracting by negotiation，绝大多数复杂采购走这条），Part 19 是小企业预留，Part 43 是合同修改，Part 49 是终止，Part 52 是标准合同条款的汇集——真正的权利义务大多藏在依 Part 52 插入合同的条款里。

竞争是联邦采购的第一原则。**Competition in Contracting Act（CICA，竞争合同法）**要求机构原则上通过「完全与公开竞争」（full and open competition）授予合同，现行条文见 **41 U.S.C. § 3301**（武装力量对应 10 U.S.C. § 3201 一带，以现行法条为准）。不走完全公开竞争的，须有书面理由并获批准（FAR Part 6.3 的例外清单，如只有一家能提供、紧急需求等）。采购金额的门槛分档——微额采购限额、简化采购限额（simplified acquisition threshold）等具体美元数额由 FAR 2.101 定义且时有调整，**一律以现行 FAR 2.101 为准，不要死背旧数字**。

### 二、授标抗议（bid protest）之一：GAO 路径

对合同授予或拟授予有异议的利害关系人（interested party，即实际或潜在投标人、其经济利益受结果直接影响者），第一条路是向 **Government Accountability Office（政府问责署，GAO）** 提出竞标抗议。法律依据为 **31 U.S.C. §§ 3551–3557**（CICA 的抗议编），程序细则在 **GAO Bid Protest Regulations，4 C.F.R. Part 21**。

- **时限（4 C.F.R. § 21.2）**：这是全题最容易丢分的地方。一般规则：抗议理由在开标或提案截止前就已知的，必须在该时点前提出；其他情形下，须在抗议人知道或应当知道抗议理由之日起 **10 天内** 提出；对授标或拟授标的抗议，若已依法要求并获得 debriefing（落标说明），时限与说明会的日期挂钩计算。具体起算以现行 4 C.F.R. § 21.2 为准。
- **CICA 自动中止（automatic stay）**：依据 **31 U.S.C. § 3553(d)(4)**，若机构在法定期限内收到 GAO 的抗议通知，须暂停授标（抗议在授标前提出时）或暂停已授合同的履行（授标后抗议）。授标后情形的关键窗口是：GAO 通知须在授标后 10 天内、或 debriefing 日期后 5 天内（以较晚者为准一类的口径）送达机构——**精确的起算与送达条件以现行 § 3553(d)(4) 条文为准**。机构首长可以「紧急且令人信服的理由」（urgent and compelling reasons）书面推翻中止，但门槛高、且可以被追问。
- **裁决期限与效力**：GAO 原则上在抗议提交后 **100 天内** 作出建议性裁决（31 U.S.C. § 3554），另有 65 天的快速通道。GAO 的决定在性质上是「建议」，但机构若不采纳，须在 60 天内向 GAO 报告，实务上极少不从。

### 三、授标抗议之二：联邦索赔法院（COFC）路径

第二条路是直接到 **U.S. Court of Federal Claims（联邦索赔法院，COFC）** 起诉。管辖依据是 **28 U.S.C. § 1491(b)(1)**：对采购的征集、拟授标或授标决定有异议的利害关系人，可主张该决定违反制定法或规章、或程序有瑕疵。审查标准借用行政法：依 § 1491(b)(4)，法院按《行政程序法》的标准（5 U.S.C. § 706）审查决定是否任意、专断或滥用裁量；救济可以是禁令与宣告判决，但胜诉方通常得不到合同本身，至多重新评标或重新征集，另可获投标与提案准备费用等法定范围内的救济。

- **Blue & Gold Fleet 弃权规则**：联邦巡回上诉法院在 **Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)** 确立——对采购文件（solicitation）中表面可见的瑕疵（patent defect），投标人必须在投标或提案截止之前提出异议；等到落选后才翻出来主张，视为弃权（waived），法院不再审查。这是实务上杀伤力极大的一条，备考与实务都要先问一句：这个问题在截止前看得见吗？
- **两条路的选择**：GAO 快、便宜、自动中止有吸引力，但决定只是建议制；COFC 是正式司法审查、可获禁令，但没有 CICA 那种行政自动中止，须另外申请临时限制令或初步禁令。两条路一般不可同时就同一事项重复推进，选路本身就是策略考点。

### 四、履约争议：Contract Disputes Act（CDA）

合同授予之后、履行之中的索赔走另一套系统——**Contract Disputes Act of 1978（合同争议法，CDA），41 U.S.C. §§ 7101–7109**，适用于联邦机构的采购合同（含货物、服务、建筑等）。

- **索赔的提交**：承包商先把索赔（claim）以书面提交 **contracting officer（订约官，CO）**，主张须达「确定的金额」（sum certain）。金额较大的索赔须附承包商的诚信认证（certification），现行分界为超过 100,000 美元者须认证，条文见 41 U.S.C. § 7103 的认证条款，**以现行法条为准**。
- **CO 最终决定**：CO 在法定期限内作出最终决定（final decision）；逾期未决的，索赔可视为被拒（deemed denied），承包商即可上诉，不必无限期等下去。CO 的决定不是一纸形式，它开启上诉时钟。
- **上诉的二选一与期限（41 U.S.C. § 7104）**：承包商收到 CO 最终决定后有两条互斥的路——(1) 向机构的合同上诉委员会（agency board of contract appeals，如 ASBCA、CBCA）上诉，期限 **90 天**；(2) 直接向 COFC 起诉，期限 **12 个月**。两条期限起算与届满口径以现行 § 7104 为准。选定一条即受其程序与既判力约束（选举原则），不可两头下注。委员会或 COFC 的判决之后，还可上诉至联邦巡回上诉法院。
- **利息**：CDA 索赔的利息自 CO 收到索赔之日起算（41 U.S.C. § 7109 一带，以现行法条为准），这是谈判与结算时常被漏算的一笔。

### 五、Tucker Act 与 Little Tucker Act 的金额分界

COFC 的一般合同管辖来自 **Tucker Act，28 U.S.C. § 1491(a)(1)**：联邦对基于宪法、制定法、规章或明示/默示合同的金钱请求放弃主权豁免，COFC 有管辖权。而 **Little Tucker Act，28 U.S.C. § 1346(a)(2)**，给了联邦地区法院对同类请求（非税、非侵权的一类）的**并存管辖**，但金额上限是 **不超过 10,000 美元**。记法很简单：10,000 美元及以下，地区法院与 COFC 都能去；超过 10,000 美元，只能走 COFC。注意竞标抗议的管辖是 § 1491(b)，与 (a) 款的一般合同管辖是同一条文的不同款，不要写混。

### 六、为政府便利而终止（termination for convenience）

联邦标准合同里政府握有一项商业合同中罕见的单方权利：**为政府便利终止**（FAR Part 49；标准条款如 FAR 52.249-2，固定价格合同）。当继续履行不再符合政府利益时，政府可以全部或部分终止，承包商无需有任何违约。结算原则是**补偿已发生的、合理的履约成本，加上已完成部分的合理利润**；但**得不到预期利润**（anticipatory profits，尚未履行的部分本来能赚的钱不在补偿内），这是与普通法违约损害赔偿最大的区别。承包商须在法定期限内提交终止结算方案，逾期权利会打折。要与「因过失终止」（termination for default）分清：后者针对承包商违约，政府可追偿超额复购成本，承包商若上诉成功，不当的 default 终止可按规则转为便利终止处理。

### 七、加州一格（只作对照，不与联邦混同）

州与地方层面的采购不走 FAR，也不走 CICA 或 CDA，走加州自己的体系：州合同的竞争性招标主要见 **California Public Contract Code（加州公共合同法）** 关于州机构采购与 State Contract Act 的编章（Public Contract Code § 10100 以下一带），地方机构（市、县、学区等）的招标规则在该法关于地方机构的部分；对州或地方公共实体提金钱请求的，先行程序是 **California Government Claims Act，Gov. Code §§ 810–996.6** 的呈报索赔（claim presentation）要求，未按期呈报往往在起诉阶段被挡下。**注意三组概念不可互换**：联邦 CDA 的 90 天/12 个月 ≠ 加州呈报期限；GAO 抗议 ≠ 加州的投标抗议程序（各机构与地方各有规则）；FAR 的终止结算 ≠ 加州合同法下的救济。具体条号与期限一律以现行加州法条为准。

### 八、易错点

1. GAO 的裁决是「建议」不是终局判决；真正有拘束力的司法救济在 COFC。
2. CICA 自动中止不是「一提抗议就自动冻住一切」——它以机构在法定期限内收到 GAO 通知为条件，超期抗议触发不了。
3. 采购文件的表面瑕疵等到授标后才提，Blue & Gold Fleet 规则直接弃权处理。
4. CDA 上诉：上诉委员会 90 天、COFC 12 个月，两个数字答反是经典失分。
5. Little Tucker Act 的 10,000 美元是上限而非下限：不超过这个数地区法院才有并存管辖。
6. 便利终止赔成本与已履约部分利润，不赔预期利润。
7. 把加州 Public Contract Code 的规则套到联邦采购上，或把 CDA 期限套到加州政府索赔上——两套体系永远分开答。

### 九、来源说明

主要依据：FAR, 48 C.F.R. Chapter 1（尤其 Parts 6, 12, 14, 15, 49, 52）；Competition in Contracting Act 抗议编, 31 U.S.C. §§ 3551–3557；GAO Bid Protest Regulations, 4 C.F.R. Part 21（尤其 § 21.2 时限）；28 U.S.C. § 1491(a), (b) 与 § 1346(a)(2)；Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)；Contract Disputes Act, 41 U.S.C. §§ 7101–7109（尤其 §§ 7103, 7104, 7109）；41 U.S.C. § 3301；California Public Contract Code §§ 10100 et seq.；California Government Code §§ 810 et seq.。金额门槛与具体期限如有修订，以现行法条与 FAR 2.101 为准。

*声明：个人学习笔记，不构成法律建议。*

---

## English

**Government Contracts and Federal Procurement: FAR, the Contract Disputes Act, and Bid Protests**

Federal procurement exam questions cluster around three problems: how the contract is awarded (the FAR and competition rules), where to protest a flawed award (the GAO or the Court of Federal Claims), and how to pursue performance disputes (the Contract Disputes Act). Each track has its own deadlines, and mixing them up is the classic way to lose points.

**1. The FAR framework.** The Federal Acquisition Regulation is codified at **48 C.F.R. Chapter 1** and is issued jointly by the Department of Defense, GSA, and NASA; agencies add supplements (e.g., the DFARS at Chapter 2). Key Parts: Part 6 (competition), Part 12 (commercial products), Part 14 (sealed bidding), Part 15 (negotiated procurement), Part 49 (terminations), and Part 52 (the standard clauses actually inserted into contracts). The Competition in Contracting Act requires full and open competition, **41 U.S.C. § 3301** (see also 10 U.S.C. § 3201 for the armed forces), unless a written exception applies. Dollar thresholds (micro-purchase, simplified acquisition threshold) live in FAR 2.101 and change over time — always check the current text rather than memorizing old figures.

**2. Bid protests at the GAO.** An interested party may protest to the Government Accountability Office under **31 U.S.C. §§ 3551–3557**, with procedure in the GAO Bid Protest Regulations, **4 C.F.R. Part 21**. Timeliness under 4 C.F.R. § 21.2 is strict: defects apparent before the closing date must be protested before it; other grounds generally must be filed within **10 days** after the basis was known or should have been known, with special debriefing-based rules for award protests. The CICA automatic stay, **31 U.S.C. § 3553(d)(4)**, suspends award or performance only if the agency receives GAO's notice within the statutory window (for post-award protests, generally within 10 days after award or 5 days after the debriefing date, whichever is later — confirm the current statutory text); the agency head may override only on written findings of urgent and compelling reasons. GAO issues its recommendation generally within 100 days (§ 3554); it is formally a recommendation, although agencies almost always follow it.

**3. Bid protests at the COFC.** Alternatively, an interested party may sue in the U.S. Court of Federal Claims under **28 U.S.C. § 1491(b)(1)**. Review follows the APA standard incorporated by § 1491(b)(4) (5 U.S.C. § 706): was the decision arbitrary, capricious, or contrary to law? Under **Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)**, a patent defect in the solicitation must be challenged before the closing date or it is waived. The COFC path offers binding judicial review and injunctions but no automatic CICA stay — interim relief must be sought from the court.

**4. Performance disputes under the CDA.** Post-award claims go under the **Contract Disputes Act, 41 U.S.C. §§ 7101–7109**. The contractor submits a written claim for a sum certain to the contracting officer; claims above the statutory threshold (currently $100,000) must be certified (see § 7103). The contracting officer issues a final decision; an untimely decision is a deemed denial. Appeals under **§ 7104** are an either/or choice: to an agency board of contract appeals within **90 days**, or to the COFC within **12 months** — the two deadlines are a favorite exam trap if reversed. Interest runs from the contracting officer's receipt of the claim (§ 7109).

**5. Tucker Act vs. Little Tucker Act.** The Tucker Act, **28 U.S.C. § 1491(a)(1)**, is the general waiver of sovereign immunity for contract claims against the United States in the COFC. The Little Tucker Act, **28 U.S.C. § 1346(a)(2)**, gives district courts concurrent jurisdiction only for claims **not exceeding $10,000**; above that, the COFC is the only forum.

**6. Termination for convenience.** Under FAR Part 49 and clauses such as FAR 52.249-2, the government may terminate in whole or in part when termination is in its interest, without any contractor default. The settlement pays allowable costs incurred plus reasonable profit on work performed — but **no anticipatory profits** on the terminated portion, a sharp break from common-law breach damages. Contrast termination for default, where the government may recover excess reprocurement costs.

**7. California contrast.** State and local procurement does not use the FAR, CICA, or the CDA. State competitive bidding is governed by the **California Public Contract Code** (the State Contract Act provisions, § 10100 et seq., and the separate local-agency parts), and money claims against California public entities first require claim presentation under the **California Government Claims Act, Gov. Code §§ 810 et seq.** Keep the systems apart: the CDA's 90-day/12-month deadlines are not California deadlines, and GAO protest practice is not California bid-protest practice. Verify current California code sections and deadlines before relying on them.

**Common traps:** treating a GAO decision as binding; assuming a protest automatically stays performance regardless of when notice arrives; raising solicitation defects only after award (Blue & Gold waiver); swapping the 90-day and 12-month CDA deadlines; reading the $10,000 Little Tucker figure as a floor instead of a ceiling; expecting anticipatory profits after a convenience termination.

*Personal study notes only; not legal advice. Sources: FAR, 48 C.F.R. ch. 1; 31 U.S.C. §§ 3551–3557; 4 C.F.R. pt. 21; 28 U.S.C. §§ 1491, 1346(a)(2); 41 U.S.C. §§ 3301, 7101–7109; Blue & Gold Fleet, 492 F.3d 1308 (Fed. Cir. 2007); Cal. Pub. Contract Code § 10100 et seq.; Cal. Gov. Code § 810 et seq.*

---

## Español

**Contratos gubernamentales y adquisiciones federales: la FAR, la Contract Disputes Act y las protestas de licitación**

Las preguntas de examen sobre adquisiciones federales giran en torno a tres problemas: cómo se adjudica el contrato (la FAR y las reglas de competencia), dónde se impugna una adjudicación defectuosa (la GAO o la Court of Federal Claims) y cómo se tramitan las disputas de ejecución (la Contract Disputes Act). Cada vía tiene sus propios plazos, y confundirlos es el error clásico.

**1. El marco de la FAR.** La Federal Acquisition Regulation está codificada en el **48 C.F.R. capítulo 1**, emitida conjuntamente por el Departamento de Defensa, la GSA y la NASA, con suplementos por agencia (p. ej., DFARS). Partes clave: la Parte 6 (competencia), la 12 (productos comerciales), la 14 (licitación sellada), la 15 (contratación negociada), la 49 (terminaciones) y la 52 (las cláusulas estándar que efectivamente se insertan en el contrato). La Competition in Contracting Act exige competencia plena y abierta, **41 U.S.C. § 3301** (véase también 10 U.S.C. § 3201 para las fuerzas armadas), salvo excepción escrita. Los umbrales monetarios (microcompras, umbral de adquisición simplificada) están en FAR 2.101 y cambian con el tiempo: hay que consultar el texto vigente.

**2. Protestas ante la GAO.** Una parte interesada puede protestar ante la Government Accountability Office conforme a **31 U.S.C. §§ 3551–3557**, con procedimiento en las GAO Bid Protest Regulations, **4 C.F.R. parte 21**. La puntualidad según 4 C.F.R. § 21.2 es estricta: los defectos visibles antes de la fecha de cierre deben protestarse antes de ella; los demás motivos, por regla general, dentro de los **10 días** siguientes a conocer o deber conocer la base, con reglas especiales vinculadas a la sesión informativa (debriefing). La suspensión automática de la CICA, **31 U.S.C. § 3553(d)(4)**, suspende la adjudicación o la ejecución solo si la agencia recibe el aviso de la GAO dentro del plazo legal (en protestas posteriores a la adjudicación, en general dentro de los 10 días posteriores a la adjudicación o 5 días después de la fecha del debriefing, lo que ocurra más tarde; verifíquese el texto legal vigente); el titular de la agencia solo puede anularla con fundamentación escrita de razones urgentes y apremiantes. La GAO emite su recomendación por lo general en 100 días (§ 3554): formalmente es una recomendación, aunque las agencias casi siempre la siguen.

**3. Protestas ante la COFC.** Como alternativa, la parte interesada puede demandar ante la U.S. Court of Federal Claims según **28 U.S.C. § 1491(b)(1)**. La revisión sigue el estándar de la APA incorporado por § 1491(b)(4) (5 U.S.C. § 706): ¿fue la decisión arbitraria, caprichosa o contraria a derecho? Según **Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)**, un defecto manifiesto de la convocatoria debe impugnarse antes de la fecha de cierre o se pierde por renuncia (waiver). La vía judicial ofrece revisión vinculante y medidas cautelares, pero no la suspensión automática de la CICA: la protección provisional debe pedirse al tribunal.

**4. Disputas de ejecución bajo la CDA.** Las reclamaciones posteriores a la adjudicación se rigen por la **Contract Disputes Act, 41 U.S.C. §§ 7101–7109**. El contratista presenta una reclamación escrita por suma cierta al oficial de contratación; las reclamaciones por encima del umbral legal (actualmente 100.000 dólares) deben certificarse (véase § 7103). El oficial dicta una decisión final; la falta de decisión oportuna equivale a denegación presunta. La apelación según el **§ 7104** es excluyente: ante la junta de apelaciones contractuales de la agencia dentro de **90 días**, o ante la COFC dentro de **12 meses** — invertir esos dos plazos es una trampa favorita de examen. Los intereses corren desde que el oficial recibió la reclamación (§ 7109).

**5. Tucker Act y Little Tucker Act.** La Tucker Act, **28 U.S.C. § 1491(a)(1)**, es la renuncia general a la inmunidad soberana para reclamaciones contractuales contra Estados Unidos ante la COFC. La Little Tucker Act, **28 U.S.C. § 1346(a)(2)**, otorga jurisdicción concurrente a los tribunales de distrito solo para reclamaciones que **no superen los 10.000 dólares**; por encima, el único foro es la COFC.

**6. Terminación por conveniencia.** Conforme a la Parte 49 de la FAR y cláusulas como FAR 52.249-2, el gobierno puede terminar total o parcialmente cuando ello favorezca su interés, sin incumplimiento del contratista. La liquidación paga los costos admisibles incurridos más una ganancia razonable sobre el trabajo ejecutado, pero **sin ganancias anticipadas** por la parte terminada, en ruptura clara con los daños por incumplimiento del derecho común. Contrástese con la terminación por incumplimiento (default), donde el gobierno puede recuperar los costos excedentes de readquisición.

**7. Contraste con California.** Las adquisiciones estatales y locales no usan la FAR, la CICA ni la CDA. La licitación competitiva estatal se rige por el **California Public Contract Code** (las disposiciones del State Contract Act, § 10100 y ss., y las partes separadas para agencias locales), y las reclamaciones dinerarias contra entidades públicas de California exigen primero la presentación de una reclamación bajo la **California Government Claims Act, Gov. Code §§ 810 y ss.** No se mezclen los sistemas: los plazos de 90 días y 12 meses de la CDA no son plazos californianos, y la práctica de protesta ante la GAO no es la protesta de licitación californiana. Verifíquense las secciones y plazos vigentes de California antes de confiar en ellos.

**Errores frecuentes:** tratar una decisión de la GAO como vinculante; suponer que toda protesta suspende automáticamente la ejecución sin importar cuándo llegue el aviso; impugnar defectos de la convocatoria solo después de la adjudicación (renuncia Blue & Gold); intercambiar los plazos de 90 días y 12 meses de la CDA; leer los 10.000 dólares de la Little Tucker Act como piso en vez de techo; esperar ganancias anticipadas tras una terminación por conveniencia.

*Notas de estudio personales; no constituye asesoría legal. Fuentes: FAR, 48 C.F.R. cap. 1; 31 U.S.C. §§ 3551–3557; 4 C.F.R. parte 21; 28 U.S.C. §§ 1491, 1346(a)(2); 41 U.S.C. §§ 3301, 7101–7109; Blue & Gold Fleet, 492 F.3d 1308 (Fed. Cir. 2007); Cal. Pub. Contract Code § 10100 y ss.; Cal. Gov. Code § 810 y ss.*

---

## 한국어 (초역, 원어민 감수 대기)

**정부 계약과 연방 조달: FAR, 계약분쟁법, 입찰 이의제기**

연방 조달 시험 문제는 세 가지로 모입니다. 계약이 어떻게 체결되는가(FAR와 경쟁 규칙), 결함 있는 낙찰에 어디서 이의를 제기하는가(GAO 또는 연방청구법원), 이행 단계의 분쟁을 어떻게 처리하는가(Contract Disputes Act). 각 절차마다 기한이 다르며, 이를 혼동하는 것이 대표적인 실점 요인입니다.

**1. FAR의 틀.** Federal Acquisition Regulation(연방조달규정)은 **48 C.F.R. Chapter 1**에 codify되어 있고 국방부, GSA, NASA가 공동으로 발행하며, 각 기관은 보충 규정을 둡니다(예: DFARS). 핵심 Part는 Part 6(경쟁), Part 12(상용품), Part 14(밀봉 입찰), Part 15(협상 조달), Part 49(해지), Part 52(실제로 계약에 삽입되는 표준 조항)입니다. Competition in Contracting Act는 완전하고 공개된 경쟁을 요구합니다(**41 U.S.C. § 3301**, 군에 대해서는 10 U.S.C. § 3201 참조). 금액 기준(micro-purchase, simplified acquisition threshold)은 FAR 2.101에 있으며 수시로 바뀌므로 현행 문언을 확인해야 합니다.

**2. GAO 입찰 이의제기.** 이해관계자는 **31 U.S.C. §§ 3551–3557**에 따라 Government Accountability Office에 이의를 제기할 수 있고, 절차는 **4 C.F.R. Part 21**(GAO Bid Protest Regulations)이 정합니다. 4 C.F.R. § 21.2의 기한은 엄격합니다. 마감일 전에 알 수 있었던 모집 문서의 결함은 마감 전에 제기해야 하고, 그 밖의 사유는 원칙적으로 그 사유를 알았거나 알 수 있었던 날부터 **10일 이내**에 제기해야 하며, 낙찰 이의에는 debriefing과 연동된 특별 규칙이 있습니다. CICA 자동 정지(**31 U.S.C. § 3553(d)(4)**)는 기관이 법정 기간 내에 GAO의 통지를 받을 때만 낙찰이나 이행을 멈춥니다(낙찰 후 이의의 경우 일반적으로 낙찰 후 10일 또는 debriefing 날짜 후 5일 중 늦은 시점까지 — 현행 법문 확인 필요). 기관장의 긴급하고 부득이한 사유에 의한 서면 번복은 예외적입니다. GAO는 통상 100일 이내에 권고를 냅니다(§ 3554). 형식상 권고이지만 기관은 거의 항상 따릅니다.

**3. 연방청구법원(COFC) 이의제기.** 대안으로 이해관계자는 **28 U.S.C. § 1491(b)(1)**에 따라 U.S. Court of Federal Claims에 소송을 제기할 수 있습니다. 심사는 § 1491(b)(4)가 준용하는 APA 기준(5 U.S.C. § 706)에 따릅니다. **Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)**에 따르면 모집 문서의 명백한 결함은 마감 전에 다투지 않으면 권리포기(waiver)로 처리됩니다. 법원 경로는 구속력 있는 심사와 금지명령을 제공하지만 CICA식 자동 정지는 없어, 법원에 별도로 잠정 구제를 신청해야 합니다.

**4. CDA에 따른 이행 분쟁.** 낙찰 이후의 청구는 **Contract Disputes Act, 41 U.S.C. §§ 7101–7109**의 적용을 받습니다. 계약자는 contracting officer에게 확정 금액의 서면 청구를 제출하고, 법정 기준액(현행 100,000달러)을 초과하는 청구는 인증이 필요합니다(§ 7103 참조). Contracting officer가 최종 결정을 내리고, 기한 내 결정이 없으면 거부로 간주됩니다. **§ 7104**의 불복은 양자택일입니다. 기관 계약불복위원회에는 **90일 이내**, COFC에는 **12개월 이내** — 이 두 기한을 뒤바꾸는 것이 단골 함정입니다. 이자는 contracting officer가 청구를 접수한 날부터 발생합니다(§ 7109).

**5. Tucker Act와 Little Tucker Act.** Tucker Act, **28 U.S.C. § 1491(a)(1)**는 COFC에서의 대미 계약 청구에 대한 주권면제의 일반적 포기입니다. Little Tucker Act, **28 U.S.C. § 1346(a)(2)**는 연방지방법원에 **10,000달러를 초과하지 않는** 청구에 대해서만 경합 관할을 부여합니다. 그 이상은 COFC가 유일한 법정입니다.

**6. 정부 편의 해지.** FAR Part 49와 FAR 52.249-2 같은 조항에 따라 정부는 계약자의 채무불이행이 없어도 정부 이익에 부합하면 전부 또는 일부를 해지할 수 있습니다. 정산은 발생한 허용 비용과 이행된 부분에 대한 합리적 이윤을 지급하지만, 해지된 부분의 **기대이익(anticipatory profits)은 지급하지 않습니다**. 이는 일반법의 채무불이행 손해배상과 크게 다릅니다. 채무불이행 해지(default)와 대비하십시오. 그 경우 정부는 초과 재조달 비용을 회수할 수 있습니다.

**7. 캘리포니아와의 대비.** 주와 지방 조달에는 FAR, CICA, CDA가 적용되지 않습니다. 주 경쟁입찰은 **California Public Contract Code**(State Contract Act 규정, § 10100 이하, 지방기관 부분 별도)가 규율하고, 캘리포니아 공공기관에 대한 금전 청구는 먼저 **California Government Claims Act, Gov. Code §§ 810 이하**에 따른 청구 제시가 필요합니다. 두 체계를 섞지 마십시오. CDA의 90일/12개월 기한은 캘리포니아 기한이 아니고, GAO 절차는 캘리포니아 입찰 이의 절차가 아닙니다. 캘리포니아 현행 조문과 기한을 반드시 확인하십시오.

**흔한 오류:** GAO 결정을 구속력 있는 것으로 취급하기, 통지 시점과 무관하게 이의만으로 이행이 자동 정지된다고 생각하기, 낙찰 후에야 모집 문서 결함을 제기하기(Blue & Gold 포기), CDA의 90일과 12개월을 뒤바꾸기, Little Tucker Act의 10,000달러를 하한으로 읽기, 편의 해지 후 기대이익을 기대하기.

*개인 학습 노트이며 법률 자문이 아닙니다. 출처: FAR, 48 C.F.R. ch. 1; 31 U.S.C. §§ 3551–3557; 4 C.F.R. pt. 21; 28 U.S.C. §§ 1491, 1346(a)(2); 41 U.S.C. §§ 3301, 7101–7109; Blue & Gold Fleet, 492 F.3d 1308 (Fed. Cir. 2007); Cal. Pub. Contract Code § 10100 et seq.; Cal. Gov. Code § 810 et seq.*

---

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Hợp đồng chính phủ và mua sắm liên bang: FAR, Contract Disputes Act và khiếu nại đấu thầu**

Câu hỏi thi về mua sắm liên bang xoay quanh ba vấn đề: hợp đồng được trao như thế nào (FAR và quy tắc cạnh tranh), khiếu nại việc trao thầu sai ở đâu (GAO hoặc Court of Federal Claims), và xử lý tranh chấp trong giai đoạn thực hiện ra sao (Contract Disputes Act). Mỗi đường có thời hạn riêng, lẫn lộn chúng là lỗi mất điểm kinh điển.

**1. Khung FAR.** Federal Acquisition Regulation được hệ thống hóa tại **48 C.F.R. Chapter 1**, do Bộ Quốc phòng, GSA và NASA cùng ban hành, các cơ quan có quy định bổ sung (ví dụ DFARS). Các Part trọng tâm: Part 6 (cạnh tranh), Part 12 (sản phẩm thương mại), Part 14 (đấu thầu niêm phong), Part 15 (mua sắm đàm phán), Part 49 (chấm dứt), Part 52 (các điều khoản chuẩn thực tế đưa vào hợp đồng). Competition in Contracting Act yêu cầu cạnh tranh đầy đủ và công khai, **41 U.S.C. § 3301** (xem thêm 10 U.S.C. § 3201 cho quân đội), trừ khi có ngoại lệ bằng văn bản. Các ngưỡng tiền (micro-purchase, simplified acquisition threshold) nằm ở FAR 2.101 và thay đổi theo thời gian — luôn kiểm tra văn bản hiện hành.

**2. Khiếu nại tại GAO.** Bên có lợi ích liên quan có thể khiếu nại lên Government Accountability Office theo **31 U.S.C. §§ 3551–3557**, thủ tục theo GAO Bid Protest Regulations, **4 C.F.R. Part 21**. Thời hạn tại 4 C.F.R. § 21.2 rất chặt: khiếm khuyết thấy rõ trước ngày đóng thầu phải khiếu nại trước thời điểm đó; các căn cứ khác nói chung phải nộp trong **10 ngày** kể từ khi biết hoặc phải biết căn cứ, kèm quy tắc đặc biệt gắn với buổi debriefing đối với khiếu nại sau trao thầu. Cơ chế tự động đình chỉ CICA, **31 U.S.C. § 3553(d)(4)**, chỉ đình chỉ trao thầu hoặc thực hiện khi cơ quan nhận được thông báo của GAO trong cửa sổ luật định (với khiếu nại sau trao thầu, thường là trong 10 ngày sau trao thầu hoặc 5 ngày sau ngày debriefing, lấy mốc muộn hơn — cần đối chiếu văn bản luật hiện hành); người đứng đầu cơ quan chỉ được ghi đè bằng văn bản nêu lý do khẩn cấp và thuyết phục. GAO ra khuyến nghị thông thường trong 100 ngày (§ 3554); hình thức chỉ là khuyến nghị nhưng các cơ quan hầu như luôn tuân theo.

**3. Khiếu nại tại COFC.** Thay vào đó, bên liên quan có thể kiện tại U.S. Court of Federal Claims theo **28 U.S.C. § 1491(b)(1)**. Việc xem xét theo chuẩn APA được § 1491(b)(4) dẫn chiếu (5 U.S.C. § 706). Theo **Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)**, khiếm khuyết hiển nhiên trong hồ sơ mời thầu phải bị chất vấn trước ngày đóng thầu, nếu không sẽ bị coi là từ bỏ quyền (waiver). Đường tòa án cho xem xét ràng buộc và lệnh cấm, nhưng không có cơ chế tự động đình chỉ kiểu CICA — biện pháp tạm thời phải xin từ tòa.

**4. Tranh chấp thực hiện theo CDA.** Khiếu kiện sau trao thầu thuộc **Contract Disputes Act, 41 U.S.C. §§ 7101–7109**. Nhà thầu nộp yêu cầu bằng văn bản với số tiền xác định cho contracting officer; yêu cầu vượt ngưỡng luật định (hiện là 100.000 đô la) phải có chứng nhận (xem § 7103). Contracting officer ra quyết định cuối cùng; quá hạn không quyết định được coi là từ chối. Kháng cáo theo **§ 7104** là lựa chọn loại trừ nhau: lên hội đồng kháng cáo hợp đồng của cơ quan trong **90 ngày**, hoặc ra COFC trong **12 tháng** — đổi ngược hai mốc này là cái bẫy thi cử quen thuộc. Tiền lãi tính từ ngày contracting officer nhận được yêu cầu (§ 7109).

**5. Tucker Act và Little Tucker Act.** Tucker Act, **28 U.S.C. § 1491(a)(1)**, là sự từ bỏ miễn trừ chủ quyền chung cho các yêu cầu hợp đồng đối với Hoa Kỳ tại COFC. Little Tucker Act, **28 U.S.C. § 1346(a)(2)**, chỉ cho tòa quận thẩm quyền đồng thời với yêu cầu **không vượt quá 10.000 đô la**; cao hơn thì COFC là diễn đàn duy nhất.

**6. Chấm dứt vì tiện ích của chính phủ.** Theo FAR Part 49 và các điều khoản như FAR 52.249-2, chính phủ có thể chấm dứt toàn bộ hoặc một phần khi việc chấm dứt phục vụ lợi ích của chính phủ, mà không cần nhà thầu vi phạm. Thanh toán gồm chi phí hợp lệ đã phát sinh cộng lợi nhuận hợp lý trên phần việc đã làm — nhưng **không có lợi nhuận kỳ vọng** trên phần bị chấm dứt, khác hẳn bồi thường vi phạm hợp đồng theo thông luật. Đối chiếu với chấm dứt do vi phạm (default), nơi chính phủ có thể thu hồi chi phí mua lại vượt mức.

**7. Đối chiếu California.** Mua sắm cấp bang và địa phương không dùng FAR, CICA hay CDA. Đấu thầu cạnh tranh của bang chịu sự điều chỉnh của **California Public Contract Code** (các quy định State Contract Act, § 10100 trở đi, và các phần riêng cho cơ quan địa phương), còn yêu cầu tiền đối với cơ quan công của California trước hết phải trình yêu cầu theo **California Government Claims Act, Gov. Code §§ 810 trở đi**. Đừng trộn hai hệ thống: thời hạn 90 ngày/12 tháng của CDA không phải thời hạn California, và thủ tục khiếu nại GAO không phải thủ tục khiếu nại đấu thầu của California. Hãy kiểm tra điều khoản và thời hạn California hiện hành trước khi tin cậy.

**Lỗi thường gặp:** coi quyết định GAO là ràng buộc; cho rằng cứ khiếu nại là tự động đình chỉ bất kể khi nào thông báo tới; chỉ nêu khiếm khuyết hồ sơ mời thầu sau khi trao thầu (từ bỏ quyền Blue & Gold); đổi ngược thời hạn 90 ngày và 12 tháng của CDA; đọc con số 10.000 đô la của Little Tucker Act thành sàn thay vì trần; kỳ vọng lợi nhuận dự tính sau chấm dứt vì tiện ích.

*Ghi chú học tập cá nhân, không phải tư vấn pháp lý. Nguồn: FAR, 48 C.F.R. ch. 1; 31 U.S.C. §§ 3551–3557; 4 C.F.R. pt. 21; 28 U.S.C. §§ 1491, 1346(a)(2); 41 U.S.C. §§ 3301, 7101–7109; Blue & Gold Fleet, 492 F.3d 1308 (Fed. Cir. 2007); Cal. Pub. Contract Code § 10100 trở đi; Cal. Gov. Code § 810 trở đi.*

---

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**सरकारी अनुबंध और संघीय खरीद: FAR, Contract Disputes Act और बोली विरोध**

संघीय खरीद के परीक्षा प्रश्न तीन समस्याओं के इर्द-गिर्द घूमते हैं: अनुबंध कैसे दिया जाता है (FAR और प्रतिस्पर्धा नियम), दोषपूर्ण आवंटन को कहाँ चुनौती दी जाए (GAO या Court of Federal Claims), और निष्पादन चरण के विवाद कैसे निपटाए जाएँ (Contract Disputes Act)। हर मार्ग की अपनी समय-सीमाएँ हैं, और उन्हें आपस में मिलाना अंक गँवाने का क्लासिक तरीका है।

**1. FAR ढाँचा।** Federal Acquisition Regulation **48 C.F.R. Chapter 1** में संहिताबद्ध है और रक्षा विभाग, GSA तथा NASA द्वारा संयुक्त रूप से जारी किया जाता है; एजेंसियाँ अपने पूरक नियम जोड़ती हैं (जैसे DFARS)। प्रमुख Parts: Part 6 (प्रतिस्पर्धा), Part 12 (वाणिज्यिक उत्पाद), Part 14 (मुहरबंद बोली), Part 15 (वार्ता द्वारा खरीद), Part 49 (समाप्ति), और Part 52 (वे मानक खंड जो वास्तव में अनुबंधों में डाले जाते हैं)। Competition in Contracting Act पूर्ण और खुली प्रतिस्पर्धा अनिवार्य करता है, **41 U.S.C. § 3301** (सशस्त्र बलों के लिए 10 U.S.C. § 3201 भी देखें), जब तक लिखित अपवाद लागू न हो। धन-सीमाएँ (micro-purchase, simplified acquisition threshold) FAR 2.101 में हैं और समय-समय पर बदलती हैं — हमेशा वर्तमान पाठ देखें।

**2. GAO में बोली विरोध।** हितबद्ध पक्ष **31 U.S.C. §§ 3551–3557** के तहत Government Accountability Office में विरोध दर्ज कर सकता है; प्रक्रिया GAO Bid Protest Regulations, **4 C.F.R. Part 21** में है। 4 C.F.R. § 21.2 की समय-सीमा कड़ी है: समापन तिथि से पहले दिखाई देने वाले दोष उसी से पहले उठाए जाने चाहिए; अन्य आधार सामान्यतः आधार ज्ञात होने या ज्ञात होना चाहिए था, उसके **10 दिनों के भीतर** दर्ज किए जाएँ, और आवंटन-पश्चात विरोधों के लिए debriefing से जुड़े विशेष नियम हैं। CICA स्वचालित रोक, **31 U.S.C. § 3553(d)(4)**, आवंटन या निष्पादन तभी रोकती है जब एजेंसी को GAO की सूचना विधिक अवधि के भीतर मिले (आवंटन-पश्चात विरोध में सामान्यतः आवंटन के 10 दिनों के भीतर या debriefing तिथि के 5 दिनों के भीतर, जो भी बाद में हो — वर्तमान विधिक पाठ सत्यापित करें); एजेंसी प्रमुख इसे केवल अत्यावश्यक और बाध्यकारी कारणों के लिखित निष्कर्ष पर ही रद्द कर सकता है। GAO सामान्यतः 100 दिनों के भीतर अपनी सिफ़ारिश देता है (§ 3554); औपचारिक रूप से यह सिफ़ारिश ही है, पर एजेंसियाँ लगभग हमेशा इसका पालन करती हैं।

**3. COFC में बोली विरोध।** वैकल्पिक रूप से हितबद्ध पक्ष **28 U.S.C. § 1491(b)(1)** के तहत U.S. Court of Federal Claims में वाद कर सकता है। समीक्षा § 1491(b)(4) द्वारा समाविष्ट APA मानक (5 U.S.C. § 706) के अनुसार होती है। **Blue & Gold Fleet, L.P. v. United States, 492 F.3d 1308 (Fed. Cir. 2007)** के अनुसार, निविदा दस्तावेज़ का स्पष्ट दोष समापन तिथि से पहले उठाना अनिवार्य है, अन्यथा वह परित्यक्त (waived) माना जाएगा। न्यायालय मार्ग बाध्यकारी समीक्षा और निषेधाज्ञा देता है, परंतु CICA जैसी स्वचालित रोक नहीं — अंतरिम राहत न्यायालय से माँगनी पड़ती है।

**4. CDA के तहत निष्पादन विवाद।** आवंटन-पश्चात दावे **Contract Disputes Act, 41 U.S.C. §§ 7101–7109** के अधीन हैं। ठेकेदार contracting officer को निश्चित राशि का लिखित दावा प्रस्तुत करता है; विधिक सीमा (वर्तमान में 100,000 डॉलर) से अधिक दावों का प्रमाणन आवश्यक है (§ 7103 देखें)। Contracting officer अंतिम निर्णय देता है; समय पर निर्णय न होना अस्वीकृति माना जाता है। **§ 7104** के तहत अपील परस्पर विकल्पी है: एजेंसी के contract appeals board में **90 दिनों के भीतर**, या COFC में **12 महीनों के भीतर** — इन दो सीमाओं को उलट देना पसंदीदा परीक्षा जाल है। ब्याज contracting officer द्वारा दावा प्राप्त करने की तिथि से चलता है (§ 7109)।

**5. Tucker Act बनाम Little Tucker Act।** Tucker Act, **28 U.S.C. § 1491(a)(1)**, COFC में संयुक्त राज्य अमेरिका के विरुद्ध अनुबंध दावों के लिए संप्रभु प्रतिरक्षा का सामान्य परित्याग है। Little Tucker Act, **28 U.S.C. § 1346(a)(2)**, जिला न्यायालयों को केवल **10,000 डॉलर से अनधिक** दावों के लिए समवर्ती क्षेत्राधिकार देता है; उससे ऊपर COFC ही एकमात्र मंच है।

**6. सुविधा हेतु समाप्ति।** FAR Part 49 और FAR 52.249-2 जैसे खंडों के तहत सरकार पूरे या आंशिक रूप से अनुबंध समाप्त कर सकती है जब समाप्ति उसके हित में हो, बिना ठेकेदार की किसी चूक के। निपटान में व्यय की गई अनुमेय लागतें और किए गए कार्य पर उचित लाभ मिलता है — परंतु समाप्त भाग पर **अपेक्षित लाभ (anticipatory profits) नहीं** मिलता, जो सामान्य-विधि अनुबंध-भंग हर्जाने से स्पष्ट भिन्न है। चूक हेतु समाप्ति (termination for default) से तुलना करें, जहाँ सरकार अतिरिक्त पुनर्खरीद लागत वसूल सकती है।

**7. California से तुलना।** राज्य और स्थानीय खरीद में FAR, CICA या CDA लागू नहीं होता। राज्य प्रतिस्पर्धात्मक बोली **California Public Contract Code** द्वारा शासित है (State Contract Act प्रावधान, § 10100 आदि, तथा स्थानीय एजेंसियों के लिए अलग भाग), और California लोक निकायों के विरुद्ध धन दावों के लिए पहले **California Government Claims Act, Gov. Code §§ 810 आदि** के तहत दावा प्रस्तुत करना आवश्यक है। दोनों प्रणालियों को मिलाएँ नहीं: CDA की 90-दिन/12-माह सीमाएँ California की सीमाएँ नहीं हैं, और GAO विरोध अभ्यास California बोली-विरोध अभ्यास नहीं है। भरोसा करने से पहले California के वर्तमान प्रावधान और समय-सीमाएँ सत्यापित करें।

**आम गलतियाँ:** GAO निर्णय को बाध्यकारी मानना; यह मानना कि विरोध मात्र से निष्पादन स्वतः रुक जाता है चाहे सूचना कभी भी आए; आवंटन के बाद ही निविदा दोष उठाना (Blue & Gold परित्याग); CDA की 90-दिन और 12-माह सीमाएँ उलट देना; Little Tucker Act के 10,000 डॉलर को न्यूनतम सीमा समझना, जबकि वह अधिकतम सीमा है; सुविधा-समाप्ति के बाद अपेक्षित लाभ की आशा रखना।

*व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं। स्रोत: FAR, 48 C.F.R. ch. 1; 31 U.S.C. §§ 3551–3557; 4 C.F.R. pt. 21; 28 U.S.C. §§ 1491, 1346(a)(2); 41 U.S.C. §§ 3301, 7101–7109; Blue & Gold Fleet, 492 F.3d 1308 (Fed. Cir. 2007); Cal. Pub. Contract Code § 10100 et seq.; Cal. Gov. Code § 810 et seq.*
