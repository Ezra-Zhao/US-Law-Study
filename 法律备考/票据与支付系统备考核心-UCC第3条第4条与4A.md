# 票据与支付系统备考核心：UCC 第 3 条、第 4 条与第 4A 条

## 中文主文

### 一、先分三条轨道：票据、银行存款取款、大额电汇

支付法备考先分轨道，混轨是丢分第一原因。UCC 第 3 条管可转让票据（negotiable instruments）——汇票（draft，含支票这个特殊物种）与本票（note）；第 4 条管银行存款与托收（bank deposits and collections），即支票在银行系统里怎么流转、什么时候算付掉；第 4A 条管大额批发性资金划拨（funds transfers，如 Fedwire 类电汇），特点是金额大、速度不可逆、欺诈损失怎么分有专门规则。消费者的电子转账（借记卡、ACH 消费转账）不在第 4A 条里，走联邦《电子资金划拨法》（EFTA，15 U.S.C. § 1693）与 Regulation E——第 4A 条第 4A-108 条明文把 EFTA 覆盖的交易排除在外。

### 二、第 3 条第一关：什么叫「可转让」

第 3-104 条的要件要逐项背：无条件付款承诺或指令（unconditional promise or order）、固定金额的金钱（fixed amount of money，利率可浮动）、凭票即付或向指定人支付（payable to bearer or to order）、见票即付或确定日期支付（on demand or at a definite time）、除付款外不加别的义务（少数法定例外除外）。少一项，纸还是合同，却进不了第 3 条的流通轨道。支票是「以银行为付款人、见票即付的汇票」（第 3-104(f) 条）。

### 三、流通的发动机：正当持票人（HDC）与抗辩切断

第 3-302 条：持票人以对价取得（for value）、善意（good faith）、且不知悉逾期、被拒付、抗辩或权利主张，方为正当持票人（holder in due course）。HDC 的核心好处在第 3-305 条：可以切断「个人抗辩」（personal defenses，如缔约欺诈、未履行对价），只剩四类「真实抗辩」（real defenses）能对抗他——未成年等使义务无效的无行为能力、可使义务归于无效的胁迫与违法、签票事实本身的欺诈（fraud in factum，如在不知情下被骗签）、破产免责。考试最爱埋的点：第 3-203(b) 条的 shelter 规则——受让人一般能承继让与人的 HDC 地位，除非自己参与过欺诈或违法。

### 四、签名、伪造与过失分担

未经授权的签名原则上不对被冒名者发生效力（第 3-403 条），伪造背书通常使付款人不能「正当付款」。但过失会翻转损失：第 3-406 条规定，对签名的伪造或票面变造有重大过失的人，不得向善意付款或受让者主张伪造，此即 negligence preclusion。第 3-404 条管冒名者与虚拟受款人（impostors/fictitious payees），第 3-405 条管雇员欺诈性背书（employer 对其委以票据职责的雇员的欺诈背书承担风险，前提是受让/付款方善意）——两条都是把伪造背书的损失从银行转回雇主/出票人的「有效背书」拟制规则，是雇主内控考点的根。

### 五、提示、保付与担保责任

流通链上每个转让者都给后手两类担保（第 3-416 条转移担保）：有权转让、签名真实有效、无变造、不知悉破产程序等；向付款人提示者另给第 3-417 条提示担保。承兑（acceptance）使汇票付款人成为主责方；支票的保付（certification）即银行承兑，保付后出票人与背书人一般免责（第 3-414、3-415 条的责任结构要对照记）。拒付须经正当提示与拒付通知，追索才成立（第 3-501 起的程序线）。

### 六、第 4 条：支票在银行里的时间与责任

第 4 条的关键词全是时间。午夜期限（midnight deadline，第 4-104(a)(10) 条定义、第 4-302 条责任）：付款银行收到票据后超过午夜期限仍未付款、退票或发出通知，要对票面金额负责，无论票据本身是否应付。第 4-215 条定最终付款（final payment）的四个时点，付款一旦最终化，临时入账（provisional settlement，第 4-201 条的推定）转为确定，银行的撤销窗口关闭。第 4-401 条：银行只能扣划「正当可付」（properly payable）的款项，超额透支、伪造签名支票原则上不得扣客户的账；第 4-402 条对应错误拒付（wrongful dishonor）的银行责任。第 4-406 条是客户一方的义务：收到对账单后须以合理 promptness 查核，未经授权签名或变造若因客户迟报而重复发生（同一作伪者、30 天后），客户被预断（precluded）；未经授权签名与变造的最终报告期是 1 年，逾期绝对预断。

