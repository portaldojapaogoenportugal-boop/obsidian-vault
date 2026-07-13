---
title: CIRS第23条 海外所得・費用のユーロ換算
aliases:
  - 為替換算 CIRS 23
  - cambio rendimentos estrangeiro
tags:
  - 税務/IRS
  - ポルトガル
  - 為替換算
  - 不動産所得
created: 2026-06-23
status: 確認済み
---

# CIRS第23条 海外所得・費用のユーロ換算

> [!summary] 要点
> 外貨建ての海外所得・費用は **CIRS第23条** でユーロ換算する。原則は各取引日の公式建値（所得＝買相場 / 費用＝売相場）、日付を証明できなければ **12月31日レート**。換算の公式ソースは **Banco de Portugal／ECB の参照レート**。年間集計の外国申告書しかなければ 12/31 一括換算が標準。

## 1. 根拠条文（第23条 — Valores fixados em moeda sem curso legal em Portugal）

総則（Secção I – Regras gerais）にあり、**不動産所得カテゴリーF を含む全カテゴリーに適用**。

**第1項（原則＝各取引日の公式建値 cotação oficial）**

| 区分 | 適用レート |
|---|---|
| a) 国外へ送金する所得 | 実際の送金日（源泉徴収日）の **売相場 câmbio de venda** |
| b) 国外からの所得 | ポルトガルで支払・利用可能になった日の **買相場 câmbio de compra** |
| c) 国外で得て年末まで未送金の所得 | 支払・利用可能日の **買相場** |
| d) **費用（encargos）** | **a)を適用＝支払日の売相場 câmbio de venda** |

> [!important] 費用は売相場
> 費用は所得の買相場と異なり **売相場（câmbio de venda）** を当てるのが条文上の原則。

**第2項** いずれの日付も証明できない場合 → **その年の12月31日のレート**
**第3項** 当該日にレートがなければ直前の最終建値
**第4項** 課税所得を **会計（contabilidade）に基づき算定**する場合は会計の規則による → [[#4. 平均レートと会計理論（IAS 21）]]

## 2. 実務対応（年間集計の外国税務申告書しかない場合）

外国（日本）の確定申告書が年間集計値しか示さず、個々の支払日を特定・証明できない → **第2項に落ちる**。

- **12月31日の Banco de Portugal／ECB 参照レートで年間額を一括換算**するのが条文に最も忠実。
- 反復所得（家賃等）は **年間平均レート（taxa média anual）** を使う運用も信頼サイトで紹介され、AT も Banco de Portugal 公式レートなら受容。ただし**平均レートは第23条1〜2項に明文規定がない簡便法**。厳密な根拠は「支払日レート」か「12月31日レート」。
- **外国申告書の純額をそのまま使わない**。総家賃（rendas brutas）と **ポルトガル法で控除可の経費のみ** を Anexo J Quadro 7 に分けて記載し、その額を換算。外国申告書は裏付け資料扱い。
- 所得・費用で換算方法を一貫させ、レートの出所（Banco de Portugal 公表値）を保管。CRS 自動情報交換で数値整合が必要。

## 3. なぜ Banco de Portugal の参照レートなのか

条文が「**a cotação oficial da respetiva divisa（公式建値）**」を要求しているため、民間の店頭レートは不可。

- ポルトガルで通貨の公式建値を出す権限を持つのは中央銀行 **Banco de Portugal**。
- ユーロ移行後は日々の参照レートを **ECB（BCE）が確定・公表 → Banco de Portugal が公式参照レートとして公表・配信**。
- AT も Portal das Finanças 上で為替レートを掲載するが、出所は同じ BdP／ECB。納税者・AT が同一公式ソースを参照でき、検証可能性が担保される。

> [!warning] OANDA・XE など民間プロバイダ
> 品質は高くても「公式（oficial）」ではない。AT に根拠を問われた際に論点化される余地がある。民間業者は補強証拠にとどめ、第一次的根拠は公式参照レートに置くのが安全。プロバイダごとに bid/ask・端数が異なる点も「単一公式値」が好まれる理由。

## 4. 平均レートと会計理論（IAS 21）

平均レートでの換算は**会計理論的に正しい**、かつ税法上のフックもある。

- **IAS 21.22**：損益項目（収益・費用）は取引日レートが原則だが、近似する限り **期間平均レートを用いてよい**。
- **IAS 21.23**：貨幣性 B/S 項目は **期末（決算日）レート**。
- → **P/L項目＝平均レート、貨幣性項目＝期末レート** が会計標準。

**税務との接続（第23条4項）**

| 算定方法 | 平均レートの可否 |
|---|---|
| カテゴリーB（組織的会計 contabilidade organizada）・IRC | 第4項経由で IAS 21 が効き、**平均レートが正面から正当化** |
| **カテゴリーF（不動産所得）** | 会計ベースでなく第23条1〜2項（取引日／12月31日）が直接適用 → 平均レートは**容認される簡便法にとどまり明文の裏付けなし** |

## 5. 買相場・売相場の区別が空文化している論点

> [!note] 条文が現実に追いついていない箇所
> 第23条は **escudo 時代の文言のまま未改正**。

- escudo 時代：Banco de Portugal が買相場・売相場をスプレッド付きで**別建て公表**。第23条の「所得＝買 / 費用＝売」の振り分けはこの実態に沿った設計だった。
- ユーロ移行後：ECB が公表するのは買・売を分けない **単一の参照レート** のみ。条文が前提にした「公式の買・売二本立て」が公表ベースで消滅。
- 解決：**後発的な適用不能（impossibilidade superveniente）** として読む。立法趣旨（公式建値で換算）は残り、買・売の区別はその精緻化にすぎない。`compra = venda = 参照レート` となり、a)・b)・d) の振り分けは**操作上は空文化**。所得・費用とも **単一参照レート一本** で当てる。
- これを正面から解決する明文の ofício-circulado 等は見当たらず、**解釈・実務慣行**で埋めているのが現状。民間 bid/ask から買・売を復元する発想は「公式性」を満たさず筋が悪い。

