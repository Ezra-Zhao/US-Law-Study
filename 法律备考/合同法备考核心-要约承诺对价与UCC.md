# 合同法备考核心：要约、承诺、对价与 UCC 第 2 条

这篇讲什么：
- 合同法是律师考试里最爱考、日常生活中也最常用的一块，但它有两套规则：普通法管服务和不动产，UCC 第 2 条管货物买卖。第一步分错，后面全错。
- 把成立三件套拆开：要约、承诺、对价，外加经常一起考的书面要求（Statute of Frauds）。
- 把普通法和 UCC 在四个地方的差别并排记：镜像规则对 2-207、信箱规则、不可撤销要约、合同变更要不要新对价。

---

## 一、先分适用法：普通法还是 UCC

### 中文
判断顺序永远是先问一句：这份合同主要卖的是货物，还是服务？

- 货物买卖：适用《统一商法典》第 2 条（Uniform Commercial Code Article 2，简称 UCC Article 2）。货物指可移动的物品，汽车、设备、库存都算。各州基本都已采纳，加州的对应文本在加州《商法典》第 2 编（California Commercial Code Division 2）。
- 服务、不动产、雇佣等：适用普通法，考试里主要以《合同法重述（第二版）》（Restatement (Second) of Contracts）的规则为准。
- 混合合同（货物加安装、设备加培训）：用主导目的检验（predominant purpose test）——看这笔交易的主要目的到底是买东西还是买服务，主要目的决定整份合同用哪套规则，不是一半一半拆开。

这个判断不是形式问题。同一句带附加条件的回复，在普通法下可能是拒绝原要约的反要约，在 UCC 商人之间却可能已经成立合同，只是附加条款进不进合同另说。先定规则，再谈成立。

### English
Always ask the threshold question first: is this contract mainly about goods, or about services?

- Sale of goods: UCC Article 2 applies. Goods are movable things — cars, equipment, inventory. Article 2 has been adopted in nearly every state; in California it appears as Division 2 of the California Commercial Code.
- Services, real property, and employment: the common law applies, tested mainly through the Restatement (Second) of Contracts.
- Mixed contracts (goods plus installation, equipment plus training): apply the predominant purpose test. The transaction's dominant purpose controls the whole contract; the rules are not split half and half.

The choice matters in practice. The same reply with an added term can be a counteroffer that kills the offer at common law, yet form a contract between merchants under the UCC, with a separate fight over whether the added term becomes part of it. Identify the governing law before analyzing formation.

### Español (译稿)
La primera pregunta es siempre la misma: ¿este contrato trata principalmente de bienes o de servicios?

- Compraventa de bienes: se aplica el Artículo 2 del Uniform Commercial Code (UCC). Son bienes las cosas muebles: automóviles, equipos, inventarios. El Artículo 2 está adoptado en casi todos los estados; en California figura como División 2 del California Commercial Code.
- Servicios, bienes inmuebles y empleo: se aplica el common law, evaluado sobre todo con el Restatement (Second) of Contracts.
- Contratos mixtos (bienes más instalación, equipos más formación): se aplica la prueba del propósito predominante (predominant purpose test). El propósito principal de la operación decide qué régimen rige todo el contrato; no se parte por la mitad.

La elección tiene consecuencias reales. Una misma respuesta con una cláusula añadida puede ser una contraoferta que extingue la oferta en el common law y, sin embargo, formar un contrato entre comerciantes bajo el UCC, con una discusión separada sobre si la cláusula añadida entra en el contrato. Primero se identifica la ley aplicable y después se analiza la formación.

---

## 二、成立三件套：要约、承诺、对价

### 中文
一份可执行的合同，核心是三件事：

**1. 要约（offer）。** 要约是一方表现出的缔约意愿，要让受要约人有理由相信：只要他说同意，合同就成立了。判断用的是客观标准——一个合理的人站在受要约人的位置，会不会把它理解成要约。广告和价目表通常只是要约邀请，不是要约；但写明数量、对象和接受方式的广告，例外情况下可以构成要约。经典例子是 Lucy v. Zehmer, 196 Va. 493 (1954)：法院看的是外在言行，而不是当事人事后声称心里在开玩笑。

