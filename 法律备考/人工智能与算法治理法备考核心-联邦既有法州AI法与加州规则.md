# 人工智能与算法治理法备考核心：联邦既有法、州 AI 法与加州规则

## 中文主文

美国没有一部统一的联邦人工智能法。备考与实务的主线是两条：第一，算法作出的决定仍然受既有法律约束——雇佣歧视看 Title VII 与 ADA、信贷看 ECOA 与公平放贷、住房看《公平住房法》、消费者报告看 FCRA，算法只是把传统责任换了一个工具，部署者不能以「是模型决定的」免责；第二，州法正在补位，联邦层面以 NIST《AI 风险管理框架》（AI RMF 1.0，2023 年发布，自愿性框架）与行政命令的进退为背景板。

先纠正一个高频误引：拜登政府的第 14110 号行政命令（2023 年，关于安全、可靠、可信 AI）已于 2025 年 1 月被第 14179 号行政命令撤销，不能再当作现行联邦 AI 政策来引。考试与实务中引用行政命令，必须先核它是否仍有效。

州法三例，按严格程度排：

1. 科罗拉多《人工智能法》（Colo. Rev. Stat. §§ 6-1-1701 起，2024 年 SB 24-205）：美国第一部综合性 AI 立法，管「高风险 AI 系统」在就业、教育、金融、住房、医疗、法律服务等重大决定中的算法歧视；开发者与部署者各有义务（文档、影响评估、向消费者披露与申诉纠正机会）。生效时间经后续立法推迟，以科罗拉多州官方当期文本为准（2025 年 SB 25-318 将主要义务的适用推迟至 2026 年 6 月 30 日）。
2. 加州《AI 透明法》（SB 942，Gov. Code 之外另见 Bus. & Prof. Code 相关编，2024 年通过）：要求大型生成式 AI 提供者提供免费 AI 检测工具并在内容中嵌入或提供来源披露，适用有门槛（月活用户量级），施行日期以当期官方版本为准。
3. 加州 AB 2013（2024 年，Civ. Code § 3110 起相关训练数据透明要求）：要求生成式 AI 开发者公开训练数据的高层级摘要，让使用者知道模型大致用什么数据训练。

加州还有两条与算法直接相关的既有线：一是 CCPA/CPRA 下的自动化决策技术（ADMT）规则，由加州隐私保护局（CPPA）推进，涉及重大决定的退出权与风险评估，适用与生效以 CPPA 当期规则为准；二是雇佣领域的 FEHA——加州民权部关于自动化决策工具的歧视责任口径与联邦 EEOC 立场一致：工具是雇主选的，歧视后果由雇主担。

联邦执法口径三句：EEOC 已明确 Title VII 的 disparate impact 分析适用于算法筛选工具；CFPB 明确 ECOA 的不利行动通知要求不因使用复杂模型而免除，债权人必须给出具体、准确的拒绝理由；FTC 以第 5 条不公平与欺骗行为管辖 AI 夸大宣传与未经同意用数据训练等行为。三家都没有因为「AI」新设豁免。

备考易错点：①把 NIST AI RMF 当强制法——它是自愿框架，只在合同、采购与过失认定中作标准参照；②把已撤销的 EO 14110 当现行法；③以为州 AI 法只管开发者——科罗拉多法同时管部署者，且义务不同；④以为算法决定没有 disparate impact——既有民权法的效果分析照样适用。

来源：NIST AI 100-1（AI RMF 1.0）；Executive Order 14179 (2025)；Colo. Rev. Stat. §§ 6-1-1701 et seq.；Cal. SB 942 (2024)、AB 2013 (2024)；EEOC 与 CFPB 关于算法工具的公开指引（以各机构官网当期版本为准）。

*个人学习笔记，不构成法律建议。*

## English

The United States has no single federal AI statute. Two points organize the field. First, existing law still governs algorithmic decisions: Title VII and the ADA for employment, ECOA for credit, the Fair Housing Act for housing, and the FCRA for consumer reports. Using a model is not a defense; the deployer remains liable. Second, states are filling the gap. At the federal level, NIST's AI Risk Management Framework (AI RMF 1.0, 2023) is voluntary, and Executive Order 14110 (2023) was revoked by Executive Order 14179 in January 2025 — never cite it as current law without checking.

