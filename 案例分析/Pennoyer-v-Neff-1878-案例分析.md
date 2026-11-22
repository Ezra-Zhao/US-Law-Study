# Pennoyer v. Neff, 95 U.S. 714 (1878) 案例分析

> 个人学习笔记，不构成法律建议。分工：本篇管 Pennoyer 案本身——案情、领地三格与判决为什么把俄勒冈那张缺席判决判成废纸；仓内《联邦民事诉讼对人管辖权备考核心》管最低接触的现代答题框架，其中只以指针提及本案、无本案本体专篇，两篇以指针分工。选题留痕：本轮主题经 ls 文件名加 git grep 正文双查——「Pennoyer」在案例分析板块文件名零命中，正文仅见于备考篇的源头一节与 README 指针，无案例本体专篇，采用。

---

## 中文主文

### 一、案情：一笔 253 美元的律师费，拖出一块地

Marcus Neff 早年到俄勒冈垦殖，依联邦赠地法主张了一块土地的权利，请当地律师 John H. Mitchell 帮他把地权手续办完。手续办完，律师费没有结清。Mitchell 在俄勒冈州法院起诉 Neff 索要未付律师费，诉请金额约 253 美元。问题在于，起诉时 Neff 已经不住在俄勒冈——他搬去了加州，人不在州内，传票送不到本人手上。Mitchell 按俄勒冈法走公告送达（service by publication）：在报纸上登公告，就算送达。Neff 没有出庭，法院在 1866 年作出缺席判决（default judgment），判 Mitchell 胜诉。

执行环节把事情放大了。为清偿这笔小额判决，法院执行官（sheriff）拍卖了 Neff 名下那块地，土地几经转手落入 Sylvester Pennoyer 之手——此人后来做过俄勒冈州长，案名里的 Pennoyer 就是他；判决书正是把 Pennoyer 当作经执行拍卖取得权利的一方来处理的。Neff 回过头来在联邦巡回法院起诉 Pennoyer，主张那张缺席判决从头就无效、拍卖跟着无效、地还是自己的。案件一路打到联邦最高法院，1878 年 1 月判决，Field 大法官执笔，Neff 胜诉：俄勒冈判决无效，Pennoyer 从拍卖里取得不了有效权利。

算例先立一条：2026 减 1878 等于 148，本案已立 148 年。它不是博物馆展品——今天每一本民事诉讼法教材讲对人管辖权，第一页几乎都从它讲起。

### 二、领地三格：管辖跟着物理权力走

Field 给出的框架后来被叫作领地主义（territoriality），核心是两条公理。第一条：每个州对自己领地内的人和财产有专属管辖（exclusive jurisdiction）。第二条：没有任何州能对领地之外的人或财产行使直接管辖（direct jurisdiction）。管辖权跟着州的物理权力走，权力到哪里为止，管辖就到哪里为止。

落到操作面，就是三格。第一格，人在州内：被告身在州内、被当面送达，州法院可以对他作对人判决（in personam），判他赔钱、判他履行义务，判决跟着人走。第二格，财产在州内：被告人不在，但他在州内有财产，州可以把财产扣押（attachment）后就财产本身或以财产为限打官司，这叫对物或准对物管辖（in rem / quasi in rem），判决效力以那件财产为限。第三格，同意与身份：被告同意受管辖，或者案件涉及州内居民的身份关系（如本州居民的婚姻状态），州也有管辖的落点。

这三格之外没有第四条路。尤其是第二格，Field 埋了一个程序要件，后文正是它咬死了 Mitchell 的判决：以财产为基础的诉讼，财产必须在诉讼开始时（at the outset）就被扣押、置于法院控制之下，管辖才成立。

### 三、判决为什么无效：两处都断了

最高法院认定俄勒冈判决无效，给了两层理由。

第一层是宪法与管辖原理层。Neff 是非居民，人不在俄勒冈、没有在州内被送达、也没有出庭应诉；他的地在诉讼开始时并没有被扣押——公告送达登报的时候，法院手里既没有人、也没有财产。按领地三格逐格对：第一格人不在，过不了；第二格财产没有在开头扣押，过不了；第三格没有同意，也过不了。三格全空，这张对人缺席判决就是州法院对一个州外人行使了它没有的直接管辖，判决自始无效（void），不是效力有瑕疵可以补正，而是从一开始就不存在约束 Neff 的力量。判决无效，靠它执行的拍卖就是无源之水，Pennoyer 买到的权利跟着倒。

