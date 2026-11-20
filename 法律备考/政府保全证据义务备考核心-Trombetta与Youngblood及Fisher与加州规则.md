# 政府保全证据义务备考核心：Trombetta、Youngblood、Fisher 与加州规则

> 个人学习笔记，不构成法律建议。分工：与仓内《联邦刑事证据开示与布雷迪义务备考核心》分工——该篇管检方把已经掌握的有利证据压着不给（披露线），本篇管证据在政府手里没有留住、灭失了怎么办（保全线）。两条线的检验完全不同，答题时先分类再套规则。选题经 ls 文件名加 git grep 正文双查：California v. Trombetta、Arizona v. Youngblood、Illinois v. Fisher 在全仓零命中，政府保全证据义务无本体专篇。

## 中文主文

### 一、先定性：证据没了，先分「压着不给」还是「没有留住」

刑事被告说「关键证据没了」，宪法上有两条完全不同的路。第一条是披露线：Brady v. Maryland, 373 U.S. 83 (1963)（美国联邦最高法院）——检方压着对被告有利的重要证据不披露，违反正当程序，重要性按 United States v. Bagley, 473 U.S. 667 (1985) 的「合理可能性会改变结果」来量。这条线的前提是证据还在、检方知道、就是不给。第二条是保全线：证据在警方或检方保管期间被销毁、丢失或任其降解，被告连看都没看到过。这条线不问检方有没有隐瞒，只问政府在灭失这件事上有没有尽到宪法要求，以及丢掉的东西到底有多重要。本篇只走第二条。分类错了，后面全错：把灭失案套 Brady 的重要性检验，或者把披露案套下面要讲的恶意要件，都是备考最常见的丢分点。

### 二、源头：Trombetta——呼吸样本案立的材料性门槛

California v. Trombetta, 467 U.S. 479 (1984)（美国联邦最高法院，Marshall 执笔，全体一致，1984 年 6 月 11 日判决）。事实是加州公路巡警查酒驾，用 Intoxilyzer 仪器测呼吸酒精，测完样本按常规不保存；被告主张没有样本就无法复测、无法挑战仪器结果，要求撤销定罪。最高法院说不违宪，并立下保全线的第一道门：被灭失的证据必须同时满足两件——其一，它的免罪价值在灭失之前就已经显而易见（apparent exculpatory value），不是事后猜测「也许能测出点什么」；其二，被告无法通过其他合理可得的手段取得可比证据。呼吸样本两件都过不了：酒精读数可以靠仪器的校准记录、操作警员的证言和交叉询问来挑战，而且加州当时允许当事人选择血液或尿液检测，那些样本是留存的。法院还点了一句事实背景：警员是按既定常规行事，没有为损害被告而销毁的主观迹象。从 1984 年算到今天，2026 − 1984 ＝ 42 年，这道「显而易见的免罪价值加无可比替代」的门槛仍是保全线的起点。

### 三、收紧：Youngblood——潜在有用证据要过恶意这一关

Arizona v. Youngblood, 488 U.S. 51 (1988)（美国联邦最高法院，Rehnquist 执笔，6 比 3，1988 年 11 月 29 日判决）。这是一起性侵男童案：警方把受害者衣物等检材没有按要求冷藏，精液样本降解，鉴定只能给出不确定结论；亚利桑那州上诉法院以政府未保全证据为由撤销定罪，最高法院推翻。规则是：对只是「潜在有用」（potentially useful）的证据——就是 Trombetta 那道门过不去、免罪价值不显而易见的证据——政府未保全不构成正当程序违反，除非被告能证明警方出于恶意（bad faith）。理由写得很直白：警察的过失、粗心，至多是没有尽到保管注意，宪法不是一份替警方保管水平兜底的保险单；要不要追问动机，看的是警方在灭失当时对证据免罪潜力的认识和处理方式。Blackmun 的异议认为不该让被告的命运取决于警察的主观心态。Trombetta 到 Youngblood 只隔 1988 − 1984 ＝ 4 年，两案合起来就是完整的保全线：先问证据是哪一格——免罪价值显而易见的走 Trombetta，仅仅潜在有用的走 Youngblood 恶意检验。这个案子还有一段沉重的后日谈：2000 年，DNA 检测指向另一名男子，Youngblood 被释放、指控撤销，距判决 2000 − 1988 ＝ 12 年。备考时要分清：这段后日谈是评价恶意门槛代价的论点素材，不是检验本身的一部分，答题时别把它写进规则。

