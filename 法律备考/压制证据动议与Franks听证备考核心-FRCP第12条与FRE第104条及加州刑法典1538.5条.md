# 压制证据动议与 Franks 听证备考核心：FRCP 第 12 条、FRE 第 104 条与加州《刑法典》第 1538.5 条

> 个人学习笔记，不构成法律建议。本篇只管刑事案件里把非法取得的证据挡在审判之外的程序：压制动议何时提、由谁证明、搜查令申请书造假时怎样打开 Franks 听证。选题经 ls 文件名加 grep 正文双查：备考板块已有《刑事诉讼程序备考核心》讲第四、第五、第六修正案与排除规则总论，案例分析板块另有 United States v. Leon 案本体分析，Franks v. Delaware 只在 Leon 篇里作关联判例与善意例外关闭线出现，压制动议与 Franks 听证在备考板块无本体专篇，本篇补这一格。

## 中文主文

### 一、先定性：压制动议打的不是有罪无罪，是证据能不能进门

压制证据动议（motion to suppress）是审前程序工具：被告主张某件证据是政府违反宪法取得的，请法院在审判开始前就裁定该证据不得呈给陪审团。它背后的实体规则是排除规则——Mapp v. Ohio, 367 U.S. 643 (1961)（美国联邦最高法院）把第四修正案的排除规则适用于各州，违反第四修正案取得的证据在州刑事审判中同样要排除；Wong Sun v. United States, 371 U.S. 471 (1963) 再给出毒树之果逻辑：非法行为的直接产物与由其线索衍生取得的证据，原则上都沾了毒。压制动议判的只是证据的进门资格，不判被告有没有罪；动议赢了，检方失去该证据后可能撤案或弱化指控，动议输了，案件照常进入审判，被告仍可在上诉中再争。本案的两个算例先记：Mapp 距今 65 年（2026 减 1961 等于 65，本地复算两遍一致）。

### 二、时机与形式：第 12 条的审前时钟与第 104 条的听证摆位

联邦刑事案件里，压制动议的提出时机由《联邦刑事诉讼规则》第 12 条管。第 12(b)(3)(C) 条把压制证据动议列入必须在审前提出的动议：理由在审前已经存在的，拖到审判中才提，原则上视为放弃；第 12(c)(3) 条只留一道窄口——逾期提出的，须有正当理由（good cause）法院才考虑。所以备考与实务的第一动作都是数日子：拿到开示材料、看出搜查扣押的毛病，就要在审前动议截止日前把压制动议递进去。

听证的摆位由《联邦证据规则》第 104 条接住。第 104(a) 条定初步问题由法官决定，法官不受证据规则约束（特权规则除外）；第 104(c) 条要求，听证若涉及供述的可采性，必须在陪审团听不到的情况下进行，其他初步问题的听证在正义需要时也应如此安排；第 104(d) 条保护被告：被告就初步问题出庭作证，不因此放弃在审判中作证或不作证的权利，且其就该初步问题之外的事项不受交叉询问。这三款合起来是压制听证的程序骨架：法官先行、陪审团回避、被告为打动议出庭不会把自己在审判中的位置赔进去。

### 三、举证责任的摆位：被告先点火，政府对无令搜查负证明之责

压制听证上的举证分两步。第一步在被告：要提出具体异议，指出哪一次搜查或扣押、违反了被告本人的哪一项权利。第四修正案权利是个人权利——Rakas v. Illinois, 439 U.S. 128 (1978) 定下，被告只能主张自己的权利受侵害，不能拿同车乘客或同住人权利受侵害来替自己压制证据，答题时先查这一点（实务上常称 target standing 不成立）。第二步在政府：搜查有令状的，令状与执行方式的合法性按申请书与令状本身审；搜查没有令状的，通说由政府以优势证据（preponderance of the evidence）证明搜查落在某项无令例外之内或另有合法依据。摆位记反是最常见的丢分点：被告的活是把争议具体地提出来并初步站住，政府的活是把无令搜查的合法性证明到位。

### 四、Franks 听证两道门：先过初步表明，再做剔除后的相当理由

