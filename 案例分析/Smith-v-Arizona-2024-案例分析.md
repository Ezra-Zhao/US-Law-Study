# Smith v. Arizona, 602 U.S. 779 (2024) 案例分析：出庭的专家转述了缺席分析员的结论，还算不算对质

> 个人学习笔记，不构成法律建议。分工：与仓内《Crawford v. Washington, 541 U.S. 36 (2004) 案例分析》分工——Crawford 篇立对质条款的总框架（证言性陈述加事先交叉询问机会），本篇管框架落到法庭科学时的一个具体口子：检方的专家本人没有做检测，他坐上证人席，把缺席分析员的记录念给陪审团听，这到底是「专家自己的意见」，还是把缺席者的证言性陈述换了个嗓子送进来。选题经 ls 文件名加 git grep 正文双查：Smith v. Arizona 与 602 U.S. 779 全仓零命中、无本体专篇；Melendez-Diaz、Bullcoming 两案仅在 Crawford 篇内作坐标提及，无本体专篇，在本篇内写清分工。

## 中文主文

### 一、案名、法院与一句话结论

Smith v. Arizona, 602 U.S. 779 (2024)，美国联邦最高法院，2024 年 6 月 21 日判决，Kagan 大法官执笔，判决结论一致（撤销并重审发回，vacated and remanded）。一句话结论：检方专家在庭上转述缺席分析员的陈述来支撑自己的专家意见，而那些陈述只有在真实时才撑得起这个意见，那么这些陈述就是「为其真实性而被呈上」（for the truth of the matter asserted），属于传闻；接下来还要逐条判断它们是不是证言性陈述，是，就触发第六修正案对质条款。亚利桑那州上诉法院当年绕开了这一步，判决被撤销、发回按新口径重审。

### 二、事实：做检测的人退休了，来作证的人没做过检测

Jason Smith 在亚利桑那州被控多项涉毒重罪，关键物证是从他住处与车辆查获的物质到底是不是冰毒等受控物质。州犯罪实验室的法庭科学分析员 Elizabeth Rast 对查获物做了检测，留下检测记录与报告，结论支持检方。案子开庭时 Rast 已经退休、不再出庭。检方改叫另一位法庭科学家 Gregg Longoni 出庭：Longoni 本人没有碰过这些检材，他复核了 Rast 的记录与报告，在证人席上向陪审团逐项讲述 Rast 做了什么、得出了什么结论，并在此基础上给出「自己的」专家意见。辩方以对质条款反对：陪审团实际听到的是 Rast 的结论，而辩方从没有机会交叉询问 Rast。州法院准许了这套作证方式，理由是 Longoni 讲的只是他形成独立意见所依据的基础、不是为了证明那些陈述本身为真，Longoni 本人又在庭上可以被交叉询问，足够了。亚利桑那州上诉法院维持这一口径，州最高法院拒绝复审，案子来到联邦最高法院。算一笔年份账：2026 减 2024 等于 2，本案判决才两年，是对质条款目前最新的一块界碑（本地复算一致）。

### 三、推理一：先问这句话是为什么被呈上——为真实性而呈上，就是传闻

最高法院先拆州法院推理的第一块砖。州法院说，专家转述的分析记录只是「意见的基础」，不算为真实性而呈上，所以不是传闻、对质条款管不着。多数意见说这一步在逻辑上站不住：Longoni 的意见之所以对陪审团有分量，恰恰因为他转述的 Rast 的检测步骤与结论是真的——如果 Rast 根本没测、或者测错了，Longoni 坐在她记录上得出的意见就一文不值。换句话说，缺席分析员的陈述支撑专家意见的方式，就是请陪审团相信这些陈述为真；只要陈述是靠「为真」在起作用，它就是为真实性而呈上的传闻陈述，不能用「这只是专家依据」一句话把它洗成非传闻。法院把标准说成功能性的：不看检方给它贴什么标签，看它在论证里实际怎么干活。

### 四、推理二：第二步才轮到证言性——逐条判断，发回重审

