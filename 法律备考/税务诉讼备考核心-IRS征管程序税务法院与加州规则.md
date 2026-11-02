# 税务诉讼备考核心：IRS 征管程序、税务法院与加州规则

> 个人学习笔记，不构成法律或税务建议。本文梳理联邦税务争议从审计、上诉办公室、缺额通知到税务法院与退款诉讼的完整链条，并对照加州 FTB 抗议、税务上诉办公室（OTA）与先缴后诉规则；条文以《国内收入法典》（Internal Revenue Code, I.R.C.）与加州现行法为准。

## 中文主文

### 一、先分清两条河：缺额程序与退款程序

联邦税务诉讼的全部结构，先看纳税人手里的钱在哪一边。**缺额程序（deficiency procedures）**处理的是 IRS 主张纳税人少报了税、税还没有评定（assessment）的阶段：IRS 先发缺额通知，纳税人可以不先交钱就去税务法院争。**退款程序（refund procedures）**处理的是税已经缴清、纳税人主张多缴了要退回的阶段：必须先向 IRS 提出退款请求，被拒或逾期不处理后，才能去地区法院或联邦索赔法院起诉。两条河的门票、时限和举证节奏完全不同，备考时所有条文都应先归到这两条河里再记。

还要分清三个动词：**评定**是 IRS 在账上正式记下税额的动作，没有评定就不能强制征收；**征收（collection）**是评定之后用留置权（lien）与强制扣缴（levy）拿钱的动作；**审计（examination）**只是查账，本身不产生可诉的税额。程序权利大多挂在评定这一步的前后。

### 二、缺额是什么：I.R.C. § 6211 的定义

I.R.C. § 6211(a) 把缺额定义为一个差额：依法应缴纳的正确税额，减去纳税人在申报表上申报的税额，再减去此前已评定的金额，并加上此前已退还的金额。说白了，缺额不是 IRS 说欠多少就是多少，而是「正确税额减去已认账部分」之后剩下的争议部分。只有缺额才走缺额程序；申报表上自己报了却没交的税、以及多数可直接评定的罚金，不经缺额通知就能评定，这也是为什么 § 6213 的保护并不是覆盖一切税单。

### 三、缺额通知与 90 天：I.R.C. §§ 6212、6213

审计结束谈不拢，IRS 会先发一封通常称为「30 天信」的初步通知，给纳税人去上诉办公室陈情的机会；仍不能解决的，IRS 依 § 6212 向纳税人最后已知地址寄出正式的**缺额通知（notice of deficiency）**，实务中叫「90 天信」。

§ 6213(a) 是整套程序的心脏，规则有三层：

1. **起诉期限**：纳税人自缺额通知寄出之日起 **90 天内**（通知寄往美国境外地址的为 **150 天**）可以向美国税务法院（U.S. Tax Court）提起诉讼，请求重新核定缺额；期限最后一日逢周六、周日或哥伦比亚特区法定假日的，不计入最后一日。逾期起诉，税务法院原则上没有管辖权，这 90 天是全税法最不能错过的时钟之一。
2. **评定禁止**：在通知寄出之后、90 天（或 150 天）届满之前，IRS 不得评定缺额、不得启动扣缴或法院征收程序；纳税人一旦及时起诉，禁令一直延续到税务法院判决成为终局为止。违反禁令的评定可以被禁止或撤销，这是 § 6213 区别于一般「先交后争」逻辑的关键保护。
3. **例外要收紧记**：数学或文书错误（math error）通知依 § 6213(b) 不算缺额通知，IRS 可以直接评定，纳税人只能在收到后 60 天内要求撤销该评定、让案件回到缺额轨道；此外 § 6213 还留有危急评定（jeopardy assessment，§ 6861）等紧急通道，属例外而非常态，答题时点到即可。

### 四、税务法院长什么样：第一条法院与 19 名法官

税务法院依 I.R.C. § 7441 是国会依宪法第一条设立的记录法院（court of record），不是第三条法院。依 § 7443，法院由 **19 名法官**组成，由总统提名、经参议院同意后任命，任期 15 年，只以是否胜任职务为任命标准。本部在华盛顿特区，法官巡回各地开庭；另有首席法官任命的特别审判法官（special trial judges）分担小额与指定案件。

考试与实务共同的分水岭在这里：**去税务法院打缺额官司，不需要先把争议税款交出去**。纳税人是先诉讼、后定账；等判决终局，IRS 才按判决评定。这与下一节的退款诉讼恰好相反，也是税务法院成为绝大多数缺额争议首选战场的原因。税务法院另有小额税务案件程序（small tax case，§ 7463，争议金额每年度不超过 50,000 美元），程序简化，但判决不得上诉、也不作先例，使用前要想清楚。

### 五、另一条河：退款诉讼与 Flora 全额缴纳规则

如果纳税人错过了 90 天，或者争议的税已经评定并缴清，就只能走退款路：先依 I.R.C. § 6511 向 IRS 提出退款请求——一般期限是申报表提交后 3 年内或税款缴纳后 2 年内，取其较晚者；请求被书面拒绝后，或提出后满 6 个月 IRS 仍不处理，纳税人才能依 § 7422 起诉。**没有先提行政退款请求，就没有退款诉讼**，§ 7422(a) 写得很硬。

法院选地区法院或联邦索赔法院（Court of Federal Claims），管辖依据是 28 U.S.C. § 1346(a)(1)。而门票规则来自判例：*Flora v. United States*, 362 U.S. 145 (1960)（重申 357 U.S. 63 (1958)）确立**全额缴纳规则（full payment rule）**——就所得税缺额而言，必须先把评定的全部税额缴清，才能在地区法院提起退款诉讼，只交一部分、只诉那一部分不行。最高法院的理由之一正是：国会已经另设了税务法院这个不用预缴的论坛，退款论坛保留先缴规则并不堵死纳税人的路。备考一句话：**税务法院先诉后缴，地区法院先缴后诉，Flora 是后半句的出处。**（可分税种如雇佣税等有按期分割的例外讨论，属进阶考点，本文只记主规则。）

