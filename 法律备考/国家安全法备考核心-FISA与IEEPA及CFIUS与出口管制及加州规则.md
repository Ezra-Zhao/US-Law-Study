# 国家安全法备考核心：FISA 监控、IEEPA 制裁、CFIUS 审查与出口管制

> 个人学习笔记，不构成法律建议。条文与判例以官方文本为准。

## 一、体系总览：总统外交权、Youngstown 三分法与司法尊让

### 中文
国家安全法在美国法里没有单一法典，它是宪法第二条总统权、国会授权法与司法审查交叠的一层。考试的分析底盘是 Youngstown Sheet & Tube Co. v. Sawyer, 343 U.S. 579 (1952) 中 Jackson 大法官协同意见的三分法：总统依国会明示或默示授权行事时权力最强；国会沉默时处于「暮光区」，看现实情势；总统与国会明示意志相悖时权力最低，只能靠宪法自身赋予总统且国会无权干预的权力。多数国家安全争讼先问授权在哪一格，再问具体制定法如何分配权力。法院在外交与移民入境等领域传统上给予政治部门较大尊让，Trump v. Hawaii, 585 U.S. 667 (2018) 是当代例子；但尊让不是免审，程序与授权边界仍可审查。

### English
National security law has no single code; it is the overlap of Article II presidential power, congressional authorizations, and judicial review. The exam chassis is Justice Jackson's Youngstown concurrence (343 U.S. 579 (1952)): presidential power is at its maximum when acting under express or implied congressional authorization, in a "zone of twilight" when Congress is silent, and at its "lowest ebb" when acting against Congress's expressed will. Most disputes first locate the action in that grid, then ask how the specific statute allocates power. Courts traditionally defer substantially to the political branches on foreign affairs and entry, as in Trump v. Hawaii, 585 U.S. 667 (2018), but deference is not abdication: statutory limits and procedure remain reviewable.

### Español (译稿)
El derecho de seguridad nacional no tiene un código único: es la superposición del poder presidencial del Artículo II, las autorizaciones del Congreso y el control judicial. El marco de examen es la concurrencia del juez Jackson en Youngstown (343 U.S. 579 (1952)): poder máximo con autorización congresional, «zona crepuscular» ante el silencio, y nivel mínimo contra la voluntad expresa del Congreso. Los tribunales suelen deferir a los poderes políticos en asuntos exteriores e ingreso, como en Trump v. Hawaii, 585 U.S. 667 (2018), sin abdicar del control sobre límites legales y procedimiento.

### 한국어 (초역 · 初译待校)
국가안보법은 단일 법전이 아니라 헌법 제2조의 대통령 권한, 의회의 수권 법률, 사법심사가 겹치는 영역입니다. 시험의 기본 틀은 Youngstown 사건(343 U.S. 579 (1952))에서 Jackson 대법관이 제시한 3분법입니다. 의회의 명시적·묵시적 수권이 있으면 권한이 최대가 되고, 의회가 침묵하면 「황혼지대」, 의회의 명시적 의사에 반하면 최소 수준이 됩니다. 법원은 외교와 입국 분야에서 정치 부문에 상당한 존중을 보여 왔으며(Trump v. Hawaii, 585 U.S. 667 (2018)), 그러나 법정 한계와 절차에 대한 심사까지 포기하지는 않습니다. (초역·待校)

