---
title: recibo verdeの前受け（Adiantamento）の発行方法と課税時期
tags: [ポルトガル税務, recibo-verde, IVA, IRS, CategoriaB, adiantamento]
created: 2026-09-23
status: 最終版（IVAの形式面のみ未確認）
updated: 2026-09-23
---

# recibo verdeの前受け（Adiantamento）の発行方法と課税時期

## 結論
- 数か月分を先に受け取ったら、**入金日**に、**全額**で、発行理由を「**Adiantamento**」にした**Fatura-Recibo**を1枚発行する。
- 月ごとに分けて発行するのは不可（法律上の発行期限を過ぎてしまう）。
- 摘要の記載例：*"Adiantamento referente à prestação de serviços de outubro de 2026 a janeiro de 2027"*

## 根拠条文
- **CIVA 第36.º条1項c)**：「Na data do recebimento, no caso de pagamentos relativos a uma transmissão de bens ou prestação de serviços **ainda não efetuada**」（まだ提供していない取引の代金は、受け取った日にインボイスを発行する）
- **CIVA 第8.º条1項c)・2項**：取引より先に支払いを受けた場合、IVAは受け取った時点で課税される。
- **AT FAQ 5856**：「fatura-recibo de todas as importâncias recebidas dos seus clientes, ainda que a título de provisão, **adiantamento** ou reembolso de despesas」（前受け・立替金を含め、受け取った金額はすべてFatura-Reciboの対象）
- 参考：**CIVA 第7.º条3項**（継続的なサービスは各支払期間の終わりに提供があったとみなす）は、前受けがない場合のルール。前受けがあるときは第36.º条1項c)が優先する。

## 「Motivo de Emissão」（発行理由）の3つの選択肢
| 選択肢 | 使う場面 | 税務上の扱い |
|---|---|---|
| Pagamento dos bens ou dos serviços | 提供済みのサービスの対価を受け取った | 所得（IRS・源泉徴収・IVAの対象） |
| **Adiantamento** | **まだ提供していない**サービスの対価（報酬）を先に受け取った | **所得**（同上） |
| Adiantamento para pagamento de despesas por conta e em nome do cliente | 顧客名義の費用を顧客の代わりに支払うための前受け | 所得にならない。IVAの課税標準にも含まれない。**源泉徴収率が消える** |

### 区分を決める2つの軸
1. **費用の名義は顧客か、自分か** → 顧客名義なら立替金（所得にならない）、自分名義なら報酬（所得になる）
2. **受け取るのはサービスの前か、後か** → 報酬を前に受け取ればAdiantamento、後ならPagamento

> ⚠️ 「Adiantamento＝自分の費用の前払い」という説明は不正確。Adiantamentoを選ぶ理由は「提供前に対価を受け取った」こと。

### 立替金（3番目の区分）を使える条件
- **CIVA 第16.º条6項c)**：「As quantias pagas em nome e por conta do adquirente … registadas pelo sujeito passivo em contas de terceiros apropriadas」→ IVAの課税標準から除かれる。
- **拘束的回答（Informação Vinculativa）n.º 27151**：費用の**領収書の原本が顧客名義（顧客のNIF）**で発行されていることが条件。自分のNIFで発行されていれば報酬（honorários）として課税される。

### 例
- 出張のホテル代€150（請求書は**自分名義**）を出張前に受け取る → **Adiantamento**（所得になる）。出張後に受け取るなら Pagamento。
- 顧客が負担する登録料€150（請求書は**顧客名義**）を代わりに支払うため先に預かる → **3番目の立替金の区分**（所得にならない）。

## 前受け（Adiantamento）の税務上の扱い
- **IRS**：発行した年のCat. B所得になる（Anexo Bに集計）。
- **源泉徴収**（CIRS 第101.º条）：相手先に源泉徴収義務があれば、**支払い時に全額**に対して源泉徴収される。
- **IVA**：入金した時点で課税。IVA免税（第53.º条）の場合は、年間の上限額の判定に入金した年の売上として算入。
- **Segurança Social**：入金した四半期のDeclaração Trimestralに全額が入る（拠出額は均されない）。→ [[declaracao-trimestral-prazos-janelas]]
- 全額を受け取った後、同じ金額でもう一度recibo verdeを発行しない（所得が二重に計上される）。

### 自分名義の費用（ホテル代など）の処理
- 請求書に自分のNIFを入れてもらい、e-faturaで「事業用（atividade）」に振り分ける。
- 簡易課税で係数0.75が適用される場合：収入の15%分は、証明できた経費の分しか認められない（**CIRS 第31.º条13項**）ので、ホテル代を証明に使えるようにしておく。※算入できる費目の細かい範囲は要確認
- IVA課税事業者の場合：ホテル代にかかったIVAは原則として差し引けない（**CIVA 第21.º条1項d)**）。
- organized accounting（contabilidade organizada）の場合：そのまま必要経費に計上する。
- 返金するとき：anulaçãoするか、nota de crédito（CIVA 第29.º条、第78.º条）で調整する。