Colorado's AI Act (Colo. Rev. Stat. §§ 6-1-1701 et seq., SB 24-205) was the first comprehensive state AI law, targeting algorithmic discrimination by "high-risk" systems in consequential decisions, with separate duties for developers and deployers; its main applicability date was postponed (SB 25-318 points to June 30, 2026 — verify the current official text). California's SB 942 (AI Transparency Act) requires large generative-AI providers to offer detection tools and provenance disclosures, and AB 2013 requires high-level training-data summaries. California's CCPA/CPRA automated decisionmaking rules and FEHA principles point the same way: the employer or business that chooses the tool bears the discrimination risk. The EEOC applies disparate-impact analysis to algorithmic screening, the CFPB requires specific adverse-action reasons even for complex models, and the FTC uses Section 5 against deceptive AI claims. None of these agencies created an "AI exception."

*Personal study notes; not legal advice.*

## Español (traducción de estudio)

Estados Unidos no tiene una ley federal única de inteligencia artificial. Rigen dos ideas: primero, las leyes vigentes sí alcanzan las decisiones algorítmicas —Title VII y la ADA en empleo, ECOA en crédito, la Ley de Vivienda Justa y la FCRA— y usar un modelo no exime de responsabilidad a quien lo despliega; segundo, los estados están llenando el vacío. El marco AI RMF 1.0 de NIST (2023) es voluntario, y la Orden Ejecutiva 14110 (2023) fue revocada por la Orden Ejecutiva 14179 en enero de 2025. La ley de Colorado (Colo. Rev. Stat. §§ 6-1-1701 y ss.) fue la primera ley estatal integral sobre sistemas de "alto riesgo" y discriminación algorítmica, con deberes distintos para desarrolladores y desplegadores y fecha de aplicación aplazada (verificar el texto oficial vigente). En California, la SB 942 exige herramientas de detección y divulgación de procedencia a grandes proveedores de IA generativa, y la AB 2013 exige resúmenes de datos de entrenamiento. EEOC, CFPB y FTC aplican las leyes existentes sin crear una "excepción IA".

*Notas personales de estudio; no constituyen asesoría legal.*

## 한국어 (초역, 교정 대기)

미국에는 단일한 연방 인공지능법이 없습니다. 핵심은 두 가지입니다. 첫째, 기존 법률이 알고리즘 결정에도 적용됩니다. 고용은 Title VII와 ADA, 신용은 ECOA, 주거는 공정주거법, 소비자 보고는 FCRA가 적용되며, 모델을 사용했다는 이유만으로 배포자가 면책되지 않습니다. 둘째, 주법이 공백을 메우고 있습니다. NIST의 AI RMF 1.0(2023)은 자발적 프레임워크이고, 행정명령 14110호(2023)는 2025년 1월 행정명령 14179호로 폐지되었습니다. 콜로라도 AI법(Colo. Rev. Stat. §§ 6-1-1701 이하)은 최초의 포괄적 주 AI법으로, 중대한 결정에 쓰이는 '고위험' 시스템의 알고리즘 차별을 규제하고 개발자와 배포자에게 서로 다른 의무를 부과합니다. 적용 시기는 연기되었으므로 현행 공식 텍스트를 확인해야 합니다. 캘리포니아 SB 942는 대형 생성형 AI 제공자에게 탐지 도구와 출처 공개를, AB 2013은 훈련 데이터 요약을 요구합니다. EEOC, CFPB, FTC 모두 기존 법을 그대로 적용하며 'AI 예외'는 없습니다.

세부 보충: 콜로라도법의 주요 의무 적용 시점은 SB 25-318로 2026년 6월 30일로 미뤄졌으며(현행 공식 본문으로 다시 확인할 것), 개발자는 문서화와 영향평가 쪽을, 배포자는 소비자에게 중대한 결정에 AI가 쓰였음을 알리고 이의 제기와 정정 기회를 주는 쪽을 맡는 식으로 의무가 나뉩니다. 캘리포니아 SB 942는 월간 이용자 규모가 큰 대형 생성형 AI 제공자에게 무료 탐지 도구와 출처 공개를 요구하고, AB 2013은 훈련 데이터의 상위 수준 요약을 공개하게 합니다(관련 조문은 Civil Code § 3110 일대).