### Tiếng Việt (bản dịch sơ bộ · 初译待校)
Luật an ninh quốc gia không có một bộ luật duy nhất; đó là vùng chồng lấp giữa quyền Tổng thống theo Điều II, các đạo luật ủy quyền của Quốc hội và quyền xét xử của tòa án. Khung phân tích thi cử là cách chia ba của Thẩm phán Jackson trong Youngstown (343 U.S. 579 (1952)): quyền lực cao nhất khi có ủy quyền của Quốc hội, «vùng tranh tối tranh sáng» khi Quốc hội im lặng, và thấp nhất khi đi ngược ý chí rõ ràng của Quốc hội. Tòa án thường tôn trọng các nhánh chính trị về đối ngoại và nhập cảnh, như Trump v. Hawaii, 585 U.S. 667 (2018), nhưng vẫn xét lại giới hạn luật định và thủ tục. (bản dịch sơ bộ·待校)

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)
राष्ट्रीय सुरक्षा विधि का कोई एकल संहिता नहीं है; यह अनुच्छेद II की राष्ट्रपति-शक्ति, कांग्रेस के授权 कानूनों और न्यायिक पुनरावलोकन का अतिव्यापन है। परीक्षा का आधार Youngstown (343 U.S. 579 (1952)) में न्यायमूर्ति Jackson का त्रिभाजन है: कांग्रेस के授权 पर शक्ति अधिकतम, मौन पर «गोधूलि क्षेत्र», और व्यक्त इच्छा के विरुद्ध न्यूनतम। विदेश मामले और प्रवेश में न्यायालय राजनीतिक शाखाओं को पर्याप्त सम्मान देते हैं (Trump v. Hawaii, 585 U.S. 667 (2018)), किंतु वैधानिक सीमाएँ और प्रक्रिया फिर भी समीक्षा योग्य रहती हैं। (प्रारंभिक अनुवाद·待校)

## 二、FISA：对外情报监控的令状轨道与第 702 条

### 中文
《外国情报监控法》(FISA, 1978)，50 U.S.C. §§ 1801 et seq.，为情报目的的电子监控与搜查设专门轨道：由外国情报监控法院 (FISC) 的法官依密呈申请签发命令，一般要求有相当理由相信目标是外国势力或其代理人。与普通刑事令状相比，FISA 的目的要件、秘密程序与事后通知规则都不同。第 702 条，50 U.S.C. § 1881a，授权在总检察长与国家情报总监年度认证下，针对合理相信位于美国境外的非美国人开展项目化收集；美国人不得被作为目标，但附带收集与「回查」(querying) 规则长期是隐私争点。702 条款带日落条款，2024 年经《改革情报与保障美国法》(RISAA) 再授权。备考易错点：FISA 命令不是第四修正案普通令状的替代品，刑事案件中证据使用另有通知与压制动议规则。

### English
The Foreign Intelligence Surveillance Act of 1978, 50 U.S.C. §§ 1801 et seq., creates a dedicated track for intelligence surveillance: judges of the Foreign Intelligence Surveillance Court (FISC) issue orders on ex parte applications, generally on probable cause that the target is a foreign power or its agent. Its purpose element, secrecy, and notice rules all differ from ordinary criminal warrants. Section 702, 50 U.S.C. § 1881a, authorizes programmatic collection under annual certifications by the Attorney General and the Director of National Intelligence, targeting non-U.S. persons reasonably believed to be abroad; U.S. persons may not be targeted, while incidental collection and querying rules remain the core privacy battleground. Section 702 carries a sunset and was reauthorized in 2024 by the Reforming Intelligence and Securing America Act (RISAA). Exam trap: a FISA order is not a substitute for an ordinary Fourth Amendment warrant, and use of the fruits in a criminal case triggers its own notice and suppression rules.

### Español (译稿)
La Ley de Vigilancia de Inteligencia Extranjera de 1978 (FISA), 50 U.S.C. §§ 1801 y ss., crea una vía específica: jueces del Tribunal FISC emiten órdenes a petición unilateral, en general con causa probable de que el objetivo es una potencia extranjera o su agente. Su elemento de finalidad, el secreto y las reglas de notificación difieren de las órdenes penales ordinarias. La Sección 702, 50 U.S.C. § 1881a, autoriza la recolección programática bajo certificaciones anuales, dirigida a no estadounidenses que razonablemente se creen en el extranjero; los estadounidenses no pueden ser objetivo, y la recolección incidental y las consultas siguen siendo el núcleo del debate sobre privacidad. La Sección 702 tiene cláusula de caducidad y fue reautorizada en 2024 por la ley RISAA.