要约怎么消灭，也是高频考点：被拒绝、被反要约撤销、期限届满或合理时间过去、要约人或受要约人死亡或丧失行为能力、要约人有效撤回。撤回一般在承诺生效前到达受要约人即可；单边合同里受要约人一旦开始履行，要约人在合理时间内不能再撤回（《重述》第 45 条的选择权逻辑）。

**2. 承诺（acceptance）。** 普通法用镜像规则（mirror image rule）：承诺必须和要约一模一样，多一条、改一条，就是反要约，原要约随之消灭。单纯问一句能不能便宜点，是询问，不是反要约，要约还活着。

承诺的生效时间看信箱规则（mailbox rule，《重述》第 63 条）：用要约允许的方式寄出的承诺，在寄出时生效，哪怕还没送到；但撤回必须在承诺生效前到达才有效。三个例外要记牢：一是要约里写明以收到为准的，按要约办；二是选择权合同（option contract）里的承诺，以收到为准；三是受要约人先寄拒绝、又寄承诺时，哪封先到哪封算数。电子即时通讯一般按收到处理，不套信箱规则。

UCC 这边宽松得多。第 2-204 条说，只要能看出当事人有缔约意思，用任何合理方式都能成立合同，缺个别条款也不必然致命；第 2-207 条处理表格之战（battle of the forms）：商人之间的承诺带了附加条款，合同照样成立，附加条款是否进入合同，要看原要约有没有明确排除、条款是否构成重大变更、对方是否已提出异议或在合理时间内提出异议。承诺若明确写成以接受附加条款为条件，那就回到反要约。

**3. 对价（consideration）。** 普通法要求交换：双方都要付出法律上的代价（legal detriment）或换得利益，而且必须是讨价还价换来的。已经存在的义务（pre-existing duty）一般不算新对价，所以普通法下改合同要新对价。两个替补通道：一是允诺禁反言（promissory estoppel，《重述》第 90 条）——允诺人应当预见到对方会合理信赖，对方也确实信赖并受损时，法院为避免不公可以强制执行；二是 UCC 的例外，见下一节。

不可撤销要约也要分两套：普通法下要靠选择权合同撑着，即受要约人另付对价换要约人在期限内不撤回；UCC 第 2-205 条的商人确定要约（firm offer）不同——商人以签名书面形式保证保持要约开放的，在所定期限内不可撤销，不需要对价，期限最长 3 个月。

### English
An enforceable contract rests on three elements:

**1. Offer.** An offer is a manifestation of willingness to contract on terms that give the offeree reason to believe assent alone will conclude the deal. The test is objective: would a reasonable person in the offeree's position read it as an offer? Advertisements and price lists are usually invitations to deal, not offers, though an ad that is specific about quantity, audience, and how to accept can exceptionally qualify. The classic illustration is Lucy v. Zehmer, 196 Va. 493 (1954): the court judged outward words and conduct, not a later claim that the party was only joking.

Offers also terminate — another heavily tested list: rejection, counteroffer, lapse of the stated period or a reasonable time, death or incapacity of either party, and effective revocation. Revocation generally works if it reaches the offeree before acceptance takes effect; once an offeree has begun performance under a unilateral contract, the offeror's power to revoke is suspended for a reasonable time under the option logic of Restatement section 45.

**2. Acceptance.** At common law the mirror image rule applies: acceptance must match the offer exactly. Add or vary a term and the reply is a counteroffer that terminates the original offer. A mere inquiry — asking whether a lower price is possible — is not a counteroffer and leaves the offer alive.

Timing follows the mailbox rule (Restatement section 63): an acceptance sent by a medium the offer invites is effective on dispatch, even before it arrives, while a revocation must arrive before acceptance becomes effective. Three exceptions matter: the offer itself may require receipt; acceptance under an option contract is effective on receipt; and where an offeree mails a rejection and then an acceptance, whichever arrives first controls. Instantaneous electronic communication is generally treated as effective on receipt, not under the mailbox rule.

The UCC is more forgiving. Section 2-204 allows formation in any manner sufficient to show agreement, and a missing term does not necessarily kill the deal. Section 2-207 governs the battle of the forms: between merchants, an acceptance with additional terms still forms a contract, and whether those terms enter it depends on whether the offer expressly limited acceptance, whether the term materially alters the deal, and whether objection was already made or follows within a reasonable time. An acceptance expressly made conditional on assent to the new terms is a counteroffer instead.