### 四、定档：Fisher——检验不因证据关键就改

Illinois v. Fisher, 540 U.S. 544 (2004)（美国联邦最高法院，per curiam 附带意见判决，2004 年 2 月 23 日）。被告因重罪人持枪被诉，中途潜逃多年，涉案枪支在警方按常规保管期满后被销毁；他归案后主张灭失枪支违反正当程序，伊利诺伊州上诉法院支持了他，最高法院未经完整审理直接推翻。法院强调两点：第一，涉案枪支至多属于「潜在有用」证据，哪怕它对案件重要，检验也不换挡，一律过 Youngblood 的恶意这一关；第二，本案销毁是按常规保管程序进行，没有任何证据显示警方是为了损害被告才销毁。被告潜逃造成的多年时滞，法院也记在背景里——政府按规程处理一件多年无人来领的证物，与盯着被告的辩护布局下手销毁，是两回事。从 Fisher 算到今天，2026 − 2004 ＝ 22 年，保全线的格局没有再动过。

### 五、答题动作：三格对号，最后查恶意

把三案排成答题顺序：第一步，先分类——证据是被压着不给，还是被灭失了？压着不给走 Brady 线，本篇到此为止。第二步，灭失的证据免罪价值在灭失前是否显而易见、且无可比替代？两件都满足，走 Trombetta，灭失本身即可构成违反。第三步，只要证据只是潜在有用，就落到 Youngblood 与 Fisher 一格：找恶意——警方知不知道这东西可能帮被告、有没有违反既定保管规程、有没有在收到保全请求后仍下手销毁、有没有选择性只留对检方有利的部分。按规程销毁、无恶意迹象，结论就是不违宪，哪怕丢掉的东西事后看很重要。反过来，一旦恶意立住，救济通常是撤销定罪或排除受影响的检方证据，具体形态由审理法院按损害裁量。记住口诀：披露看重要性，保全先看价值格、再看心。

### 六、加州落点：源头就在加州，州法可以给得更多

这条线的源头案本身就是加州案：Trombetta 里的执法者是加州公路巡警，测的是加州酒驾。而且加州法院走在前面——加州最高法院 People v. Hitch, 12 Cal.3d 641 (1974) 早先就在州法层面处理过呼吸测试样本的保全问题，对由检方独占控制的关键检材给出过保全要求。理解 Trombetta 的正确姿势是：它划的是联邦宪法的地板——联邦正当程序只要求到 Trombetta 与 Youngblood 为止；州完全可以在自己的宪法与法律里要求政府保全得更多，加州法院在州法问题上仍有自己的空间，答题时把「联邦地板」和「州法加码」分开写。程序侧的抓手是加州《刑法典》第 1054.1 条的检方开示清单，其中包括检方掌握的免罪证据；实务动作只有一条但很要紧：辩方尽早以书面提出具体证据的保全请求并留痕——书面请求本身不改变 Youngblood 的检验，却能固定「警方知道这东西重要」这一事实，日后论证恶意时就是最硬的那块拼图。与仓内《压制证据动议与 Franks 听证备考核心》分工：该篇管搜查扣押来的证据怎么压，本篇管证据在政府手里消失了怎么算账。