令状案里最锋利的一支动议，是主张签发令状所依据的申请书（affidavit）造了假，通道由 Franks v. Delaware, 438 U.S. 154 (1978)（美国联邦最高法院）打开。本案距今 48 年（2026 减 1978 等于 48，本地复算两遍一致）。Franks 给被告开的只是一场证据听证，而且要连过两道门。

第一道门是实质性初步表明（substantial preliminary showing）：被告须具体指出申请书中哪一句是假的，并表明该陈述是申请人在明知虚假、或轻率漠视真实（reckless disregard for the truth）的心态下放入的；单纯过失、笔误或证据不足都不够，只有结论、没有支撑材料的指控也过不了门，申请时应附上说明与可提供的宣誓陈述等材料。第二道门是必要性：被指虚假的陈述必须对治安法官作出相当理由（probable cause）认定是必要的——把虚假陈述从申请书里剔除之后，剩下的内容若仍足以支持相当理由，听证不开、令状不废。多数巡回法院把同一检验扩及故意或轻率地遗漏重大事实的情形：按遗漏的事实补入后重新判断相当理由。两道门都过了，被告在听证上再以优势证据证明虚假与心态，法院做剔除（或补入）后的相当理由判断；虚假陈述确属必要成分的，令状无效，由此取得的证据依毒树之果排除。

### 五、与 Leon 的分工：信赖关与造假关是两条线

Franks 常与善意例外被放在一起考，分工要说清。United States v. Leon, 468 U.S. 897 (1984) 定的是：警察合理信赖一张表面有效的令状行事时，纵使令状后来被认定缺乏相当理由，证据也不排除——威慑的对象不在这种警察身上。但 Leon 自己在判决里划了关闭线，其中第一条正是法官被误导：申请书里有申请人明知虚假或轻率漠视真实、且对相当理由成立必要的信息时，信赖不再合理。Franks 听证就是打这条关闭线的程序通道。两案合读的口诀：Leon 管信赖成立时不排除，Franks 管申请书造假时先开听证、再谈排除；顺序不能反——先 Franks 后 Leon，先查申请书的真假，再谈执行警察的信赖是否合理。

### 六、加州落点：第 1538.5 条的成文通道与联邦口径对齐

加州刑事案件的压制动议走《刑法典》第 1538.5 条这条成文通道：被告以搜查或扣押违反州或联邦宪法为由，可在一审提出压制动议并请求举行听证，由审理法院先行裁定证据可采性，实务节奏与联邦的审前动议加听证同构。另有一条加州特有的对齐规则要记：加州《宪法》第一条第 28(f)(2) 条是 1982 年第 8 号提案写入的真实证据条款，加州最高法院在 In re Lance W., 37 Cal.3d 873 (1985) 中据此认定，除联邦宪法本身要求排除的情形外，州法院不得再以州宪法为据排除相关证据——也就是说，加州压制之争的胜负标准原则上与联邦第四修正案口径对齐，Franks 与 Leon 的联邦框架在加州法院直接可用。第 1538.5 条一带另有检方救济坐标：准许压制并导致案件无法继续的裁定，检方有相应的上诉与复审通道，答题时只记有此坐标、按该条原文核对适用情形。

### 七、备考要点

1. 定性先行：压制动议只判证据进门资格，实体底盘是 Mapp 的排除规则与 Wong Sun 的毒树之果。
2. 时钟在第 12 条：第 12(b)(3)(C) 条压制动议必须审前提出，逾期看第 12(c)(3) 条的正当理由窄口。
3. 听证摆位看第 104 条：法官决定初步问题，供述可采性听证须在陪审团听不到时进行，被告就初步问题作证受第 104(d) 条保护。
4. 举证两步：被告先具体异议并守住本人权利（Rakas 的个人权利线），政府对无令搜查以优势证据证明合法。
5. Franks 两道门：实质性初步表明（明知或轻率漠视的虚假陈述）加必要性（剔除后相当理由不再成立），多数巡回扩及故意遗漏。
6. 与 Leon 分工：先 Franks 查申请书真假、后 Leon 谈信赖；加州走第 1538.5 条，排除标准经第 28(f)(2) 条与 Lance W. 与联邦对齐。