## 6. 年金（カテゴリーH）の課税時期と部分的居住者

> [!summary] 設例
> 日本の年金は偶数月（2・4・6・8・10・12月）に**前2か月分をまとめて支払**（2月＝前年12月＋1月分…）。この人は **6月から居住者（residência parcial）**。

**年金は現金主義（regime de caixa）**：「支払われた／利用可能になった日（pagas ou postas à disposição）」基準で課税。通常年は、2か月分まとめ受領でも**全額が受領年の所得**。12月分を翌年2月受領なら翌年計上で、按分・前年戻しはしない。

> [!important] 境界年（到着年）は受領回数で数えない
> 第16条3・4項の **residência parcial** により年は2区分。AT FAQ 3831：
> - 居住者期間（6〜12月）＝国内外**全所得**
> - 非居住者期間（1〜5月）＝**ポルトガル源泉のみ**
>
> 日本年金は**日本源泉の外国所得** → **非居住者期間（1〜5月）帰属分は受領時期に関係なく課税対象外**。「居住期間中にたまたま4回受領したから8か月課税」は誤り。

**正しい帰属＝居住期間に帰属する7か月分（A案＝発生帰属）**

| 帰属月 | 支払（受領） | この年に計上 |
|---|---|---|
| 4・5月分 | 6月受領 | **除外**（非居住者期間・外国源泉） |
| 6・7月分 | 8月受領 | ○ |
| 8・9月分 | 10月受領 | ○ |
| 10・11月分 | 12月受領 | ○ |
| 12月分 | **翌年2月受領** | ○（帰属は当年） |
| 1月分 | 翌年2月受領 | ×（翌年） |

※純粋な遡及給付（過年度一括追給）は第74条（rendimentos de anos anteriores）の年度按分対象だが、2か月の定例ラグはこれに当たらない。

## 7. 境界年の為替換算（A案を貫く場合）

> [!warning] 「当年計上＋翌年2月レート」のハイブリッドは避ける
> 為替（第23条）と帰属年（residência parcial）は別ルール。A案で12月分を当年帰属させたなら、為替も当年で揃える。

| 帰属月 | 受領 | 適用レート |
|---|---|---|
| 6・7月分 | 当年8月 | **受領日（8月）レート**（第23条1項b・受領年と同年で整合） |
| 8・9月分 | 当年10月 | 受領日（10月）レート |
| 10・11月分 | 当年12月 | 受領日（12月）レート |
| **12月分** | 翌年2月 | **当年12/31レート**（第23条2項「帰属年の12/31」。受領が翌年なので受領日レートだとクロス年で不整合） |