### 한국어 (초역 · 初译待校)
1978년 해외정보감시법(FISA, 50 U.S.C. §§ 1801 이하)은 정보 목적 감시에 별도 경로를 둡니다. 해외정보감시법원(FISC) 판사가 일방 신청에 따라 명령을 발부하며, 통상 대상이 외국 세력 또는 그 대리인이라는 상당한 이유가 필요합니다. 목적 요건, 비밀 절차, 사후 통지 규칙이 일반 형사 영장과 다릅니다. 제702조(50 U.S.C. § 1881a)는 법무장관과 국가정보국장의 연례 인증 아래 국외에 있다고 합리적으로 믿어지는 비미국인을 대상으로 한 프로그램식 수집을 허용합니다. 미국인을 표적으로 삼을 수는 없으며, 부수적 수집과 조회(querying) 규칙이 프라이버시 논쟁의 핵심입니다. 702조는 일몰 조항이 있고 2024년 RISAA로 재수권되었습니다. (초역·待校)

### Tiếng Việt (bản dịch sơ bộ · 初译待校)
Đạo luật Giám sát Tình báo Nước ngoài 1978 (FISA), 50 U.S.C. §§ 1801 trở đi, lập một kênh riêng cho giám sát tình báo: thẩm phán của Tòa FISC ra lệnh theo đơn một phía, thường đòi hỏi căn cứ hợp lý rằng đối tượng là thế lực nước ngoài hoặc điệp viên của nó. Yếu tố mục đích, tính bí mật và quy tắc thông báo đều khác lệnh khám hình sự thông thường. Mục 702, 50 U.S.C. § 1881a, cho phép thu thập theo chương trình dưới chứng nhận hằng năm, nhắm vào người không phải công dân Mỹ được cho là đang ở nước ngoài; không được nhắm vào người Mỹ, còn việc thu thập ngẫu nhiên và quy tắc truy vấn vẫn là trung tâm tranh luận về riêng tư. Mục 702 có điều khoản hoàng hôn và được tái ủy quyền năm 2024 bởi đạo luật RISAA. (bản dịch sơ bộ·待校)

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)
विदेशी खुफिया निगरानी अधिनियम 1978 (FISA), 50 U.S.C. §§ 1801 आगे, खुफिया निगरानी के लिए अलग मार्ग बनाता है: FISC न्यायाधीश एकपक्षीय आवेदनों पर आदेश देते हैं, सामान्यतः इस संभाव्य कारण पर कि लक्ष्य विदेशी शक्ति या उसका अभिकर्ता है। इसका उद्देश्य-तत्व, गोपनीयता और सूचना नियम सामान्य आपराधिक वारंट से भिन्न हैं। धारा 702, 50 U.S.C. § 1881a, वार्षिक प्रमाणनों के अधीन कार्यक्रमगत संग्रह की अनुमति देती है, जिसका लक्ष्य विदेश में माने जाने वाले गैर-अमेरिकी व्यक्ति हैं; अमेरिकी व्यक्तियों को लक्ष्य नहीं बनाया जा सकता, और आनुषंगिक संग्रह तथा क्वेरी नियम गोपनीयता विवाद के केंद्र में रहते हैं। धारा 702 में सूर्यास्त खंड है और 2024 में RISAA द्वारा पुनः प्राधिकृत हुई। (प्रारंभिक अनुवाद·待校)

## 三、IEEPA：紧急经济权力、制裁执行与授权边界