*个人学习笔记，不构成法律建议。*

## English

A motion to suppress is a pretrial tool: the defendant argues that evidence was obtained in violation of the Constitution and asks the court to bar it from the jury before trial begins. Its substantive base is the exclusionary rule — Mapp v. Ohio, 367 U.S. 643 (1961) (65 years ago: 2026 minus 1961) applied the Fourth Amendment exclusionary rule to the states, and Wong Sun v. United States, 371 U.S. 471 (1963) supplied the fruit-of-the-poisonous-tree logic for direct and derivative products of illegality. Timing is governed by Federal Rule of Criminal Procedure 12: Rule 12(b)(3)(C) lists suppression motions among those that must be raised before trial, and Rule 12(c)(3) excuses a late motion only for good cause. The hearing sits under Federal Rule of Evidence 104: under Rule 104(a) the judge decides preliminary questions; under Rule 104(c) a hearing on the admissibility of a confession must be conducted outside the jury's hearing; and under Rule 104(d) a defendant who testifies on a preliminary question does not thereby lose trial testimony rights and is not subject to cross-examination on other issues. Burdens come in two steps: the defendant must make a specific objection and invoke the defendant's own rights — Rakas v. Illinois, 439 U.S. 128 (1978) holds Fourth Amendment rights are personal and cannot be asserted vicariously — and the government then bears the burden, generally by a preponderance, of justifying a warrantless search under an exception or other lawful basis.

The sharpest warrant-case motion attacks the affidavit itself, through Franks v. Delaware, 438 U.S. 154 (1978) (48 years ago). A Franks hearing has two gates: first, a substantial preliminary showing that the affidavit contains a statement that is false and was included knowingly or with reckless disregard for the truth — negligence, mistake, or conclusory allegations are not enough; second, materiality — the false statement must be necessary to the probable-cause finding, so if the affidavit purged of the false material still supports probable cause, there is no hearing and no relief. Most circuits extend the same test to deliberate or reckless omissions, reinserting the omitted facts before judging probable cause. At the hearing the defendant must prove falsity and state of mind by a preponderance; if the false statement was necessary, the warrant is void and the fruits are excluded. United States v. Leon, 468 U.S. 897 (1984) is the companion line: good-faith reliance on a facially valid warrant normally defeats exclusion, but Leon itself closed that door where the magistrate was misled by knowing or reckless falsity necessary to probable cause — so the order of analysis is Franks first, Leon second. In California, the suppression motion runs through Penal Code Section 1538.5, and because Article I, Section 28(f)(2) of the state constitution (Proposition 8 of 1982), as read in In re Lance W., 37 Cal.3d 873 (1985), ties state exclusion to what the federal Constitution requires, the federal Franks and Leon framework applies directly in California courts.

*Note: Personal study notes, not legal advice.*

## Español (初译待校)

La moción de supresión es una herramienta previa al juicio: el acusado sostiene que una prueba se obtuvo violando la Constitución y pide que se le cierre la puerta antes de que la vea el jurado. Su base sustantiva es la regla de exclusión: Mapp v. Ohio, 367 U.S. 643 (1961) (hace 65 años) aplicó la regla de la Cuarta Enmienda a los estados, y Wong Sun v. United States, 371 U.S. 471 (1963) aportó la lógica del fruto del árbol envenenado. El plazo lo fija la Regla 12 de las Reglas Federales de Procedimiento Penal: la Regla 12(b)(3)(C) exige plantear la supresión antes del juicio y la Regla 12(c)(3) solo excusa la tardanza por causa justificada. La audiencia se rige por la Regla 104 de las Reglas Federales de Evidencia: el juez decide las cuestiones preliminares (104(a)); la audiencia sobre admisibilidad de una confesión debe celebrarse fuera del oído del jurado (104(c)); y el acusado que declara sobre una cuestión preliminar no pierde sus derechos en el juicio ni puede ser contrainterrogado sobre otros temas (104(d)). La carga va en dos pasos: el acusado debe objetar con concreción e invocar sus propios derechos — Rakas v. Illinois, 439 U.S. 128 (1978): los derechos de la Cuarta Enmienda son personales e intransferibles — y el gobierno debe justificar, por preponderancia, todo registro sin orden judicial.