### 六、不打官司先谈：审计复议与独立上诉办公室

诉讼之前其实有两层行政缓冲。其一是**审计复议（audit reconsideration）**：税已评定后，纳税人拿出审计时没提交过的新证据、或指出 IRS 算错了，可以请求 IRS 重新打开审计结论——它不是法典明文的诉权，而是 IRS 的行政实务安排，不能替代 90 天期限，正在走税务法院的案件也不能靠它拖住时钟。

其二是 **IRS 独立上诉办公室（IRS Independent Office of Appeals）**，法定依据 I.R.C. § 7803(e)：国会要求其以不诉讼方式公正解决联邦税务争议，且该程序原则上向所有纳税人开放（generally available to all taxpayers）。30 天信阶段去上诉办公室谈和解，是实务中最常见的止争点；上诉官员按诉讼风险（hazards of litigation）评估折让，这与审计人员只认事实与条文的口径不同。征收环节的上诉也多由该办公室承接，见下一节。注意边界：上诉办公室谈不成，不延长任何法定起诉期限，90 天信一出，时钟照走。

### 七、征收侧的听证：§ 6320 与 § 6330 CDP

税一旦评定且逾期不缴，IRS 可以登记**联邦税收留置权（Notice of Federal Tax Lien）**，也可以**强制扣缴（levy）**银行存款、工资等财产。征收不是没有刹车：I.R.C. § 6320 给留置权登记后的听证权，§ 6330 给扣缴之前的听证权，合称**征收正当程序听证（Collection Due Process, CDP）**。要点：IRS 须在扣缴前至少 30 天发出载明听证权的通知；纳税人在 30 天内提出 CDP 请求的，由独立上诉办公室举行听证，可争征收方式是否恰当、可提分期协议（§ 6159）或和解要约（offer in compromise）等替代方案；对底层税额本身有异议的，只有在此前没收到过缺额通知、也没有其他机会争辩时，才能在 CDP 中翻出来。听证决定（notice of determination）后 30 天内可向税务法院起诉。逾期提出的只能请求「等同听证」（equivalent hearing），决定不可诉——及时与逾期的差别就在这里。

### 八、加州侧：FTB 抗议、OTA 上诉与先缴后诉

加州没有与联邦税务法院完全对应的「先诉后缴」论坛，节奏是行政前置加先缴后诉：

1. **向特许经营税委员会（Franchise Tax Board, FTB）抗议**：FTB 发出拟评定通知（Notice of Proposed Assessment）后，纳税人一般在 **60 天内**提出书面抗议（protest），由 FTB 举行听证并作出行动通知（Notice of Action）。
2. **向税务上诉办公室（Office of Tax Appeals, OTA）上诉**：对 FTB 的行动通知不服，一般在 **30 天内**向 OTA 上诉。OTA 由 2017 年《纳税人透明与公平法》设立，**自 2018 年 1 月 1 日起承接原州平税局（Board of Equalization, BOE）的税务上诉职能**，由三名行政法法官组成合议庭审理，管辖 FTB 的所得税与特许经营税上诉以及加州税务与收费管理局（CDTFA）的销售使用税等上诉；OTA 决定可附先例意见。走完 OTA 仍不服、且税款问题进入法院阶段的，受下一条宪法规则约束。
3. **先缴后诉是宪法硬线**：加州宪法第十三条第 32 款（Cal. Const. art. XIII, § 32）规定，任何法院不得发出阻止或禁止州征收税款的法律或衡平程序；只有在**先缴纳**被主张为非法的税款之后，才能依立法机关规定的方式提起追回之诉。这就是加州的 pay-then-sue（先缴后诉）规则，比联邦的 Flora 规则更彻底——联邦至少还留了税务法院这条不预缴的路，加州在法院层面没有对应出口，所以加州税务争议的胜负手更多落在 FTB 抗议与 OTA 这两层行政程序里，期限一天都不能松。

### 九、备考自查清单

- 缺额定义 § 6211、通知 § 6212、90/150 天与评定禁止 § 6213，能默写三者的分工；
- 税务法院：第一条法院（§ 7441）、19 名总统任命法官、任期 15 年（§ 7443）、不预缴可诉、小额程序 § 7463 的代价；
- 退款链：§ 6511 请求期限（3 年/2 年取晚）→ § 7422 先请求后起诉 → *Flora*（1960）全额缴纳；
- 行政缓冲：审计复议只是实务安排、不停钟；独立上诉办公室 § 7803(e)，按诉讼风险谈和解；
- 征收听证：留置权 § 6320、扣缴 § 6330，CDP 30 天请求、决定后 30 天诉税务法院；
- 加州：FTB 60 天抗议 → OTA 30 天上诉（2018 年起取代 BOE 上诉职能）→ 法院阶段受 Cal. Const. art. XIII, § 32 先缴后诉约束。

*声明：个人学习笔记，不构成法律或税务建议。来源：I.R.C. §§ 6159、6211、6212、6213、6320、6330、6511、7422、7441、7443、7463、7803(e)；28 U.S.C. § 1346(a)(1)；Flora v. United States, 362 U.S. 145 (1960)；Cal. Const. art. XIII, § 32；2017 年加州《纳税人透明与公平法》（AB 102）与 OTA、FTB 官方上诉指引。具体期限以收到的通知文本与现行官方规则为准。*

---

## English

