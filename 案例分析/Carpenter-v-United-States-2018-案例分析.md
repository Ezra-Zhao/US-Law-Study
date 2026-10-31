# Carpenter v. United States 案例分析：政府调取长期手机定位记录，是一次第四修正案「搜查」

> 个人学习笔记，不构成法律建议。Personal study notes, not legal advice.

## 中文主文

**案名与出处**：Carpenter v. United States, 585 U.S. 296 (2018)，美国联邦最高法院，2018 年 6 月 22 日判决，5 比 4，首席大法官 John Roberts 执笔多数意见。异议有四份，分别由 Kennedy、Thomas、Alito 与 Gorsuch 大法官执笔。

**事实**：Timothy Carpenter 被指控参与密歇根与俄亥俄一带的一系列武装抢劫。一名同案者供出了同伙的手机号后，政府没有申请传统搜查令，而是依据《存储通信法》（Stored Communications Act, 18 U.S.C. § 2703(c)(2)、(d)）申请法院命令——该条只要求政府提出「具体而明确的事实」，显示有合理理由相信记录与正在进行的刑事调查相关且重要，门槛低于搜查令所需的「相当理由（probable cause）」。运营商 MetroPCS 与 Sprint 交出了 Carpenter 的历史基站定位信息（cell-site location information, CSLI）：共 12,898 个定位点，覆盖 127 天，平均每天 101 个点，足以重建他四个月的行踪；检方据此证明案发时他的手机在四处抢劫地点附近。地区法院拒绝排除该证据，Carpenter 被定罪；第六巡回上诉法院维持，理由是他已把定位信息「分享」给运营商，依第三方原则（third-party doctrine）对其没有合理隐私期待。

**争点**：政府在没有搜查令的情况下调取长期历史 CSLI，是否构成第四修正案所禁止的无令搜查？

**多数意见**：构成搜查。理由分三层。第一，CSLI 「深度揭示」一个人的行踪：手机几乎不间断地与基站连接，记录能回溯出一个人去过哪里、和谁在一起，其全面程度接近给每个人装上追踪器，能「穿越时间」重演过去。第二，这种收集是「不可避免且自动」的——只要手机开着就产生记录，用户并没有像拨电话号码那样「自愿传递」信息，因此不能套用 Smith v. Maryland, 442 U.S. 735 (1979)（拨号记录）与 United States v. Miller, 425 U.S. 435 (1976)（银行记录）确立的第三方原则，把 CSLI 当作普通商业记录。第三，结合 United States v. Jones, 565 U.S. 400 (2012) 中关于长期 GPS 监控的协同意见，个人对自己长期行踪整体不被政府系统收集，保有合理隐私期待。结论：政府调取覆盖至少 7 天的历史 CSLI 是一次搜查，一般必须事先取得以相当理由为基础的搜查令；本案依据 § 2703(d) 命令取得不满足这一要求。

**判决的自我限缩**：多数意见反复强调这是一个「狭窄」的判决——不推翻 Smith 与 Miller 对一般商业记录的适用；不处理实时 CSLI、不处理「基站倾倒（tower dump）」；不影响传票等传统调查手段在短期记录上的使用；紧急情形仍可走无令例外。7 天是本案划出的下限，7 天以内的调取是否也要搜查令，判决没有回答，留给下级法院在后续案件中摸索。

**为什么重要**：这是数字时代第四修正案的分水岭：第三方原则第一次被大规模数据挡住——数据握在公司手里，不等于政府可以绕过搜查令。备考时注意它的推理结构不是「信息在谁手里」，而是三问：数据揭示的深度、收集的自动性、回溯的时间跨度。后续关于地理围栏令（geofence warrants）、数据经纪商购买等争论，都从这三问出发。

**加州衔接**：加州《电子通信隐私法》（CalECPA, 2015 年 SB 178，Penal Code §§ 1546–1546.4）比联邦底线更严：政府获取电子通信信息（包括定位信息）原则上须持搜查令或其他法定令状，并对通知与紧急例外有专门规定，且早于 Carpenter 判决两年多就已生效。在加州办案，光满足联邦 Carpenter 标准还不够，还要过 CalECPA 这一关。

**备考要点**：1) 案号 585 U.S. 296 (2018)、5 比 4、Roberts 执笔；2) 数据锚点 12,898 个定位点、127 天、每天约 101 点；3) 法律张力是 § 2703(d) 的「合理理由」低门槛对第四修正案搜查令的相当理由；4) 第三方原则没有被推翻，只是 CSLI 被划为例外——Smith/Miller 仍管普通商业记录；5) 判决明示不处理实时 CSLI 与 tower dump，别把结论外推。