### 中文
《国际紧急经济权力法》(IEEPA, 1977)，50 U.S.C. §§ 1701–1706，是现代经济制裁的主引擎：总统先依《国家紧急状态法》宣布国家紧急状态，认定源自美国境外的异常且非凡威胁，再据此冻结资产、禁止或限制交易。执行落在财政部外国资产控制办公室 (OFAC)，名单制裁 (SDN) 与行业性制裁并行。备考要点有三：一，IEEPA 的触发要件是程序与实体双门——无紧急状态宣布即无授权；二，其文义列举的是冻结、禁止、管制进出口等权力，关税并未明列，能否据此加征关税在 2025 年成为重大诉讼争点，答题时应标明争点而非当作定论；三，IEEPA 明文排除人道主义捐赠与信息材料等类别，授权有内建边界。

### English
The International Emergency Economic Powers Act of 1977, 50 U.S.C. §§ 1701–1706, is the main engine of modern economic sanctions: the President first declares a national emergency under the National Emergencies Act as to an unusual and extraordinary threat originating abroad, then blocks assets and prohibits or regulates transactions. Administration sits with the Treasury Department's Office of Foreign Assets Control (OFAC), through list-based (SDN) and sectoral sanctions. Three exam points: first, the trigger is both procedural and substantive — no declared emergency, no authority; second, IEEPA's text enumerates blocking, prohibiting, and regulating imports and exports, and does not expressly list tariffs, so whether it can support tariff imposition became a major litigated question in 2025 and should be flagged as contested rather than settled; third, the statute itself carves out categories such as humanitarian donations and informational materials — the grant has built-in edges.

### Español (译稿)
La Ley de Poderes Económicos de Emergencia Internacional de 1977 (IEEPA), 50 U.S.C. §§ 1701–1706, es el motor principal de las sanciones económicas modernas: el Presidente declara primero una emergencia nacional por una amenaza inusual y extraordinaria originada en el extranjero, y luego bloquea activos y prohíbe o regula transacciones. La ejecución corresponde a la OFAC del Departamento del Tesoro. Tres puntos de examen: sin declaración de emergencia no hay autoridad; el texto enumera bloquear, prohibir y regular importaciones y exportaciones, pero no menciona expresamente los aranceles, cuestión muy litigada en 2025 que debe tratarse como controvertida; y la propia ley excluye categorías como donaciones humanitarias y materiales informativos.

### 한국어 (초역 · 初译待校)
1977년 국제긴급경제권한법(IEEPA, 50 U.S.C. §§ 1701–1706)은 현대 경제제재의 주된 동력입니다. 대통령이 먼저 국가비상사태법에 따라 국외에서 비롯된 비정상적이고 비상한 위협에 대해 비상사태를 선언한 뒤, 자산을 동결하고 거래를 금지·규제합니다. 집행은 재무부 해외자산통제국(OFAC)이 맡습니다. 시험 포인트는 세 가지입니다. 비상사태 선언이 없으면 권한도 없습니다. 법문은 동결·금지·수출입 규제를 열거할 뿐 관세를 명시하지 않아, 관세 부과 근거가 될 수 있는지는 2025년 주요 소송 쟁점이 되었으므로 단정하지 말고 쟁점으로 표시해야 합니다. 그리고 인도적 기부와 정보 자료 등 제외 범주가 법 안에 내장되어 있습니다. (초역·待校)