Federal tax litigation runs on two tracks, and every rule in this note belongs to one of them. Deficiency procedures govern the stage where the IRS says more tax is due but has not yet assessed it: the taxpayer may litigate in the Tax Court without paying first. Refund procedures govern tax already paid: the taxpayer must first file an administrative refund claim and may sue only after it is denied or left unanswered.

**What a deficiency is (I.R.C. § 6211).** A deficiency is the excess of the correct tax imposed over the tax shown on the return, reduced by amounts previously assessed (or collected without assessment) and increased by amounts previously rebated. Only that disputed remainder travels through deficiency procedures; tax a taxpayer reported but did not pay, and most assessable penalties, can be assessed without a deficiency notice.

**The notice and the 90 days (§§ 6212, 6213).** After an unresolved examination — usually preceded by a preliminary "30-day letter" offering an Appeals conference — the IRS mails a notice of deficiency under § 6212 to the taxpayer's last known address. Section 6213(a) then does three things. First, timing: the taxpayer may petition the U.S. Tax Court within **90 days** after the notice is mailed, or **150 days** if the notice is addressed to a person outside the United States, not counting a Saturday, Sunday, or District of Columbia legal holiday as the last day; a late petition generally leaves the Tax Court without jurisdiction. Second, restraint: no assessment, levy, or court collection proceeding may be made or begun until the period expires, and if a petition is filed, until the Tax Court's decision becomes final. Third, exceptions are narrow: a math-error notice under § 6213(b) is not a notice of deficiency and may be assessed at once (the taxpayer has 60 days to ask that it be abated so deficiency procedures apply), and jeopardy assessments under § 6861 are an emergency carve-out, not the norm.

**The Tax Court (§§ 7441, 7443).** The Tax Court is a court of record established by Congress under Article I (§ 7441). Under § 7443 it is composed of **19 judges** appointed by the President with the advice and consent of the Senate, serving 15-year terms; it sits in Washington, D.C., and travels nationwide, assisted by special trial judges. Its defining feature is prepayment review: a taxpayer litigates a deficiency **without first paying it**, and assessment waits for a final decision. The small tax case procedure (§ 7463, disputes of $50,000 or less per year) is faster and informal, but its decisions are neither appealable nor precedential.

**The refund track and Flora.** A taxpayer who missed the 90 days, or whose tax is already assessed and paid, must claim a refund first: § 6511 generally allows a claim within 3 years from filing the return or 2 years from paying the tax, whichever is later; suit under § 7422 is barred until the claim is denied or six months pass without action. Refund suits go to a district court or the Court of Federal Claims under 28 U.S.C. § 1346(a)(1), and *Flora v. United States*, 362 U.S. 145 (1960), affirming 357 U.S. 63 (1958), imposes the **full payment rule**: for an income-tax deficiency the entire assessed amount must be paid before a refund suit may be brought. One sentence for the exam: Tax Court is litigate first, pay later; refund court is pay first, litigate later — and *Flora* is the citation for the second half.

**Before court: reconsideration and Appeals.** Audit reconsideration — asking the IRS to reopen an assessed examination on new evidence — is an administrative practice, not a statutory right, and it never extends the 90-day clock. The statutory buffer is the IRS Independent Office of Appeals under § 7803(e), charged with resolving federal tax controversies without litigation, fairly and impartially, with a process generally available to all taxpayers; Appeals officers may weigh the hazards of litigation, which examiners do not.

**Collection hearings (§§ 6320, 6330).** Once tax is assessed and unpaid, the IRS may file a Notice of Federal Tax Lien and may levy on bank accounts and wages — but § 6320 (lien) and § 6330 (levy) give Collection Due Process rights. The IRS must give notice of the right to a hearing at least 30 days before a first levy; a timely CDP request (within 30 days) goes to Appeals, where the taxpayer may challenge collection alternatives such as an installment agreement (§ 6159) or an offer in compromise, and may contest the underlying liability only if there was no prior notice of deficiency and no earlier opportunity to dispute it. The notice of determination may be petitioned to the Tax Court within 30 days. A late request earns only an equivalent hearing, whose decision is not reviewable in court.

**California.** There is no prepayment court on the federal model. The path is administrative first: protest an FTB Notice of Proposed Assessment in writing, generally within **60 days**; then appeal the FTB's Notice of Action to the **Office of Tax Appeals (OTA)**, generally within **30 days**. Created by the Taxpayer Transparency and Fairness Act of 2017, the OTA has heard tax appeals since **January 1, 2018**, taking over the appeals function of the Board of Equalization; three-administrative-law-judge panels hear FTB income and franchise tax appeals and CDTFA sales and use tax appeals. At the courthouse door, Cal. Const. art. XIII, § 32 imposes pay-then-sue: no court may enjoin collection of a California tax, and an action to recover an allegedly illegal tax lies only **after payment**. Because California offers no Tax Court equivalent, the FTB protest and OTA appeal carry the real weight of a state tax dispute — and their short deadlines are unforgiving.

*Personal study notes only; not legal or tax advice. Sources: I.R.C. §§ 6159, 6211–6213, 6320, 6330, 6511, 7422, 7441, 7443, 7463, 7803(e); 28 U.S.C. § 1346(a)(1); Flora v. United States, 362 U.S. 145 (1960); Cal. Const. art. XIII, § 32; California Taxpayer Transparency and Fairness Act of 2017 (AB 102).*

## Español (traducción de estudio, pendiente de revisión nativa)

El litigio fiscal federal corre por dos vías. Los procedimientos de deficiencia cubren la etapa en que el IRS sostiene que se debe más impuesto pero aún no lo ha liquidado (assessment): el contribuyente puede litigar ante el Tribunal Fiscal (Tax Court) sin pagar antes. Los procedimientos de devolución cubren el impuesto ya pagado: primero hay que reclamar administrativamente y solo se puede demandar tras la denegación o el silencio.

