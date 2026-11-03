# 美国国家安全法地图：FISA 与 IEEPA 及 CFIUS 与出口管制

> 个人学习笔记，不构成法律建议。国家安全法是美国法律里联邦主导最彻底、程序最不公开的一块。本文按「监控—制裁—投资审查—出口管制—刑事兜底」五条线画地图，条文细节与授权期限以现行官方文本为准。

## 中文主文

### 一、总览：五条线，一个共同点

美国没有一部统一的「国家安全法典」，而是几部各管一段的法律拼起来：

| 线 | 主法 | 管什么 | 主管 |
| --- | --- | --- | --- |
| 对外情报监控 | FISA，50 U.S.C. § 1801 起 | 针对外国势力与代理人的电子监控与实物搜查 | 司法部、情报界，FISC 审查 |
| 经济制裁与紧急经济权 | IEEPA，50 U.S.C. § 1701 起 | 总统宣布国家紧急状态后冻结资产、禁止交易 | 财政部 OFAC 执行 |
| 外资投资审查 | 50 U.S.C. § 4565（FIRRMA 后） | 外资收购美国企业的安全审查 | CFIUS，财政部牵头 |
| 出口管制 | EAR（商务部）/ ITAR（国务院） | 两用品与军品的出口、再出口与技术转移 | BIS / DDTC |
| 刑事兜底 | 间谍法 18 U.S.C. § 793 一带等 | 窃取、泄露国防信息与为外国窃取商业秘密 | 司法部起诉 |

共同点：权力几乎全在联邦行政分支，法院审查多为事后或秘密进行，国会靠授权期限与报告要求拴住行政权——看每一部法时，先找它的「日落与报告」条款。

### 二、FISA：对外情报监控的法定通道

《外国情报监控法》（Foreign Intelligence Surveillance Act, FISA）编在 50 U.S.C. § 1801 起：

- **基本定义在 § 1801**：「外国势力（foreign power）」与「外国势力的代理人（agent of a foreign power）」是全法钥匙概念；对美国人（公民与合法永久居民）的「代理人」认定门槛明显更高，这是后面所有程序分层的根；
- **传统个案令（Title I）**：政府向外国情报监控法院（FISC）申请命令，须证明目标是外国势力或其代理人、监控是为获取对外情报，依 § 1805 核发；FISC 依 § 1803 设立，由首席大法官从各巡回区指派地区法官轮流组成，程序不公开、对方不到场；
- **第 702 条（50 U.S.C. § 1881a）**：由 2008 年《FISA 修正法》加入，允许在司法部长与国家情报总监年度认证、FISC 审查定向与最小化程序的前提下，批量获取「有合理理由相信位于美国境外」的非美国人的通信，不必逐人取得个案令；美国人的通信被「附带收集」是历次再授权辩论的焦点。第 702 条带日落条款、经多次再授权，当前期限与 2024 年改革法（RISAA）附加的改革要求以现行条文为准；
- 图上定位：FISA 管的是「政府为情报目的的监控授权」，与普通刑事搜查令（第四修正案、Title III 窃听）是两套系统；企业实务中接到 FISA 令或国家安全函件时，保密义务与挑战路径都与普通传票不同，不要按普通法务流程处理。

### 三、IEEPA：总统的紧急经济武器

《国际紧急经济权力法》（International Emergency Economic Powers Act, IEEPA）编在 50 U.S.C. § 1701 起：

- **启动条件（§ 1701）**：总统宣布存在源自美国境外、针对国家安全、外交或经济的「异常而非同寻常的威胁」，并依《国家紧急状态法》宣布国家紧急状态；
- **核心权力（§ 1702）**：紧急状态下，总统可调查、阻止、禁止涉及外国或外国国民利益的财产交易，包括冻结（blocking）资产、外汇与支付限制等；但 § 1702(b) 明列除外：个人通信、捐赠、信息与信息材料、旅行相关交易等不在授权之列，这一条是历次诉讼攻防的高频条文；
- **执行机关是财政部外国资产控制办公室（OFAC）**：各制裁项目（按国家、按主题）以行政法规形式落在 31 C.F.R. 各章，SDN 清单是实务中最常查的一份名单；与「名单上的人交易」本身即可招致民事严格责任式的处罚，合规筛查因此是硬动作；
- **边界**：IEEPA 授权极宽但并非无边——其能否支持加征关税等用途近年在联邦法院引发重大诉讼，相关判例仍在发展，具体用途的合法性以现行判例为准，不可把「紧急权力」理解成万能条款。

