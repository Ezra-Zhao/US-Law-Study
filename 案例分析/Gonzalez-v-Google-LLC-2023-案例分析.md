# 案例分析：Gonzalez v. Google LLC, 598 U.S. 617 (2023)——230 条款这回没被判，帮凶责任先被 Taamneh 判了

## 中文主文

### 一、案件坐标

- **案名与引证**：Gonzalez v. Google LLC, 598 U.S. 617 (2023)（美国联邦最高法院，全体一致的简短意见，per curiam）。
- **原告**：Reynaldo Gonzalez，女儿 Nohemi Gonzalez 在 2015 年 11 月 13 日巴黎袭击中遇害。
- **被告**：Google LLC，运营 YouTube。
- **诉因**：原告依据《反恐怖主义赞助者正义法》（Justice Against Sponsors of Terrorism Act, JASTA），主张 Google 违反《美国法典》第 18 编第 2333 条第 (d) 款第 (2) 项的帮助与教唆责任：YouTube 的推荐算法向用户推荐了伊斯兰国（ISIS）相关视频，等于帮助了恐怖组织。
- **被告抗辩**：通信规范法第 230 条（47 U.S.C. § 230(c)(1)）——互动计算机服务提供者不因第三方发布的内容被视为发布者，免责。
- **一句话结论**：最高法院没有就第 230 条作出实体判断，而是把案件发回第九巡回上诉法院，要求按同日判决的 Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023) 重审——因为按 Taamneh 的标准，原告的帮助与教唆主张本身就站不住，第 230 条的问题变得没有必要回答。

### 二、事实与程序：从地方法院到最高法院的窄路

2015 年 11 月 13 日，巴黎多处遭袭，Nohemi Gonzalez 遇害。原告起诉称，Google 通过 YouTube 的算法推荐，把 ISIS 的招募与宣传视频推给可能感兴趣的用户，从而“帮助”了 ISIS 实施袭击。原告并没有主张 Google 亲自制作了这些视频，也没有主张 Google 事先知道具体某一次袭击的计划；核心指控是算法推荐这套通用服务放大了极端内容。

加州北区联邦地区法院驳回起诉，理由是第 230 条阻断了这类以第三方内容为基础的索赔。第九巡回上诉法院大体维持（Gonzalez v. Google LLC, 2 F.4th 871 (9th Cir. 2021)），认定第 230 条覆盖了原告的大部分主张。最高法院受理后，把本案与 Twitter v. Taamneh 并案审理：Taamneh 案的原告同样依据 JASTA 起诉 Twitter、Google 与 Facebook，指控三家平台允许 ISIS 使用其服务招募与宣传。

2023 年 5 月 18 日，最高法院同日作出两份判决：Taamneh 案是长篇多数意见（Thomas 大法官执笔，全体一致），Gonzalez 案则只有一页多的 per curiam 意见——撤销第九巡回的判决，发回重审。算一笔时间账：从袭击发生（2015 年 11 月）到最高法院判决（2023 年 5 月），间隔约 7 年 6 个月（2023 减 2015 等于 8 个年份跨度，按月算约 90 个月，本地复算两遍一致）。

### 三、Taamneh 的标准：帮凶要的是有意识、可归责的参与

理解 Gonzalez 必须先懂 Taamneh。JASTA 的帮助与教唆责任借用了普通法的帮助责任框架，Thomas 大法官把它拆成三个问题：被告是否明知自己在帮助一个恐怖行为；帮助行为与恐怖行为之间有没有足够的关联；以及帮助本身是不是“有意识、可归责的参与”。

Taamneh 的回答划了一条很高的线：仅仅向公众提供通用服务——哪怕知道有恐怖分子也在用这项服务——不等于帮助恐怖主义。平台没有为 ISIS 量身定制服务，没有参与挑选、策划或实施具体袭击，也没有在内容上与 ISIS 形成共谋；算法推荐在这套分析里被视为平台对所有用户一视同仁的通用功能，而不是针对 ISIS 的定向协助。多数意见的原话逻辑是：帮助责任针对的是“有意识地参与”某一不法行为的人，而不是“碰巧被坏人用上了”的服务提供者。