**Qué es la deficiencia (§ 6211 del I.R.C.).** Es el exceso del impuesto correcto sobre el declarado en la declaración, menos lo ya liquidado y más lo ya devuelto. Solo ese resto disputado sigue la vía de deficiencia; el impuesto declarado y no pagado, y la mayoría de las multas liquidables directamente, no requieren aviso de deficiencia.

**El aviso y los 90 días (§§ 6212, 6213).** Tras una auditoría sin acuerdo —normalmente precedida por la «carta de 30 días» que ofrece acudir a Apelaciones— el IRS envía el aviso de deficiencia (notice of deficiency) a la última dirección conocida (§ 6212). El § 6213(a) hace tres cosas: fija el plazo para demandar ante el Tax Court en **90 días** desde el envío, o **150 días** si el aviso se dirige fuera de Estados Unidos, sin contar como último día el sábado, domingo o feriado legal del Distrito de Columbia; prohíbe liquidar, embargar o cobrar judicialmente hasta que venza el plazo y, si hay demanda, hasta que la sentencia del Tax Court sea firme; y deja excepciones estrechas, como el aviso por error matemático del § 6213(b), liquidable de inmediato (con 60 días para pedir su anulación y volver a la vía de deficiencia), y las liquidaciones de urgencia (jeopardy) del § 6861.

**El Tribunal Fiscal (§§ 7441, 7443).** Es un tribunal de registro creado por el Congreso bajo el Artículo I (§ 7441), compuesto por **19 jueces** nombrados por el Presidente con el consentimiento del Senado, con mandatos de 15 años (§ 7443). Su rasgo definitorio es la revisión sin pago previo: el contribuyente litiga la deficiencia **sin pagarla antes** y la liquidación espera la sentencia firme. El procedimiento de casos menores (§ 7463, hasta 50.000 dólares por año) es informal, pero sus decisiones no son apelables ni crean precedente.

**La vía de devolución y Flora.** Quien perdió los 90 días, o ya pagó, debe reclamar primero: el § 6511 permite la reclamación dentro de los 3 años desde la declaración o 2 años desde el pago, lo que ocurra más tarde; el § 7422 prohíbe demandar hasta la denegación o seis meses sin respuesta. La demanda va al tribunal de distrito o al Tribunal de Reclamaciones Federales (28 U.S.C. § 1346(a)(1)), y *Flora v. United States*, 362 U.S. 145 (1960) impone la **regla del pago íntegro**: para una deficiencia de impuesto sobre la renta hay que pagar todo lo liquidado antes de demandar la devolución. Frase de examen: Tax Court es litigar primero y pagar después; la devolución es pagar primero y litigar después, y *Flora* es la cita de la segunda mitad.

**Antes del tribunal.** La reconsideración de auditoría (audit reconsideration) es una práctica administrativa, no un derecho legal, y nunca prorroga los 90 días. El cauce legal es la Oficina Independiente de Apelaciones del IRS (Independent Office of Appeals), § 7803(e), encargada de resolver controversias sin litigio, de forma justa e imparcial y con un proceso en general disponible para todos los contribuyentes; sus funcionarios sí pueden ponderar el riesgo de litigio.

**Audiencias de cobro (§§ 6320, 6330).** Liquidado e impagado el impuesto, el IRS puede inscribir un gravamen fiscal federal (lien) y embargar (levy) cuentas y salarios, pero los §§ 6320 y 6330 otorgan el debido proceso de cobro (CDP): aviso del derecho a audiencia al menos 30 días antes del primer embargo; la solicitud oportuna (30 días) va a Apelaciones, donde caben alternativas como el acuerdo de pago a plazos (§ 6159) o la oferta de transacción (offer in compromise), y solo puede discutirse la deuda de fondo si no hubo aviso de deficiencia ni oportunidad previa de discutirla. La determinación puede recurrirse ante el Tax Court en 30 días; la solicitud tardía solo da una audiencia equivalente, sin revisión judicial.

**California.** No hay tribunal de pago posterior al estilo federal. La ruta es administrativa: protestar por escrito el aviso de liquidación propuesta del FTB (Notice of Proposed Assessment), en general dentro de **60 días**, y apelar la decisión (Notice of Action) ante la **Oficina de Apelaciones Fiscales (Office of Tax Appeals, OTA)**, en general dentro de **30 días**. Creada por la Ley de Transparencia y Equidad del Contribuyente de 2017, la OTA conoce apelaciones desde el **1 de enero de 2018**, en sustitución de la función apelativa de la Junta de Igualación (Board of Equalization); paneles de tres jueces administrativos oyen apelaciones del FTB y del CDTFA. En sede judicial rige el «pagar y luego demandar» de la Constitución de California, art. XIII, § 32: ningún tribunal puede impedir el cobro de un impuesto estatal y la acción de recuperación solo procede **tras el pago**. Sin un equivalente al Tax Court, el peso real del litigio estatal está en la protesta ante el FTB y la apelación ante la OTA, con plazos breves e improrrogables en la práctica.

*Notas personales de estudio; no constituye asesoramiento legal ni fiscal. Fuentes: I.R.C. §§ 6159, 6211–6213, 6320, 6330, 6511, 7422, 7441, 7443, 7463, 7803(e); 28 U.S.C. § 1346(a)(1); Flora v. United States, 362 U.S. 145 (1960); Cal. Const. art. XIII, § 32; AB 102 (2017).*

## 한국어 (초역, 원어민 감수 대기)

연방 조세소송은 두 갈래로 나뉩니다. 부족세액 절차(deficiency procedures)는 IRS가 추가 세금을 주장하지만 아직 부과(assessment)하지 않은 단계를 다루어, 납세자는 먼저 내지 않고 조세법원(Tax Court)에서 다툴 수 있습니다. 환급 절차는 이미 낸 세금에 관한 것으로, 먼저 행정상 환급청구를 해야 하고 거절되거나 방치된 뒤에야 소송할 수 있습니다.