**3. Consideration.** The common law requires a bargained-for exchange in which each side incurs a legal detriment or confers a benefit. A pre-existing duty is generally not new consideration, so a common-law modification needs fresh consideration. Two backstops exist: promissory estoppel (Restatement section 90), under which a promise the promisor should reasonably expect to induce reliance can be enforced to avoid injustice when reliance in fact occurred; and the UCC departures in the next section.

Irrevocable offers split the same way. At common law an option contract does the work: separate consideration buys the offeror's promise to hold the offer open. Under UCC section 2-205, a merchant's signed writing that gives assurance the offer will be held open — a firm offer — is irrevocable for the stated period, capped at three months, with no consideration required.

### Español (译稿)
Un contrato exigible descansa en tres elementos:

**1. Oferta (offer).** Es la manifestación de voluntad de contratar en unos términos que dan al destinatario motivos para creer que basta su asentimiento para cerrar el acuerdo. El criterio es objetivo: ¿una persona razonable en la posición del destinatario lo entendería como oferta? Los anuncios y las listas de precios suelen ser invitaciones a negociar, no ofertas, aunque un anuncio concreto en cantidad, público y forma de aceptación puede ser excepcionalmente una oferta. El ejemplo clásico es Lucy v. Zehmer, 196 Va. 493 (1954): el tribunal juzgó las palabras y la conducta externas, no la afirmación posterior de que era una broma.

La oferta también se extingue, y esa lista se pregunta mucho: rechazo, contraoferta, vencimiento del plazo fijado o de un tiempo razonable, muerte o incapacidad de cualquiera de las partes y revocación eficaz. La revocación suele ser válida si llega al destinatario antes de que la aceptación surta efecto; cuando el destinatario ya empezó a cumplir en un contrato unilateral, el poder de revocar queda suspendido por un tiempo razonable según la lógica de opción de la sección 45 del Restatement.

**2. Aceptación (acceptance).** En el common law rige la regla de la imagen especular (mirror image rule): la aceptación debe coincidir exactamente con la oferta. Añadir o cambiar un término convierte la respuesta en contraoferta y extingue la oferta original. Una simple pregunta —si es posible un precio menor— es una consulta, no una contraoferta, y la oferta sigue viva.

El momento de eficacia sigue la regla del buzón (mailbox rule, sección 63 del Restatement): la aceptación enviada por un medio que la oferta admite es eficaz al despacharse, aunque aún no haya llegado; en cambio, la revocación debe llegar antes de que la aceptación sea eficaz. Hay tres excepciones clave: la propia oferta puede exigir la recepción; la aceptación bajo un contrato de opción (option contract) es eficaz al recibirse; y si el destinatario envía primero un rechazo y luego una aceptación, manda el que llegue primero. La comunicación electrónica instantánea se trata, en general, como eficaz al recibirse, no bajo la regla del buzón.

El UCC es más flexible. La sección 2-204 permite la formación por cualquier medio suficiente para mostrar acuerdo, y la falta de algún término no mata necesariamente el contrato. La sección 2-207 regula la batalla de formularios (battle of the forms): entre comerciantes, una aceptación con términos adicionales forma igualmente el contrato, y si esos términos entran en él depende de si la oferta limitó expresamente la aceptación, de si el término altera materialmente el acuerdo y de si ya hubo objeción o esta llega en un tiempo razonable. Una aceptación expresamente condicionada al asentimiento a los nuevos términos sí es contraoferta.

**3. Contraprestación (consideration).** El common law exige un intercambio negociado en el que cada parte asuma un detrimento jurídico u otorgue un beneficio. Un deber preexistente no suele ser nueva contraprestación, así que modificar un contrato de common law exige contraprestación nueva. Existen dos vías de respaldo: el promissory estoppel (sección 90 del Restatement), que permite exigir una promesa cuando el promitente debía prever la confianza razonable del otro y esta se produjo, para evitar una injusticia; y las excepciones del UCC de la sección siguiente.

Las ofertas irrevocables también se dividen: en el common law hace falta un contrato de opción, con contraprestación separada a cambio de mantener la oferta abierta; bajo la sección 2-205 del UCC, la oferta firme de un comerciante (firm offer) —seguro escrito y firmado de que la oferta se mantendrá abierta— es irrevocable durante el plazo indicado, con un máximo de tres meses, sin necesidad de contraprestación.

---

## 三、书面要求与变更：Statute of Frauds 和改合同