传闻只是第一道门。对质条款只管证言性（testimonial）陈述，所以第二步要问：Rast 的这些记录与陈述，按其作出时的首要目的（primary purpose），是不是为了在日后刑事追诉中作证而准备的。多数意见没有替下级法院把这一步做完，而是把案子发回，要求按陈述逐条审查其证言性。这一安排本身就是规则的一部分：实验室报告类材料不能整批打包定性，要一条一条看它生成时的目的与情境。多数意见同时与 2012 年 Williams v. Illinois, 567 U.S. 50 (2012) 的复数意见划清界限——Williams 当年四人复数意见主张专家转述的实验室报告不为真实性而呈上、且该报告非证言性，两点都没有拿到多数支持，本案明确不走那条路；2024 减 2012 等于 12，十二年后法院把口子收回到 Crawford 的原框架里。

### 五、分界：与 Melendez-Diaz、Bullcoming 差在哪里

三案排成一列最清楚。第一，Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009)：实验室出具的宣誓证明（说查获物是可卡因、重量多少）本身就是证言性陈述，出证明的分析员必须出庭受交叉询问，不能用一纸宣誓书代替；2024 减 2009 等于 15，本案是它十五年后的续篇。第二，Bullcoming v. New Mexico, 564 U.S. 647 (2011)：做血检的分析员不出庭、换一位同事来「代读」报告，不行——替代证人不能替缺席分析员受询问。本案与 Bullcoming 的差别在作证方式多绕了一层：Longoni 不是单纯代读，他声称在 Rast 记录之上形成了自己的独立意见。多数意见的回答是：多绕这一层不改变分析的第一步——只要他的意见靠 Rast 陈述为真才成立，那些陈述仍是为真实性而呈上的传闻；至于「真独立复核」与「换嗓子转述」的界线，落在第二步的逐条审查与事实认定里。第三，与 Crawford 本案的关系：Crawford 管的是庭外证言性陈述的总门槛，本篇管的是这道门槛穿过「专家意见」这层外衣时怎么算账。

### 六、留下的规则与边界

一，两步走不能跳步：先问缺席陈述是否为真实性而呈上（看它在专家论证里实际起什么作用），再逐条问它是否证言性；州法院当年就是跳过了第一步的实质审查。二，标签不算数：检方把转述叫作「专家依据」「独立意见的基础」，都不能自动把它变非传闻；陪审团必须相信缺席陈述为真、意见才有价值的，就是为真实性而呈上。三，本案没有说专家不能依据他人数据：专家依据同行记录形成意见是法庭科学的日常，本案管的是检方把缺席者的证言性结论送进陪审团耳朵时，被告的交叉询问权不能被这层转述绕过去。四，本案也没有一锤定音说所有实验室记录都是证言性的：证言性要逐条按首要目的判断，发回重审正是因为这一步还没做。五，实务后果直接：检方要么让做检测的分析员出庭，要么重新检测，要么就得准备好逐条论证缺席陈述的非证言性；分析员退休、离职不再是绕开对质的现成出口。六，年份感：2026 减 2004 等于 22，从 Crawford 重立对质框架到本案收口专家转述，隔了 22 年；2024 减 2011 等于 13，距 Bullcoming 的替代证人之禁 13 年。

### 七、加州落点

加州在州法层面先走了一步：People v. Sanchez, 63 Cal.4th 665 (2016)，加州最高法院认定，专家在庭上转述与案件具体事实有关的庭外陈述（case-specific hearsay），这些陈述就是为真实性而呈上的传闻，须有传闻例外才进得来——与本案第一步的逻辑同构，且比联邦早了八年。落到加州日常，分三格看：第一格，州法传闻门——《证据法典》第 1200 条先挡传闻，专家意见的依据范围看第 801 条与第 802 条，专家可以依据不可采的材料形成意见，但把案件具体事实的传闻内容讲给陪审团听，Sanchez 之后要另找例外。第二格，联邦宪法门——就算州法放行，只要缺席陈述是证言性的、又为真实性而呈上，第六修正案对质条款照样拦，本案之后这道门的算法在加州法院同样适用。第三格，实务格——加州检方处理实验室证据的稳妥做法与联邦一致：让实际检测的分析员出庭，或安排可出庭的分析员重新检测；辩方则应逐条盯住转述内容，先攻「为真实性而呈上」、再攻「证言性」，两步都留下记录供上诉审查。

