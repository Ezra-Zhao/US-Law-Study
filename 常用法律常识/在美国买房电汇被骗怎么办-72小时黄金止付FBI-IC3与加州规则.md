# 在美国买房电汇被骗怎么办：72 小时黄金止付、FBI IC3 与加州规则

> 个人学习笔记，不构成法律建议。涉及大额资金被骗，请立即联系银行与当地警方，并咨询律师。

## 中文主文

### 一、先认清这种骗局长什么样

买房尾款电汇诈骗是商业电邮入侵（business email compromise, BEC）里最伤人的一类：骗子黑进或仿冒经纪人、托管公司（escrow）或产权公司的邮箱，在临近过户时发来一封「汇款指示变更」邮件，账号换成骗子的，语气、签名、房号全对得上。钱一旦按 Fedwire 电汇出去，几分钟内就被分层转走。FBI 的互联网犯罪投诉中心（IC3）历年报告都把 BEC 列为损失最高的网络犯罪类型之一，地产交易是重灾区。

识别点只有三条最硬：第一，真正的托管公司几乎不会在过户前临时用邮件变更收款账户；第二，骗子邮件域名常差一个字母；第三，对方会催你「今天必须汇出、不要打电话确认」。越催，越要停。

### 二、钱刚汇出：按小时算的止付动作

1. **立刻打银行电话**（用银行卡背面的号码，不用邮件里的号码）：说明是诈骗电汇，请求发起 recall（召回）并冻结后续转出；同时要求银行联系收款行请求冻结。电汇不像信用卡有拒付权，召回成不成全看钱还在不在对方账户，所以速度就是一切。
2. **立刻向 FBI IC3 报案**（ic3.gov）：IC3 的恢复资产团队（Recovery Asset Team）与银行之间有快速通道（Financial Fraud Kill Chain），实务口径是汇款后 72 小时内报案、且金额较大时，冻结成功率明显更高——72 小时是黄金线，不是保证线。
3. **报警留档**：向房屋所在地或居住地警局报案，拿到报告号；后面给保险、托管公司和银行补材料都要用。
4. **通知托管公司与经纪人**（用你独立保存的电话打）：让他们确认真实汇款指示、暂停过户时钟，并保全邮件头（email header）等证据——是谁的邮箱被黑，决定后面责任在谁。
5. **算例（时间线）**：周一 10:00 汇出，周一 10:20 发现异常。若当天完成银行召回加 IC3 报案，落在第 0 天；拖到周四 10:00 才报案，已满 72 小时，钱大概率已被转走多层。同一笔钱，差的是 71 小时 40 分钟的行动差。

### 三、钱追不回时，责任与救济往哪走

- **托管与经纪责任**：若能证明是托管公司或经纪方的邮箱被黑、或其未按行业标准核验，加州可主张其过失责任；托管业受《托管法》监管（Financial Code § 17000 起），持牌托管由 DFPI 监管、独立托管与律师托管各有主管。先发书面索赔函并保全证据，再谈诉讼。
- **产权保险不管这件事**：所有权险（owner's policy）保的是产权瑕疵，不保你主动汇错账户——这是最常见的误解。部分新式「wire fraud」附加险或经纪方的网络责任险（cyber liability）才可能覆盖，别默认有。
- **银行一侧**：UCC 第 4A 章管电汇，若银行执行了与你指示不符的指令、或收款行有明显红旗仍放行，才有争点；你本人按骗子指示汇款时，银行通常不担责，但召回与冻结配合义务要盯紧并留书面记录。
- **税务上**：个人住宅交易的被盗损失在 2018–2025 年间受 TCJA 限制，原则上不得按个人盗窃损失扣除（§ 165(h)(5)，联邦灾难宣告例外）；别听「可以抵税」的旧说法。

### 四、还没汇款的人：四条防骗铁律