**부족세액의 정의(I.R.C. §6211).** 부족세액은 올바른 세액에서 신고서에 표시된 세액을 빼고, 이미 부과된 금액을 공제하며, 이미 환급된 금액을 더한 차액입니다. 이 다툼 있는 잔액만 부족세액 절차를 밟습니다. 신고하고도 내지 않은 세금과 대부분의 직접 부과 벌과금은 부족세액 통지 없이 부과할 수 있습니다.

**통지와 90일(§§6212, 6213).** 감사에서 합의가 안 되면 — 보통 항소국 회의를 제안하는 '30일 서한'이 먼저 갑니다 — IRS는 §6212에 따라 납세자의 최종 확인 주소로 부족세액 통지(notice of deficiency)를 발송합니다. §6213(a)의 핵심은 셋입니다. 첫째, 기한: 통지 발송 후 **90일**(미국 외 주소는 **150일**) 안에 조세법원에 제소할 수 있고, 마지막 날이 토요일·일요일·컬럼비아 특별구 법정공휴일이면 그날은 마지막 날로 세지 않습니다. 늦으면 원칙적으로 조세법원에 관할이 없습니다. 둘째, 부과 금지: 기간이 끝나기 전에는, 제소한 경우 조세법원 판결이 확정되기 전에는 부과·압류·법원 징수를 할 수 없습니다. 셋째, 예외는 좁습니다. §6213(b)의 계산 오류 통지는 부족세액 통지가 아니어서 즉시 부과할 수 있고(납세자는 60일 안에 그 부과 취소를 구해 부족세액 절차로 돌아갈 수 있습니다), §6861의 긴급 부과(jeopardy assessment)는 비상 통로일 뿐입니다.

**조세법원(§§7441, 7443).** 조세법원은 §7441에 따라 의회가 헌법 제1조 아래 세운 기록법원(court of record)으로, §7443에 따라 대통령이 상원의 동의를 얻어 임명하는 **법관 19명**, 임기 15년으로 구성됩니다. 결정적 특징은 선납 없는 심리입니다. **쟁점 세액을 먼저 내지 않고** 다툴 수 있고, 부과는 확정 판결 뒤로 미뤄집니다. 소액 조세사건 절차(§7463, 연도별 50,000달러 이하)는 빠르지만 결정에 불복할 수 없고 선례도 되지 않습니다.

**환급 트랙과 Flora.** 90일을 놓쳤거나 이미 부과·납부한 경우에는 먼저 환급청구가 필요합니다. §6511은 원칙적으로 신고 후 3년 또는 납부 후 2년 중 늦은 때까지 청구를 허용하고, §7422는 청구가 거절되거나 6개월간 처리되지 않기 전에는 소송을 막습니다. 소송은 지방법원이나 연방청구법원(28 U.S.C. §1346(a)(1))으로 가며, *Flora v. United States*, 362 U.S. 145 (1960)는 **전액 납부 규칙(full payment rule)**을 세웠습니다. 소득세 부족세액은 부과액 전부를 내야 환급소송을 할 수 있습니다. 시험용 한 줄: 조세법원은 '먼저 다투고 나중에 납부', 환급법원은 '먼저 내고 나중에 다툼', 후자의 출처가 *Flora*입니다.

**소송 전 완충.** 감사 재심(audit reconsideration)은 새 증거로 부과된 감사를 다시 열어 달라는 행정 실무일 뿐 법정 권리가 아니며 90일 시계를 멈추지 않습니다. 법정 완충은 §7803(e)의 IRS 독립항소국(Independent Office of Appeals)으로, 소송 없이 공정하게 분쟁을 풀고 원칙적으로 모든 납세자에게 열려 있으며, 소송 위험(hazards of litigation)을 감안한 합의가 가능합니다.

**징수 청문(§§6320, 6330).** 부과된 세금이 체납되면 IRS는 연방조세 유치권(lien)을 등기하고 급여·예금에 압류(levy)를 할 수 있지만, §6320(유치권)과 §6330(압류)이 징수 적법절차(CDP) 청문을 보장합니다. 첫 압류 최소 30일 전에 청문권 통지를 해야 하고, 30일 안의 적시 CDP 신청은 항소국이 심리합니다. 분할납부 합의(§6159)나 합의 제안(offer in compromise) 같은 대안을 제시할 수 있고, 본안 채무 자체는 부족세액 통지를 받은 적도, 다툴 기회도 없었던 경우에만 다툴 수 있습니다. 결정 통지 후 30일 안에 조세법원에 제소할 수 있고, 늦은 신청은 법원 심사를 받을 수 없는 동등 청문(equivalent hearing)에 그칩니다.

**캘리포니아.** 연방식 선심리 법원이 없습니다. 경로는 행정이 먼저입니다. FTB의 부과 예정 통지에 대해 원칙적으로 **60일 안에** 서면 항의(protest)를 하고, FTB의 조치 통지에 대해 원칙적으로 **30일 안에** **조세항소국(Office of Tax Appeals, OTA)**에 항소합니다. OTA는 2017년 납세자 투명성·공정법으로 설립되어 **2018년 1월 1일부터** 주 평등위원회(Board of Equalization)의 항소 기능을 이어받았고, 행정법 판사 3인 합의부가 FTB와 CDTFA 항소를 심리합니다. 법원 단계에서는 캘리포니아 헌법 제13조 §32의 '선납 후 소송'이 적용됩니다. 어떤 법원도 주세 징수를 막을 수 없고, 위법하다고 주장하는 세금은 **낸 뒤에야** 반환 소송을 할 수 있습니다. 조세법원 같은 출구가 없어 주세 분쟁의 승부처는 FTB 항의와 OTA 항소이며, 그 짧은 기한은 양보가 없습니다.