## 年をまたぐ場合
**CIRS 第3.º条6項**：Cat. Bの所得は「desde o momento em que para efeitos de IVA seja obrigatória a emissão de fatura」（IVAのルールでインボイスの発行が義務になった時点）から課税対象になる。ただし、帳簿に基づいて所得を計算する場合はCIRC 第18.º条（発生主義）による。

OCCの技術見解 PT20372：
- 簡易課税でIVA通常課税 → インボイスの発行義務が生じた時点で課税
- 簡易課税でIVA免税 → 入金した時点で課税（現金主義）
- organized accounting → 発生主義（especialização económica）

例：2026年11月に、2026年11月〜2027年2月分を受け取った場合
| | 簡易課税 | organized accounting |
|---|---|---|
| IRS | **2026年に全額** | 2026年に2か月分、2027年に2か月分 |
| 源泉徴収 | 2026年に全額分 | 2026年に全額分（2026年の税額から差し引く） |
| IVA | 2026年の申告期間に全額 | 同じ |
| Segurança Social | 2026年第4四半期に全額 | 同じ |

- 対策：顧客に年をまたがないように支払ってもらう（12月分までと1月分以降で入金を分ける）。

> ✅ **前受けの場合は、IVAの有無にかかわらず入金日に所得を計上する**（IVAがあっても問題にならない）。
>
> 参考（前受け以外で違いが出る場面）：「簡易課税＝現金主義」ではない。後払いの場合だけ差が出る。
> 例：2026年12月にサービスを提供し、2027年1月に入金された場合
> - IVA通常課税 → **2026年**（提供から5営業日以内にインボイスの発行義務が生じる。CIVA 第36.º条1項a)）
> - IVA免税 → **2027年**（入金した時点。OCC PT20372）

## organized accounting（contabilidade organizada）とrecibo verdeの関係
- organized accountingは**所得の計算方法**（CIRS 第28.º条）の話で、**インボイスの発行手段**とは別。organized accountingを選んだからPortalのrecibo verdeが使えなくなる、という規定は見当たらない。
- Portalを使えないのは会社（Lda・SA）で、会社は認証ソフトで発行する。
- どちらの手段で発行しても、**入金日に前受け分のインボイスを発行する義務は同じ**（CIVA 第36.º条1項c)）。
- organized accountingでの違いは帳簿の中だけ：前受け金をいったん繰延収益として計上し、サービスを提供した期間ごとに収益に振り替える。
- 認証ソフトを使う場合は、「前受けインボイス → 完了時に最終インボイスで前受け分を差し引く」運用が一般的。
- ❓ 売上高によって認証ソフトの使用が義務になるか（Portaria 363/2010）の基準額と、Portal利用者の扱いは未確認。

## IVA免税（第53.º条）の場合
- IVAを請求も納付もしないので、完了時の追加書類の有無で税額が変わることはない。実害はほぼない。
- ただし**インボイスの発行義務は免除されない**（CIVA 第29.º条）。前受け分は入金日に発行し、「IVA - regime de isenção [art. 53.º]」と記載する（Portalで免税の条項を選べば自動で記載される）。
- **前受け分は年間の上限額の判定に全額算入される** → まとめて受け取ったことでその年の売上が上限を超えると、免税の適用から外れる。これがIVA免税の人にとって前受けの最大のリスク。
- ❓ 上限額は近年改正されているので、正確な金額と、超えたときに課税に切り替わる時期は最新の条文で確認する。

## 全額を前受けした後、完了時に追加の書類は必要か
| 観点 | 結論 |
|---|---|
| IRS | **不要**。所得の計上は入金日で完了する（CIRS 第3.º条6項）。金額の入った書類をもう一度発行すると二重に計上される |
| IVAの税額 | **新たな税額は生じない**。全額分のIVAは前受けの時点で課税済み（CIVA 第8.º条1項c)・2項） |
| IVA（インボイスの発行義務、CIVA 第29.º条1項b)） | 条文をどう読むかで分かれる（下記）。ATの公式見解は未確認 |
| IVA免税の場合 | 実害なし |
| 一部だけ前受けした場合 | 残額を受け取ったときに「Pagamento」で発行する（推測。公式資料では未確認） |

**→ 簡易課税でrecibo verdeを使っている場合は、読み方Aに立ち、追加の書類は発行しないのが現実的な判断。** 税額には影響しない。