把这条标准套回 Gonzalez：原告指控的核心同样是通用推荐服务，没有指控 Google 参与了巴黎袭击的策划或实施，也没有指出 Google 明知某一次具体袭击仍提供针对性协助。按 Taamneh 的标准，这类主张“几乎没有”成立的可能——这是 Gonzalez 意见自己的措辞方向：既然原告的主张在 Taamneh 标准下难以成立，法院就没有必要再去碰第 230 条这个更大的问题。

### 四、为什么最高法院不判第 230 条：司法克制的教科书

Gonzalez 案受理时，外界最期待的是最高法院第一次对第 230 条作实质解释：平台的算法推荐，到底算不算“第三方内容”从而免责，还是算平台自己的行为从而可诉？法院选择了不回答，理由是司法克制中的“能不判就不判”：如果案件可以在更窄的理由上解决，就不要去碰更宽的宪法或制定法问题。

这个选择有两层含义。第一层是程序性的：Taamneh 解决的是 JASTA 责任的实体门槛，Gonzalez 的主张连这道门都过不去，第 230 条的豁免问题因此成了“假问题”——无论第 230 条怎么解释，结果都一样。第二层是制度性的：第 230 条的边界牵动整个互联网平台的责任架构，法院不愿在没有必要的时候，用一个附带案件把这条线的解释写死。Gonzalez 因此成了一堂“未决问题”的课：最高法院没有说算法推荐受第 230 条保护，也没有说不受保护，它只是说本案不需要回答。

### 五、与 Taamneh 的分工：一个判实体，一个省程序

两案同日判决，分工清晰：Taamneh 是实体案，定标准——JASTA 的帮助责任需要有意识、可归责的参与，通用服务不够格；Gonzalez 是程序案，示克制——既然实体标准已经决定了结果，就把第 230 条留给以后的案子。学 Taamneh 要背标准，学 Gonzalez 要背方法：先看原告的主张能不能过实体门槛，再问要不要碰豁免条款；顺序反过来，就会多判一个本可以不判的大问题。

### 六、留给以后的问题：第 230 条与算法推荐还在排队

Gonzalez 之后，第 230 条与算法推荐的关系仍然悬而未决。几个方向值得备考时留意：其一，平台“自己的行为”与“第三方内容”的分界——推荐排序、置顶、定向推送，究竟是平台在说话，还是在转述他人说话；其二，JASTA 责任的边界——如果原告能拿出平台明知具体袭击计划仍提供针对性协助的证据，Taamneh 的标准是否就被满足；其三，国会的角色——第 230 条的改革呼声一直存在，法院不判，不等于立法者不动。

### 七、加州一节：发回之后，第九巡回的活儿还没完

发回第九巡回之后，案件要按 Taamneh 的标准重新处理：原告能否补出更具体的“有意识参与”事实，是程序继续的关键。加州的考生还要留意一点：本案的下级法院都在加州北区与第九巡回，但判决的法律问题是联邦法——JASTA 与第 230 条都是联邦制定法，加州法在这里没有独立的落点；加州的意义在于管辖与程序：这类全国性平台诉讼多在加州北区起诉，第九巡回的先例对加州实务影响直接。

### 八、要点清单

1. Gonzalez v. Google LLC, 598 U.S. 617 (2023)：per curiam，撤销并发回，未决第 230 条。
2. 诉因是 JASTA 下的帮助与教唆责任（18 U.S.C. § 2333(d)(2)），不是第 230 条本身。
3. Taamneh, 598 U.S. 471 (2023)：帮助责任须有意识、可归责的参与；通用服务不够。
4. 法院不判第 230 条的理由是司法克制：实体门槛已决定结果，豁免问题无须回答。
5. 算法推荐在本案中被按通用功能处理，未被认定为针对 ISIS 的定向协助。
6. 记住分工：Taamneh 定标准，Gonzalez 示克制。

*声明：本文为个人学习笔记，不构成法律建议；判例引证与条文请再核官方文本。来源：Gonzalez v. Google LLC, 598 U.S. 617 (2023)；Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023)；18 U.S.C. § 2333(d)(2)（JASTA）；47 U.S.C. § 230(c)(1)；Gonzalez v. Google LLC, 2 F.4th 871 (9th Cir. 2021)。*

---

## English