*개인 학습 노트이며 법률·세무 자문이 아닙니다. 출처: I.R.C. §§6159, 6211–6213, 6320, 6330, 6511, 7422, 7441, 7443, 7463, 7803(e); 28 U.S.C. §1346(a)(1); Flora v. United States, 362 U.S. 145 (1960); Cal. Const. art. XIII, §32; 2017년 캘리포니아 AB 102.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Tranh tụng thuế liên bang đi theo hai đường. Thủ tục thiếu thuế (deficiency) xử lý giai đoạn IRS cho rằng còn nợ thuế nhưng chưa định thuế (assessment): người nộp thuế có thể kiện tại Tòa án Thuế mà không phải nộp trước. Thủ tục hoàn thuế xử lý phần thuế đã nộp: phải yêu cầu hoàn thuế về mặt hành chính trước, bị từ chối hoặc quá hạn không giải quyết mới được kiện.

**Thiếu thuế là gì (I.R.C. § 6211).** Đó là phần thuế đúng vượt quá thuế đã khai trên tờ khai, trừ đi số đã định thuế trước đó và cộng lại số đã hoàn trước đó. Chỉ phần chênh lệch còn tranh chấp này mới đi theo thủ tục thiếu thuế; thuế đã khai mà chưa nộp và hầu hết các khoản phạt định thuế trực tiếp không cần thông báo thiếu thuế.

**Thông báo và 90 ngày (§§ 6212, 6213).** Sau kiểm tra không thỏa thuận được — thường có «thư 30 ngày» mời họp với cơ quan Phúc thẩm trước — IRS gửi thông báo thiếu thuế (notice of deficiency) tới địa chỉ cuối cùng đã biết theo § 6212. Điều § 6213(a) làm ba việc: ấn định thời hạn kiện ra Tòa án Thuế là **90 ngày** kể từ ngày gửi, hoặc **150 ngày** nếu thông báo gửi đến địa chỉ ngoài Hoa Kỳ, không tính thứ Bảy, Chủ nhật hay ngày lễ pháp định của Đặc khu Columbia là ngày cuối; cấm định thuế, cưỡng chế (levy) hay truy thu qua tòa cho đến khi hết hạn và, nếu đã kiện, cho đến khi phán quyết của Tòa án Thuế thành chung thẩm; và giữ ngoại lệ hẹp — thông báo lỗi toán học theo § 6213(b) không phải thông báo thiếu thuế nên định thuế được ngay (người nộp thuế có 60 ngày xin hủy để quay lại thủ tục thiếu thuế), còn định thuế khẩn cấp (jeopardy) theo § 6861 chỉ là lối thoát hiểm.

**Tòa án Thuế (§§ 7441, 7443).** Đây là tòa án lưu hồ sơ (court of record) do Quốc hội lập theo Điều I Hiến pháp (§ 7441), gồm **19 thẩm phán** do Tổng thống bổ nhiệm với sự đồng ý của Thượng viện, nhiệm kỳ 15 năm (§ 7443). Đặc điểm quyết định là xét xử không cần nộp trước: người nộp thuế tranh luận về khoản thiếu **mà chưa phải trả**, và việc định thuế chờ đến phán quyết chung thẩm. Thủ tục vụ thuế nhỏ (§ 7463, tranh chấp không quá 50.000 đô la mỗi năm) nhanh và ít hình thức, nhưng phán quyết không được kháng cáo và không thành tiền lệ.

**Đường hoàn thuế và vụ Flora.** Ai lỡ 90 ngày, hoặc thuế đã định và đã nộp, phải yêu cầu hoàn thuế trước: § 6511 thường cho phép yêu cầu trong 3 năm kể từ khi nộp tờ khai hoặc 2 năm kể từ khi nộp thuế, lấy mốc muộn hơn; § 7422 cấm kiện cho đến khi yêu cầu bị từ chối hoặc sáu tháng trôi qua không được xử lý. Vụ kiện đi ra tòa địa hạt liên bang hoặc Tòa Khiếu nại Liên bang (28 U.S.C. § 1346(a)(1)), và *Flora v. United States*, 362 U.S. 145 (1960) đặt ra **quy tắc nộp đủ (full payment rule)**: với thiếu thuế thu nhập, phải nộp toàn bộ số đã định thuế mới được kiện đòi hoàn. Một câu cho kỳ thi: Tòa án Thuế là kiện trước trả sau; tòa hoàn thuế là trả trước kiện sau — và *Flora* là căn cứ của nửa sau.

**Trước khi ra tòa.** Xem xét lại kiểm tra (audit reconsideration) chỉ là thực hành hành chính, không phải quyền theo luật, và không bao giờ kéo dài đồng hồ 90 ngày. Đệm pháp định là Văn phòng Phúc thẩm Độc lập của IRS (Independent Office of Appeals) theo § 7803(e): giải quyết tranh chấp không qua kiện tụng, công bằng và vô tư, về nguyên tắc mở cho mọi người nộp thuế, và cán bộ phúc thẩm có thể cân nhắc rủi ro kiện tụng (hazards of litigation).

**Phiên điều trần truy thu (§§ 6320, 6330).** Thuế đã định mà không nộp, IRS có thể đăng ký quyền lưu giữ thuế liên bang (lien) và cưỡng chế (levy) tài khoản, tiền lương — nhưng §§ 6320 và 6330 cho quyền điều trần đúng thủ tục truy thu (CDP): phải báo quyền điều trần ít nhất 30 ngày trước lần cưỡng chế đầu tiên; yêu cầu CDP đúng hạn (30 ngày) do Phúc thẩm xử lý, tại đó có thể đề xuất thỏa thuận trả góp (§ 6159) hay đề nghị thỏa hiệp (offer in compromise), và chỉ được tranh luận về chính khoản nợ nếu trước đó chưa từng nhận thông báo thiếu thuế và chưa có cơ hội tranh luận. Sau thông báo quyết định (notice of determination), có 30 ngày để kiện ra Tòa án Thuế; yêu cầu muộn chỉ được điều trần tương đương (equivalent hearing), không được tòa xem lại.