### 七、联邦叠加层与第 4A 条

支票之上还有两层联邦法：Regulation CC（12 C.F.R. Part 229）管资金可用期与退票时限，《Check 21 法》（12 U.S.C. §§ 5001 起）让替代支票（substitute check）与原件同效、支撑电子截票。第 4A 条只记三件事：适用范围限于批发性信用划拨；第 4A-202、4A-203 条的「商业上合理的」安全程序（security procedure）是损失分配的开关——银行按约定安全程序善意执行了付款指令，指令即使是骗子发出的，也以客户的授权论，损失归客户；接收银行未按程序核验的，损失反转。错汇、迟汇的救济窄（第 4A-305 条迟延利息与附随损失的明文约定门槛），与消费转账的 EFTA 纠错权形成对照，是论述题的固定对照组。

### 八、加州衔接

加州《商法典》（Commercial Code）第 3 编、第 4 编、第 4A 编与 UCC 对应条文大体一致，条号采「编号＋条号」结构（如第 3 编为 3101 条起）。加州考点只抓两处本地特色：一是支票与账户争议常与《加州金融法典》的银行监管并行；二是消费转账争议优先找 EFTA/Regulation E 的联邦纠错通道，不进第 4A 条。

*声明：个人学习笔记，不构成法律建议。来源：UCC Articles 3、4、4A（§§ 3-104、3-203、3-302、3-305、3-403 至 3-406、3-416、3-417、4-104、4-201、4-215、4-302、4-401、4-402、4-406、4A-102、4A-108、4A-202、4A-305）；15 U.S.C. § 1693；12 C.F.R. Part 229；12 U.S.C. §§ 5001 起；California Commercial Code Divisions 3、4、4A。*

---

## English

UCC payments law runs on three tracks: Article 3 for negotiable instruments, Article 4 for bank deposits and collections, and Article 4A for wholesale funds transfers; consumer electronic transfers sit outside Article 4A under the EFTA (§ 4A-108). An instrument is negotiable under § 3-104 only if it is an unconditional promise or order to pay a fixed amount of money, payable to bearer or to order, on demand or at a definite time, with no extra undertakings. A holder in due course (§ 3-302) takes for value, in good faith, and without notice, and under § 3-305 cuts off personal defenses, while the four real defenses — incapacity that nullifies, duress or illegality that voids, fraud in the factum, and discharge in insolvency — survive; § 3-203(b) adds the shelter rule. Loss from forged signatures shifts under §§ 3-404 to 3-406: impostor and employee-fraud rules make some forged endorsements effective against the drawer or employer, and negligence that substantially contributes to a forgery precludes the negligent party. Transfer and presentment warranties run through §§ 3-416 and 3-417. Article 4 is built on time: the midnight deadline and § 4-302 accountability, final payment under § 4-215, the properly-payable rule of § 4-401, wrongful dishonor under § 4-402, and the customer's statement-examination duty under § 4-406 (30-day repeat-wrongdoer preclusion, one-year outer limit). Regulation CC and the Check 21 Act overlay the check system, and Article 4A allocates wire fraud loss mainly through the commercially reasonable security procedure of §§ 4A-202 and 4A-203. *Personal study notes only; not legal advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