El ataque más fino contra una orden judicial es contra la propia declaración jurada, por la vía de Franks v. Delaware, 438 U.S. 154 (1978) (hace 48 años). La audiencia Franks tiene dos puertas: una demostración preliminar sustancial de que la declaración contiene una afirmación falsa incluida a sabiendas o con desprecio temerario por la verdad — la negligencia o las alegaciones conclusorias no bastan — y la necesidad: la afirmación falsa debe ser necesaria para la causa probable, de modo que si la declaración depurada aún la sostiene, no hay audiencia ni remedio. La mayoría de los circuitos extiende la prueba a las omisiones deliberadas o temerarias, reinsertando los hechos omitidos. En la audiencia el acusado prueba la falsedad y el estado mental por preponderancia; si la afirmación era necesaria, la orden es nula y se excluyen los frutos. United States v. Leon, 468 U.S. 897 (1984) es la línea compañera: la confianza de buena fe en una orden facialmente válida suele evitar la exclusión, pero el propio Leon cerró esa puerta cuando el juez fue engañado con falsedad necesaria para la causa probable; el orden es Franks primero, Leon después. En California la moción sigue el § 1538.5 del Código Penal, y como el artículo I, § 28(f)(2) de la constitución estatal (Proposición 8 de 1982), según In re Lance W., 37 Cal.3d 873 (1985), ata la exclusión estatal a lo que exige la Constitución federal, el marco de Franks y Leon se aplica directamente. (初译待校)

*Notas personales de estudio; no es asesoramiento legal.*

## 한국어 (初译待校)

증거배제 신청은 재판 전 도구입니다. 피고인은 증거가 헌법에 위반되게 수집됐다고 주장하며 배심이 보기 전에 그 증거를 막아 달라고 법원에 요청합니다. 실체적 바탕은 배제법칙입니다. Mapp v. Ohio, 367 U.S. 643 (1961)(65년 전)은 수정헌법 제4조의 배제법칙을 주에도 적용했고, Wong Sun v. United States, 371 U.S. 471 (1963)은 독수독과 논리를 제공했습니다. 시기는 연방형사소송규칙 제12조가 정합니다. 제12(b)(3)(C)조는 배제 신청을 재판 전에 제기해야 할 신청으로 열거하고, 제12(c)(3)조는 정당한 사유가 있을 때만 지각 신청을 받아 줍니다. 심리는 연방증거규칙 제104조 아래에 있습니다. 제104(a)조에서 판사가 예비 문제를 결정하고, 제104(c)조에서 자백의 허용성에 관한 심리는 배심이 듣지 못하는 곳에서 열려야 하며, 제104(d)조에서 예비 문제에 대해 증언한 피고인은 재판에서의 증언권을 잃지 않고 다른 사항에 대해 반대신문을 받지 않습니다. 입증책임은 두 단계입니다. 피고인이 구체적으로 이의를 제기하고 자기 자신의 권리를 주장해야 합니다. Rakas v. Illinois, 439 U.S. 128 (1978)은 제4조 권리가 개인적 권리라 남의 권리 침해를 대신 주장할 수 없다고 했습니다. 그다음 영장 없는 수색의 적법성은 정부가 우월한 증거로 예외나 다른 적법 근거를 입증해야 합니다.