Gonzalez v. Google LLC, 598 U.S. 617 (2023) is a short per curiam decision that decided almost nothing about Section 230 — and that is the point. Reynaldo Gonzalez sued Google under the Justice Against Sponsors of Terrorism Act (18 U.S.C. § 2333(d)(2)), alleging YouTube's recommendation algorithms aided ISIS by promoting its videos; his daughter Nohemi was killed in the November 13, 2015 Paris attacks. Google invoked Section 230 (47 U.S.C. § 230(c)(1)). The Supreme Court vacated and remanded in light of Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023), decided the same day: under Taamneh, aiding-and-abetting liability under JASTA requires conscious, culpable participation in a terrorist act, and merely providing generic services that terrorists also use does not qualify. Because the plaintiffs' claims were unlikely to survive that standard, the Court had no need to reach the Section 230 question — a textbook exercise in judicial restraint, deciding the case on the narrowest ground. The algorithm-recommendation question under Section 230 therefore remains open. Personal study notes only; not legal advice.

## Español — traducción preliminar, pendiente de revisión (初译待校)

Gonzalez v. Google LLC, 598 U.S. 617 (2023) es una breve opinión per curiam que casi no decide nada sobre la Sección 230, y ese es el punto. Reynaldo Gonzalez demandó a Google bajo la Ley de Justicia contra los Patrocinadores del Terrorismo (18 U.S.C. § 2333(d)(2)), alegando que los algoritmos de recomendación de YouTube ayudaron al ISIS al promover sus videos; su hija Nohemi murió en los atentados de París del 13 de noviembre de 2015. Google invocó la Sección 230 (47 U.S.C. § 230(c)(1)). La Corte Suprema anuló y devolvió el caso a la luz de Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023), decidido el mismo día: según Taamneh, la responsabilidad por complicidad bajo JASTA exige una participación consciente y culpable en un acto terrorista, y la mera prestación de servicios genéricos que también usan los terroristas no basta. Como era improbable que las reclamaciones sobrevivieran a ese estándar, la Corte no necesitó resolver la cuestión de la Sección 230: un ejercicio clásico de moderación judicial. La cuestión de las recomendaciones algorítmicas bajo la Sección 230 sigue abierta. Notas personales de estudio; no es asesoría legal.

## 한국어 — 초역, 교정 대기 중 (初译待校)

Gonzalez v. Google LLC, 598 U.S. 617 (2023)은 제230조에 대해 거의 아무것도 결정하지 않은 짧은 per curiam 결정이며, 그 점이 핵심이다. Reynaldo Gonzalez는 딸 Nohemi가 2015년 11월 13일 파리 테러로 사망하자, YouTube 추천 알고리즘이 ISIS 영상을 확산시켜 도왔다며 테러지원자정의법(JASTA, 18 U.S.C. § 2333(d)(2))에 따라 Google을 고소했다. Google은 제230조(47 U.S.C. § 230(c)(1))를 내세웠다. 연방대법원은 같은 날 선고된 Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023)에 비추어 파기환송했다. Taamneh에 따르면 JASTA상 방조 책임은 테러 행위에 대한 의식적이고 비난 가능한 참여를 요구하며, 테러리스트도 이용하는 일반 서비스를 제공했다는 것만으로는 부족하다. 원고의 청구가 그 기준을 통과하기 어렵다고 보았기에, 법원은 제230조 문제를 다룰 필요가 없었다. 이는 가장 좁은 근거로 사건을 해결하는 사법적 자제의 전형이다. 알고리즘 추천과 제230조의 관계는 여전히 미결 상태다. 개인 학습 노트이며 법률 자문이 아니다.

## Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

Gonzalez v. Google LLC, 598 U.S. 617 (2023) là một ý kiến per curiam ngắn, gần như không quyết định gì về Điều 230 — và đó chính là điểm mấu chốt. Reynaldo Gonzalez kiện Google theo Đạo luật Công lý chống Nhà tài trợ Khủng bố (18 U.S.C. § 2333(d)(2)), cho rằng thuật toán gợi ý của YouTube đã tiếp tay cho ISIS bằng cách quảng bá video của tổ chức này; con gái ông, Nohemi, thiệt mạng trong vụ tấn công Paris ngày 13 tháng 11 năm 2015. Google viện dẫn Điều 230 (47 U.S.C. § 230(c)(1)). Tòa án Tối cao đã hủy và gửi trả vụ án theo Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023), được quyết định cùng ngày: theo Taamneh, trách nhiệm tiếp tay theo JASTA đòi hỏi sự tham gia có ý thức và đáng trách vào một hành vi khủng bố, và việc chỉ cung cấp dịch vụ chung mà kẻ khủng bố cũng dùng là chưa đủ. Vì yêu sách của nguyên đơn khó vượt qua tiêu chuẩn đó, Tòa không cần xét đến Điều 230 — một bài học kinh điển về sự kiềm chế tư pháp. Câu hỏi về gợi ý thuật toán theo Điều 230 vẫn còn bỏ ngỏ. Ghi chú học tập cá nhân; không phải tư vấn pháp lý.

## हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

Gonzalez v. Google LLC, 598 U.S. 617 (2023) एक संक्षिप्त per curiam निर्णय है जो धारा 230 के बारे में लगभग कुछ भी तय नहीं करता — और यही इसका सार है। Reynaldo Gonzalez ने आतंकवाद प्रायोजकों के विरुद्ध न्याय अधिनियम (18 U.S.C. § 2333(d)(2)) के तहत Google पर मुकदमा किया और आरोप लगाया कि YouTube की अनुशंसा एल्गोरिदम ने ISIS के वीडियो प्रचारित करके उसकी मदद की; उनकी बेटी Nohemi की 13 नवंबर 2015 के पेरिस हमलों में मृत्यु हुई थी। Google ने धारा 230 (47 U.S.C. § 230(c)(1)) का सहारा लिया। उच्चतम न्यायालय ने उसी दिन सुनाए गए Twitter, Inc. v. Taamneh, 598 U.S. 471 (2023) के आलोक में मामला खारिज कर वापस भेज दिया: Taamneh के अनुसार JASTA के तहत सहायता दायित्व के लिए आतंकी कृत्य में सचेत और दोषपूर्ण भागीदारी चाहिए, और केवल सामान्य सेवाएँ देना — जिनका आतंकवादी भी उपयोग करते हों — पर्याप्त नहीं है। चूँकि वादी के दावे उस मानक पर टिकने की संभावना कम थी, न्यायालय को धारा 230 का प्रश्न छूने की आवश्यकता नहीं पड़ी — यह न्यायिक संयम का एक आदर्श उदाहरण है। एल्गोरिदम अनुशंसा और धारा 230 का प्रश्न अभी भी खुला है। व्यक्तिगत अध्ययन नोट्स; कानूनी सलाह नहीं।


## 补译增量（2026-11-15 10:55轮）

说明：逐节核读后，中文主文已有、而韩/越/印三语同缺的细节有以下 2 项，本节只译这 2 项已有细节，不新增事实。一、下级法院链条细节：加州北区联邦地区法院以第 230 条驳回起诉，第九巡回上诉法院以 Gonzalez v. Google LLC, 2 F.4th 871 (9th Cir. 2021) 大体维持，认定第 230 条覆盖原告的大部分主张。二、时间账细节：从 2015 年 11 月巴黎袭击到 2023 年 5 月最高法院判决，间隔约 7 年 6 个月，按月算约 90 个月。

### 한국어 (初译待校)

하나, 하급법원 경과 세부사항: 캘리포니아 북부지구 연방지방법원은 제230조를 이유로 소를 각하했고, 제9순회 항소법원은 Gonzalez v. Google LLC, 2 F.4th 871 (9th Cir. 2021)로 대체로 이를 유지하며 제230조가 원고 주장의 대부분을 덮는다고 보았습니다. 둘, 시간 계산 세부사항: 2015년 11월 파리 테러부터 2023년 5월 연방대법원 판결까지의 간격은 약 7년 6개월, 개월 수로는 약 90개월입니다. (초역, 원어민 감수 대기 · 初译待校)

### Tiếng Việt (初译待校)

Một, chi tiết về chuỗi tòa cấp dưới: Tòa án liên bang Khu vực Bắc California đã bác đơn kiện dựa trên Điều 230, và Tòa Phúc thẩm Khu vực 9, trong vụ Gonzalez v. Google LLC, 2 F.4th 871 (9th Cir. 2021), về cơ bản giữ nguyên, cho rằng Điều 230 bao phủ phần lớn các yêu sách của nguyên đơn. Hai, chi tiết về khoảng thời gian: từ vụ tấn công Paris tháng 11 năm 2015 đến phán quyết của Tòa án Tối cao tháng 5 năm 2023 là khoảng 7 năm 6 tháng, tính theo tháng là khoảng 90 tháng. (Bản dịch sơ bộ, chờ hiệu đính · 初译待校)