### CIVA 第29.º条1項b)の文言
> 「Emitir obrigatoriamente uma fatura **por cada** transmissão de bens ou **prestação de serviços** (...), **bem como pelos pagamentos** que lhes sejam efetuados antes da data da transmissão de bens ou da prestação de serviços」

※つなぎの言葉は「ou（または）」ではなく「**bem como**（〜とともに、〜も）」。

| 読み方 | 内容 | 完了時の書類 |
|---|---|---|
| **A：場面ごとの発行義務** | 提供したら提供のインボイスを、前払いを受けたら前払いのインボイスを、それぞれの時点で発行せよ、という意味。全額を前受けしてインボイスを発行済みなら、その取引についての発行義務は果たしている | 不要 |
| **B：累積的な義務** | 「bem como」を「〜に加えて〜も」と読み、提供ごとのインボイスは前受けがあっても別に必要とする | 必要（請求額は0） |

- organized accountingでの一般的な実務は、読み方Bに沿った運用（下記）。
- Portalのrecibo verdeには前受けを選ぶ入力項目はあるが、前受け分を差し引いた金額0の最終書類を作る機能は確認できていない。読み方Aを前提にした設計とも考えられる（推測）。

### organized accountingの運用：最終インボイスで前受け分を差し引く
例：4か月分の報酬€1,000、IVA 23%（€230）を全額前受けした場合

**① 入金時：前受けのインボイス（Fatura de adiantamento）**
- 認証ソフトで「adiantamento」のインボイスを発行する。€1,000 ＋ IVA €230 ＝ €1,230
- IVA €230は、この申告期間に納める（CIVA 第8.º条1項c)）
- 帳簿：現金・預金 €1,230 ／ **顧客からの前受金**（SNCの勘定科目218など）€1,000 ＋ 売上に係るIVA €230
  → この時点では**まだ収益として計上しない**

**② 毎月、あるいは完了時：最終インボイス（Fatura final）**
- インボイスには次のように記載する。
  - サービスの提供：€1,000 ＋ IVA €230
  - 前受け分の差し引き：**−€1,000 − IVA €230**（前受けインボイスの番号を記載）
  - **請求額：€0、今回のIVA：€0**
- 帳簿：顧客からの前受金 €1,000 ／ **売上（SNCの勘定科目72）€1,000**
  → ここで初めて収益として計上する（発生主義、CIRC 第18.º条）

**この運用の目的**
- 取引ごとのインボイスを残し、第29.º条1項b)を読み方Bで解釈した場合にも対応できるようにする
- 売上として計上した額とインボイスの額を、SAF-T（ATに提出する会計データ）の上で一致させる
- IVAは差し引き0なので、二重に課税されることはない

※勘定科目の番号は一般的なSNCの例。実際の科目は会計士の設定によって変わる。

## ❓ 未確認の点（まとめ）
- CIVA 第29.º条1項b)の読み方（AかBか）についてのATの公式見解。全額を前受けした後、形式上、最終書類が必要か。
- Portalのrecibo verdeで、前受け分を差し引いた最終書類を作れるか。
- 認証ソフトの使用が義務になる基準（Portaria 363/2010）。
- IVA免税（第53.º条）の最新の上限額と、超えたときに課税に切り替わる時期。
- 確認先：e-balcãoでATに照会するか、会計士に確認する。最終書類についての照会文の例：
    > *"Emiti uma fatura-recibo com o motivo 'Adiantamento' pelo valor total de serviços a prestar nos próximos 4 meses. Após a prestação dos serviços, é necessário emitir algum documento adicional?"*

## 出典
- [AT – FAQ Fatura Recibo-verde](https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/questoes_frequentes/Pages/faqs-00070.aspx)
- [CIVA 第36.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva36.aspx)
- [CIVA 第8.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva8.aspx)
- [CIVA 第29.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva29.aspx)
- [CIVA 第16.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva16.aspx)
- [OCC – IRS: Momento de tributação de rendimentos (PT20372)](https://www.occ.pt/pt-pt/noticias/irs-momento-de-tributacao-de-rendimentos-modelo-10)
- [Audico – IV 27151 解説](https://www.audico.pt/irs-categoria-b-adiantamento-de-despesas-em-nome-e-por-conta-de-cliente/)
- [Montepio – Recibos verdes: guia](https://www.montepio.org/ei/pessoal/impostos/recibos-verdes-que-modalidades-existem/)
- [MoneyLab – Como preencher os novos recibos verdes](https://moneylab.pt/2024/10/03/como-preencher-os-novos-recibos-verdes)
- [Qonto – Faturas e recibos verdes: as 12 dúvidas mais comuns](https://qonto.com/pt/blog/gestao-empresarial/faturacao/faturas-e-recibos-verdes)