영장 사건에서 가장 날카로운 신청은 진술서 자체를 공격하는 Franks v. Delaware, 438 U.S. 154 (1978)(48년 전)의 통로입니다. Franks 심리에는 두 개의 문이 있습니다. 첫째, 진술서에 거짓임을 알았거나 진실에 대한 무모한 무시를 하고 넣은 거짓 진술이 있다는 실질적인 예비 소명입니다. 과실이나 결론뿐인 주장은 부족합니다. 둘째, 필요성입니다. 거짓 진술이 상당한 이유의 인정에 필요해야 하고, 거짓 부분을 제거한 진술서가 여전히 상당한 이유를 뒷받침하면 심리는 열리지 않습니다. 대부분의 순회법원은 같은 검사를 고의 또는 무모한 중대 사실 누락에도 확장해, 누락된 사실을 다시 넣어 상당한 이유를 판단합니다. 심리에서 피고인은 거짓과 심리 상태를 우월한 증거로 입증해야 하고, 거짓 진술이 필요했던 경우 영장은 무효가 되며 그 열매는 배제됩니다. United States v. Leon, 468 U.S. 897 (1984)은 짝이 되는 선입니다. 표면상 유효한 영장에 대한 선의의 신뢰는 보통 배제를 막지만, Leon 자체가 상당한 이유에 필요한 거짓으로 판사가 오도된 경우에는 그 문을 닫았습니다. 그래서 순서는 Franks가 먼저, Leon이 다음입니다. 캘리포니아에서 배제 신청은 형법전 제1538.5조를 따르고, 주 헌법 제1조 제28(f)(2)항(1982년 제8호 발의안)이 In re Lance W., 37 Cal.3d 873 (1985)에서 읽힌 대로 주 차원의 배제를 연방 헌법이 요구하는 범위에 묶어 두므로, Franks와 Leon의 연방 틀이 캘리포니아 법원에도 직접 적용됩니다. (初译待校)

*개인 학습 노트이며 법률 조언이 아닙니다.*

## Tiếng Việt (初译待校)

Đơn xin loại trừ chứng cứ là công cụ trước phiên tòa: bị cáo cho rằng chứng cứ bị thu giữ trái Hiến pháp và xin tòa chặn nó trước khi bồi thẩm đoàn nhìn thấy. Nền tảng thực chất là quy tắc loại trừ — Mapp v. Ohio, 367 U.S. 643 (1961) (65 năm trước) áp dụng quy tắc loại trừ của Tu chính án 4 cho các bang, và Wong Sun v. United States, 371 U.S. 471 (1963) đưa ra logic quả của cây độc. Thời hạn do Quy tắc 12 của Quy tắc Tố tụng Hình sự Liên bang định: Quy tắc 12(b)(3)(C) liệt kê đơn loại trừ vào nhóm phải nộp trước phiên tòa, và Quy tắc 12(c)(3) chỉ chấp nhận nộp muộn khi có lý do chính đáng. Phiên điều trần nằm dưới Quy tắc 104 của Quy tắc Chứng cứ Liên bang: thẩm phán quyết định các vấn đề sơ bộ theo 104(a); điều trần về tính chấp nhận được của lời thú tội phải diễn ra ngoài tầm nghe của bồi thẩm đoàn theo 104(c); và bị cáo làm chứng về vấn đề sơ bộ không vì thế mất quyền làm chứng tại phiên tòa và không bị thẩm vấn chéo về các vấn đề khác theo 104(d). Gánh nặng đi hai bước: bị cáo phải phản đối cụ thể và viện dẫn quyền của chính mình — Rakas v. Illinois, 439 U.S. 128 (1978): quyền Tu chính án 4 là quyền cá nhân, không thể viện dẫn thay người khác — và sau đó chính phủ phải chứng minh, theo tiêu chuẩn preponderance, rằng cuộc khám xét không lệnh thuộc một ngoại lệ hoặc có căn cứ hợp pháp khác.