### 四、CFIUS 与 FIRRMA：外资买美国企业的安全门

- **制度沿革**：审查权源自 1950 年《国防生产法》第 721 条，经 1988 年 Exon-Florio 修正与 2007 年 FINSA 成形，2018 年《外国投资风险审查现代化法》（FIRRMA）大幅扩围，现编在 50 U.S.C. § 4565；
- **CFIUS**（美国外国投资委员会）是跨部门委员会，财政部长任主席，成员包括司法、国防、国土安全、商务、国务院等；审查对象是可能导致外国人控制美国企业的交易（covered transactions）；
- **FIRRMA 的扩围两点最要紧**：一是不取得控制权的「关键技术、关键基础设施、敏感个人数据」（即 TID）企业非控制性投资也被纳入；二是在军事设施等敏感地点附近的房地产交易另有覆盖（法规在 31 C.F.R. 第 800、802 章）；
- **程序**：多数交易自愿申报，特定关键技术交易有强制申报；结果可以是无条件放行、附缓解协议放行，或建议总统阻止/撤销——总统否决权在 § 4565(d) 一带，历史上被正式动用的次数很少，但「主动撤回并放弃交易」在审查压力下并不少见；
- 实务定位：CFIUS 审查的是「国家安全风险」而非产业政策，但它与出口管制共用「关键技术」的定义语言，做交易尽调时两条线要一起看。

### 五、出口管制双轨：EAR 管两用，ITAR 管军品

- **EAR（出口管理条例）**：由商务部工业与安全局（BIS）执行，法规在 15 C.F.R. 第 730–774 章，现行成文法授权是 2018 年《出口管制改革法》（ECRA，50 U.S.C. § 4801 起）——在此之前 EAR 长期靠 IEEPA 紧急状态续命，这也是 IEEPA 在贸易线如此重要的历史原因。EAR 管军民两用品与较不敏感军品：核心工具是商务管制清单（CCL）与 ECCN 编号、「实体清单（Entity List）」、以及按目的地与最终用户分级的许可证要求；「视同出口（deemed export）」——在美国境内向外国国民释放受控技术也算出口——是雇主与高校最容易漏的一条；
- **ITAR（国际武器贸易条例）**：由国务院国防贸易管制局（DDTC）执行，法规在 22 C.F.R. 第 120–130 章，授权是《武器出口管制法》22 U.S.C. § 2778；管美国军品清单（USML）上的防务物品与防务服务，门槛比 EAR 严：原则上都要许可证、经纪与制造协议另有登记要求；
- **分界线**：一件物项先查 USML、在不在决定走 ITAR 还是 EAR；「600 系列」等改革把部分较不敏感军品从 USML 移到 CCL，分类判断（jurisdiction determination）做错，后面许可证全错；
- 制裁与出口管制不要混：IEEPA/OFAC 管「跟谁交易」，EAR/ITAR 管「什么东西、技术能给谁」，一笔对俄或对华的交易可能同时撞上三套规则。

### 六、刑事兜底：间谍法与相关罪名

- **18 U.S.C. § 793** 是《间谍法》（1917 年）的核心条文之一：搜集、记录、传递或企图传递国防信息（national defense information），意图或有理由相信其将被用于损害美国或使外国获益的，构成犯罪；§ 794 管把国防信息交给外国政府，§ 798 管通信情报的专门披露；
- 注意 § 793 的用词是「国防信息」而非仅限「机密文件」：是否有密级是重要事实，但条文结构并不以密级标记为唯一要件，办案与辩护的争点常在信息的「国防相关性」与被告的主观状态；
- 周边罪名：§ 1924（未经授权移除、留存机密材料）、《经济间谍法》18 U.S.C. § 1831（为外国政府窃取商业秘密）与 § 1832（一般商业秘密窃取）、以及代理人未登记的 18 U.S.C. § 951 与《外国代理人登记法》（FARA，22 U.S.C. § 611 起）——这一组拼起来，才是国安刑事执法的完整工具箱。