来源口径：U.S. Const. amend. XIV；Brady v. Maryland, 373 U.S. 83 (1963)；United States v. Bagley, 473 U.S. 667 (1985)；California v. Trombetta, 467 U.S. 479 (1984)；Arizona v. Youngblood, 488 U.S. 51 (1988)；Illinois v. Fisher, 540 U.S. 544 (2004)；People v. Hitch, 12 Cal.3d 641 (1974)；Cal. Penal Code § 1054.1。算例本地复算两遍一致：2026 − 1984 ＝ 42、2026 − 1988 ＝ 38、1988 − 1984 ＝ 4、2026 − 2004 ＝ 22、2000 − 1988 ＝ 12。

声明：个人学习笔记，不构成法律建议。

---

## English

**The government's duty to preserve evidence: Trombetta, Youngblood, Fisher and California.** Lost evidence runs on a different track from suppressed evidence. Brady v. Maryland, 373 U.S. 83 (1963) governs favorable evidence the prosecution holds back, with materiality measured under United States v. Bagley, 473 U.S. 667 (1985); the preservation line governs evidence destroyed, lost or allowed to degrade in government custody. California v. Trombetta, 467 U.S. 479 (1984) (Marshall, J., unanimous, decided June 11, 1984) set the first gate: destroyed breath samples in California Highway Patrol DUI cases did not violate due process, because evidence triggers the duty only if its exculpatory value was apparent before destruction and the defendant cannot obtain comparable evidence by other reasonably available means — the readings could be challenged through calibration records and cross-examination, and blood or urine alternatives were preserved. Arizona v. Youngblood, 488 U.S. 51 (1988) (Rehnquist, C.J., 6 to 3, decided November 29, 1988) added the second gate: for merely potentially useful evidence — there, unrefrigerated clothing whose semen samples degraded in a child sexual-assault case — failure to preserve violates due process only if the defendant proves police bad faith; negligence in storage is not a constitutional violation. A sobering coda: DNA testing in 2000 pointed to another man and Youngblood was released, 12 years after the decision — material for evaluating the bad-faith rule, not part of the test. Illinois v. Fisher, 540 U.S. 544 (2004) (per curiam, February 23, 2004) locked the framework: a gun destroyed under routine retention procedures while the defendant was a fugitive stayed in the Youngblood category even though it mattered to the case; the test does not change with the evidence's importance, and routine destruction without bad faith is constitutional. California is where the line began: People v. Hitch, 12 Cal.3d 641 (1974) had addressed breath-sample preservation under state law before Trombetta fixed the federal floor, and states remain free to demand more under their own law; Penal Code section 1054.1 lists the prosecution's disclosure duties, and the practical move is an early written preservation demand, which does not change the Youngblood test but fixes what the police knew. Arithmetic, recomputed twice: 2026 − 1984 = 42; 2026 − 1988 = 38; 1988 − 1984 = 4; 2026 − 2004 = 22; 2000 − 1988 = 12. Personal study notes only; not legal advice.

---

## Español — traducción de estudio (初译待校)