Đòn tấn công sắc nhất trong vụ án có lệnh là tấn công chính bản tuyên thệ, qua Franks v. Delaware, 438 U.S. 154 (1978) (48 năm trước). Phiên điều trần Franks có hai cổng: một chứng minh sơ bộ đáng kể rằng bản tuyên thệ chứa phát biểu sai được đưa vào khi biết là sai hoặc coi thường sự thật một cách liều lĩnh — sơ suất hay cáo buộc kết luận suông đều không đủ; và tính cần thiết: phát biểu sai phải cần cho việc xác định probable cause, nên nếu bản tuyên thệ sau khi loại bỏ phần sai vẫn đủ probable cause thì không có điều trần và không có biện pháp khắc phục nào. Phần lớn các tòa circuit mở rộng cùng phép thử cho việc cố ý hoặc liều lĩnh bỏ sót sự kiện trọng yếu, bằng cách đưa sự kiện bị bỏ sót trở lại rồi mới xét probable cause. Tại phiên điều trần, bị cáo phải chứng minh tính sai và trạng thái tâm lý theo preponderance; nếu phát biểu sai là cần thiết, lệnh vô hiệu và thành quả bị loại trừ. United States v. Leon, 468 U.S. 897 (1984) là tuyến đi kèm: sự tin cậy thiện chí vào một lệnh có vẻ hợp lệ thường chặn việc loại trừ, nhưng chính Leon đã đóng cánh cửa đó khi thẩm phán bị đánh lừa bằng sự sai lệch cần thiết cho probable cause; thứ tự là Franks trước, Leon sau. Tại California, đơn loại trừ đi theo § 1538.5 Bộ luật Hình sự, và vì Điều I, § 28(f)(2) của hiến pháp bang (Đề xuất 8 năm 1982), theo cách đọc trong In re Lance W., 37 Cal.3d 873 (1985), gắn việc loại trừ ở cấp bang với những gì Hiến pháp liên bang đòi hỏi, nên khung Franks và Leon áp dụng trực tiếp tại tòa án California. (初译待校)

*Ghi chú học tập cá nhân, không phải tư vấn pháp lý.*

## हिन्दी (初译待校)

दमन प्रस्ताव (motion to suppress) विचारण-पूर्व का साधन है: अभियुक्त कहता है कि साक्ष्य संविधान का उल्लंघन करके प्राप्त किया गया और न्यायालय से कहता है कि जूरी के देखने से पहले उसे रोक दिया जाए। इसका वास्तविक आधार अपवर्जन नियम है — Mapp v. Ohio, 367 U.S. 643 (1961) (65 वर्ष पूर्व) ने चौथे संशोधन के अपवर्जन नियम को राज्यों पर लागू किया, और Wong Sun v. United States, 371 U.S. 471 (1963) ने विषैले वृक्ष के फल का तर्क दिया। समय संघीय आपराधिक प्रक्रिया नियम 12 से तय होता है: नियम 12(b)(3)(C) दमन प्रस्तावों को विचारण से पहले उठाए जाने वालों में गिनता है, और नियम 12(c)(3) देर से आए प्रस्ताव को केवल उचित कारण पर ही क्षमा करता है। सुनवाई संघीय साक्ष्य नियम 104 के अधीन होती है: 104(a) के तहत न्यायाधीश प्रारंभिक प्रश्न तय करता है; 104(c) के तहत स्वीकारोक्ति की ग्राह्यता पर सुनवाई जूरी की सुनवाई से बाहर होनी चाहिए; और 104(d) के तहत प्रारंभिक प्रश्न पर गवाही देने वाला अभियुक्त विचारण में गवाही के अपने अधिकार नहीं खोता और अन्य विषयों पर प्रति-परीक्षण के अधीन नहीं होता। भार दो चरणों में चलता है: अभियुक्त को विशिष्ट आपत्ति उठानी होती है और अपने ही अधिकारों का सहारा लेना होता है — Rakas v. Illinois, 439 U.S. 128 (1978): चौथे संशोधन के अधिकार व्यक्तिगत हैं, किसी और के अधिकार का उल्लंघन अपने लिए नहीं उठाया जा सकता — और फिर सरकार को preponderance से यह सिद्ध करना होता है कि बिना वारंट की तलाशी किसी अपवाद या अन्य वैध आधार में आती है।