来源口径：Smith v. Arizona, 602 U.S. 779 (2024) 判决书与概要（2024 年 6 月 21 日判决，Kagan 执笔，撤销亚利桑那州上诉法院判决并发回重审）；Crawford v. Washington, 541 U.S. 36 (2004)；Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009)；Bullcoming v. New Mexico, 564 U.S. 647 (2011)；Williams v. Illinois, 567 U.S. 50 (2012)（复数意见）；People v. Sanchez, 63 Cal.4th 665 (2016)；Cal. Evid. Code §§ 1200, 801, 802。算例本地复算两遍一致：2026 − 2024 = 2；2024 − 2012 = 12；2024 − 2009 = 15；2026 − 2004 = 22；2024 − 2011 = 13。

声明：个人学习笔记，不构成法律建议。

---

## English

**Smith v. Arizona, 602 U.S. 779 (2024)** (decided June 21, 2024; opinion by Justice Kagan; judgment unanimous, vacating and remanding). Jason Smith was prosecuted in Arizona on drug charges; the identity of the seized substances was proved through the state crime lab. The analyst who ran the tests, Elizabeth Rast, had retired by trial, so the State called a different forensic scientist, Gregg Longoni, who had not tested the evidence himself. Working from Rast's notes and report, Longoni told the jury what Rast had done and concluded, and offered his own expert opinion on that basis. The Arizona courts allowed this on the theory that Rast's statements were presented merely as the basis of Longoni's independent opinion, not for their truth. The Supreme Court disagreed at step one: an absent analyst's statements that an expert conveys in support of his opinion are presented for their truth — and are therefore hearsay — when they support the opinion only if true; if Rast had not tested, or had tested wrongly, the opinion built on her records would be worthless. The label the prosecution attaches does not control; the function the statements perform does. At step two, the Confrontation Clause reaches only testimonial statements, so the case was remanded for a statement-by-statement assessment of whether Rast's records were testimonial under the primary-purpose test. The Court expressly declined to follow the Williams v. Illinois, 567 U.S. 50 (2012) plurality, which had reasoned that an expert's basis testimony is not offered for its truth. The decision sits in a line with Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009) (a lab affidavit is testimonial; the analyst must testify) and Bullcoming v. New Mexico, 564 U.S. 647 (2011) (a surrogate may not simply read the absent analyst's report), and it comes 2026 − 2004 = 22 years after Crawford v. Washington, 541 U.S. 36 (2004) rebuilt the framework. California note: California reached a parallel result on state hearsay law in People v. Sanchez, 63 Cal.4th 665 (2016), holding that case-specific hearsay related by an expert is offered for its truth and needs an exception; Evidence Code sections 1200, 801, and 802 frame the state-law inquiry, while the Sixth Amendment supplies the federal floor after Smith. *Personal study notes; not legal advice.*

---

## Español — traducción de estudio (初译待校)

**Smith v. Arizona, 602 U.S. 779 (2024)** (decidido el 21 de junio de 2024; opinión de la jueza Kagan; revocación y devolución por unanimidad en el resultado). Jason Smith fue procesado en Arizona por delitos de drogas; la identidad de las sustancias incautadas se probaba mediante el laboratorio estatal. La analista que hizo las pruebas, Elizabeth Rast, ya estaba jubilada en el juicio, así que la acusación llamó a otro científico forense, Gregg Longoni, que no había analizado la evidencia. A partir de las notas y el informe de Rast, Longoni relató al jurado lo que Rast había hecho y concluido, y ofreció su propia opinión pericial sobre esa base. Los tribunales de Arizona lo admitieron con la teoría de que las declaraciones de Rast se presentaban solo como base de la opinión independiente de Longoni, no por su verdad. El Tribunal Supremo discrepó en el primer paso: las declaraciones de un analista ausente que un perito transmite en apoyo de su opinión se presentan por su verdad —y son, por tanto, hearsay— cuando apoyan la opinión solo si son verdaderas; si Rast no hubiera analizado, o lo hubiera hecho mal, la opinión construida sobre sus registros no valdría nada. No manda la etiqueta de la acusación, sino la función que las declaraciones cumplen. En el segundo paso, la cláusula de confrontación solo alcanza declaraciones testimoniales, así que el caso se devolvió para valorar declaración por declaración si los registros de Rast eran testimoniales según el criterio del propósito principal. El Tribunal declinó expresamente seguir la pluralidad de Williams v. Illinois, 567 U.S. 50 (2012). La decisión se alinea con Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009) y Bullcoming v. New Mexico, 564 U.S. 647 (2011), y llega 2026 − 2004 = 22 años después de Crawford v. Washington, 541 U.S. 36 (2004). Nota de California: California llegó a un resultado paralelo en su derecho estatal de hearsay con People v. Sanchez, 63 Cal.4th 665 (2016); las secciones 1200, 801 y 802 del Código de Prueba enmarcan el análisis estatal, y la Sexta Enmienda aporta el suelo federal tras Smith. *Notas de estudio personal; no es asesoría legal.* (traducción de estudio, pendiente de revisión)