1. 过户开始时就把托管公司的**官方电话**存进手机；任何汇款指示只认这个电话回拨核对的结果，绝不认邮件里给的号码。
2. 第一次汇款指示与之后任何「变更」，都要电话向已知联系人**口头复述账号后四位**核对。
3. 汇款前先小额验证不可行（电汇无小额试汇惯例），替代办法是要求托管公司通过加密门户发送指示，不走明文邮件附件。
4. 邮箱开双重验证；经纪人发来的链接不点，手动输官网地址。

### 五、加州特别提示

加州交易量大、托管制成熟，骗子的邮件往往直接仿冒本地托管公司。向 DFPI 投诉持牌托管、向加州房地产局（DRE）投诉经纪人，双线并行不冲突；若怀疑自家经纪邮箱被黑，要求其公司启动网络事件响应，这既是自保也是给其他客户止损。

*声明：个人学习笔记，不构成法律/税务建议。*

## English

**Wire fraud at closing — the 72-hour rule.** Closing-funds wire fraud is a business email compromise (BEC) variant: criminals spoof or hack the escrow, broker, or title mailbox and send last-minute "updated wiring instructions." Hard signals: a genuine escrow company almost never changes its receiving account by email before closing; look-alike domains differ by one letter; pressure to "send today, do not call" is itself a red flag.

**First hours.** (1) Call your bank at the number on your card — request a wire recall and ask it to alert the receiving bank to freeze funds; wires have no chargeback right, so recovery depends on the money still being there. (2) File at ic3.gov immediately: the FBI IC3 Recovery Asset Team runs the Financial Fraud Kill Chain with banks, and reports within 72 hours of the transfer have materially better freeze odds — a golden window, not a guarantee. (3) File a local police report for the report number. (4) Call escrow and your agent on independently saved numbers to pause closing and preserve email headers. Timeline math: sent Monday 10:00, spotted 10:20, recall plus IC3 the same day is hour zero; waiting until Thursday 10:00 burns the full 72 hours.

**If the money is gone.** Liability may fall on an escrow or brokerage whose mailbox was breached (California escrow is regulated under Financial Code § 17000 et seq.); a title owner's policy does **not** cover money you wired to the wrong account; UCC Article 4A governs wire disputes; and personal theft-loss deductions are generally suspended for 2018–2025 under § 165(h)(5). Prevention: save escrow's real phone number at the start, verbally confirm the last four digits of any account by calling that number, take instructions only through an encrypted portal, and use MFA on email. *Study notes only, not legal advice.*

## Español

**Fraude con la transferencia del cierre: la regla de las 72 horas.** Es una variante del compromiso de correo empresarial (BEC): suplantan el correo de la compañía de depósito (escrow), del agente o de títulos y envían "instrucciones actualizadas" a último momento. Señales duras: una empresa de escrow seria casi nunca cambia su cuenta por correo antes del cierre; los dominios falsos difieren en una letra; la prisa ("envíe hoy, no llame") es en sí una alerta.

**Primeras horas.** (1) Llame a su banco al número de su tarjeta: pida la revocación (recall) de la transferencia y que avise al banco receptor para congelar los fondos; no existe contracargo en transferencias wire. (2) Denuncie de inmediato en ic3.gov: el equipo Recovery Asset Team del FBI IC3 coordina con los bancos (Financial Fraud Kill Chain) y las denuncias dentro de las 72 horas tienen mejores probabilidades de congelamiento — ventana dorada, no garantía. (3) Denuncie ante la policía local. (4) Llame a escrow y a su agente a números guardados por separado para pausar el cierre y preservar los encabezados del correo. Cálculo: enviado el lunes 10:00 y detectado 10:20, actuar el mismo día es la hora cero; esperar al jueves 10:00 consume las 72 horas.

**Si el dinero se perdió.** Puede haber responsabilidad de escrow o del agente si su correo fue vulnerado (en California, la Ley de Escrow, Financial Code § 17000 y ss.); la póliza de título **no** cubre dinero transferido a la cuenta equivocada; el Artículo 4A del UCC rige las disputas; la deducción por robo personal está suspendida en general entre 2018 y 2025, § 165(h)(5). Prevención: guarde el teléfono real de escrow desde el inicio, confirme verbalmente los últimos cuatro dígitos llamando a ese número, acepte instrucciones solo por portal cifrado y use doble factor en el correo. *Notas de estudio, no asesoría legal.*