### Tiếng Việt (bản dịch sơ bộ · 初译待校)
Đạo luật Quyền lực Kinh tế Khẩn cấp Quốc tế 1977 (IEEPA), 50 U.S.C. §§ 1701–1706, là động cơ chính của trừng phạt kinh tế hiện đại: Tổng thống trước hết tuyên bố tình trạng khẩn cấp quốc gia về một mối đe dọa bất thường và phi thường từ nước ngoài, rồi phong tỏa tài sản và cấm hoặc điều tiết giao dịch. Việc thi hành thuộc OFAC của Bộ Tài chính. Ba điểm thi: không có tuyên bố khẩn cấp thì không có thẩm quyền; văn bản luật liệt kê phong tỏa, cấm và điều tiết xuất nhập khẩu nhưng không ghi rõ thuế quan, nên câu hỏi IEEPA có hỗ trợ áp thuế hay không đã thành tranh tụng lớn năm 2025 và phải nêu như vấn đề đang tranh cãi; và luật tự loại trừ các hạng mục như quyên góp nhân đạo và tài liệu thông tin. (bản dịch sơ bộ·待校)

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)
अंतर्राष्ट्रीय आपातकालीन आर्थिक शक्ति अधिनियम 1977 (IEEPA), 50 U.S.C. §§ 1701–1706, आधुनिक आर्थिक प्रतिबंधों का मुख्य इंजन है: राष्ट्रपति पहले विदेश से उत्पन्न असामान्य और असाधारण खतरे पर राष्ट्रीय आपात घोषित करता है, फिर संपत्ति अवरुद्ध और लेनदेन निषिद्ध या विनियमित करता है। प्रशासन राजकोष विभाग के OFAC के पास है। तीन परीक्षा बिंदु: आपात घोषणा के बिना कोई प्राधिकार नहीं; पाठ अवरोध, निषेध और आयात-निर्यात विनियमन गिनाता है किंतु शुल्क का स्पष्ट उल्लेख नहीं करता, इसलिए IEEPA शुल्क का समर्थन कर सकता है या नहीं — यह 2025 में प्रमुख विवाद बना और इसे विवादित ही दर्शाना चाहिए; और कानून स्वयं मानवीय दान व सूचना सामग्री जैसी श्रेणियों को बाहर रखता है। (प्रारंभिक अनुवाद·待校)

## 四、CFIUS 与出口管制：交易审查的两道闸

### 中文
外国投资审查由外国在美投资委员会 (CFIUS) 负责，授权在 50 U.S.C. § 4565；2018 年《外国投资风险审查现代化法》(FIRRMA) 把审查从「控制型交易」扩到涉及关键技术、关键基础设施与敏感个人数据 (TID) 的特定非控制性投资，并对部分交易设强制申报。CFIUS 可施加缓解条件，总统可阻止或撤销威胁国家安全的交易，2018 年阻止博通收购高通是常引例子。出口管制是另一道闸：《出口管制改革法》(ECRA, 2018)，50 U.S.C. §§ 4801 et seq.，由商务部工业与安全局 (BIS) 以《出口管理条例》(EAR) 执行，实体清单、最终用途与「视为出口」都是高频考点。答题时先分清：CFIUS 管「谁买」，出口管制管「什么能卖给谁」。

### English
Foreign-investment review belongs to the Committee on Foreign Investment in the United States (CFIUS), authorized at 50 U.S.C. § 4565. The Foreign Investment Risk Review Modernization Act of 2018 (FIRRMA) expanded review beyond control transactions to certain non-controlling investments involving critical technologies, critical infrastructure, and sensitive personal data (TID businesses), and imposed mandatory declarations for some deals. CFIUS can impose mitigation conditions, and the President can block or unwind transactions that threaten national security — the 2018 blocking of Broadcom's bid for Qualcomm is the standard example. Export controls are the second gate: the Export Control Reform Act of 2018, 50 U.S.C. §§ 4801 et seq., administered by the Commerce Department's Bureau of Industry and Security (BIS) through the Export Administration Regulations (EAR), with the Entity List, end-use controls, and "deemed exports" as frequent exam topics. Keep the two gates straight: CFIUS asks who is buying; export controls ask what may be sold to whom.

### Español (译稿)
La revisión de la inversión extranjera corresponde al Comité CFIUS, autorizado en 50 U.S.C. § 4565. La ley FIRRMA de 2018 amplió la revisión más allá de las operaciones de control, alcanzando ciertas inversiones no controlantes en tecnologías críticas, infraestructura crítica y datos personales sensibles (empresas TID), con declaraciones obligatorias para algunas operaciones. El CFIUS puede imponer condiciones de mitigación y el Presidente puede bloquear o deshacer operaciones que amenacen la seguridad nacional; el bloqueo en 2018 de la oferta de Broadcom por Qualcomm es el ejemplo clásico. Los controles de exportación son la segunda puerta: la ley ECRA de 2018, 50 U.S.C. §§ 4801 y ss., ejecutada por la Oficina BIS mediante el reglamento EAR, con la Lista de Entidades, controles de uso final y las «exportaciones presuntas» como temas frecuentes.