## English

**Case**: Carpenter v. United States, 585 U.S. 296 (2018), U.S. Supreme Court, decided June 22, 2018, 5-4; Chief Justice Roberts for the majority, with four separate dissents (Kennedy, Thomas, Alito, Gorsuch). **Facts**: Investigating a string of armed robberies in Michigan and Ohio, the government obtained Timothy Carpenter's historical cell-site location information (CSLI) not by warrant but by court orders under the Stored Communications Act, 18 U.S.C. § 2703(c)(2) and (d), which require only specific and articulable facts showing reasonable grounds to believe the records are relevant and material — less than probable cause. The carriers produced 12,898 location points over 127 days, about 101 points a day, placing his phone near four robbery scenes. The Sixth Circuit upheld the conviction under the third-party doctrine of Smith v. Maryland, 442 U.S. 735 (1979), and United States v. Miller, 425 U.S. 435 (1976). **Holding**: Acquiring historical CSLI covering at least seven days is a Fourth Amendment search; the government generally needs a warrant supported by probable cause. CSLI is deeply revealing, collected automatically and inescapably whenever a phone is on, and lets the government travel back in time — so it does not fit the voluntary-conveyance logic of Smith and Miller. **Limits**: the Court called its decision narrow: Smith and Miller still govern ordinary business records; real-time CSLI and tower dumps are not addressed; exigent circumstances remain an exception. **California**: CalECPA (Penal Code §§ 1546-1546.4, enacted 2015) already required a warrant for electronic communication information, including location data, before Carpenter was decided.

## Español

**Caso**: Carpenter v. United States, 585 U.S. 296 (2018), Corte Suprema de EE. UU., 22 de junio de 2018, 5 a 4; opinión del presidente del tribunal, Roberts, y cuatro disensos (Kennedy, Thomas, Alito, Gorsuch). **Hechos**: el Gobierno obtuvo el historial de localización por torres de telefonía (CSLI) de Timothy Carpenter sin orden de registro, mediante órdenes del Stored Communications Act (18 U.S.C. § 2703(c)(2) y (d)), cuyo estándar — motivos razonables de relevancia — es inferior a la causa probable. Las operadoras entregaron 12.898 puntos de localización en 127 días, unos 101 por día. **Decisión**: obtener CSLI histórico de al menos siete días es un «registro» bajo la Cuarta Enmienda y, por regla general, exige una orden judicial con causa probable. El CSLI es profundamente revelador, se genera de forma automática e inevitable y permite reconstruir el pasado, por lo que no encaja en la doctrina del tercero de Smith v. Maryland, 442 U.S. 735 (1979), y United States v. Miller, 425 U.S. 435 (1976). **Límites**: la sentencia es expresamente estrecha: no altera Smith y Miller para registros comerciales ordinarios, no resuelve el CSLI en tiempo real ni los «tower dumps». **California**: CalECPA (Penal Code §§ 1546-1546.4, de 2015) ya exigía orden judicial para datos de localización. *(Traducción de estudio, pendiente de revisión por hablante nativo / 初译待校)*

## 한국어

**사건**: Carpenter v. United States, 585 U.S. 296 (2018), 미국 연방대법원, 2018년 6월 22일, 5대 4. Roberts 대법원장의 다수의견, Kennedy·Thomas·Alito·Gorsuch 대법관의 반대의견. **사실**: 정부는 저장통신법(18 U.S.C. § 2703(c)(2), (d))상 법원 명령으로 — 상당한 이유(probable cause)보다 낮은 «관련성과 중요성에 대한 합리적 근거» 기준 — Timothy Carpenter의 과거 기지국 위치정보(CSLI)를 확보했다. 통신사는 127일간 12,898개 지점, 하루 평균 약 101개의 위치기록을 제공했다. **판결**: 최소 7일간의 과거 CSLI 취득은 수정헌법 제4조의 «수색»이며 원칙적으로 상당한 이유에 기초한 영장이 필요하다. CSLI는 행적을 깊이 드러내고, 휴대전화가 켜져 있으면 자동·불가피하게 생성되며, 과거를 되짚을 수 있어 Smith v. Maryland, 442 U.S. 735 (1979)와 United States v. Miller, 425 U.S. 435 (1976)의 제3자 원칙을 그대로 적용할 수 없다. **한계**: 판결은 스스로 «좁은» 결정임을 강조한다 — 일반 영업기록에 대한 Smith·Miller는 유지되고, 실시간 CSLI와 타워 덤프는 판단하지 않았다. **캘리포니아**: CalECPA(Penal Code §§ 1546-1546.4, 2015년)는 본 판결 이전부터 위치정보 취득에 영장을 요구했다. *(초벌 번역, 원어민 교정 대기 / 初译待校)*