### 七、加州的边界：州层只有边角，没有主战场

- **能核实的总原则**：对外监控、制裁、外资审查、出口管制与间谍罪全部是联邦事项，加州没有自己的 FISC、没有州级制裁名单、也不能另设外资安全审查与联邦并行；州法在这块的直接立法空间受联邦优先适用（preemption）与对外事务专属性的双重挤压；
- **州层真实存在的边角**有三类：一是州与地方机构的自身合规（州采购、州雇员接触受控技术时的雇主合规，与普通企业同一套联邦规则）；二是应急与治安协作（加州州长办公室下设的应急服务与情报融合机制配合联邦工作，属行政协作而非独立授权）；三是州法管「人」的一般罪名（跟踪、盗窃、非法侵入计算机等）在国安案件中偶尔作为州层指控出现，但定性仍是普通犯罪，不是州版国家安全法；
- 因此凡是「加州对某国产品的禁令」「加州自己的实体清单」一类说法，先要求出处：多半是联邦规则在州采购环节的落地，而不是加州自创的国安立法。

*声明：个人学习笔记，不构成法律建议。来源：50 U.S.C. §§ 1801、1803、1805、1881a（FISA 与第 702 条）；50 U.S.C. §§ 1701、1702（IEEPA）；50 U.S.C. § 4565（CFIUS/FIRRMA）与 31 C.F.R. Parts 800、802；50 U.S.C. § 4801 起（ECRA）与 15 C.F.R. Parts 730–774（EAR）；22 U.S.C. § 2778 与 22 C.F.R. Parts 120–130（ITAR）；18 U.S.C. §§ 793、794、798、951、1831、1924。授权期限与制裁项目以现行条文与 OFAC 现行法规为准。*

---

## English

U.S. national security law is not one code but five federal machines. (1) Surveillance: FISA, 50 U.S.C. § 1801 et seq., defines "foreign power" and "agent of a foreign power" in § 1801; traditional orders issue from the secretive Foreign Intelligence Surveillance Court (established by § 1803; orders under § 1805), while Section 702, 50 U.S.C. § 1881a, added in 2008, authorizes programmatic acquisition targeting non-U.S. persons reasonably believed to be abroad, under annual certifications and FISC review of targeting and minimization procedures — incidental collection of Americans' communications drives every reauthorization fight, and its current sunset and post-RISAA terms should be checked against the current text. (2) Sanctions: IEEPA, 50 U.S.C. § 1701 et seq., lets the President, after declaring a national emergency over an unusual and extraordinary foreign threat, block assets and prohibit transactions (§ 1702), subject to carve-outs in § 1702(b) for personal communications, donations, information and travel; OFAC at Treasury runs the programs and the SDN List, and recent litigation over uses such as tariffs shows the power is broad but not unlimited. (3) Investment screening: CFIUS, chaired by Treasury under 50 U.S.C. § 4565 as expanded by FIRRMA (2018), reviews covered transactions for control and — new under FIRRMA — certain non-controlling investments in critical technology, critical infrastructure and sensitive personal data (TID) businesses, plus sensitive real estate (31 C.F.R. Parts 800, 802). (4) Export controls run on two tracks: the EAR (Commerce/BIS, 15 C.F.R. Parts 730–774, now under ECRA, 50 U.S.C. § 4801 et seq.) for dual-use items, with ECCNs, the Entity List and deemed-export rules; and ITAR (State/DDTC, 22 C.F.R. Parts 120–130, under 22 U.S.C. § 2778) for USML defense articles and services. (5) The criminal backstop centers on the Espionage Act, notably 18 U.S.C. § 793 (gathering or transmitting national defense information), with §§ 794, 798, 951, 1831 and 1924 around it. California has no parallel system: these fields are federal, and the state's role is limited to its own compliance, emergency-management cooperation and ordinary state crimes. *Personal study notes only; not legal advice.*