또 다른 세부 보충: 캘리포니아 프라이버시 보호국(CPPA)이 추진하는 CCPA/CPRA 자동화 의사결정 기술(ADMT) 규칙은 중대한 결정에서의 거부권(opt-out)과 위험 평가를 다루고, 고용 분야에서는 FEHA상 차별 책임이 도구 제공자가 아니라 도구를 고른 사용자에게 돌아간다는 점에서 연방 EEOC의 입장과 같습니다. 시험에서 자주 틀리는 지점은 세 가지입니다. NIST AI RMF는 자발적 틀일 뿐 강제법이 아니라는 점, 행정명령 14110호는 이미 폐지되어 현행법으로 인용할 수 없다는 점, 그리고 알고리즘 결정에도 기존 민권법의 차별적 영향(disparate impact) 분석이 그대로 적용된다는 점입니다.

*개인 학습 노트이며 법률 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Hoa Kỳ không có một đạo luật liên bang duy nhất về trí tuệ nhân tạo. Hai điểm chính: thứ nhất, luật hiện hành vẫn điều chỉnh các quyết định bằng thuật toán — Title VII và ADA trong việc làm, ECOA trong tín dụng, Đạo luật Nhà ở Công bằng và FCRA — và việc dùng mô hình không miễn trách nhiệm cho bên triển khai; thứ hai, các bang đang lấp khoảng trống. Khung AI RMF 1.0 của NIST (2023) mang tính tự nguyện, và Sắc lệnh 14110 (2023) đã bị Sắc lệnh 14179 thu hồi vào tháng 1 năm 2025. Luật AI của Colorado (Colo. Rev. Stat. §§ 6-1-1701 trở đi) là luật bang toàn diện đầu tiên, nhắm vào phân biệt đối xử thuật toán của các hệ thống "rủi ro cao", với nghĩa vụ riêng cho nhà phát triển và bên triển khai; thời điểm áp dụng đã bị hoãn nên cần kiểm tra văn bản chính thức hiện hành. SB 942 của California yêu cầu các nhà cung cấp AI tạo sinh lớn cung cấp công cụ phát hiện và công bố nguồn gốc, AB 2013 yêu cầu tóm tắt dữ liệu huấn luyện. EEOC, CFPB và FTC đều áp dụng luật hiện hành, không có "ngoại lệ AI".

Bổ sung chi tiết: thời điểm áp dụng các nghĩa vụ chính của luật Colorado đã bị SB 25-318 dời tới ngày 30 tháng 6 năm 2026 (cần kiểm tra lại văn bản chính thức hiện hành), và nghĩa vụ được chia ra: nhà phát triển lo tài liệu và đánh giá tác động, còn bên triển khai lo thông báo cho người tiêu dùng khi AI được dùng trong quyết định hệ trọng và cho cơ hội khiếu nại, đính chính. SB 942 của California yêu cầu các nhà cung cấp AI tạo sinh lớn — có ngưỡng lượng người dùng hằng tháng — cung cấp công cụ phát hiện miễn phí và công bố nguồn gốc nội dung, còn AB 2013 yêu cầu công khai bản tóm tắt cấp cao về dữ liệu huấn luyện (điều khoản liên quan quanh Civil Code § 3110).

Bổ sung chi tiết khác: các quy tắc công nghệ ra quyết định tự động (ADMT) theo CCPA/CPRA do Cơ quan Bảo vệ Quyền riêng tư California (CPPA) thúc đẩy bao gồm quyền từ chối (opt-out) đối với các quyết định hệ trọng và đánh giá rủi ro, và trong lĩnh vực việc làm, trách nhiệm phân biệt đối xử theo FEHA thuộc về người sử dụng lao động đã chọn công cụ chứ không phải nhà cung cấp công cụ — cùng lập trường với EEOC liên bang. Ba điểm dễ sai khi thi: Khung AI RMF của NIST chỉ là khung tự nguyện chứ không phải luật bắt buộc; Sắc lệnh 14110 đã bị thu hồi nên không thể dẫn như luật hiện hành; và phân tích tác động phân biệt (disparate impact) của luật dân quyền hiện hành vẫn áp dụng nguyên vẹn cho các quyết định bằng thuật toán.