El derecho de pagos del UCC corre por tres vías: el Artículo 3 para los títulos negociables, el Artículo 4 para depósitos y cobro bancario, y el Artículo 4A para transferencias mayoristas de fondos; las transferencias electrónicas del consumidor quedan fuera del 4A y se rigen por la EFTA (§ 4A-108). Un título es negociable (§ 3-104) solo si es promesa u orden incondicional de pagar una suma fija de dinero, pagadera al portador o a la orden, a la vista o en fecha cierta, sin obligaciones adicionales. El tenedor de buena fe y a título oneroso (holder in due course, § 3-302) queda libre de las defensas personales según el § 3-305, pero subsisten las defensas reales: incapacidad que anula, coacción o ilegalidad que invalida, fraude en el hecho (fraud in the factum) y liberación en insolvencia; el § 3-203(b) añade la regla del refugio (shelter). La pérdida por firmas falsificadas se reparte en los §§ 3-404 a 3-406: las reglas del impostor y del empleado infiel hacen eficaces ciertos endosos falsos frente al librador o empleador, y la negligencia que contribuye sustancialmente a la falsificación excluye a la parte negligente. Las garantías de transferencia y presentación están en los §§ 3-416 y 3-417. El Artículo 4 es cuestión de plazos: el plazo de medianoche y la responsabilidad del § 4-302, el pago final del § 4-215, la regla de cargo legítimo del § 4-401, el rechazo indebido del § 4-402 y el deber del cliente de revisar estados de cuenta del § 4-406 (preclusión de 30 días para el mismo falsificador y límite externo de un año). La Regulation CC y la ley Check 21 se superponen al sistema de cheques, y el Artículo 4A reparte la pérdida por fraude en transferencias sobre todo mediante el procedimiento de seguridad comercialmente razonable de los §§ 4A-202 y 4A-203. *Notas personales de estudio; no constituye asesoría legal.*

## 한국어 (초역, 원어민 감수 대기)

UCC 지급법은 세 트랙으로 나뉩니다. 제3편은 유통증권, 제4편은 은행 예금·추심, 제4A편은 거액 자금이체를 다루고, 소비자 전자이체는 제4A편에서 제외되어 EFTA가 적용됩니다(§ 4A-108). 증권이 유통성을 갖추려면(§ 3-104) 무조건의 지급 약속·지시, 확정 금액, 지참인·지시인 지급, 요구불 또는 확정일 지급, 부수 의무 없음이 필요합니다. 정당한 소지인(§ 3-302)은 대가를 지급하고 선의이며 항변을 알지 못해 § 3-305에 따라 인적 항변을 차단하지만, 의무를 무효로 하는 무능력, 무효 사유가 되는 강박·위법, 서명 사실 자체에 대한 사기(fraud in the factum), 파산 면책의 네 가지 물적 항변은 남고, § 3-203(b)의 shelter 규칙도 중요합니다. 위조 서명의 손실은 §§ 3-404~3-406이 배분합니다. 사기꾼·가공 수취인, 직원의 사기 배서 규칙은 일부 위조 배서를 발행인·고용주에게 유효하게 하고, 위조에 실질적으로 기여한 과실은 과실 있는 당사자를 배제합니다. 양도·제시 담보는 §§ 3-416, 3-417에 있습니다. 제4편은 시간의 법입니다. 자정 기한과 § 4-302 책임, § 4-215 최종 지급, § 4-401 정당지급 원칙, § 4-402 부당 지급거절, § 4-406 고객의 계산서 검토 의무(동일 위조자 30일 배제, 1년 최종 기한)가 핵심입니다. Regulation CC와 Check 21 Act가 수표 시스템에 겹치고, 제4A편은 §§ 4A-202, 4A-203의 상업적으로 합리적인 보안 절차로 전신송금 사기 손실을 배분합니다. *개인 학습 노트이며 법률 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Luật thanh toán UCC chạy trên ba đường: Điều 3 cho công cụ chuyển nhượng, Điều 4 cho tiền gửi và thu hộ ngân hàng, Điều 4A cho chuyển tiền bán buôn; chuyển tiền điện tử của người tiêu dùng nằm ngoài Điều 4A và chịu EFTA (§ 4A-108). Một công cụ chỉ có tính chuyển nhượng theo § 3-104 khi là cam kết hoặc lệnh trả tiền vô điều kiện, số tiền cố định, trả cho người cầm phiếu hoặc theo lệnh, trả ngay khi xuất trình hoặc vào ngày xác định, và không kèm nghĩa vụ phụ. Người nắm giữ hợp lệ (holder in due course, § 3-302) nhận với đối giá, thiện chí, không biết về kháng biện, và theo § 3-305 cắt đứt các kháng biện cá nhân, nhưng bốn kháng biện thực chất vẫn tồn tại: mất năng lực làm vô hiệu nghĩa vụ, cưỡng bức hoặc bất hợp pháp làm vô hiệu, gian lận về chính việc ký (fraud in the factum), và giải nợ trong phá sản; § 3-203(b) thêm quy tắc shelter. Tổn thất do chữ ký giả được phân bổ tại §§ 3-404 đến 3-406: quy tắc kẻ mạo danh và nhân viên gian lận khiến một số lưng ký giả có hiệu lực đối với người ký phát hoặc chủ lao động, và lỗi bất cẩn góp phần đáng kể vào việc giả mạo sẽ loại trừ bên bất cẩn. Bảo đảm chuyển nhượng và xuất trình nằm ở §§ 3-416 và 3-417. Điều 4 là luật về thời gian: hạn nửa đêm và trách nhiệm § 4-302, thanh toán cuối cùng § 4-215, quy tắc chỉ được ghi nợ khoản "properly payable" § 4-401, từ chối trả sai § 4-402, và nghĩa vụ kiểm tra sao kê của khách hàng § 4-406 (loại trừ 30 ngày với cùng kẻ giả mạo, giới hạn ngoài cùng một năm). Regulation CC và đạo luật Check 21 phủ lên hệ thống séc, còn Điều 4A phân bổ tổn thất gian lận chuyển khoản chủ yếu qua thủ tục an ninh hợp lý về thương mại tại §§ 4A-202 và 4A-203. *Ghi chú học tập cá nhân, không phải tư vấn pháp lý.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