## Español (traducción de estudio, pendiente de revisión nativa)

El derecho de seguridad nacional de EE. UU. no es un código único sino cinco máquinas federales. (1) Vigilancia: la FISA (50 U.S.C. § 1801 y ss.) define «potencia extranjera» y «agente» en el § 1801; las órdenes clásicas las emite el tribunal secreto FISC (§ 1803; órdenes según el § 1805), y la Sección 702 (§ 1881a, de 2008) autoriza adquisiciones programáticas dirigidas a no estadounidenses razonablemente ubicados en el extranjero, con certificación anual y revisión del FISC; su vigencia actual debe verificarse en el texto vigente. (2) Sanciones: la IEEPA (50 U.S.C. § 1701 y ss.) permite al Presidente, declarada una emergencia nacional por una amenaza extranjera inusual y extraordinaria, bloquear activos y prohibir transacciones (§ 1702), con exclusiones en el § 1702(b); la OFAC ejecuta los programas y la lista SDN, y los litigios recientes muestran que el poder es amplio pero no ilimitado. (3) Inversión: el CFIUS, presidido por el Tesoro conforme al 50 U.S.C. § 4565 ampliado por FIRRMA (2018), revisa el control extranjero y ciertas inversiones no controlantes en tecnología crítica, infraestructura crítica y datos personales sensibles (31 C.F.R. partes 800 y 802). (4) Exportaciones: las EAR (Comercio/BIS, 15 C.F.R. partes 730–774, hoy bajo la ECRA, 50 U.S.C. § 4801 y ss.) para bienes de doble uso, y las ITAR (Estado/DDTC, 22 C.F.R. partes 120–130, bajo 22 U.S.C. § 2778) para artículos de defensa de la USML. (5) El respaldo penal es la Ley de Espionaje, en especial el 18 U.S.C. § 793, junto a los §§ 794, 798, 951, 1831 y 1924. California no tiene un sistema paralelo: son materias federales. *Notas personales de estudio; no constituye asesoría legal.*

## 한국어 (초역, 원어민 감수 대기)

미국의 국가안보법은 하나의 법전이 아니라 다섯 개의 연방 제도입니다. (1) 감시: FISA(50 U.S.C. § 1801 이하)는 § 1801에서 «외국 세력»과 «그 대리인»을 정의하고, 전통적 명령은 비밀 법원인 FISC(§ 1803 설치, § 1805 명령)가 발부합니다. 2008년에 도입된 제702조(§ 1881a)는 해외에 있다고 합리적으로 믿어지는 비미국인을 대상으로 한 프로그램식 수집을 연례 인증과 FISC의 절차 심사 아래 허용합니다. 현재의 일몰 기한은 현행 조문으로 확인해야 합니다. (2) 제재: IEEPA(50 U.S.C. § 1701 이하)는 대통령이 비정상적이고 비상한 해외 위협에 대해 국가비상사태를 선언하면 § 1702에 따라 자산을 동결하고 거래를 금지할 수 있게 하며, § 1702(b)에 개인 통신·기부·정보·여행 등의 제외가 있습니다. 집행은 재무부 OFAC와 SDN 명단이 담당하고, 최근 소송들은 이 권한이 넓지만 무한하지 않음을 보여줍니다. (3) 투자 심사: FIRRMA(2018)로 확장된 50 U.S.C. § 4565에 따라 재무부가 의장인 CFIUS가 외국인 지배 거래와 핵심 기술·핵심 인프라·민감한 개인 데이터(TID) 기업에 대한 일부 비지배 지분 투자를 심사합니다(31 C.F.R. Part 800, 802). (4) 수출 통제: 이중용도는 EAR(상무부 BIS, 15 C.F.R. Part 730–774, 현재 근거법은 ECRA, 50 U.S.C. § 4801 이하), 군수품은 ITAR(국무부 DDTC, 22 C.F.R. Part 120–130, 근거 22 U.S.C. § 2778)가 담당합니다. (5) 형사적 뒷받침은 간첩법, 특히 18 U.S.C. § 793(국방 정보의 수집·전달)이며 §§ 794, 798, 951, 1831, 1924가 함께합니다. 캘리포니아에는 병행 제도가 없습니다. 이 분야는 연방 전속입니다. 