## Tiếng Việt

**Vụ án**: Carpenter v. United States, 585 U.S. 296 (2018), Tòa án Tối cao Hoa Kỳ, phán quyết ngày 22 tháng 6 năm 2018, tỉ lệ 5-4; Chánh án Roberts viết ý kiến đa số, bốn thẩm phán Kennedy, Thomas, Alito và Gorsuch bất đồng. **Sự việc**: Chính phủ lấy thông tin vị trí trạm phát sóng trong quá khứ (CSLI) của Timothy Carpenter không bằng lệnh khám xét mà bằng lệnh tòa theo Đạo luật Truyền thông Lưu trữ (18 U.S.C. § 2703(c)(2) và (d)) — tiêu chuẩn «căn cứ hợp lý về tính liên quan» thấp hơn căn cứ xác đáng (probable cause). Nhà mạng đã cung cấp 12.898 điểm vị trí trong 127 ngày, trung bình khoảng 101 điểm mỗi ngày. **Phán quyết**: Việc thu thập CSLI lịch sử từ bảy ngày trở lên là một cuộc «khám xét» theo Tu chính án thứ tư và nói chung cần lệnh dựa trên probable cause. CSLI tiết lộ sâu về hành tung, được tạo tự động và không thể tránh mỗi khi điện thoại bật, và cho phép «quay ngược thời gian», nên không phù hợp với học thuyết bên thứ ba trong Smith v. Maryland, 442 U.S. 735 (1979) và United States v. Miller, 425 U.S. 435 (1976). **Giới hạn**: phán quyết tự nhận là hẹp — Smith và Miller vẫn áp dụng cho hồ sơ kinh doanh thông thường; CSLI thời gian thực và «tower dump» chưa được xét. **California**: CalECPA (Penal Code §§ 1546-1546.4, năm 2015) đã yêu cầu lệnh đối với dữ liệu vị trí từ trước phán quyết này. *(Bản dịch sơ bộ, chờ người bản ngữ hiệu đính / 初译待校)*

## हिन्दी

**मामला**: Carpenter v. United States, 585 U.S. 296 (2018), अमेरिकी सर्वोच्च न्यायालय, 22 जून 2018, 5-4; मुख्य न्यायाधीश Roberts का बहुमत मत, Kennedy, Thomas, Alito और Gorsuch के असहमति मत। **तथ्य**: सरकार ने Timothy Carpenter की ऐतिहासिक सेल-साइट स्थान जानकारी (CSLI) वारंट से नहीं, बल्कि Stored Communications Act (18 U.S.C. § 2703(c)(2) और (d)) के अंतर्गत न्यायालय आदेशों से प्राप्त की — जिनका मानक «प्रासंगिकता के उचित आधार» probable cause से नीचे है। वाहकों ने 127 दिनों में 12,898 स्थान-बिंदु दिए, औसतन लगभग 101 प्रतिदिन। **निर्णय**: कम से कम सात दिनों की ऐतिहासिक CSLI प्राप्त करना चौथे संशोधन के अंतर्गत «तलाशी» है और सामान्यतः probable cause पर आधारित वारंट आवश्यक है। CSLI गहराई से खुलासा करने वाली है, फ़ोन चालू होते ही स्वचालित और अनिवार्य रूप से बनती है, और सरकार को समय में पीछे जाने देती है — इसलिए Smith v. Maryland, 442 U.S. 735 (1979) और United States v. Miller, 425 U.S. 435 (1976) का तृतीय-पक्ष सिद्धांत यहाँ लागू नहीं होता। **सीमा**: निर्णय स्वयं को संकीर्ण कहता है — सामान्य व्यावसायिक अभिलेखों पर Smith और Miller बने रहते हैं; वास्तविक-समय CSLI और tower dump पर कोई निर्णय नहीं। **California**: CalECPA (Penal Code §§ 1546-1546.4, 2015) इस निर्णय से पहले ही स्थान-डेटा के लिए वारंट माँगता था। *(प्रारंभिक अनुवाद, देशी समीक्षा लंबित / 初译待校)*

---
*个人学习笔记，不构成法律建议。*