UCC भुगतान-विधि तीन पटलों पर चलती है: अनुच्छेद 3 परक्राम्य लिखतों (negotiable instruments) के लिए, अनुच्छेद 4 बैंक जमा व वसूली के लिए, और अनुच्छेद 4A थोक निधि-अंतरण के लिए; उपभोक्ता इलेक्ट्रॉनिक अंतरण अनुच्छेद 4A से बाहर हैं और EFTA के अधीन हैं (§ 4A-108). कोई लिखत § 3-104 के तहत तभी परक्राम्य है जब वह निश्चित धनराशि के भुगतान का बिना-शर्त वादा या आदेश हो, धारक को या आदेशानुसार देय हो, माँग पर या निश्चित तिथि पर देय हो, और उसमें अतिरिक्त दायित्व न हो. सद्भावी मूल्यवान धारक (holder in due course, § 3-302) § 3-305 के तहत व्यक्तिगत प्रतिरक्षाओं (personal defenses) को काट देता है, किंतु चार वास्तविक प्रतिरक्षाएँ बची रहती हैं — दायित्व को शून्य करने वाली अक्षमता, शून्य करने वाला दबाव या अवैधता, हस्ताक्षर-तथ्य पर ही धोखा (fraud in the factum), और दिवाला-मुक्ति; § 3-203(b) shelter नियम जोड़ता है. जाली हस्ताक्षरों की हानि §§ 3-404 से 3-406 बाँटते हैं: छद्मवेशी व कर्मचारी-धोखाधड़ी नियम कुछ जाली पृष्ठांकनों को जारीकर्ता या नियोक्ता के विरुद्ध प्रभावी बनाते हैं, और जालसाजी में सार्थक योगदान देने वाली लापरवाही लापरवाह पक्ष को वर्जित करती है. अंतरण व प्रस्तुति वारंटियाँ §§ 3-416 व 3-417 में हैं. अनुच्छेद 4 समय का कानून है: मध्यरात्रि समय-सीमा व § 4-302 उत्तरदायित्व, § 4-215 अंतिम भुगतान, § 4-401 का properly payable नियम, § 4-402 अनुचित अनादर, और § 4-406 में ग्राहक का विवरण-जाँच कर्तव्य (एक ही जालसाज़ के लिए 30 दिन की वर्जना, एक वर्ष की बाहरी सीमा). Regulation CC व Check 21 Act चेक-प्रणाली पर अध्यारोपित होते हैं, और अनुच्छेद 4A तार-अंतरण धोखाधड़ी की हानि मुख्यतः §§ 4A-202 व 4A-203 की वाणिज्यिक रूप से युक्तियुक्त सुरक्षा-प्रक्रिया से बाँटता है. *व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं।*