보충 세부사항(중국어 본문과 정렬): FISC는 § 1803에 따라 설치되며, 대법원장이 각 순회구에서 지명한 지방법원 판사들로 구성되고 절차는 비공개·일방(ex parte)으로 진행됩니다. 미국인(시민과 합법 영주권자)에 대해서는 «대리인» 인정의 문턱이 해외 대상자보다 분명히 높고, 이것이 절차 층위의 출발점입니다. FISA는 정보 목적의 감시 허가 제도이며, 일반 형사 수색영장이나 Title III 도청과는 별개 체계입니다. 기업이 FISA 명령이나 국가안보 서한을 받으면 비밀유지 의무와 이의 경로가 일반 소환장과 달라 일반 법무 절차로 처리해서는 안 됩니다. § 1702(b)의 제외 항목에는 개인 통신, 인도적 기부, 정보·정보자료, 여행 관련 거래가 열거돼 있고 소송의 쟁점이 자주 됩니다. OFAC 제재에서는 SDN 명단에 오른 상대와의 거래 자체가 민사상 엄격책임에 가까운 처벌을 부를 수 있어, 거래 전 명단 대조(screening)는 선택이 아니라 필수 절차입니다. CFIUS 절차는 대개 자발적 신고이나 특정 핵심 기술 거래에는 강제 신고가 있고, 대통령의 거래 금지 권한(§ 4565(d) 부근)은 공식적으로 발동된 횟수가 적지만 심사 압박 속에서 거래를 스스로 철회·포기하는 사례는 적지 않습니다. 수출 통제의 실무 함정은 «의제 수출(deemed export)» — 미국 안에서 외국 국적자에게 통제 기술을 공개하는 것도 수출로 본다는 점 — 과, 물품이 USML에 있는지부터 가르는 관할 판정(jurisdiction determination)이며, 600 시리즈 같은 개혁으로 비교적 덜 민감한 군용품 일부가 USML에서 CCL로 옮겨졌습니다. § 793의 핵심 용어는 «기밀 문서»가 아니라 «국방 정보(national defense information)»입니다. 비밀 등급 표시가 중요한 사실이긴 해도 조문의 유일한 요건은 아니며, 쟁점은 정보의 국방 관련성과 피고인의 주관적 상태에 모입니다. 주변 조문으로는 § 1924(기밀 자료의 무단 반출·보관), 경제간첩법 § 1831(외국 정부를 위한 영업비밀 절취)과 § 1832(일반 영업비밀 절취), 미등록 외국 대리인에 관한 § 951과 FARA(22 U.S.C. § 611 이하)가 있습니다. 캘리포니아의 접점은 세 가지뿐입니다. 주·지방 기관 자체의 연방 규칙 준수, 주지사실 산하 비상·정보 융합 기구의 연방 협력(행정 협력이지 독립 권한이 아님), 그리고 스토킹·절도·컴퓨터 무단침입 같은 일반 주 범죄가 국가안보 사건에서 부수적으로 등장하는 경우입니다.

*개인 학습 노트이며 법률 자문이 아닙니다.*

## Tiếng Việt (bản dịch sơ bộ, chờ hiệu đính)