---

## 한국어 — 초역, 교정 대기 중 (初译待校)

**Smith v. Arizona, 602 U.S. 779 (2024)**(2024년 6월 21일 판결, Kagan 대법관 의견, 결과 만장일치로 파기·환송). Jason Smith는 Arizona에서 마약 혐의로 기소됐고, 압수 물질의 성분은 주 범죄연구소 검사가 입증해야 했습니다. 검사를 수행한 분석가 Elizabeth Rast는 재판 시점에 이미 은퇴했으므로, 검찰은 검사를 직접 하지 않은 다른 법과학자 Gregg Longoni를 증인으로 세웠습니다. Longoni는 Rast의 기록과 보고서를 토대로 Rast가 무엇을 했고 어떤 결론을 냈는지를 배심원에게 설명하고, 그 위에 자기 전문가 의견을 제시했습니다. Arizona 법원은 Rast의 진술이 Longoni의 독립 의견의 근거로만 제시됐을 뿐 그 진실성을 위해 제시된 것이 아니라는 논리로 이를 허용했습니다. 연방대법원은 첫 단계에서 동의하지 않았습니다. 전문가가 자기 의견을 뒷받침하려고 전달하는 부재 분석가의 진술은, 그 진술이 진실일 때만 의견을 뒷받침한다면, 진실성을 위해 제시된 것이며 따라서 전문(hearsay)입니다. Rast가 검사하지 않았거나 잘못 검사했다면 그 기록 위에 세운 의견은 가치가 없습니다. 검찰이 붙이는 이름표가 아니라 진술이 실제로 수행하는 기능이 기준입니다. 두 번째 단계에서 대면권 조항은 증언적 진술에만 미치므로, 사건은 Rast의 기록이 주요 목적 기준에서 증언적인지를 진술별로 판단하도록 환송됐습니다. 대법원은 Williams v. Illinois, 567 U.S. 50 (2012) 복수 의견을 따르지 않겠다고 명시했습니다. 이 판결은 Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009), Bullcoming v. New Mexico, 564 U.S. 647 (2011)와 같은 계보에 서 있고, Crawford v. Washington, 541 U.S. 36 (2004) 이후 2026 − 2004 = 22년 만에 나왔습니다. 캘리포니아에서는 People v. Sanchez, 63 Cal.4th 665 (2016)가 주 전문법에서 평행한 결론에 도달했고, 증거법전 §1200, §801, §802가 주법 분석의 틀이며, Smith 이후 연방 하한은 수정헌법 제6조가 제공합니다. 본 자료는 개인 학습 노트이며 법률 자문이 아닙니다. (초역, 원어민 감수 대기)

---

## Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