**California.** Không có tòa «kiện trước trả sau» kiểu liên bang. Lộ trình là hành chính trước: kháng nghị bằng văn bản đối với thông báo dự định định thuế của FTB (Notice of Proposed Assessment), thường trong **60 ngày**; rồi kháng cáo thông báo hành động (Notice of Action) lên **Văn phòng Kháng cáo Thuế (Office of Tax Appeals, OTA)**, thường trong **30 ngày**. OTA do Đạo luật Minh bạch và Công bằng với Người nộp thuế 2017 lập ra, nghe kháng cáo từ **ngày 1 tháng 1 năm 2018**, thay thế chức năng kháng cáo của Hội đồng Bình đẳng (Board of Equalization); hội đồng ba thẩm phán hành chính xử lý kháng cáo của FTB và CDTFA. Ở cửa tòa, Hiến pháp California Điều XIII, § 32 áp «trả trước kiện sau»: không tòa nào được ngăn việc thu thuế của bang, và chỉ **sau khi đã nộp** khoản thuế bị cho là trái luật mới kiện đòi lại được. Không có lối thoát tương đương Tòa án Thuế, nên thắng thua của tranh chấp thuế bang nằm ở kháng nghị FTB và kháng cáo OTA — và các thời hạn ngắn ngủi ấy không khoan nhượng.

*Ghi chép học tập cá nhân, không phải tư vấn pháp lý hay thuế. Nguồn: I.R.C. §§ 6159, 6211–6213, 6320, 6330, 6511, 7422, 7441, 7443, 7463, 7803(e); 28 U.S.C. § 1346(a)(1); Flora v. United States, 362 U.S. 145 (1960); Cal. Const. art. XIII, § 32; AB 102 (2017) của California.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

संघीय कर-विवाद दो रास्तों पर चलता है। कमी-प्रक्रिया (deficiency procedures) उस चरण की है जब IRS कहता है कि और कर बकाया है पर अभी निर्धारण (assessment) नहीं हुआ: करदाता पहले दिए बिना कर न्यायालय (Tax Court) में लड़ सकता है। वापसी-प्रक्रिया पहले चुकाए गए कर की है: पहले प्रशासनिक वापसी-दावा करना होगा, और अस्वीकृति या अनुत्तर के बाद ही वाद चलेगा।

**कमी क्या है (I.R.C. § 6211).** कमी वह राशि है जो सही कर के, रिटर्न में दिखाए कर से अधिक होने पर बनती है — पहले निर्धारित राशि घटाकर और पहले लौटाई राशि जोड़कर। केवल यही विवादित शेष कमी-प्रक्रिया से जाता है; घोषित पर अचुकाया कर और अधिकांश सीधे निर्धारणीय दंडों के लिए कमी-सूचना ज़रूरी नहीं।

**सूचना और 90 दिन (§§ 6212, 6213).** असहमत ऑडिट के बाद — आमतौर पर उससे पहले अपील्स सम्मेलन का प्रस्ताव देने वाला '30-दिन पत्र' आता है — IRS § 6212 के तहत करदाता के अंतिम ज्ञात पते पर कमी-सूचना (notice of deficiency) भेजता है। § 6213(a) तीन काम करता है: कर न्यायालय में याचिका की अवधि भेजने से **90 दिन**, अमेरिका से बाहर के पते पर **150 दिन**, रखता है, और अंतिम दिन शनिवार, रविवार या डिस्ट्रिक्ट ऑफ़ कोलंबिया का विधिक अवकाश हो तो वह दिन अंतिम नहीं गिना जाता; अवधि बीतने तक, और याचिका दायर हो तो कर न्यायालय का निर्णय अंतिम होने तक, निर्धारण, लेवी (levy) या न्यायालयीन वसूली प्रतिबंधित रहती है; अपवाद संकीर्ण हैं — § 6213(b) की गणित-त्रुटि सूचना कमी-सूचना नहीं है और तुरंत निर्धारित हो सकती है (करदाता 60 दिनों में उसे रद्द कराकर कमी-प्रक्रिया में लौट सकता है), और § 6861 का आपात निर्धारण (jeopardy assessment) अपवाद ही है।

**कर न्यायालय (§§ 7441, 7443).** यह § 7441 के तहत कांग्रेस द्वारा अनुच्छेद I के अधीन स्थापित अभिलेख-न्यायालय (court of record) है, जिसमें § 7443 के अनुसार राष्ट्रपति द्वारा सीनेट की सहमति से नियुक्त **19 न्यायाधीश** होते हैं, कार्यकाल 15 वर्ष। इसकी निर्णायक विशेषता पूर्व-भुगतान के बिना समीक्षा है: करदाता विवादित कमी **पहले चुकाए बिना** लड़ सकता है और निर्धारण अंतिम निर्णय तक रुकता है। लघु कर-प्रकरण प्रक्रिया (§ 7463, प्रति वर्ष 50,000 डॉलर तक) त्वरित है, पर उसके निर्णय अपील-योग्य नहीं और नज़ीर भी नहीं बनते।