Luật an ninh quốc gia Hoa Kỳ không phải một bộ luật duy nhất mà là năm cỗ máy liên bang. (1) Giám sát: FISA (50 U.S.C. § 1801 trở đi) định nghĩa «thế lực nước ngoài» và «điệp viên» tại § 1801; lệnh truyền thống do tòa bí mật FISC ban hành (§ 1803 thành lập, § 1805 về lệnh), và Mục 702 (§ 1881a, năm 2008) cho phép thu thập theo chương trình nhắm vào người không phải công dân Mỹ được cho là đang ở nước ngoài, với chứng nhận hằng năm và FISC xét duyệt thủ tục; thời hạn hiệu lực hiện tại cần đối chiếu văn bản hiện hành. (2) Trừng phạt: IEEPA (50 U.S.C. § 1701 trở đi) cho phép Tổng thống, sau khi tuyên bố tình trạng khẩn cấp quốc gia về mối đe dọa bất thường từ nước ngoài, phong tỏa tài sản và cấm giao dịch theo § 1702, với các ngoại lệ tại § 1702(b); OFAC thuộc Bộ Tài chính thực thi qua các chương trình và danh sách SDN, và kiện tụng gần đây cho thấy quyền này rộng nhưng không vô hạn. (3) Thẩm tra đầu tư: CFIUS do Bộ Tài chính chủ trì theo 50 U.S.C. § 4565, được FIRRMA (2018) mở rộng, xét các giao dịch tạo quyền kiểm soát và một số khoản đầu tư không kiểm soát vào công nghệ then chốt, hạ tầng then chốt và dữ liệu cá nhân nhạy cảm (31 C.F.R. Phần 800, 802). (4) Kiểm soát xuất khẩu: EAR (Bộ Thương mại/BIS, 15 C.F.R. Phần 730–774, nay dựa trên ECRA, 50 U.S.C. § 4801 trở đi) cho hàng lưỡng dụng; ITAR (Bộ Ngoại giao/DDTC, 22 C.F.R. Phần 120–130, theo 22 U.S.C. § 2778) cho vật phẩm quốc phòng USML. (5) Lưới hình sự là Đạo luật Gián điệp, nổi bật là 18 U.S.C. § 793, cùng các §§ 794, 798, 951, 1831, 1924. California không có hệ thống song song: đây là lĩnh vực liên bang. 

Chi tiết bổ sung (căn chỉnh với bản tiếng Trung): FISC được thành lập theo § 1803, gồm các thẩm phán tòa quận do Chánh án Tòa Tối cao chỉ định luân phiên từ các khu vực tư pháp, xét xử kín và một phía (ex parte). Đối với người Mỹ (công dân và thường trú nhân hợp pháp), ngưỡng công nhận là «điệp viên của thế lực nước ngoài» cao hơn rõ rệt so với người nước ngoài, và đó là điểm khởi đầu của mọi tầng thủ tục. FISA là cơ chế ủy quyền giám sát vì mục đích tình báo, tách biệt với lệnh khám xét hình sự thông thường và nghe lén Title III; doanh nghiệp nhận được lệnh FISA hoặc thư an ninh quốc gia thì nghĩa vụ giữ bí mật và đường khiếu nại khác hẳn trát đòi thông thường, không được xử lý theo quy trình pháp chế thông thường. Các ngoại lệ tại § 1702(b) liệt kê cụ thể: thông tin liên lạc cá nhân, quyên góp nhân đạo, thông tin và tài liệu thông tin, giao dịch liên quan đến du lịch — đây là điều khoản thường xuyên bị tranh tụng. Trong chế tài OFAC, chỉ riêng việc giao dịch với người nằm trong danh sách SDN đã có thể dẫn tới chế tài dân sự gần như trách nhiệm tuyệt đối, nên việc sàng lọc danh sách trước giao dịch là thao tác bắt buộc. Thủ tục CFIUS phần lớn là khai báo tự nguyện, nhưng một số giao dịch công nghệ then chốt phải khai báo bắt buộc; quyền phủ quyết của Tổng thống (quanh § 4565(d)) rất ít khi được chính thức dùng, song việc tự rút và bỏ giao dịch dưới áp lực thẩm tra không hề hiếm. Hai cái bẫy thực tiễn của kiểm soát xuất khẩu là «xuất khẩu được coi như đã xảy ra (deemed export)» — việc tiết lộ công nghệ bị kiểm soát cho công dân nước ngoài ngay trong nước Mỹ cũng tính là xuất khẩu — và việc xác định thẩm quyền phân loại (jurisdiction determination) bắt đầu từ câu hỏi vật phẩm có nằm trong USML hay không; cải cách như «dòng 600» đã chuyển một số vật phẩm quân sự kém nhạy cảm từ USML sang CCL. Thuật ngữ cốt lõi của § 793 là «thông tin quốc phòng (national defense information)» chứ không chỉ «tài liệu mật»: dấu phân loại là một thực tế quan trọng nhưng không phải điều kiện duy nhất của điều luật, và tranh chấp thường xoay quanh tính liên quan quốc phòng của thông tin và trạng thái chủ quan của bị cáo. Các tội xung quanh gồm § 1924 (mang ra và giữ trái phép tài liệu mật), § 1831 của Đạo luật Gián điệp Kinh tế (đánh cắp bí mật thương mại vì chính phủ nước ngoài) và § 1832 (đánh cắp bí mật thương mại nói chung), § 951 về điệp viên không đăng ký và FARA (22 U.S.C. § 611 trở đi). Phần California chỉ có ba mép: việc tự tuân thủ quy tắc liên bang của cơ quan bang và địa phương; hợp tác hành chính qua cơ chế khẩn cấp và hợp nhất tình báo thuộc Văn phòng Thống đốc (là hợp tác, không phải ủy quyền độc lập); và các tội bang thông thường như theo dõi, trộm cắp, truy cập máy tính trái phép đôi khi xuất hiện phụ kèm trong vụ án an ninh quốc gia.