第二层是州法程序层，写得更细碎但同样致命：Mitchell 申请公告送达所依据的宣誓书（affidavit）本身不符合俄勒冈法的要求。也就是说，就算退到州法内部看，这次公告送达的启动手续也不合格。两层理由叠在一起，最高法院连给俄勒冈法院留台阶的余地都没有。

有一处定位要写准：本案判决时第十四修正案已经生效（1868 年批准），Field 的论述后来被读作正当程序管辖学的源头——管辖权的边界被安放在正当程序的根基上，后世把「没有管辖的判决违反正当程序」这条线追溯到这里。但本案判决书本身的推理骨架仍是州际管辖的一般原理与领地公理，正当程序的完整展开是后人在这个框架上续写的，答题时把两层分开，别把后世的话全算到 Field 头上。

### 四、遗产：这套框架管了 67 年，又被换了什么

领地三格此后管了美国管辖法大半个世纪，直到 International Shoe Co. v. Washington, 326 U.S. 310 (1945) 换轨：被告不在州内出现时，改看最低接触（minimum contacts）——接触够、诉讼维持不违背公平游戏与实质正义的传统观念，管辖就成立。算例：1945 减 1878 等于 67，Pennoyer 框架整整管了 67 年才被换轨。

但说 Pennoyer 被推翻是不准确的，它更像是被收编。三格里有两格至今活着：一是过境送达（tag jurisdiction）——被告本人身在论坛州时被当面送达即成立管辖，Burnham v. Superior Court, 495 U.S. 604 (1990) 全院一致维持其存续，那正是第一格的直系后代，而且 Burnham 案就起于加州法院。二是同意——注册经营视为同意管辖在 Mallory v. Norfolk Southern Railway Co., 600 U.S. 122 (2023) 被多元意见维持，老先例未被推翻。第二格的命运不同：Shaffer v. Heitner, 433 U.S. 186 (1977) 判明连对物与准对物管辖也要过最低接触检验，只扣一件与诉因无关的财产拽不来管辖——算例：1977 减 1878 等于 99，本案 99 年后，它的第二格被现代标准接管。

今天读本案，真正要带走的是它的问题意识而不是答案：法院凭什么能判一个不在场的人？Field 的回答是物理权力，现代法的回答是接触加公平，问题本身从 1878 年问到今天没有变过。

### 五、加州落点（单独注明）

加州与本案有三处接口。第一，长臂的尽头仍是宪法：加州《民事诉讼法典》第 410.10 条把州法院的对人管辖放到「宪法与法律允许的任何基础上」，即长臂伸到正当程序允许的极限为止——条文写法是现代的，但它划界的问题意识正是 Pennoyer 留下的：边界在哪里、谁说了算，答案是宪法说了算。第二，Burnham 的过境送达起于加州：外州被告在加州境内被当面送达，加州法院对他有管辖，这条 Pennoyer 第一格的活口在加州是现行法的一部分，短期入境加州的人被送达不是都市传说。第三，扣押的开头要件在加州仍有对应物：加州扣押法（《民事诉讼法典》第 481.010 条以下）对诉前与诉中扣押的启动、担保与听证有成套规定，「先把财产置于法院控制之下才谈得上以财产为基础推进程序」的次序感，与本案第二格的要求一脉相承；只是 Shaffer 之后，扣押解决的是保全与程序控制，管辖本身还要另过最低接触这一关，两件事不要混写。

### 六、要点清单

一，案名与出处：Pennoyer v. Neff, 95 U.S. 714 (1878)，联邦最高法院，Field 执笔；诉请律师费约 253 美元，缺席判决作出于 1866 年。二，领地三格：人在州内当面送达（对人）、财产在州内且诉讼开始时已扣押（对物／准对物）、同意或身份关系。三，无效理由两层：三格全空、对州外非居民的对人判决自始无效；公告送达的宣誓书不合州法要求。四，定位分寸：正当程序的根基地位是后世读法，判决书骨架是领地公理，两层分开写。五，后世命运分格记：第一格活在 Burnham（1990，过境送达）、第三格活在 Mallory（2023，注册同意）、第二格被 Shaffer（1977）收编进最低接触。六，与备考篇分工：现代最低接触的两问答题结构看仓内对人管辖权备考篇，本篇只管本案本体。