### 한국어 (초역 · 初译待校)
외국인 투자 심사는 대미외국인투자위원회(CFIUS)가 담당하며 근거는 50 U.S.C. § 4565입니다. 2018년 외국인투자위험심사현대화법(FIRRMA)은 심사 범위를 지배 거래에서 핵심 기술·핵심 인프라·민감한 개인정보(TID 사업)와 관련된 특정 비지배 투자까지 넓히고 일부 거래에 강제 신고를 부과했습니다. CFIUS는 완화 조건을 붙일 수 있고, 대통령은 국가안보를 위협하는 거래를 막거나 되돌릴 수 있습니다. 2018년 브로드컴의 퀄컴 인수 저지가 대표 사례입니다. 수출통제는 두 번째 관문으로, 2018년 수출통제개혁법(ECRA, 50 U.S.C. §§ 4801 이하)을 상무부 산업안보국(BIS)이 수출관리규정(EAR)으로 집행합니다. 실체 목록(Entity List), 최종 용도 통제, 「간주 수출」이 단골 주제입니다. (초역·待校)

### Tiếng Việt (bản dịch sơ bộ · 初译待校)
Việc rà soát đầu tư nước ngoài thuộc Ủy ban CFIUS, theo 50 U.S.C. § 4565. Đạo luật FIRRMA 2018 mở rộng rà soát vượt qua giao dịch kiểm soát, tới một số khoản đầu tư không kiểm soát liên quan công nghệ trọng yếu, hạ tầng trọng yếu và dữ liệu cá nhân nhạy cảm (doanh nghiệp TID), với khai báo bắt buộc cho một số thương vụ. CFIUS có thể áp điều kiện giảm thiểu, và Tổng thống có thể chặn hoặc hủy giao dịch đe dọa an ninh quốc gia; vụ chặn Broadcom mua Qualcomm năm 2018 là ví dụ chuẩn. Kiểm soát xuất khẩu là cổng thứ hai: Đạo luật ECRA 2018, 50 U.S.C. §§ 4801 trở đi, do Cục BIS của Bộ Thương mại thi hành qua EAR, với Danh sách Thực thể, kiểm soát mục đích sử dụng cuối và «xuất khẩu được coi như» là chủ đề thi thường gặp. (bản dịch sơ bộ·待校)

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)
विदेशी निवेश समीक्षा CFIUS समिति के पास है, जिसका आधार 50 U.S.C. § 4565 है। FIRRMA 2018 ने समीक्षा को नियंत्रण लेनदेनों से आगे बढ़ाकर महत्वपूर्ण प्रौद्योगिकी, महत्वपूर्ण अवसंरचना और संवेदनशील व्यक्तिगत डेटा (TID व्यवसाय) से जुड़े कुछ गैर-नियंत्रण निवेशों तक फैलाया और कुछ सौदों पर अनिवार्य घोषणा लगाई। CFIUS शमन शर्तें लगा सकता है और राष्ट्रपति राष्ट्रीय सुरक्षा को खतरा पहुँचाने वाले सौदे रोक या पलट सकता है; 2018 में Broadcom की Qualcomm बोली का अवरोध मानक उदाहरण है। निर्यात नियंत्रण दूसरा द्वार है: ECRA 2018, 50 U.S.C. §§ 4801 आगे, जिसे वाणिज्य विभाग का BIS EAR के माध्यम से लागू करता है; Entity List, अंतिम-उपयोग नियंत्रण और «माने गए निर्यात» बार-बार पूछे जाने वाले विषय हैं। (प्रारंभिक अनुवाद·待校)

## 五、考试争点清单与加州注记