### 中文
成立不等于能告得赢。有一类合同口头成立也难以执行，必须有书面证据，这就是防止欺诈法（Statute of Frauds）。普通法一侧常考的清单可以用一句话串起来：以结婚为对价的允诺、一年内不可能履行完的合同、土地利益、遗产执行人自掏腰包还债的允诺、保证人替别人还债的允诺。货物这一类在 UCC 一侧。

UCC 第 2-201 条：价款 500 美元或以上的货物买卖合同，要有足以表明合同已订立的书面记录、注明数量，并由被要求履行的一方签名，否则原则上不可执行。加州对应条文是加州《商法典》第 2201 条，门槛同为 500 美元。普通法一侧的加州清单在加州《民法典》第 1624 条。

例外同样爱考：第 2-201 条下，为买方特别制造且不适合转卖他人的货物、诉讼中承认合同存在、已付款并被接受或已收货并接受的部分，都可以绕开书面要求；商人之间还有确认书规则——一方收到足够约束发送方的书面确认，收件方有理由知悉内容又不在 10 天内书面提出异议的，书面要求对他也视为满足。

改合同的差别再记一次：普通法改合同要新对价，还受既存义务规则约束（履行中途威胁罢工要加钱，典型的不算）；UCC 第 2-209 条明确改货物合同不需要对价，只要求善意，但改完后总价达到 500 美元或以上的，仍要满足第 2-201 条的书面要求。

### English
Formation is not the same as enforceability. One family of contracts is hard to enforce without a writing: the Statute of Frauds. On the common-law side the tested list covers promises in consideration of marriage, contracts that cannot by their terms be performed within one year, interests in land, an executor's promise to pay estate debts personally, and a surety's promise to answer for another's debt. Goods sit on the UCC side.

UCC section 2-201 provides that a contract for the sale of goods for $500 or more is generally not enforceable unless there is a writing sufficient to indicate a contract was made, stating the quantity, and signed by the party against whom enforcement is sought. California's counterpart is California Commercial Code section 2201, with the same $500 threshold; California's common-law list appears in California Civil Code section 1624.

The exceptions are tested just as often. Under section 2-201, specially manufactured goods not suitable for resale to others, an admission in court that a contract was made, and goods paid for and accepted or received and accepted can each take the deal outside the writing requirement. Between merchants there is also the confirmatory-memo rule: a written confirmation sufficient against the sender binds the recipient who has reason to know its contents and does not object in writing within 10 days.

For modifications, keep the split in view. A common-law modification needs new consideration and runs into the pre-existing duty rule (the mid-performance threat to stop work unless paid more is the standard example). UCC section 2-209 states that modification of a goods contract needs no consideration, though good faith is required, and if the contract as modified reaches $500 or more, the section 2-201 writing requirement still applies.

### Español (译稿)
Formación no es lo mismo que exigibilidad. Una familia de contratos es difícil de exigir sin un escrito: el Statute of Frauds. En el common law, la lista evaluada incluye las promesas a cambio de matrimonio, los contratos que por sus términos no pueden cumplirse en un año, los intereses sobre tierras, la promesa de un albacea de pagar deudas de la herencia con fondos propios y la promesa de un garante de responder por la deuda de otro. Los bienes quedan del lado del UCC.

La sección 2-201 del UCC dispone que un contrato de compraventa de bienes por $500 o más, en general, no es exigible sin un escrito suficiente para indicar que se celebró un contrato, que indique la cantidad y firmado por la parte contra la que se pide el cumplimiento. El equivalente de California es la sección 2201 del California Commercial Code, con el mismo umbral de $500; la lista de common law de California está en la sección 1624 del California Civil Code.

Las excepciones se preguntan igual de a menudo. Bajo la sección 2-201, los bienes fabricados especialmente para el comprador y no aptos para revenderse, la admisión en juicio de que hubo contrato y los bienes pagados y aceptados o recibidos y aceptados pueden sacar el acuerdo del requisito de escrito. Entre comerciantes existe además la regla de la nota confirmatoria: una confirmación escrita suficiente contra el remitente vincula al destinatario que tiene motivos para conocer su contenido y no objeta por escrito en 10 días.