## 한국어 (초역, 원어민 감수 대기)

**마감 자금 송금 사기 — 72시간 규칙.** 에스크로·브로커·타이틀 회사의 메일함을 위조하거나 해킹해 막판에 "변경된 송금 지시"를 보내는 기업 이메일 침해(BEC) 수법입니다. 진짜 에스크로 회사는 마감 전에 이메일로 수취 계정을 바꾸는 일이 거의 없고, 가짜 도메인은 한 글자만 다르며, "오늘 보내고 전화하지 말라"는 재촉 자체가 위험 신호입니다.

**첫 몇 시간.** (1) 카드 뒷면 번호로 은행에 전화해 송금 회수(recall)와 수취 은행의 동결 요청을 하세요. 전신송금에는 차지백이 없습니다. (2) ic3.gov에 즉시 신고하세요. FBI IC3의 Recovery Asset Team이 은행들과 Financial Fraud Kill Chain으로 공조하며, 송금 후 72시간 이내 신고가 동결 가능성을 크게 높입니다(황금 시간대일 뿐 보장은 아님). (3) 지역 경찰에 신고해 접수 번호를 받으세요. (4) 별도로 저장한 번호로 에스크로와 에이전트에게 전화해 마감을 멈추고 이메일 헤더를 보전하세요. 월요일 10:00 송금, 10:20 발견 시 당일 조치는 0시간째, 목요일 10:00까지 미루면 72시간이 소진됩니다.

**돈을 잃은 뒤.** 메일함이 뚫린 에스크로나 브로커의 과실 책임이 문제될 수 있고(캘리포니아 에스크로는 Financial Code § 17000 이하로 규제), 소유권 보험은 잘못 보낸 송금을 보장하지 않으며, 전신송금 분쟁은 UCC 제4A편, 개인 도난 손실 공제는 2018–2025년 § 165(h)(5)로 원칙적으로 중단됩니다. 예방: 처음부터 에스크로의 실제 전화번호를 저장하고, 그 번호로 전화해 계좌 끝 네 자리를 구두로 확인하며, 지시는 암호화 포털로만 받고, 이메일에 이중 인증을 켜세요. *학습 노트이며 법률 자문이 아닙니다.*