### 中文
收束成五条可背诵的争点：一，Youngstown 三分法先定格，再谈具体法条；二，FISA 与普通令状在目的、秘密性与通知上全不同，702 的争点在附带收集与回查；三，IEEPA 的命门是紧急状态触发与授权文义边界，制裁执行看 OFAC；四，CFIUS 管投资人身份与交易结构，出口管制管物项与目的地；五，定密与泄密另有轨道——定密依第 13526 号行政命令体系，泄密刑事风险看《间谍法》18 U.S.C. §§ 793–798。加州注记：加州没有州版 FISA；州与地方执法机关获取电子通信受《加州电子通信隐私法》(CalECPA, Penal Code §§ 1546 et seq.) 约束，一般须有令状且有通知与压制规则，与联邦情报轨道分开答。

### English
Five memorizable issue lines: (1) place the action in the Youngstown grid before reaching for any statute; (2) FISA differs from ordinary warrants in purpose, secrecy, and notice, and Section 702 fights are about incidental collection and querying; (3) IEEPA turns on the emergency trigger and the edges of its text, with OFAC running enforcement; (4) CFIUS polices who the investor is and how the deal is structured, while export controls police the item and the destination; (5) classification and leaks run on separate tracks — classification under the Executive Order 13526 system, and leak prosecutions under the Espionage Act, 18 U.S.C. §§ 793–798. California note: California has no state FISA. State and local acquisition of electronic communications is governed by the California Electronic Communications Privacy Act (CalECPA), Penal Code §§ 1546 et seq., which generally requires a warrant and has its own notice and suppression rules — keep it separate from the federal intelligence track.

### Español (译稿)
Cinco líneas memorizables: (1) ubique la acción en el esquema de Youngstown antes de acudir a cualquier ley; (2) FISA difiere de las órdenes ordinarias en finalidad, secreto y notificación, y el debate de la Sección 702 gira sobre recolección incidental y consultas; (3) IEEPA depende del disparador de emergencia y de los límites de su texto, con la OFAC ejecutando; (4) el CFIUS vigila quién invierte y cómo se estructura la operación, mientras los controles de exportación vigilan el artículo y el destino; (5) clasificación y filtraciones van por vías separadas: clasificación bajo el sistema de la Orden Ejecutiva 13526 y persecución de filtraciones bajo la Ley de Espionaje, 18 U.S.C. §§ 793–798. Nota de California: no existe una FISA estatal; el acceso estatal y local a comunicaciones electrónicas se rige por la ley CalECPA, Penal Code §§ 1546 y ss., que en general exige orden judicial.

### 한국어 (초역 · 初译待校)
암기용 쟁점 다섯 가지. ① 구체 법령 전에 Youngstown 3분법으로 위치부터 정할 것. ② FISA는 목적·비밀성·통지에서 일반 영장과 다르고 702조의 쟁점은 부수적 수집과 조회입니다. ③ IEEPA의 급소는 비상사태 발동 요건과 법문상의 권한 경계이며 집행은 OFAC가 맡습니다. ④ CFIUS는 투자자가 누구이고 거래가 어떻게 짜였는지를, 수출통제는 물품과 목적지를 봅니다. ⑤ 비밀 지정과 누설은 별도 궤도로, 지정은 행정명령 13526 체계, 누설 처벌은 간첩법(18 U.S.C. §§ 793–798)입니다. 캘리포니아 주: 주 차원의 FISA는 없습니다. 주·지방 기관의 전자통신 취득은 캘리포니아 전자통신프라이버시법(CalECPA, Penal Code §§ 1546 이하)이 규율하며 일반적으로 영장이 필요합니다. (초역·待校)