**El deber del gobierno de preservar la prueba: Trombetta, Youngblood, Fisher y California.** La prueba perdida sigue una vía distinta de la prueba ocultada. Brady v. Maryland, 373 U.S. 83 (1963) regula la prueba favorable que la fiscalía retiene, con la materialidad medida según United States v. Bagley, 473 U.S. 667 (1985); la línea de preservación regula la prueba destruida, extraviada o degradada bajo custodia estatal. California v. Trombetta, 467 U.S. 479 (1984) (Marshall, por unanimidad, 11 de junio de 1984) fijó la primera puerta: las muestras de aliento no conservadas en casos de DUI de la Patrulla de Caminos de California no violaron el debido proceso, porque el deber solo nace si el valor exculpatorio era aparente antes de la destrucción y el acusado no puede obtener prueba comparable por otros medios razonables — las lecturas podían impugnarse con los registros de calibración y el contrainterrogatorio, y las alternativas de sangre u orina sí se conservaban. Arizona v. Youngblood, 488 U.S. 51 (1988) (Rehnquist, 6 a 3, 29 de noviembre de 1988) añadió la segunda puerta: para la prueba meramente potencialmente útil — allí, ropa no refrigerada cuyas muestras de semen se degradaron en un caso de agresión sexual infantil — la falta de preservación solo viola el debido proceso si el acusado prueba la mala fe policial; la negligencia en el almacenamiento no es una violación constitucional. Una coda sobria: en 2000 el ADN señaló a otro hombre y Youngblood quedó libre, 12 años después de la sentencia — material para evaluar la regla de la mala fe, no parte de la prueba jurídica. Illinois v. Fisher, 540 U.S. 544 (2004) (per curiam, 23 de febrero de 2004) cerró el marco: un arma destruida según los procedimientos rutinarios de custodia mientras el acusado estaba fugitivo permaneció en la categoría de Youngblood aunque fuera importante para el caso; la prueba no cambia con la importancia de la evidencia, y la destrucción rutinaria sin mala fe es constitucional. California es donde empezó la línea: People v. Hitch, 12 Cal.3d 641 (1974) ya había tratado la preservación de muestras de aliento en el derecho estatal antes de que Trombetta fijara el piso federal, y los estados pueden exigir más en su propio derecho; la sección 1054.1 del Código Penal enumera los deberes de divulgación de la fiscalía, y el movimiento práctico es una solicitud escrita temprana de preservación, que no cambia la prueba de Youngblood pero fija lo que la policía sabía. Aritmética, recalculada dos veces: 2026 − 1984 = 42; 2026 − 1988 = 38; 1988 − 1984 = 4; 2026 − 2004 = 22; 2000 − 1988 = 12. Notas personales de estudio; no es asesoría legal. (初译待校)

---

## 한국어 — 초역, 교정 대기 중 (初译待校)

**정부의 증거 보전 의무: Trombetta, Youngblood, Fisher와 캘리포니아.** 사라진 증거는 숨긴 증거와 다른 궤도를 달린다. Brady v. Maryland, 373 U.S. 83 (1963)은 검사가 쥐고 공개하지 않은 유리한 증거를 다루고 중요성은 United States v. Bagley, 473 U.S. 667 (1985)로 재며, 보전 라인은 정부 보관 중에 파괴·분실·변질된 증거를 다룬다. California v. Trombetta, 467 U.S. 479 (1984)(Marshall 대법관, 전원 일치, 1984년 6월 11일 판결)가 첫 관문을 세웠다. 캘리포니아 고속도로순찰대의 음주운전 사건에서 보존되지 않은 호흡 샘플은 적법절차를 위반하지 않았는데, 그 이유는 보전 의무가 증거의 무죄 입증 가치가 파괴 전에 명백했고 피고인이 다른 합리적으로 이용 가능한 수단으로 비교 가능한 증거를 얻을 수 없을 때만 생기기 때문이다. 측정값은 교정 기록과 반대신문으로 다툴 수 있었고, 혈액·소변 대안은 보존되었다. Arizona v. Youngblood, 488 U.S. 51 (1988)(Rehnquist 대법원장, 6대 3, 1988년 11월 29일 판결)이 두 번째 관문을 더했다. 냉장되지 않아 정액 샘플이 변질된 아동 성폭행 사건의 옷처럼 단지 잠재적으로 유용한 증거에 대해서는, 피고인이 경찰의 악의(bad faith)를 입증할 때만 보전 실패가 적법절차 위반이 되며, 보관상의 과실은 위헌이 아니다. 무거운 뒷이야기 하나: 2000년 DNA 검사가 다른 남자를 가리켜 Youngblood는 판결 12년 뒤 석방되었는데, 이는 악의 기준을 평가하는 소재이지 기준 자체의 일부는 아니다. Illinois v. Fisher, 540 U.S. 544 (2004)(per curiam, 2004년 2월 23일)는 틀을 고정했다. 피고인이 도주 중일 때 통상 보관 절차에 따라 폐기된 총은 사건에 중요했더라도 Youngblood 범주에 머물렀고, 검사는 증거의 중요성에 따라 바뀌지 않으며, 악의 없는 통상 폐기는 합헌이다. 이 라인은 캘리포니아에서 시작되었다. People v. Hitch, 12 Cal.3d 641 (1974)이 Trombetta가 연방 하한을 정하기 전에 주법 차원에서 호흡 샘플 보전을 다뤘고, 주는 자체 법으로 더 많이 요구할 수 있다. 형법전 제1054.1조는 검사의 공개 의무를 열거하고, 실무상 움직임은 조기 서면 보전 요청으로, 이는 Youngblood 검사를 바꾸지 않지만 경찰이 무엇을 알았는지를 고정한다. 산식(두 번 재계산): 2026 − 1984 = 42, 2026 − 1988 = 38, 1988 − 1984 = 4, 2026 − 2004 = 22, 2000 − 1988 = 12. 개인 학습 노트이며 법률 자문이 아니다. (初译待校)