**Smith v. Arizona, 602 U.S. 779 (2024)** (phán quyết ngày 21 tháng 6 năm 2024; ý kiến của Thẩm phán Kagan; hủy án và chuyển lại xét xử, nhất trí về kết quả). Jason Smith bị truy tố tại Arizona về các tội ma túy; việc xác định chất bị thu giữ phải dựa vào phòng thí nghiệm tội phạm của bang. Nhà phân tích đã làm xét nghiệm, Elizabeth Rast, đã nghỉ hưu khi vụ án ra tòa, nên bên công tố gọi một nhà khoa học pháp y khác, Gregg Longoni, người không tự xét nghiệm chứng cứ. Dựa trên ghi chép và báo cáo của Rast, Longoni kể cho bồi thẩm đoàn Rast đã làm gì và kết luận ra sao, rồi đưa ra ý kiến chuyên gia của mình trên cơ sở đó. Các tòa Arizona cho phép với lý thuyết rằng lời khai của Rast chỉ được trình bày làm cơ sở cho ý kiến độc lập của Longoni, chứ không phải vì tính đúng của chúng. Tòa Tối cao không đồng ý ở bước một: lời khai của nhà phân tích vắng mặt mà một chuyên gia truyền đạt để hỗ trợ ý kiến của mình được trình bày vì tính đúng của chúng — và do đó là lời đồn (hearsay) — khi chúng chỉ hỗ trợ ý kiến nếu chúng đúng; nếu Rast không xét nghiệm, hoặc xét nghiệm sai, ý kiến xây trên hồ sơ của bà sẽ vô giá trị. Nhãn dán của bên công tố không quyết định; chức năng thực tế của lời khai mới quyết định. Ở bước hai, điều khoản đối chất chỉ áp dụng với lời khai có tính chất làm chứng, nên vụ án được chuyển lại để đánh giá từng lời khai xem hồ sơ của Rast có phải là lời khai làm chứng theo tiêu chí mục đích chính hay không. Tòa từ chối rõ ràng việc đi theo ý kiến đa số tương đối trong Williams v. Illinois, 567 U.S. 50 (2012). Phán quyết nằm cùng dòng với Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009) và Bullcoming v. New Mexico, 564 U.S. 647 (2011), và đến 2026 − 2004 = 22 năm sau Crawford v. Washington, 541 U.S. 36 (2004). Ghi chú California: California đạt kết quả song song trong luật lời đồn của bang với People v. Sanchez, 63 Cal.4th 665 (2016); các mục 1200, 801 và 802 của Bộ luật Chứng cứ định khung phân tích của bang, còn Tu chính án thứ sáu đặt sàn liên bang sau Smith. *Ghi chú học tập cá nhân, không phải tư vấn pháp lý.* (Bản dịch sơ bộ, chờ hiệu đính)

---

## हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

**Smith v. Arizona, 602 U.S. 779 (2024)** (निर्णय 21 जून 2024; न्यायमूर्ति Kagan का मत; परिणाम में सर्वसम्मति से निर्णय रद्द कर पुनः सुनवाई हेतु वापसी)। Jason Smith पर Arizona में मादक पदार्थों के आरोपों में मुकदमा चला; ज़ब्त पदार्थों की पहचान राज्य अपराध प्रयोगशाला के परीक्षण से सिद्ध होनी थी। परीक्षण करने वाली विश्लेषक Elizabeth Rast सुनवाई के समय सेवानिवृत्त हो चुकी थीं, इसलिए अभियोजन ने एक अन्य फोरेंसिक वैज्ञानिक Gregg Longoni को बुलाया, जिसने स्वयं साक्ष्य का परीक्षण नहीं किया था। Rast के नोट्स और रिपोर्ट के आधार पर Longoni ने जूरी को बताया कि Rast ने क्या किया और क्या निष्कर्ष निकाला, और उसी आधार पर अपनी विशेषज्ञ राय दी। Arizona की अदालतों ने यह इस सिद्धांत पर स्वीकार किया कि Rast के कथन केवल Longoni की स्वतंत्र राय के आधार के रूप में प्रस्तुत किए गए थे, उनकी सत्यता के लिए नहीं। सर्वोच्च न्यायालय पहले चरण में असहमत हुआ: अनुपस्थित विश्लेषक के वे कथन, जिन्हें कोई विशेषज्ञ अपनी राय के समर्थन में प्रस्तुत करता है, यदि वे राय को केवल तभी समर्थित करते हैं जब वे सत्य हों, तो वे अपनी सत्यता के लिए प्रस्तुत माने जाएँगे — अर्थात वे hearsay हैं; यदि Rast ने परीक्षण ही न किया होता, या गलत किया होता, तो उसके अभिलेखों पर बनी राय बेकार होती। निर्णायक अभियोजन का लगाया नाम नहीं, बल्कि कथनों का वास्तविक कार्य है। दूसरे चरण में, सामना-अधिकार खंड केवल गवाही-स्वरूप (testimonial) कथनों पर लागू होता है, इसलिए मामला इस निर्देश के साथ वापस भेजा गया कि Rast के अभिलेख मुख्य-उद्देश्य कसौटी पर गवाही-स्वरूप हैं या नहीं, यह कथन-दर-कथन परखा जाए। न्यायालय ने Williams v. Illinois, 567 U.S. 50 (2012) की बहुलक राय का अनुसरण स्पष्ट रूप से अस्वीकार किया। यह निर्णय Melendez-Diaz v. Massachusetts, 557 U.S. 305 (2009) और Bullcoming v. New Mexico, 564 U.S. 647 (2011) की परंपरा में है, और Crawford v. Washington, 541 U.S. 36 (2004) के 2026 − 2004 = 22 वर्ष बाद आया। California टिप्पणी: California ने People v. Sanchez, 63 Cal.4th 665 (2016) में राज्य hearsay विधि में समानांतर निष्कर्ष दिया था; साक्ष्य संहिता की धाराएँ 1200, 801 और 802 राज्य-स्तरीय विश्लेषण का ढाँचा देती हैं, और Smith के बाद छठा संशोधन संघीय न्यूनतम स्तर प्रदान करता है। *व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं।* (प्रारंभिक अनुवाद, समीक्षा लंबित)