En las modificaciones, la división se mantiene. Modificar un contrato de common law exige nueva contraprestación y choca con la regla del deber preexistente (el ejemplo típico es amenazar a mitad de la ejecución con parar si no se paga más). La sección 2-209 del UCC establece que modificar un contrato de bienes no exige contraprestación, aunque sí buena fe, y si el contrato ya modificado alcanza los $500 o más, sigue aplicando el requisito de escrito de la sección 2-201.

---

## 四、考试怎么考、日常怎么用

### 中文
在统一律师考试（UBE）里，合同法是 MBE 的七个科目之一：MBE 共 200 题、175 题计分，合同这一科大约占其中的二十多题，另在论述题里经常和 UCC 货物买卖混着出。加州律师考试的论述题同样爱出合同，只是会掺进加州自己的规则，备考时普通法与 UCC 的对照表要单独背一遍。

日常里最实用的其实是三条：一是签服务合同前先看有没有书面要求兜底，口头答应的一年以上服务、土地和担保类安排，落字才稳；二是网购和采购里收到对方带附加条款的确认单，不要默默放着——商人之间的 10 天异议期和重大变更规则，过期就可能算进合同；三是改合同的时候把对价或善意留痕做好，普通法合同补一份新对价说明，货物合同把修改写下来并核对 500 美元的书面门槛。

### English
On the Uniform Bar Examination, Contracts is one of the seven MBE subjects: the MBE has 200 questions, 175 of them scored, and Contracts accounts for roughly two dozen of the scored items, with UCC sales issues also appearing regularly in essays. California's essays test contracts as well, layered with California-specific rules, so the common-law-versus-UCC comparison deserves its own study pass.

In daily life, three points do most of the work. First, check the writing requirement before relying on an oral deal: service arrangements that cannot be completed within a year, land deals, and surety promises are far safer in writing. Second, do not let a confirmation with extra terms sit unanswered in a business purchase — between merchants, the 10-day objection window and the material-alteration rule can quietly decide what the contract contains. Third, paper your modifications: note fresh consideration for a common-law change, and for goods, write the modification down and check it against the $500 writing threshold.

### Español (译稿)
En el Uniform Bar Examination, Contratos es una de las siete materias del MBE: el MBE tiene 200 preguntas, 175 puntuables, y Contratos supone aproximadamente una veintena larga de las puntuables, además de aparecer con frecuencia en los ensayos junto con la compraventa del UCC. Los ensayos de California también evalúan contratos, con reglas propias del estado, así que la comparación entre common law y UCC merece una pasada de estudio aparte.

En la vida diaria, tres ideas hacen casi todo el trabajo. Primero, revise el requisito de escrito antes de confiar en un acuerdo oral: los servicios que no pueden completarse en un año, los negocios sobre tierras y las promesas de garantía son mucho más seguros por escrito. Segundo, no deje sin respuesta una confirmación con términos adicionales en una compra comercial: entre comerciantes, el plazo de objeción de 10 días y la regla de la alteración material pueden decidir en silencio el contenido del contrato. Tercero, documente las modificaciones: anote la nueva contraprestación en un cambio de common law y, en bienes, ponga la modificación por escrito y contrástela con el umbral de $500.

---

## 来源与说明

- 《合同法重述（第二版）》（Restatement (Second) of Contracts）第 45、63、90 条：选择权逻辑、信箱规则与允诺禁反言。
- 《统一商法典》第 2 条（UCC Article 2）第 2-201、2-204、2-205、2-207、2-209 条：书面要求、成立方式、商人确定要约、表格之战与合同变更；加州对应文本为加州《商法典》第 2 编，第 2201 条为书面要求。
- 加州《民法典》第 1624 条：加州普通法一侧的防止欺诈清单。
- Lucy v. Zehmer, 196 Va. 493 (1954)：客观缔约意思的经典判例。
- NCBE 公布的 MBE 科目结构：200 题、175 题计分、七个科目。

## 免责声明

本篇为个人学习笔记，不构成法律建议。合同是否成立、能否执行，要结合具体事实、州法差异和最新判例判断；涉及自己的合同纠纷，请咨询有执业资格的律师。

This article is a personal study note and does not constitute legal advice. Enforceability turns on specific facts, state variations, and current case law; consult a licensed attorney for your own dispute.

Este artículo es una nota personal de estudio y no constituye asesoría legal. La exigibilidad depende de los hechos concretos, de las variaciones estatales y de la jurisprudencia vigente; consulte a un abogado con licencia para su caso.