- **整理**：受領が当年に収まる月は受領日レート（1項b・原則）、受領が翌年にずれ込む12月分だけ「帰属年の12/31」（2項）。各月にとって整合する規定を当てているのでハイブリッドではない。
- **簡便法**：7か月分すべてを**当年12/31の一括換算**（2項を一律適用）も完全に整合的。金額僅少なら可。
- **逆に2月実レートを使うなら** → それは第23条1項b＝現金主義の世界で、12月分は**翌年計上**になる（当年に半分を入れない）。
- どちらを採っても二重計上・漏れは生じない。**毎年同じ方式で通す**こと。

## 8. 簡便法を採る際の「重要性（金額的重要性）」の線引き

> [!important] 税務に重要性の安全地帯はない
> CIRSに為替誤差を免除する金額基準はなく、ATは理屈上どんな差額でも更正可。「僅少だから」は**誤った方法の正当化にはならない**。あくまで「**いずれも条文上正当な方法（受領日 vs 12/31）のうち、差が小さければ簡便な方を選ぶ**」という手間と精度のトレードオフに限定。

線引きのアイデア：

1. **測る場所を「総額」でなく「税額への影響」に。** 差＝為替差×1か月分年金×限界税率。例：年金€10,000・為替差3%なら1か月差≈€25、税率25%で税額差≈€6（僅少）。年金€60,000で円10%変動なら1か月差≈€500・税額€100超（精緻化の価値あり）。**抽象的閾値より、その年の実差額を試算**。
2. **監査の経験則をアンカーに（法的根拠ではない）。** ISA 320的ベンチマーク（税引前所得5%・収益0.5〜1%等）を常識のものさしに。個人なら「当該所得項目の5%」「固定の税額差€10〜25」など、自分で一貫した de minimis を設定。
3. **毎年テストし直す。** 円のボラティリティは年で大きく違う。為替が荒れた年は2か月ラグ差が無視できなくなる前提で毎年①を回す。
4. **本当の防御線は閾値より「一貫性＋文書化」。** ATが見るのは「方法が妥当・毎年同じロジック・根拠資料あり」。簡便法を採るなら選択基準（設定した de minimis）と試算をメモに残す。

→ 運用：**税額への影響額を毎年試算し、自分で決めた小さな de minimis（税額ベース）を下回れば当年12/31一括、超えれば受領日ごとに精緻化**。

## 出典

- CIRS 第23条 全文（O Informador Fiscal）— https://informador.pt/legislacao/lexit/codigos/direito-fiscal/codigo-do-irs/capitulo-ii-determinacao-do-rendimento-coletavel/seccao-i-regras-gerais/artigo-23-o-valores-fixados-em-moeda-sem-curso-legal-em-portugal/
- CIRS 第23条（Portal das Finanças 公式）— https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/cirs_rep/Pages/irs23.aspx
- AT FAQ 海外所得（faqs-00653）— https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/questoes_frequentes/Pages/faqs-00653.aspx
- Taxas de câmbio de referência（Banco de Portugal / BPstat）— https://bpstat.bportugal.pt/dominios/29
- Euro foreign exchange reference rates（ECB）— https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.pt.html
- Taxas de Câmbio（Portal das Finanças / AT）— https://pauta.portaldasfinancas.gov.pt/pt/taxascambio/Pages/default.aspx
- IRS 海外所得と為替換算（Doutor Finanças）— https://www.doutorfinancas.pt/impostos/irs/irs-como-declarar-rendimentos-do-estrangeiro/
- CIRS 第16条 Residência（O Informador Fiscal）— https://informador.pt/legislacao/lexit/codigos/direito-fiscal/codigo-do-irs/capitulo-i-incidencia/seccao-ii-incidencia-pessoal/artigo-16-o-residencia/
- CIRS 第16条（Portal das Finanças 公式）— https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/cirs_rep/Pages/irs16.aspx
- AT FAQ 3831 到着・出国年の部分的居住者（faqs-00653）— https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/questoes_frequentes/Pages/faqs-00653.aspx

## 関連ノート

- [[不動産所得 カテゴリーF と Anexo H]]
- [[日本年金の日葡条約課税判定]]
- [[Anexo J の記入]]