*声明：个人学习笔记，不构成法律建议。*

---

## English

Pennoyer v. Neff, 95 U.S. 714 (1878), grew out of an unpaid legal fee of about $253. Marcus Neff had hired Oregon lawyer John H. Mitchell to perfect his land claim; when Mitchell sued for the fee in Oregon state court, Neff had moved to California, so Mitchell used service by publication, Neff never appeared, and a default judgment entered in 1866. The sheriff sold Neff's land to satisfy the judgment, and the land ended up in the hands of Sylvester Pennoyer, later governor of Oregon. Neff sued Pennoyer in federal court to recover the land, and the Supreme Court, per Justice Field, held the Oregon judgment void (2026 − 1878 = 148 years ago). Field's framework was territorial: every state has exclusive jurisdiction over persons and property within its territory, and no state may exercise direct jurisdiction over persons or property outside it. In practice that meant three boxes — personal service on a defendant present in the state (in personam), property in the state attached at the outset of the suit (in rem or quasi in rem, with judgment limited to the property), or consent and domestic status. Mitchell's judgment fit none: Neff was a nonresident never served in Oregon and never appearing, and his land had not been attached when the suit began, so publication alone could not support a personal judgment against him; the supporting affidavit for publication was also defective under Oregon law. A void judgment could support no valid sheriff's sale, so Pennoyer took nothing. The territorial frame governed for 67 years (1945 − 1878 = 67) until International Shoe Co. v. Washington, 326 U.S. 310 (1945), substituted minimum contacts. Pennoyer was absorbed rather than simply overruled: its first box survives as tag jurisdiction in Burnham v. Superior Court, 495 U.S. 604 (1990) — a case that itself arose in California — and consent by registration survived in Mallory v. Norfolk Southern Railway Co., 600 U.S. 122 (2023), while Shaffer v. Heitner, 433 U.S. 186 (1977) (1977 − 1878 = 99 years later) subjected even quasi in rem jurisdiction to minimum contacts. California's long-arm statute, Code of Civil Procedure § 410.10, extends jurisdiction on any basis permitted by the Constitution, and its attachment statutes (Code Civ. Proc. § 481.010 et seq.) preserve Pennoyer's sequencing instinct — property must be brought under the court's control before it can anchor proceedings — though after Shaffer attachment handles security and control, while jurisdiction itself must separately pass minimum contacts. *Personal study notes only; not legal advice.*

## Español — traducción de estudio (初译待校)

