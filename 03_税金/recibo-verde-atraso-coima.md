---
title: recibo verdeの発行期限と遅れた場合の過料（coima）
tags: [ポルトガル税務, recibo-verde, IVA, RGIT, coima, 発行期限]
created: 2026-09-23
status: 一部未確認あり
---

# recibo verdeの発行期限と遅れた場合の過料（coima）

関連：[[recibo verde 前受け(Adiantamento)と課税時期]]

## 1. 発行期限
期限は**入金日ではなく、課税時期（原則としてサービスを提供し終えた時点）**から数える。例外は前受けで、この場合は入金日が基準になり、猶予はない。

| 場面 | 期限 | 根拠 |
|---|---|---|
| 通常（サービス提供の後に請求） | **課税時期の翌日から5営業日以内**（サービスの課税時期は原則として完了時点） | CIVA 第36.º条1項a)、第7.º条1項b) |
| **前受け**（提供前に入金） | **入金日当日** | CIVA 第36.º条1項c) |
| 継続的なサービス（月払いの契約など） | 各支払いが対象とする期間の終わりが課税時期 → そこから5営業日以内 | CIVA 第7.º条3項、第36.º条1項a) |
| EU域内の事業者向けのサービス（リバースチャージ） | 提供した月の**翌月15日まで** | CIVA 第36.º条1項b) |

- IVA免税（第53.º条）の人にも同じ期限が適用される（インボイスの発行義務は免除されない。CIVA 第29.º条）。
- ポルトガルの祝日は営業日に数えない。

### 入金のタイミングと発行する書類
| 入金のタイミング | 対応 |
|---|---|
| 提供前（前受け） | 入金日に**Fatura-Recibo**（発行理由：Adiantamento） |
| 完了から5営業日以内 | 完了日の翌日から5営業日以内に**Fatura-Recibo** |
| 完了から5営業日を過ぎて | 5営業日以内に**Fatura**を先に発行 → 入金された時点で**Recibo** |

例：9月30日（水）に完了
- 10月2日に入金 → **10月7日（水）まで**にFatura-Recibo
- 10月20日に入金 → 10月7日までにFatura、10月20日にRecibo

- Reciboの発行期限はCIVAに定めがない。CIRS 第115.º条（受け取った金額について領収書を発行する義務）から、受け取った時点での発行が原則。「何日以内」という明文の猶予期間は未確認。

## 2. 遅れた場合の過料
**RGIT 第123.º条1項**
> 「A não passagem de recibos ou facturas ou a sua **emissão fora dos prazos legais**, nos casos em que a lei o exija, é punível com coima de **(euro) 150 a (euro) 3750**.」

- 期限を過ぎて発行した場合も、発行しなかった場合と同じ条文、同じ過料の範囲。
- 参考：同条2項（買い手がインボイスを求めなかった、または保存しなかった場合）は€75〜€2,000。

## 3. 過料の免除・軽減（2022年1月1日施行、Lei 7/2021による改正後）
| 制度 | 条文 | 内容 |
|---|---|---|
| 免除① | RGIT 第29.º条1項 | 過去5年間に、a) 税務違反で有罪が確定したことがなく、b) 過料の免除や軽減（第29.º条・第30.º条）も受けたことがなければ、過料は科されない |
| 免除② | RGIT 第29.º条2項・4項 | a) 税収に実害がなく、b) 不備を是正済みなら、過料は科されない。**弁明期間内に申請**し、それまでに是正しておく。※納付すべき税額を納めていない場合は、常に「実害あり」とされる（同3項） |
| 軽減 | RGIT 第30.º条 | 違反の通知（auto de notícia）を受ける前に自分から是正した場合、**過失の場合の最低額の12.5%**に減る（€150 → 約€19）。通知を受けてから30日以内に支払い、税務上の状況を是正することが条件。税務調査の事前聴聞の期限までなら50% |
| 特別軽減 | RGIT 第32.º条 | 弁明期間内に責任を認めて是正すれば、上限額と下限額が**半分**になる（最低€25。第30.º条で計算した額を下回らない）。違反が軽く過失も小さければ、**警告だけ**で済むこともある（同3項） |

※第29.º条1項の適用条件の細部（故意でない違反に限られるかなど）は、条文の全文で確認し直す。

## 4. 税額への影響
- **IVAの課税事業者**：インボイスが遅れても、IVAは本来の期限が終わった時点で課税される（CIVA 第8.º条1項a)）。IVAの申告や納付まで遅れると、延滞利息と、IVAを納めなかったことに対する別の過料の問題が生じる。この場合、第29.º条2項の「税収に実害がない」には当たらない。
- **IVA免税（第53.º条）**：税額には影響しないので、「税収に実害がない」に当たりやすい。問題は第123.º条の手続き違反だけ。
- IRSについても、所得を計上すべき時期は変わらない（CIRS 第3.º条6項：インボイスの発行義務が生じた時点）。

## 5. 実務上の対応
1. 気づいた時点で**すぐに発行する**（自分から是正しておくと、免除や軽減を受けやすくなる）。
2. IVAの課税事業者は、その申告期間のIVA申告に正しく反映されているか確認する。
3. 通知が来たら、**弁明期間内**に第29.º条2項（免除）か第32.º条（特別軽減）を申請する。
- 期限を少し過ぎた程度で初めてなら、実際に過料が科されることはあまりない（実務上の理解で、統計的な裏付けはない）。

## ❓ 未確認の点
- RGIT 第29.º条1項の適用条件の細部。
- Reciboの発行期限の明文。
- 過失の場合に上限額が半分になる規定（RGIT 第26.º条）の現行の文言。

## 出典
- [CIVA 第36.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva36.aspx)
- [CIVA 第8.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva8.aspx)
- [CIVA 第29.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/civa_rep/Pages/iva29.aspx)
- [RGIT 第123.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/rgit/Pages/rgit123.aspx)
- [RGIT 第29.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/rgit/Pages/rgit29.aspx)
- [RGIT 第30.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/rgit/Pages/rgit30.aspx)
- [RGIT 第32.º条](https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/rgit/Pages/rgit32.aspx)