보험 쪽의 경계도 분명히 해 둘 필요가 있습니다. 소유자 권리보험(owner's policy)이 보장하지 않는다고 해서 모든 보험이 닫힌 것은 아니고, 일부 신형 송금사기 특약(wire fraud endorsement)이나 브로커 측의 사이버 책임보험(cyber liability)이 보장할 수 있는 경우가 있어, 담보 여부를 전제하지 말고 약관을 확인해야 합니다. 은행 쪽에서는 UCC 제4A편상 은행이 고객의 지시와 다르게 집행했거나 수취 은행이 명백한 위험 신호를 무시한 경우에만 다툼이 생기고, 본인이 사기꾼의 지시에 따라 송금한 경우에는 은행이 원칙적으로 책임지지 않습니다. 다만 회수와 동결에 대한 협조는 서면 기록을 남기며 계속 요구해야 합니다.

캘리포니아에서는 신고를 두 갈래로 병행할 수 있습니다. 면허 있는 에스크로에 대해서는 금융보호혁신부(DFPI)에, 브로커에 대해서는 부동산국(DRE)에 각각 민원을 넣는 것으로, 두 트랙은 서로 충돌하지 않습니다. 자기 브로커의 메일함이 해킹당한 것으로 의심되면 그 회사에 사이버 사건 대응(cyber incident response) 개시를 요구하십시오. 이는 본인을 지키는 일인 동시에 다른 고객들의 피해를 막는 일이기도 합니다.

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

**Lừa đảo chuyển khoản tiền cọc/mua nhà — quy tắc 72 giờ.** Đây là biến thể xâm phạm email doanh nghiệp (BEC): kẻ gian giả mạo hoặc chiếm hộp thư của công ty ký quỹ (escrow), môi giới hay công ty title rồi gửi "chỉ dẫn chuyển tiền mới" vào phút chót. Dấu hiệu cứng: công ty escrow thật hầu như không bao giờ đổi tài khoản nhận qua email trước ngày closing; tên miền giả chỉ khác một ký tự; càng giục "gửi ngay hôm nay, đừng gọi điện" càng đáng ngờ.

**Những giờ đầu.** (1) Gọi ngân hàng theo số trên thẻ: yêu cầu thu hồi lệnh chuyển (recall) và nhờ thông báo ngân hàng nhận đóng băng tiền; chuyển khoản wire không có chargeback. (2) Báo ngay tại ic3.gov: đội Recovery Asset Team của FBI IC3 phối hợp với ngân hàng qua Financial Fraud Kill Chain, và báo trong vòng 72 giờ sau khi chuyển giúp tăng rõ rệt cơ hội đóng băng — là cửa sổ vàng, không phải bảo đảm. (3) Trình báo cảnh sát địa phương để lấy số hồ sơ. (4) Gọi escrow và môi giới bằng số đã lưu riêng để tạm dừng closing và lưu giữ header email. Ví dụ: gửi thứ Hai 10:00, phát hiện 10:20, xử lý cùng ngày là giờ 0; chờ đến thứ Năm 10:00 là đã hết 72 giờ.

**Nếu mất tiền.** Trách nhiệm có thể thuộc về escrow/môi giới nếu hộp thư của họ bị xâm nhập (escrow tại California chịu sự điều chỉnh của Financial Code § 17000 trở đi); bảo hiểm title **không** bồi thường tiền bạn tự chuyển nhầm tài khoản; tranh chấp wire theo Điều 4A UCC; khấu trừ thiệt hại do trộm cắp cá nhân nhìn chung bị đình chỉ 2018–2025 theo § 165(h)(5). Phòng tránh: lưu số điện thoại thật của escrow ngay từ đầu, gọi số đó để xác nhận bằng lời bốn số cuối tài khoản, chỉ nhận chỉ dẫn qua cổng mã hóa, bật xác thực hai lớp cho email. *Ghi chú học tập, không phải tư vấn pháp lý.*

Ranh giới bảo hiểm cũng cần nói rõ: việc bảo hiểm quyền sở hữu của chủ nhà (owner's policy) không bồi thường không có nghĩa là mọi bảo hiểm đều đóng — một số điều khoản bổ sung mới về lừa đảo chuyển khoản (wire fraud endorsement) hoặc bảo hiểm trách nhiệm mạng (cyber liability) của bên môi giới có thể bồi thường, nên phải kiểm tra hợp đồng thay vì mặc định là không có. Phía ngân hàng, theo Điều 4A UCC, tranh chấp chỉ nảy sinh khi ngân hàng thực hiện lệnh khác với chỉ dẫn của khách hàng hoặc ngân hàng nhận phớt lờ dấu hiệu nguy hiểm rõ ràng; còn khi chính bạn chuyển tiền theo chỉ dẫn của kẻ lừa đảo, ngân hàng về nguyên tắc không chịu trách nhiệm — tuy nhiên vẫn phải tiếp tục yêu cầu phối hợp thu hồi và đóng băng, và lưu lại bằng văn bản.

Tại California, khiếu nại có thể đi hai đường song song mà không xung đột: khiếu nại công ty escrow có giấy phép lên DFPI (Department of Financial Protection and Innovation), và khiếu nại môi giới lên DRE (Department of Real Estate). Nếu nghi ngờ hộp thư của chính môi giới của bạn bị xâm nhập, hãy yêu cầu công ty của họ khởi động ứng phó sự cố mạng (cyber incident response) — việc này vừa bảo vệ bạn, vừa ngăn thiệt hại cho các khách hàng khác.

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

**क्लोज़िंग वायर धोखाधड़ी — 72 घंटे का नियम।** यह बिज़नेस ईमेल समझौते (BEC) का रूप है: अपराधी एस्क्रो, ब्रोकर या टाइटल कंपनी के मेलबॉक्स की नकल या हैक करके अंतिम समय पर "बदले हुए वायर निर्देश" भेजते हैं। पक्के संकेत: असली एस्क्रो कंपनी क्लोज़िंग से पहले ईमेल से प्राप्तकर्ता खाता लगभग कभी नहीं बदलती; नकली डोमेन में एक अक्षर का अंतर होता है; "आज ही भेजो, फोन मत करो" वाली जल्दबाज़ी खुद चेतावनी है।

**पहले घंटे।** (1) कार्ड पर दिए नंबर से बैंक को फोन करें — वायर रिकॉल का अनुरोध करें और प्राप्तकर्ता बैंक से धन फ्रीज़ करने को कहें; वायर में चार्जबैक नहीं होता। (2) तुरंत ic3.gov पर शिकायत करें: FBI IC3 की Recovery Asset Team बैंकों के साथ Financial Fraud Kill Chain चलाती है, और ट्रांसफर के 72 घंटे के भीतर की शिकायतों में फ्रीज़ की संभावना स्पष्ट रूप से अधिक रहती है — यह स्वर्णिम खिड़की है, गारंटी नहीं। (3) स्थानीय पुलिस में रिपोर्ट दर्ज करें। (4) अलग से सहेजे नंबरों से एस्क्रो और एजेंट को फोन कर क्लोज़िंग रोकें और ईमेल हेडर सुरक्षित रखें। गणना: सोमवार 10:00 भेजा, 10:20 पता चला — उसी दिन कार्रवाई घंटा शून्य है; गुरुवार 10:00 तक प्रतीक्षा में पूरे 72 घंटे खत्म।

**धन चला गया तो।** यदि एस्क्रो या ब्रोकरेज का मेलबॉक्स भेदा गया हो तो उसकी लापरवाही का प्रश्न उठ सकता है (कैलिफोर्निया एस्क्रो Financial Code § 17000 और आगे से विनियमित); टाइटल ओनर पॉलिसी गलत खाते में भेजे धन को कवर **नहीं** करती; वायर विवाद UCC Article 4A से चलते हैं; व्यक्तिगत चोरी-हानि कटौती 2018–2025 के लिए § 165(h)(5) से सामान्यतः निलंबित है। रोकथाम: शुरू से एस्क्रो का असली फोन नंबर सहेजें, उसी नंबर पर फोन कर खाते के अंतिम चार अंक मौखिक रूप से सत्यापित करें, निर्देश केवल एन्क्रिप्टेड पोर्टल से लें, ईमेल पर MFA लगाएँ। *केवल अध्ययन नोट, कानूनी सलाह नहीं।*

बीमा की सीमा भी स्पष्ट करनी चाहिए: title owner's policy का कवर न करना यह नहीं कहता कि हर बीमा बंद है — कुछ नई wire fraud endorsement या ब्रोकर की cyber liability policy कवर कर सकती है, इसलिए मानकर न चलें, policy की शर्तें जाँचें। बैंक पक्ष में, UCC Article 4A के तहत विवाद तभी बनता है जब बैंक ने ग्राहक के निर्देश से अलग निष्पादन किया हो या प्राप्तकर्ता बैंक ने स्पष्ट red flag अनदेखा किया हो; जब आप स्वयं ठग के निर्देश पर धन भेजते हैं तो बैंक सामान्यतः उत्तरदायी नहीं होता — फिर भी recall और freeze में सहयोग की माँग लिखित अभिलेख के साथ जारी रखनी चाहिए।

California में शिकायत दो समानांतर मार्गों से हो सकती है और दोनों में टकराव नहीं है: लाइसेंसी escrow के विरुद्ध DFPI (Department of Financial Protection and Innovation) को और ब्रोकर के विरुद्ध DRE (Department of Real Estate) को। यदि संदेह हो कि आपके अपने ब्रोकर का मेलबॉक्स हैक हुआ है, तो उसकी firm से cyber incident response शुरू करने की माँग करें — यह आपकी अपनी सुरक्षा भी है और अन्य ग्राहकों की हानि रोकना भी।