Pennoyer v. Neff, 95 U.S. 714 (1878), nació de unos honorarios legales impagados de unos 253 dólares. Marcus Neff había contratado al abogado de Oregón John H. Mitchell para perfeccionar su título sobre una tierra; cuando Mitchell demandó el pago ante un tribunal estatal de Oregón, Neff se había mudado a California, así que Mitchell recurrió a la notificación por publicación, Neff nunca compareció y en 1866 se dictó sentencia en rebeldía. El sheriff vendió la tierra de Neff para satisfacer la sentencia y la tierra terminó en manos de Sylvester Pennoyer, luego gobernador de Oregón. Neff demandó a Pennoyer ante un tribunal federal para recuperar la tierra, y la Corte Suprema, con ponencia del juez Field, declaró nula la sentencia de Oregón (2026 − 1878 = hace 148 años). El marco de Field era territorial: cada estado tiene jurisdicción exclusiva sobre las personas y los bienes dentro de su territorio, y ningún estado puede ejercer jurisdicción directa sobre personas o bienes fuera de él. En la práctica había tres casillas: notificación personal al demandado presente en el estado (in personam), bienes en el estado embargados desde el inicio del litigio (in rem o cuasi in rem, con sentencia limitada a los bienes), o consentimiento y estado civil. La sentencia de Mitchell no encajaba en ninguna: Neff era un no residente al que nunca se notificó en Oregón ni compareció, y su tierra no había sido embargada al comenzar el pleito, de modo que la sola publicación no podía sostener una sentencia personal contra él; además, la declaración jurada que sustentaba la publicación era defectuosa según la ley de Oregón. Una sentencia nula no podía sostener una venta válida del sheriff, así que Pennoyer no adquirió nada. El marco territorial gobernó 67 años (1945 − 1878 = 67) hasta que International Shoe Co. v. Washington, 326 U.S. 310 (1945), lo sustituyó por los contactos mínimos. Pennoyer fue absorbido más que revocado: su primera casilla sobrevive como jurisdicción por presencia en Burnham v. Superior Court, 495 U.S. 604 (1990) —un caso surgido en California— y el consentimiento por registro sobrevivió en Mallory v. Norfolk Southern Railway Co., 600 U.S. 122 (2023), mientras que Shaffer v. Heitner, 433 U.S. 186 (1977) (1977 − 1878 = 99 años después) sometió incluso la jurisdicción cuasi in rem a los contactos mínimos. El estatuto de brazo largo de California, Código de Procedimiento Civil § 410.10, extiende la jurisdicción sobre cualquier base permitida por la Constitución, y sus normas de embargo (§ 481.010 y siguientes) conservan el instinto de secuencia de Pennoyer —los bienes deben quedar bajo control del tribunal antes de anclar el procedimiento—, aunque tras Shaffer el embargo se ocupa de la garantía y el control, mientras la jurisdicción misma debe superar por separado los contactos mínimos. *Notas personales de estudio; no constituye asesoría legal.* (Traducción de estudio, pendiente de revisión)

## 한국어 — 초역, 교정 대기 중 (初译待校)

Pennoyer v. Neff, 95 U.S. 714 (1878)는 약 253달러의 미지급 변호사 보수에서 비롯됐다. Marcus Neff는 오리건 변호사 John H. Mitchell에게 토지 권리 완비를 맡겼는데, Mitchell이 오리건 주법원에 보수 청구를 제기했을 때 Neff는 이미 캘리포니아로 이주한 뒤였다. 그래서 Mitchell은 공시송달을 이용했고, Neff는 출석하지 않았으며, 1866년 궐석판결이 내려졌다. 집행관은 판결 충족을 위해 Neff의 토지를 매각했고, 그 토지는 훗날 오리건 주지사가 되는 Sylvester Pennoyer의 손에 들어갔다. Neff는 토지 회복을 구해 Pennoyer를 연방 법원에 제소했고, 대법원은 Field 대법관의 의견으로 오리건 판결이 무효라고 했다(2026 − 1878 = 148년 전). Field의 틀은 영토주의였다. 각 주는 자기 영토 안의 사람과 재산에 대해 배타적 관할을 가지며, 어떤 주도 영토 밖의 사람이나 재산에 직접 관할을 행사할 수 없다. 실무상 세 칸이었다. 주 안에 현존하는 피고에 대한 대인 송달(대인관할), 소송 개시 시점에 압류된 주 내 재산(대물관할·준대물관할, 판결 효력은 그 재산에 한함), 그리고 동의와 신분관계이다. Mitchell의 판결은 어느 칸에도 들지 않았다. Neff는 오리건에서 송달받은 적도 출석한 적도 없는 비거주자였고, 토지는 소송 시작 때 압류되지 않았으므로 공시만으로는 그에 대한 대인판결을 지탱할 수 없었다. 공시를 뒷받침한 진술서도 오리건 법상 흠결이 있었다. 무효인 판결은 집행관 매각의 근거가 될 수 없어 Pennoyer는 아무것도 취득하지 못했다. 영토 틀은 67년간 지배하다가(1945 − 1878 = 67) International Shoe Co. v. Washington, 326 U.S. 310 (1945)이 최소 접촉으로 교체했다. Pennoyer는 폐기라기보다 흡수됐다. 첫째 칸은 Burnham v. Superior Court, 495 U.S. 604 (1990)의 과경 송달 관할로 살아남았고 — 그 사건 자체가 캘리포니아에서 나왔다 — 등록에 의한 동의는 Mallory v. Norfolk Southern Railway Co., 600 U.S. 122 (2023)에서 유지됐으며, Shaffer v. Heitner, 433 U.S. 186 (1977)(1977 − 1878 = 99년 뒤)는 준대물관할조차 최소 접촉 심사를 받게 했다. 캘리포니아 롱암법인 민사소송법전 제410.10조는 헌법이 허용하는 모든 근거로 관할을 넓히고, 그 압류 규정(제481.010조 이하)은 재산이 절차의 닻이 되려면 먼저 법원의 통제 아래 들어와야 한다는 Pennoyer의 순서 감각을 간직하고 있다. 다만 Shaffer 이후 압류는 담보와 통제를 맡고, 관할 자체는 최소 접촉을 별도로 통과해야 한다. *개인 학습 노트이며 법률 자문이 아닙니다.*

## Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

Pennoyer v. Neff, 95 U.S. 714 (1878) bắt nguồn từ khoản phí luật sư chưa trả khoảng 253 đô la. Marcus Neff đã thuê luật sư Oregon John H. Mitchell hoàn thiện quyền đối với một mảnh đất; khi Mitchell kiện đòi phí tại tòa tiểu bang Oregon, Neff đã chuyển tới California, nên Mitchell dùng tống đạt bằng công bố, Neff không bao giờ xuất hiện, và một phán quyết vắng mặt được tuyên năm 1866. Cảnh sát trưởng bán đất của Neff để thi hành phán quyết, và mảnh đất rơi vào tay Sylvester Pennoyer — sau này là thống đốc Oregon. Neff kiện Pennoyer tại tòa liên bang để đòi lại đất, và Tòa Tối cao, theo ý kiến của Thẩm phán Field, tuyên phán quyết Oregon vô hiệu (2026 − 1878 = 148 năm trước). Khung của Field là chủ nghĩa lãnh thổ: mỗi bang có thẩm quyền độc quyền đối với người và tài sản trong lãnh thổ của mình, và không bang nào có thể thực thi thẩm quyền trực tiếp đối với người hay tài sản ngoài lãnh thổ. Trong thực hành có ba ô: tống đạt trực tiếp cho bị đơn đang có mặt trong bang (đối nhân), tài sản trong bang bị kê biên ngay từ đầu vụ kiện (đối vật hoặc bán đối vật, phán quyết giới hạn ở tài sản đó), hoặc đồng ý và quan hệ thân phận. Phán quyết của Mitchell không khớp ô nào: Neff là người không cư trú, chưa từng được tống đạt tại Oregon và chưa từng xuất hiện, và đất của ông chưa bị kê biên khi vụ kiện bắt đầu, nên chỉ công bố thôi không thể chống đỡ một phán quyết đối nhân chống lại ông; bản khai tuyên thệ làm căn cứ cho việc công bố cũng có khiếm khuyết theo luật Oregon. Một phán quyết vô hiệu không thể làm căn cứ cho một vụ bán hợp lệ của cảnh sát trưởng, nên Pennoyer không nhận được gì. Khung lãnh thổ chi phối 67 năm (1945 − 1878 = 67) cho tới khi International Shoe Co. v. Washington, 326 U.S. 310 (1945) thay nó bằng tiếp xúc tối thiểu. Pennoyer bị hấp thụ hơn là bị lật đổ: ô thứ nhất của nó sống tiếp thành thẩm quyền tống đạt khi đi ngang qua trong Burnham v. Superior Court, 495 U.S. 604 (1990) — một vụ án xuất phát từ California — và đồng ý bằng đăng ký sống tiếp trong Mallory v. Norfolk Southern Railway Co., 600 U.S. 122 (2023), trong khi Shaffer v. Heitner, 433 U.S. 186 (1977) (1977 − 1878 = 99 năm sau) buộc ngay cả thẩm quyền bán đối vật cũng phải qua kiểm nghiệm tiếp xúc tối thiểu. Luật tay dài của California, Bộ luật Tố tụng Dân sự § 410.10, mở rộng thẩm quyền trên mọi cơ sở Hiến pháp cho phép, và các quy định kê biên của nó (§ 481.010 và tiếp theo) giữ lại trực giác về trình tự của Pennoyer — tài sản phải được đưa vào kiểm soát của tòa trước khi có thể neo giữ thủ tục — dù sau Shaffer, kê biên lo phần bảo đảm và kiểm soát, còn thẩm quyền tự nó phải qua tiếp xúc tối thiểu một cách riêng biệt. *Ghi chú học tập cá nhân, không phải tư vấn pháp lý.*

## हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

Pennoyer v. Neff, 95 U.S. 714 (1878) की जड़ लगभग 253 डॉलर के अवैतनिक वकील-शुल्क में थी। Marcus Neff ने Oregon के वकील John H. Mitchell को अपनी भूमि का अधिकार पूर्ण कराने के लिए रखा था; जब Mitchell ने Oregon राज्य न्यायालय में शुल्क का दावा किया, Neff California जा चुके थे, इसलिए Mitchell ने प्रकाशन द्वारा तामील का सहारा लिया, Neff कभी उपस्थित नहीं हुए, और 1866 में एकपक्षीय निर्णय हो गया। शेरिफ़ ने निर्णय की पूर्ति के लिए Neff की भूमि बेच दी और वह भूमि Sylvester Pennoyer — बाद में Oregon के गवर्नर — के हाथों में पहुँची। Neff ने भूमि वापस पाने के लिए Pennoyer पर संघीय न्यायालय में मुकदमा किया, और सर्वोच्च न्यायालय ने न्यायमूर्ति Field के मत से Oregon के निर्णय को शून्य ठहराया (2026 − 1878 = 148 वर्ष पूर्व)। Field का ढाँचा क्षेत्रीय था: हर राज्य को अपने क्षेत्र के भीतर के व्यक्तियों और संपत्ति पर अनन्य अधिकार-क्षेत्र है, और कोई राज्य क्षेत्र के बाहर के व्यक्तियों या संपत्ति पर प्रत्यक्ष अधिकार-क्षेत्र नहीं चला सकता। व्यवहार में तीन खाने थे — राज्य में उपस्थित प्रतिवादी पर व्यक्तिगत तामील (व्यक्तिगत अधिकार-क्षेत्र), मुकदमे की शुरुआत में ही कुर्क राज्य-स्थित संपत्ति (वस्तु-विषयक या अर्ध-वस्तु-विषयक, निर्णय का प्रभाव उसी संपत्ति तक सीमित), या सहमति और वैवाहिक स्थिति। Mitchell का निर्णय किसी खाने में नहीं बैठा: Neff अनिवासी थे, Oregon में उन्हें कभी तामील नहीं हुई, वे कभी उपस्थित नहीं हुए, और मुकदमा शुरू होते समय उनकी भूमि कुर्क नहीं थी, इसलिए केवल प्रकाशन उनके विरुद्ध व्यक्तिगत निर्णय का आधार नहीं बन सकता था; प्रकाशन के आधार बने शपथपत्र में भी Oregon कानून के अनुसार दोष था। शून्य निर्णय शेरिफ़ की वैध बिक्री का आधार नहीं बन सकता था, इसलिए Pennoyer को कुछ नहीं मिला। क्षेत्रीय ढाँचा 67 वर्ष चला (1945 − 1878 = 67), फिर International Shoe Co. v. Washington, 326 U.S. 310 (1945) ने उसे न्यूनतम संपर्क से बदल दिया। Pennoyer को उलटा कम, समाहित अधिक किया गया: उसका पहला खाना Burnham v. Superior Court, 495 U.S. 604 (1990) में पारगमन-तामील अधिकार-क्षेत्र के रूप में जीवित रहा — वह मामला स्वयं California से उठा था — और पंजीकरण द्वारा सहमति Mallory v. Norfolk Southern Railway Co., 600 U.S. 122 (2023) में बनी रही, जबकि Shaffer v. Heitner, 433 U.S. 186 (1977) (1977 − 1878 = 99 वर्ष बाद) ने अर्ध-वस्तु-विषयक अधिकार-क्षेत्र को भी न्यूनतम संपर्क की कसौटी पर रखा। California का long-arm कानून, सिविल प्रक्रिया संहिता § 410.10, संविधान द्वारा अनुमत किसी भी आधार पर अधिकार-क्षेत्र फैलाता है, और उसके कुर्की प्रावधान (§ 481.010 आदि) Pennoyer की क्रम-भावना को सहेजते हैं — संपत्ति कार्यवाही का लंगर बने, उससे पहले उसे न्यायालय के नियंत्रण में आना होगा — हालाँकि Shaffer के बाद कुर्की सुरक्षा और नियंत्रण संभालती है, जबकि अधिकार-क्षेत्र को स्वयं न्यूनतम संपर्क अलग से पार करना होता है। *व्यक्तिगत अध्ययन नोट्स मात्र; विधिक सलाह नहीं।*