---

## Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

**Nghĩa vụ bảo quản chứng cứ của nhà nước: Trombetta, Youngblood, Fisher và California.** Chứng cứ bị mất đi theo một đường khác với chứng cứ bị giấu. Brady v. Maryland, 373 U.S. 83 (1963) điều chỉnh chứng cứ có lợi mà bên công tố giữ lại không công bố, với tính quan trọng đo theo United States v. Bagley, 473 U.S. 667 (1985); đường bảo quản điều chỉnh chứng cứ bị hủy, bị thất lạc hoặc bị phân hủy khi nhà nước đang giữ. California v. Trombetta, 467 U.S. 479 (1984) (Thẩm phán Marshall, nhất trí toàn thể, phán quyết ngày 11 tháng 6 năm 1984) dựng cổng đầu tiên: mẫu hơi thở không được lưu giữ trong các vụ DUI của Tuần tra Cao tốc California không vi phạm thủ tục hợp lệ, vì nghĩa vụ chỉ phát sinh khi giá trị minh oan của chứng cứ đã rõ ràng trước lúc bị hủy và bị cáo không thể có được chứng cứ tương đương bằng phương tiện hợp lý khác — kết quả đo có thể bị tranh cãi qua hồ sơ hiệu chuẩn và thẩm vấn chéo, còn mẫu máu hoặc nước tiểu thay thế thì được lưu giữ. Arizona v. Youngblood, 488 U.S. 51 (1988) (Chánh án Rehnquist, tỉ lệ 6 trên 3, phán quyết ngày 29 tháng 11 năm 1988) thêm cổng thứ hai: đối với chứng cứ chỉ tiềm năng hữu ích — ở đó là quần áo không được làm lạnh khiến mẫu tinh dịch phân hủy trong vụ xâm hại tình dục trẻ em — việc không bảo quản chỉ vi phạm thủ tục hợp lệ khi bị cáo chứng minh được ác ý (bad faith) của cảnh sát; sơ suất trong bảo quản không phải vi phạm hiến pháp. Một đoạn kết nặng nề: năm 2000, xét nghiệm DNA chỉ sang một người đàn ông khác và Youngblood được thả, 12 năm sau phán quyết — đây là chất liệu để đánh giá quy tắc ác ý, không phải một phần của tiêu chuẩn. Illinois v. Fisher, 540 U.S. 544 (2004) (per curiam, ngày 23 tháng 2 năm 2004) khóa khung lại: khẩu súng bị hủy theo thủ tục lưu giữ thường lệ trong lúc bị cáo bỏ trốn vẫn ở nhóm Youngblood dù quan trọng với vụ án; tiêu chuẩn không thay đổi theo tầm quan trọng của chứng cứ, và hủy theo thường lệ mà không có ác ý là hợp hiến. California là nơi đường này bắt đầu: People v. Hitch, 12 Cal.3d 641 (1974) đã xử lý việc bảo quản mẫu hơi thở theo luật bang trước khi Trombetta ấn định sàn liên bang, và các bang vẫn có thể đòi hỏi nhiều hơn theo luật của mình; Điều 1054.1 Bộ luật Hình sự liệt kê nghĩa vụ công bố của bên công tố, và bước thực tế là yêu cầu bảo quản bằng văn bản từ sớm — nó không đổi tiêu chuẩn Youngblood nhưng cố định điều cảnh sát đã biết. Số học, tính lại hai lần: 2026 − 1984 = 42; 2026 − 1988 = 38; 1988 − 1984 = 4; 2026 − 2004 = 22; 2000 − 1988 = 12. Ghi chú học tập cá nhân; không phải tư vấn pháp lý. (初译待校)