*Ghi chú học tập cá nhân, không phải tư vấn pháp lý.*

## हिन्दी (प्रारंभिक अनुवाद, मूल-भाषी समीक्षा लंबित)

अमेरिका का राष्ट्रीय सुरक्षा कानून एक संहिता नहीं, पाँच संघीय व्यवस्थाएँ हैं। (1) निगरानी: FISA (50 U.S.C. § 1801 आदि) की § 1801 «विदेशी शक्ति» और «उसके एजेंट» को परिभाषित करती है; पारंपरिक आदेश गुप्त न्यायालय FISC (§ 1803 द्वारा स्थापित; आदेश § 1805) देता है, और धारा 702 (§ 1881a, 2008) विदेश में माने जाने वाले गैर-अमेरिकी व्यक्तियों को लक्षित कार्यक्रम-आधारित संग्रह को वार्षिक प्रमाणन और FISC की प्रक्रिया-समीक्षा के तहत अनुमति देती है; वर्तमान समाप्ति-तिथि मौजूदा पाठ से जाँचें। (2) प्रतिबंध: IEEPA (50 U.S.C. § 1701 आदि) राष्ट्रपति को, असामान्य और असाधारण विदेशी खतरे पर राष्ट्रीय आपातकाल घोषित करने के बाद, § 1702 के तहत संपत्ति अवरुद्ध करने और लेन-देन रोकने की शक्ति देता है, § 1702(b) में कुछ अपवाद हैं; प्रवर्तन राजकोष विभाग के OFAC और SDN सूची से होता है, और हाल के मुकदमे दिखाते हैं कि यह शक्ति व्यापक है पर असीम नहीं। (3) निवेश समीक्षा: FIRRMA (2018) से विस्तारित 50 U.S.C. § 4565 के तहत राजकोष की अध्यक्षता वाला CFIUS नियंत्रण वाले लेन-देन और महत्वपूर्ण प्रौद्योगिकी, महत्वपूर्ण अवसंरचना व संवेदनशील व्यक्तिगत डेटा (TID) व्यवसायों में कुछ गैर-नियंत्रण निवेशों की समीक्षा करता है (31 C.F.R. भाग 800, 802)। (4) निर्यात नियंत्रण: दोहरे उपयोग की वस्तुओं पर EAR (वाणिज्य/BIS, 15 C.F.R. भाग 730–774, अब ECRA, 50 U.S.C. § 4801 आदि के तहत) और USML रक्षा वस्तुओं पर ITAR (विदेश विभाग/DDTC, 22 C.F.R. भाग 120–130, 22 U.S.C. § 2778 के तहत)। (5) आपराधिक आधार जासूसी अधिनियम है, विशेषकर 18 U.S.C. § 793, साथ में §§ 794, 798, 951, 1831, 1924। California के पास समानांतर व्यवस्था नहीं है: ये विषय संघीय हैं। 