## 补译增量（2026-11-19 23:55 轮）

> 本节为存量补译增量：经逐节核读，中文主文有、韩／越／印三语同缺的细节共 2 项——①程序链一格：亚利桑那州上诉法院维持州法院口径后，州最高法院拒绝复审，案子才来到联邦最高法院（中文主文第二节）；②实务出路一格：检方可以安排重新检测，且分析员退休、离职不再是绕开对质的现成出口（中文主文第六节第五项）。以下三语各补齐这 2 项，纯增量，不改原文，不新增事实。

### 한국어 — 초역, 교정 대기 중 (初译待校)

1. 절차 경위: Arizona 항소법원이 주 법원의 판단을 유지한 뒤, Arizona주 대법원은 재심리(review)를 거부했고, 그 후에야 사건이 연방대법원에 이르렀습니다. 즉 연방대법원의 심사는 주 법원 단계의 구제가 모두 소진된 뒤에 이루어진 것입니다. (초역, 교정 대기 중)
2. 실무상 출구: 검찰 측의 대응 방법에는 검사를 다시 실시하는 것(retest)이 포함됩니다. 출석 가능한 분석가가 새로 검사하거나 원래 분석가가 출석하는 방법이 있으며, 분석가가 은퇴했거나 퇴직했다는 사정은 대면권을 우회할 수 있는 손쉬운 출구가 더 이상 아닙니다. (초역, 교정 대기 중)

### Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

1. Diễn tiến thủ tục: sau khi Tòa phúc thẩm Arizona giữ nguyên cách xử lý của tòa cấp dưới, Tòa Tối cao bang Arizona đã từ chối xét lại (denied review), và chỉ sau đó vụ án mới lên tới Tòa Tối cao liên bang. Nói cách khác, việc xét xử ở cấp liên bang diễn ra sau khi các bước cứu xét ở cấp bang đã kết thúc. (Bản dịch sơ bộ, chờ hiệu đính)
2. Lối ra thực tiễn: bên công tố có thể sắp xếp xét nghiệm lại (retest) — cho một nhà phân tích có thể ra tòa tiến hành xét nghiệm mới, hoặc để chính nhà phân tích ban đầu ra tòa; việc nhà phân tích đã nghỉ hưu hay thôi việc không còn là lối thoát có sẵn để né tránh quyền đối chất. (Bản dịch sơ bộ, chờ hiệu đính)

### हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

1. प्रक्रियात्मक क्रम: Arizona अपील न्यायालय ने निचली अदालत के दृष्टिकोण को बरकरार रखा, उसके बाद Arizona सर्वोच्च न्यायालय ने पुनर्विचार (review) अस्वीकार कर दिया, और तभी मामला संघीय सर्वोच्च न्यायालय तक पहुँचा। अर्थात संघीय समीक्षा राज्य-स्तरीय चरण पूरे होने के बाद ही हुई। (प्रारंभिक अनुवाद, समीक्षा लंबित)
2. व्यावहारिक रास्ता: अभियोजन के विकल्पों में पुनः परीक्षण (retest) शामिल है — उपस्थित हो सकने वाले विश्लेषक से नया परीक्षण कराना, या मूल विश्लेषक को ही उपस्थित कराना; विश्लेषक का सेवानिवृत्त होना या नौकरी छोड़ना अब सामना-अधिकार को टालने का तैयार बहाना नहीं रह गया है। (प्रारंभिक अनुवाद, समीक्षा लंबित)