---

## हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

**साक्ष्य संरक्षित रखने का सरकारी दायित्व: Trombetta, Youngblood, Fisher और California.** खोया हुआ साक्ष्य छिपाए गए साक्ष्य से अलग रास्ते पर चलता है। Brady v. Maryland, 373 U.S. 83 (1963) उस अनुकूल साक्ष्य को नियंत्रित करता है जिसे अभियोजन दबा लेता है, और उसकी महत्वपूर्णता United States v. Bagley, 473 U.S. 667 (1985) से मापी जाती है; संरक्षण-रेखा उस साक्ष्य को देखती है जो सरकारी हिरासत में नष्ट, गुम या क्षीण हो गया हो। California v. Trombetta, 467 U.S. 479 (1984) (न्यायमूर्ति Marshall, सर्वसम्मत, 11 जून 1984 को निर्णय) ने पहला द्वार बनाया: California Highway Patrol के DUI मामलों में न रखे गए श्वास-नमूनों ने उचित प्रक्रिया का उल्लंघन नहीं किया, क्योंकि दायित्व तभी उठता है जब साक्ष्य का दोषमुक्ति-मूल्य नष्ट होने से पहले स्पष्ट हो और प्रतिवादी अन्य युक्तिसंगत उपलब्ध साधनों से तुलनीय साक्ष्य न पा सके — माप को अंशांकन अभिलेखों और प्रतिपरीक्षण से चुनौती दी जा सकती थी, और रक्त या मूत्र के विकल्प संरक्षित थे। Arizona v. Youngblood, 488 U.S. 51 (1988) (मुख्य न्यायमूर्ति Rehnquist, 6 बनाम 3, 29 नवंबर 1988) ने दूसरा द्वार जोड़ा: केवल संभावित रूप से उपयोगी साक्ष्य के लिए — वहाँ एक बाल यौन-शोषण मामले में बिना फ्रिज रखे कपड़े जिनके वीर्य-नमूने क्षीण हो गए — संरक्षण की विफलता तभी उचित प्रक्रिया का उल्लंघन है जब प्रतिवादी पुलिस की दुर्भावना (bad faith) सिद्ध करे; भंडारण में लापरवाही संवैधानिक उल्लंघन नहीं है। एक गंभीर परिशिष्ट: 2000 में DNA परीक्षण ने किसी अन्य व्यक्ति की ओर संकेत किया और Youngblood निर्णय के 12 वर्ष बाद रिहा हुआ — यह दुर्भावना-नियम के मूल्यांकन की सामग्री है, परीक्षण का भाग नहीं। Illinois v. Fisher, 540 U.S. 544 (2004) (per curiam, 23 फरवरी 2004) ने ढाँचा बंद कर दिया: प्रतिवादी के फरार रहने के दौरान नियमित धारण-प्रक्रिया से नष्ट बंदूक मामले के लिए महत्वपूर्ण होते हुए भी Youngblood श्रेणी में रही; परीक्षण साक्ष्य के महत्व से नहीं बदलता, और बिना दुर्भावना के नियमित विनाश संवैधानिक है। यह रेखा California से शुरू हुई: People v. Hitch, 12 Cal.3d 641 (1974) ने Trombetta द्वारा संघीय न्यूनतम तय किए जाने से पहले राज्य-कानून स्तर पर श्वास-नमूना संरक्षण को छुआ था, और राज्य अपने कानून में अधिक माँग कर सकते हैं; दंड संहिता धारा 1054.1 अभियोजन के प्रकटीकरण दायित्वों को सूचीबद्ध करती है, और व्यावहारिक कदम शीघ्र लिखित संरक्षण-माँग है, जो Youngblood परीक्षण नहीं बदलती किंतु यह तय कर देती है कि पुलिस क्या जानती थी। अंकगणित, दो बार पुनर्गणना: 2026 − 1984 = 42; 2026 − 1988 = 38; 1988 − 1984 = 4; 2026 − 2004 = 22; 2000 − 1988 = 12। व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं। (初译待校)