पूरक विवरण (चीनी मूल पाठ के अनुरूप): FISC § 1803 के तहत स्थापित है; इसमें मुख्य न्यायाधीश द्वारा विभिन्न सर्किटों से नामित जिला न्यायाधीश बारी-बारी से बैठते हैं और कार्यवाही गुप्त व एकपक्षीय (ex parte) होती है। अमेरिकी व्यक्तियों (नागरिकों और वैध स्थायी निवासियों) के लिए «विदेशी शक्ति का एजेंट» मानने की दहलीज़ विदेशी लक्ष्यों की तुलना में स्पष्ट रूप से ऊँची है, और यही सभी प्रक्रियागत स्तरों की जड़ है। FISA खुफ़िया उद्देश्य की निगरानी-प्राधिकरण व्यवस्था है; यह सामान्य आपराधिक तलाशी-वारंट और Title III वायरटैप से अलग प्रणाली है। किसी कंपनी को FISA आदेश या राष्ट्रीय सुरक्षा पत्र मिले तो गोपनीयता दायित्व और चुनौती का मार्ग सामान्य सम्मन से भिन्न होता है — सामान्य विधि-प्रक्रिया से न निपटें। § 1702(b) के अपवादों में व्यक्तिगत संचार, मानवीय दान, सूचना व सूचना-सामग्री और यात्रा-संबंधी लेन-देन गिने गए हैं; यही धारा मुकदमों में बार-बार उठती है। OFAC प्रतिबंधों में SDN सूची के व्यक्ति से लेन-देन ही नागरिक कठोर-दायित्व जैसी सज़ा ला सकता है, इसलिए लेन-देन-पूर्व सूची-जाँच (screening) अनिवार्य कदम है। CFIUS प्रक्रिया अधिकतर स्वैच्छिक घोषणा की है, परंतु कुछ महत्वपूर्ण-प्रौद्योगिकी लेन-देनों में अनिवार्य घोषणा है; राष्ट्रपति की अवरोध-शक्ति (§ 4565(d) के आसपास) औपचारिक रूप से बहुत कम बार प्रयोग हुई है, किंतु समीक्षा के दबाव में लेन-देन स्वयं वापस लेना या छोड़ देना असामान्य नहीं है। निर्यात नियंत्रण की दो व्यावहारिक गलतफ़हमियाँ हैं: «माना गया निर्यात (deemed export)» — अमेरिका के भीतर विदेशी नागरिक को नियंत्रित प्रौद्योगिकी देना भी निर्यात है — और अधिकार-क्षेत्र निर्धारण (jurisdiction determination), जो इस प्रश्न से शुरू होता है कि वस्तु USML में है या नहीं; 600 श्रृंखला जैसे सुधारों ने कुछ कम संवेदनशील सैन्य वस्तुएँ USML से CCL में स्थानांतरित की हैं। § 793 का केंद्रीय शब्द «गोपनीय दस्तावेज़» नहीं, «राष्ट्रीय रक्षा सूचना (national defense information)» है: वर्गीकरण-चिह्न महत्वपूर्ण तथ्य है परंतु धारा की एकमात्र शर्त नहीं; विवाद प्रायः सूचना की रक्षा-संबंधिता और आरोपी की मानसिक स्थिति पर केंद्रित होता है। आसपास के प्रावधानों में § 1924 (वर्गीकृत सामग्री का अनधिकृत हटाना व रखना), आर्थिक जासूसी अधिनियम § 1831 (विदेशी सरकार के लिए व्यापार-रहस्य चोरी) व § 1832 (सामान्य व्यापार-रहस्य चोरी), अपंजीकृत विदेशी एजेंटों पर § 951 और FARA (22 U.S.C. § 611 आदि) शामिल हैं। California के किनारे केवल तीन हैं: राज्य व स्थानीय संस्थाओं का स्वयं संघीय नियमों का पालन; राज्यपाल कार्यालय के अधीन आपातकालीन व खुफ़िया-समन्वय तंत्र का संघीय सहयोग (यह प्रशासनिक सहयोग है, स्वतंत्र अधिकार नहीं); और पीछा करना, चोरी, अनधिकृत कंप्यूटर-प्रवेश जैसे सामान्य राज्य-अपराधों का राष्ट्रीय सुरक्षा मामलों में गौण आरोपों के रूप में आना।

*व्यक्तिगत अध्ययन नोट; कानूनी सलाह नहीं।*