वारंट वाले मामलों में सबसे तीखा हमला स्वयं शपथपत्र पर होता है, Franks v. Delaware, 438 U.S. 154 (1978) (48 वर्ष पूर्व) के मार्ग से। Franks सुनवाई के दो द्वार हैं: पहला, यह ठोस प्रारंभिक प्रदर्शन कि शपथपत्र में ऐसा कथन है जो झूठा है और जानबूझकर या सत्य के प्रति लापरवाह अवहेलना के साथ डाला गया था — लापरवाही या केवल निष्कर्ष वाले आरोप पर्याप्त नहीं; दूसरा, आवश्यकता: झूठा कथन probable cause की खोज के लिए आवश्यक होना चाहिए, इसलिए यदि झूठे भाग को हटाने के बाद भी शपथपत्र probable cause देता है तो न सुनवाई होगी न उपाय। अधिकांश circuit यही परीक्षण जानबूझकर या लापरवाही से किए गए महत्वपूर्ण तथ्यों के लोप पर भी लागू करते हैं, लुप्त तथ्य को वापस रखकर probable cause परखते हैं। सुनवाई में अभियुक्त को preponderance से झूठ और मनःस्थिति सिद्ध करनी होती है; यदि झूठा कथन आवश्यक था तो वारंट शून्य होता है और उसके फल अपवर्जित होते हैं। United States v. Leon, 468 U.S. 897 (1984) साथ वाली रेखा है: सतही रूप से वैध वारंट पर सद्भावपूर्ण भरोसा सामान्यतः अपवर्जन रोकता है, परंतु Leon ने स्वयं वह द्वार वहाँ बंद किया जहाँ न्यायाधीश को probable cause के लिए आवश्यक झूठ से गुमराह किया गया हो; क्रम है पहले Franks, फिर Leon। California में दमन प्रस्ताव दंड संहिता § 1538.5 से चलता है, और क्योंकि राज्य संविधान का अनुच्छेद I, § 28(f)(2) (1982 का प्रस्ताव 8), In re Lance W., 37 Cal.3d 873 (1985) में पढ़े गए रूप में, राज्य अपवर्जन को उसी से बाँधता है जो संघीय संविधान चाहता है, इसलिए Franks और Leon का संघीय ढाँचा California की अदालतों में सीधे लागू होता है। (初译待校)

*व्यक्तिगत अध्ययन नोट, कानूनी सलाह नहीं।*

## 补译增量（2026-11-22 01:55 轮）

### 한국어 (초역, 원어민 감수 대기 / 初译待校)

보충 세부: 첫째, 연방증거규칙 제104(a)조에서 판사가 예비 문제를 결정할 때 판사는 증거규칙에 구속되지 않으며, 특권에 관한 규칙만은 예외입니다. 둘째, Franks의 실질적인 예비 소명은 서류로 뒷받침되어야 합니다. 신청할 때는 설명과 제출할 수 있는 선서 진술 등의 자료를 붙여야 하고, 뒷받침 자료 없이 결론만 내세우는 주장은 첫 번째 문을 통과하지 못합니다.

### Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính / 初译待校)

Chi tiết bổ sung: thứ nhất, theo Quy tắc 104(a) của Quy tắc Chứng cứ Liên bang, khi quyết định các vấn đề sơ bộ, thẩm phán không bị ràng buộc bởi các quy tắc chứng cứ, chỉ trừ các quy tắc về đặc quyền. Thứ hai, chứng minh sơ bộ đáng kể của Franks phải có tài liệu chống lưng: khi nộp đơn phải kèm bản giải trình và những bản tuyên thệ có thể cung cấp được; cáo buộc chỉ có kết luận mà không có tài liệu hỗ trợ thì không qua nổi cổng đầu tiên.

### हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित / 初译待校)

पूरक विवरण: पहला, संघीय साक्ष्य नियम 104(a) के तहत प्रारंभिक प्रश्न तय करते समय न्यायाधीश साक्ष्य-नियमों से बँधा नहीं होता, केवल विशेषाधिकार संबंधी नियम इसका अपवाद हैं। दूसरा, Franks का ठोस प्रारंभिक प्रदर्शन दस्तावेज़ों से समर्थित होना चाहिए: आवेदन के साथ व्याख्या और उपलब्ध कराए जा सकने वाले शपथ-कथन जैसी सामग्री लगानी होती है; बिना सहायक सामग्री के केवल निष्कर्ष वाले आरोप पहला द्वार पार नहीं करते।