### Tiếng Việt (bản dịch sơ bộ · 初译待校)
Năm dòng tranh điểm cần thuộc: (1) đặt hành động vào lưới Youngstown trước khi viện tới bất kỳ đạo luật nào; (2) FISA khác lệnh thường ở mục đích, bí mật và thông báo, và tranh luận về Mục 702 xoay quanh thu thập ngẫu nhiên và truy vấn; (3) IEEPA tùy thuộc điều kiện kích hoạt khẩn cấp và ranh giới văn bản, với OFAC thi hành; (4) CFIUS xem ai là nhà đầu tư và cấu trúc thương vụ, còn kiểm soát xuất khẩu xem mặt hàng và điểm đến; (5) phân loại bí mật và rò rỉ đi theo kênh riêng — phân loại theo hệ thống Sắc lệnh 13526, truy tố rò rỉ theo Đạo luật Gián điệp, 18 U.S.C. §§ 793–798. Ghi chú California: California không có FISA cấp bang; việc cơ quan bang và địa phương tiếp cận truyền thông điện tử chịu sự điều chỉnh của CalECPA, Penal Code §§ 1546 trở đi, thường đòi hỏi lệnh tòa. (bản dịch sơ bộ·待校)

### हिन्दी (प्रारंभिक अनुवाद · 初译待校)
पाँच याद रखने योग्य विवाद-रेखाएँ: (1) किसी कानून से पहले कार्रवाई को Youngstown ढाँचे में रखें; (2) FISA उद्देश्य, गोपनीयता और सूचना में सामान्य वारंट से भिन्न है, और धारा 702 का विवाद आनुषंगिक संग्रह व क्वेरी पर है; (3) IEEPA आपात ट्रिगर और अपने पाठ की सीमाओं पर निर्भर है, प्रवर्तन OFAC करता है; (4) CFIUS निवेशक की पहचान और सौदे की संरचना देखता है, निर्यात नियंत्रण वस्तु और गंतव्य देखता है; (5) वर्गीकरण और लीक अलग मार्गों पर हैं — वर्गीकरण कार्यकारी आदेश 13526 प्रणाली से, लीक अभियोजन जासूसी अधिनियम, 18 U.S.C. §§ 793–798 से। कैलिफ़ोर्निया टिप्पणी: राज्य FISA नहीं है; राज्य व स्थानीय अभिकरणों की इलेक्ट्रॉनिक संचार तक पहुँच CalECPA, Penal Code §§ 1546 आगे से शासित है, जिसमें सामान्यतः वारंट आवश्यक है। (प्रारंभिक अनुवाद·待校)

## 参考依据

- Youngstown Sheet & Tube Co. v. Sawyer, 343 U.S. 579 (1952)（Jackson 协同意见三分法）；Trump v. Hawaii, 585 U.S. 667 (2018)
- Foreign Intelligence Surveillance Act, 50 U.S.C. §§ 1801 et seq.；§ 702, 50 U.S.C. § 1881a；Reforming Intelligence and Securing America Act (2024)
- International Emergency Economic Powers Act, 50 U.S.C. §§ 1701–1706；National Emergencies Act, 50 U.S.C. §§ 1601 et seq.
- CFIUS: 50 U.S.C. § 4565；Foreign Investment Risk Review Modernization Act of 2018；Export Control Reform Act, 50 U.S.C. §§ 4801 et seq.
- Espionage Act, 18 U.S.C. §§ 793–798；Exec. Order No. 13526；California Electronic Communications Privacy Act, Cal. Penal Code §§ 1546 et seq.

## 免责声明

本篇为个人学习笔记，不构成法律建议。条文与判例请以官方原文为准。

*This article is a personal study note, not legal advice. / Este artículo es una nota de estudio personal, no constituye asesoría legal.*
*이 글은 개인 학습 노트이며 법률 자문이 아닙니다. (초역·待校) / Bài viết này là ghi chú học tập cá nhân, không cấu thành tư vấn pháp lý. (bản dịch sơ bộ·待校) / यह लेख व्यक्तिगत अध्ययन नोट है और कानूनी सलाह नहीं है। (प्रारंभिक अनुवाद·待校)*