*Ghi chú học tập cá nhân; không phải tư vấn pháp lý.*

## हिन्दी (प्रारंभिक अनुवाद, समीक्षा लंबित)

संयुक्त राज्य अमेरिका में कोई एकल संघीय AI कानून नहीं है। दो बातें मुख्य हैं: पहला, मौजूदा कानून एल्गोरिद्म-आधारित निर्णयों पर भी लागू होते हैं — रोज़गार में Title VII और ADA, ऋण में ECOA, आवास में Fair Housing Act और FCRA — और मॉडल का उपयोग करने से तैनात करने वाला दायित्व से मुक्त नहीं होता; दूसरा, राज्य इस कमी को पूरा कर रहे हैं। NIST का AI RMF 1.0 (2023) स्वैच्छिक है, और कार्यकारी आदेश 14110 (2023) को जनवरी 2025 में कार्यकारी आदेश 14179 द्वारा निरस्त कर दिया गया। Colorado का AI अधिनियम (Colo. Rev. Stat. §§ 6-1-1701 आदि) पहला व्यापक राज्य AI कानून था, जो 'उच्च-जोखिम' प्रणालियों के एल्गोरिद्मिक भेदभाव को लक्षित करता है और डेवलपर व तैनातकर्ता पर अलग-अलग दायित्व डालता है; इसकी लागू-तिथि टाली गई है, इसलिए वर्तमान आधिकारिक पाठ जाँचें। California का SB 942 बड़े जनरेटिव AI प्रदाताओं से पहचान-उपकरण और स्रोत-प्रकटीकरण माँगता है, और AB 2013 प्रशिक्षण-डेटा सारांश माँगता है। EEOC, CFPB और FTC मौजूदा कानून ही लागू करते हैं — कोई 'AI अपवाद' नहीं है।

विस्तृत पूरक: Colorado कानून के मुख्य दायित्वों की लागू-तिथि SB 25-318 द्वारा 30 जून 2026 तक टाली गई है (वर्तमान आधिकारिक पाठ पुनः जाँचें), और दायित्व बँटे हुए हैं — डेवलपर दस्तावेज़ीकरण व प्रभाव-मूल्यांकन संभालता है, जबकि तैनातकर्ता उपभोक्ता को यह बताता है कि किसी महत्वपूर्ण निर्णय में AI का उपयोग हुआ और उसे आपत्ति व सुधार का अवसर देता है। California का SB 942 बड़े जनरेटिव AI प्रदाताओं — जिन पर मासिक उपयोगकर्ता-संख्या की सीमा लागू होती है — से मुफ़्त पहचान-उपकरण और स्रोत-प्रकटीकरण माँगता है, और AB 2013 प्रशिक्षण-डेटा का उच्च-स्तरीय सारांश सार्वजनिक करने को कहता है (संबंधित प्रावधान Civil Code § 3110 के आसपास)।

एक और विस्तृत पूरक: California Privacy Protection Agency (CPPA) द्वारा आगे बढ़ाए जा रहे CCPA/CPRA के automated decisionmaking technology (ADMT) नियम महत्वपूर्ण निर्णयों में opt-out अधिकार और जोखिम-मूल्यांकन को कवर करते हैं, और रोज़गार क्षेत्र में FEHA के तहत भेदभाव की ज़िम्मेदारी उपकरण-प्रदाता पर नहीं, उपकरण चुनने वाले नियोक्ता पर पड़ती है — संघीय EEOC की स्थिति भी यही है। परीक्षा की तीन आम गलतियाँ: NIST AI RMF केवल स्वैच्छिक ढाँचा है, बाध्यकारी कानून नहीं; कार्यकारी आदेश 14110 निरस्त हो चुका है, इसलिए उसे वर्तमान कानून कहकर उद्धृत नहीं किया जा सकता; और मौजूदा नागरिक-अधिकार कानूनों का disparate impact विश्लेषण एल्गोरिद्मिक निर्णयों पर भी पूरी तरह लागू होता है।

*व्यक्तिगत अध्ययन नोट्स; कानूनी सलाह नहीं है।*