### हिन्दी (初译待校)

एक, निचली अदालतों की शृंखला का विवरण: कैलिफ़ोर्निया के उत्तरी ज़िले के संघीय ज़िला न्यायालय ने धारा 230 के आधार पर मुकदमा ख़ारिज किया, और नौवें सर्किट ने Gonzalez v. Google LLC, 2 F.4th 871 (9th Cir. 2021) में उसे मोटे तौर पर बनाए रखा और माना कि धारा 230 वादी के अधिकांश दावों को आवरित करती है। दो, समय-गणना का विवरण: नवंबर 2015 के पेरिस हमलों से मई 2023 के सर्वोच्च न्यायालय के निर्णय तक का अंतराल लगभग 7 वर्ष 6 माह है, महीनों में गिनें तो लगभग 90 माह। (प्रारंभिक अनुवाद, समीक्षा लंबित · 初译待校)


## 补译增量（2026-11-16 02:55轮）

说明：逐节核读后，中文主文已有、而韩/越/印三语同缺的细节再补以下 2 项，本节只译这 2 项已有细节，不新增事实。一、指控边界细节：原告并没有主张 Google 亲自制作了这些视频，也没有主张 Google 事先知道具体某一次袭击的计划，核心指控是算法推荐这套通用服务放大了极端内容。二、未决问题细节：第 230 条与算法推荐的关系仍悬而未决，其中一个方向是平台自己的行为与第三方内容的分界——推荐排序、置顶、定向推送，究竟是平台在说话，还是在转述他人说话。

### 한국어 (初译待校)

하나, 고소 범위의 세부사항: 원고는 Google이 해당 영상을 직접 제작했다고 주장하지 않았고, Google이 특정 테러의 계획을 사전에 알았다고도 주장하지 않았습니다. 핵심 주장은 추천 알고리즘이라는 일반 서비스가 극단적 콘텐츠를 확산시켰다는 것입니다. 둘, 미결 문제의 세부사항: 제230조와 알고리즘 추천의 관계는 여전히 정해지지 않았으며, 그 방향 중 하나는 플랫폼 자체의 행위와 제3자 콘텐츠의 경계입니다. 추천 순위 지정, 상단 고정, 표적 푸시가 플랫폼이 말하는 것인지, 타인의 말을 전달하는 것인지가 문제입니다. (초역, 원어민 감수 대기 · 初译待校)

### Tiếng Việt (初译待校)

Một, chi tiết về ranh giới của cáo buộc: nguyên đơn không khẳng định rằng Google tự sản xuất các video đó, cũng không cho rằng Google biết trước kế hoạch của một vụ tấn công cụ thể nào; cáo buộc cốt lõi là dịch vụ chung mang tên gợi ý thuật toán đã khuếch đại nội dung cực đoan. Hai, chi tiết về vấn đề chưa được quyết: quan hệ giữa Điều 230 và gợi ý thuật toán vẫn còn bỏ ngỏ, và một hướng trong đó là ranh giới giữa hành vi của chính nền tảng và nội dung của bên thứ ba — việc xếp hạng gợi ý, ghim lên đầu và đẩy có mục tiêu, rốt cuộc là nền tảng đang nói, hay đang chuyển lời của người khác. (Bản dịch sơ bộ, chờ hiệu đính · 初译待校)

### हिन्दी (初译待校)

एक, आरोप की सीमा का विवरण: वादी ने यह दावा नहीं किया कि Google ने स्वयं वे वीडियो बनाए थे, और यह भी नहीं कि Google को किसी विशिष्ट हमले की योजना पहले से ज्ञात थी; मूल आरोप यह था कि अनुशंसा एल्गोरिदम नामक सामान्य सेवा ने चरमपंथी सामग्री को बढ़ाया। दो, अनिर्णीत प्रश्न का विवरण: धारा 230 और एल्गोरिदम अनुशंसा का संबंध अभी भी खुला है, और उसकी एक दिशा मंच के अपने आचरण और तृतीय-पक्ष सामग्री के बीच की सीमा है — अनुशंसा क्रम, ऊपर रखना और लक्षित पुश, आख़िर मंच का स्वयं बोलना है या दूसरों की बात आगे बढ़ाना। (प्रारंभिक अनुवाद, समीक्षा लंबित · 初译待校)
