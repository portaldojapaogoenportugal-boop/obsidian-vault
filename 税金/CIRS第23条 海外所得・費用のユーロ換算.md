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

## 出典

- CIRS 第23条 全文（O Informador Fiscal）— https://informador.pt/legislacao/lexit/codigos/direito-fiscal/codigo-do-irs/capitulo-ii-determinacao-do-rendimento-coletavel/seccao-i-regras-gerais/artigo-23-o-valores-fixados-em-moeda-sem-curso-legal-em-portugal/
- CIRS 第23条（Portal das Finanças 公式）— https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/cirs_rep/Pages/irs23.aspx
- AT FAQ 海外所得（faqs-00653）— https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/questoes_frequentes/Pages/faqs-00653.aspx
- Taxas de câmbio de referência（Banco de Portugal / BPstat）— https://bpstat.bportugal.pt/dominios/29
- Euro foreign exchange reference rates（ECB）— https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.pt.html
- Taxas de Câmbio（Portal das Finanças / AT）— https://pauta.portaldasfinancas.gov.pt/pt/taxascambio/Pages/default.aspx
- IRS 海外所得と為替換算（Doutor Finanças）— https://www.doutorfinancas.pt/impostos/irs/irs-como-declarar-rendimentos-do-estrangeiro/

## 関連ノート

- [[不動産所得 カテゴリーF と Anexo H]]
- [[日本年金の日葡条約課税判定]]
- [[Anexo J の記入]]