## 补译增量（2026-11-22 03:55 轮）

本节为存量补译增量：以下两项细节仅见于中文主文，此前韩／越／印三语段同缺（关键词回查确认：Donation 赠地表述与「全院一致」表述在三语段均为零命中），现各补一段，纯增量、只加不删。

### 한국어 — 초역, 교정 대기 중 (初译待校)

- 연방 증지법에 따른 토지 주장: Marcus Neff가 오리건에서 다진 토지 권리는 연방 증지법(Donation Land Claim)에 따라 주장한 것이었습니다. 그는 그 권리 완비 절차를 변호사 John H. Mitchell에게 맡겼고, 나중에 문제가 된 약 253달러의 미지급 보수는 바로 그 절차에서 생긴 것이었습니다.
- Burnham의 전원 일치 유지: Pennoyer 첫째 칸의 직계 후손인 과경 송달 관할(tag jurisdiction)은 Burnham v. Superior Court, 495 U.S. 604 (1990)에서 전원 일치로 그 존속이 유지됐습니다. 표결이 갈리지 않았다는 점이 중요합니다. 영토 틀의 이 부분은 폐기된 것이 아니라, 현대법 안에서도 다툼 없이 살아남은 부분입니다.

### Tiếng Việt — bản dịch sơ bộ, chờ hiệu đính (初译待校)

- Quyền đất theo luật tặng đất liên bang: Quyền đối với mảnh đất mà Marcus Neff gây dựng tại Oregon là quyền ông xác lập theo luật tặng đất liên bang (Donation Land Claim). Ông thuê luật sư John H. Mitchell hoàn thiện thủ tục cho quyền đó, và khoản phí chưa trả khoảng 253 đô la gây ra vụ kiện sau này sinh ra chính từ thủ tục ấy.
- Burnham duy trì với sự nhất trí toàn thể: Thẩm quyền tống đạt khi đi ngang qua (tag jurisdiction) — hậu duệ trực hệ của ô thứ nhất trong Pennoyer — được duy trì tồn tại với sự nhất trí toàn thể của Tòa trong Burnham v. Superior Court, 495 U.S. 604 (1990). Việc biểu quyết không hề chia rẽ là điểm đáng chú ý: phần này của khung lãnh thổ không bị gạt bỏ, mà sống sót ngay trong luật hiện đại mà không gây tranh cãi.

### हिन्दी — प्रारंभिक अनुवाद, समीक्षा लंबित (初译待校)

- संघीय दान-भूमि कानून के तहत भूमि का दावा: Oregon में Marcus Neff ने जिस भूमि-अधिकार को पक्का किया था, वह संघीय दान-भूमि दावे (Donation Land Claim) के तहत किया गया दावा था। उस अधिकार की प्रक्रिया पूर्ण कराने के लिए उन्होंने वकील John H. Mitchell को रखा था, और बाद में विवाद बनी लगभग 253 डॉलर की अवैतनिक फीस उसी प्रक्रिया से उत्पन्न हुई थी।
- Burnham में सर्वसम्मत बनाए रखना: Pennoyer के पहले खाने की सीधी वंशज, पारगमन-तामील अधिकार-क्षेत्र (tag jurisdiction), को Burnham v. Superior Court, 495 U.S. 604 (1990) में सर्वसम्मति से बनाए रखा गया। मत विभाजित न होना ही महत्त्वपूर्ण है: क्षेत्रीय ढाँचे का यह हिस्सा रद्द नहीं हुआ, बल्कि आधुनिक कानून के भीतर भी बिना विवाद के जीवित रहा।