---

## 补译增量（2026-11-19 18:55轮）

> 本节为存量补译增量：把中文主文已有、韩／越／印三语同缺的 2 项细节补齐至三语，只译已有事实、不新增事实。两项细节为：其一，Trombetta 案中加州公路巡警测呼吸酒精所用的仪器是 Intoxilyzer；其二，Youngblood 案中 Blackmun 的异议认为，不该让被告的命运取决于警察的主观心态。

### 한국어 — 초역, 교정 대기 중 (初译待校)

보충 항목 1 (측정 기기): Trombetta 사건에서 캘리포니아 고속도로 순찰대(California Highway Patrol)가 호흡 알코올을 측정할 때 사용한 기기는 Intoxilyzer였다. 검사가 끝난 뒤 검체는 정해진 관행대로 보존되지 않았고, 피고인은 검체가 없으면 재측정으로 기기 결과에 다툴 수 없다고 주장했다.

보충 항목 2 (Blackmun 반대의견): Youngblood 사건에서 Blackmun 대법관의 반대의견은 피고인의 운명이 경찰의 주관적 심리에 달려서는 안 된다는 취지였다. 다수의견이 잠재적으로만 유용한 증거에 대해 경찰의 악의(bad faith)를 요구한 데 대해, 반대의견은 그 주관적 기준 자체를 문제 삼았다.

### Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

Mục bổ sung 1 (thiết bị đo): Trong vụ Trombetta, thiết bị mà Tuần tra Xa lộ California (California Highway Patrol) dùng để đo nồng độ cồn trong hơi thở là máy Intoxilyzer. Sau khi đo, mẫu hơi thở không được lưu giữ theo thông lệ đã định, và bị cáo cho rằng không có mẫu thì không thể đo lại để tranh cãi kết quả của máy.

Mục bổ sung 2 (ý kiến bất đồng của Blackmun): Trong vụ Youngblood, ý kiến bất đồng của Thẩm phán Blackmun cho rằng số phận của bị cáo không nên phụ thuộc vào trạng thái tâm lý chủ quan của cảnh sát. Trước việc đa số đòi hỏi ác ý (bad faith) của cảnh sát đối với chứng cứ chỉ tiềm tàng hữu ích, ý kiến bất đồng chất vấn chính tiêu chuẩn chủ quan đó.

### हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

पूरक 항목 1 (माप-यंत्र): Trombetta मामले में California Highway Patrol ने श्वास-अल्कोहल मापने के लिए जिस यंत्र का उपयोग किया वह Intoxilyzer था। माप के बाद नमूने निर्धारित प्रथा के अनुसार संरक्षित नहीं रखे गए, और प्रतिवादी का तर्क था कि नमूने के बिना पुनः माप करके यंत्र के परिणाम को चुनौती नहीं दी जा सकती।

पूरक 항목 2 (Blackmun का असहमति-मत): Youngblood मामले में न्यायमूर्ति Blackmun के असहमति-मत का सार यह था कि प्रतिवादी का भाग्य पुलिस की व्यक्तिपरक मानसिकता पर निर्भर नहीं होना चाहिए। बहुमत ने केवल संभावित रूप से उपयोगी साक्ष्य के लिए पुलिस की दुर्भावना (bad faith) माँगी, जिस पर असहमति-मत ने उसी व्यक्तिपरक कसौटी पर प्रश्न उठाया।