**वापसी रास्ता और Flora.** जो 90 दिन चूक गया, या जिसका कर निर्धारित व चुकाया जा चुका है, उसे पहले वापसी-दावा करना होगा: § 6511 सामान्यतः रिटर्न के 3 वर्ष या भुगतान के 2 वर्ष — जो बाद में हो — तक दावा देता है; § 7422 दावे की अस्वीकृति या छह माह की निष्क्रियता से पहले वाद रोकता है। वाद ज़िला न्यायालय या संघीय दावा न्यायालय में जाता है (28 U.S.C. § 1346(a)(1)), और *Flora v. United States*, 362 U.S. 145 (1960) ने **पूर्ण भुगतान नियम (full payment rule)** स्थापित किया: आयकर-कमी पर निर्धारित पूरी राशि चुकाए बिना वापसी-वाद नहीं चल सकता। परीक्षा की एक पंक्ति: कर न्यायालय में पहले लड़ो, बाद में दो; वापसी-न्यायालय में पहले दो, बाद में लड़ो — दूसरी छमाही का स्रोत *Flora* है।

**न्यायालय से पहले।** ऑडिट पुनर्विचार (audit reconsideration) प्रशासनिक व्यवहार मात्र है, वैधानिक अधिकार नहीं, और 90 दिन की घड़ी कभी नहीं रोकता। वैधानिक माध्यम है § 7803(e) के तहत IRS स्वतंत्र अपील कार्यालय (Independent Office of Appeals), जिसका काम बिना मुकदमे, निष्पक्ष रूप से विवाद सुलझाना है और जो सिद्धांततः सभी करदाताओं के लिए उपलब्ध है; उसके अधिकारी मुकदमे के जोखिम (hazards of litigation) को तौल सकते हैं।

**वसूली सुनवाई (§§ 6320, 6330).** निर्धारित कर अचुकाया रहे तो IRS संघीय कर ग्रहणाधिकार (lien) दर्ज कर सकता है और खातों व वेतन पर लेवी कर सकता है — परंतु § 6320 (lien) और § 6330 (levy) वसूली उचित-प्रक्रिया (CDP) सुनवाई देते हैं: पहली लेवी से कम से कम 30 दिन पहले सुनवाई-अधिकार की सूचना आवश्यक है; समय पर (30 दिनों में) CDP अनुरोध अपील कार्यालय सुनता है, जहाँ किस्त-समझौता (§ 6159) या समझौता-प्रस्ताव (offer in compromise) जैसे विकल्प रखे जा सकते हैं, और मूल देयता पर तभी बहस हो सकती है जब पहले न कमी-सूचना मिली हो न बहस का अवसर। निर्धारण-सूचना (notice of determination) के 30 दिनों में कर न्यायालय में याचिका संभव है; देर का अनुरोध केवल समतुल्य सुनवाई (equivalent hearing) देता है, जिसकी न्यायिक समीक्षा नहीं होती।

**कैलिफ़ोर्निया।** संघीय शैली का पूर्व-भुगतान-रहित न्यायालय यहाँ नहीं है। रास्ता पहले प्रशासनिक है: FTB के प्रस्तावित निर्धारण नोटिस पर सामान्यतः **60 दिनों में** लिखित विरोध (protest), फिर FTB के कार्रवाई नोटिस के विरुद्ध सामान्यतः **30 दिनों में** **कर अपील कार्यालय (Office of Tax Appeals, OTA)** में अपील। OTA 2017 के करदाता पारदर्शिता व निष्पक्षता अधिनियम से बना और **1 जनवरी 2018 से** बोर्ड ऑफ़ इक्वलाइज़ेशन के अपील-कार्य को संभालता है; तीन प्रशासनिक न्यायाधीशों के पैनल FTB और CDTFA की अपीलें सुनते हैं। न्यायालय के द्वार पर कैलिफ़ोर्निया संविधान अनुच्छेद XIII, § 32 का 'पहले दो, फिर लड़ो' नियम लागू है: कोई न्यायालय राज्य के कर-संग्रह को रोक नहीं सकता, और अवैध बताया गया कर **चुकाने के बाद ही** उसकी वसूली का वाद चल सकता है। कर न्यायालय जैसा विकल्प न होने से राज्य-कर विवाद का असली भार FTB विरोध और OTA अपील पर है — और उनकी छोटी समय-सीमाएँ कोई ढील नहीं देतीं।

*व्यक्तिगत अध्ययन नोट; कानूनी या कर सलाह नहीं। स्रोत: I.R.C. §§ 6159, 6211–6213, 6320, 6330, 6511, 7422, 7441, 7443, 7463, 7803(e); 28 U.S.C. § 1346(a)(1); Flora v. United States, 362 U.S. 145 (1960); Cal. Const. art. XIII, § 32; कैलिफ़ोर्निया AB 102 (2017).*

---

## 六语集中声明区 / Multilingual Disclaimer

- 中文：个人学习笔记，不构成法律或税务建议。具体案件请咨询有执业资格的律师或税务专业人士。
- English: Personal study notes only; not legal or tax advice. For a specific matter, consult a licensed attorney or tax professional.
- Español: Notas personales de estudio; no constituye asesoramiento legal ni fiscal. Para un caso concreto, consulte a un abogado o profesional fiscal con licencia. (traducción de estudio)
- 한국어: 개인 학습 노트이며 법률·세무 자문이 아닙니다. 구체적인 사안은 자격을 갖춘 변호사나 세무 전문가에게 상담하세요. (초역, 원어민 감수 대기)
- Tiếng Việt: Ghi chép học tập cá nhân, không phải tư vấn pháp lý hay thuế. Với vụ việc cụ thể, hãy hỏi luật sư hoặc chuyên gia thuế có giấy phép hành nghề. (bản dịch sơ bộ, chờ hiệu đính)
- हिन्दी: व्यक्तिगत अध्ययन नोट; कानूनी या कर सलाह नहीं है। किसी विशिष्ट मामले के लिए लाइसेंसधारी वकील या कर विशेषज्ञ से परामर्श करें। (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)
