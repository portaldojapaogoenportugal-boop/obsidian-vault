---
title: 健康保険料控除とAnexo H
tags:
  - IRS
  - deducoes-a-coleta
  - despesas-de-saude
  - anexo-h
  - modelo-37
created: 2026-07-03
type: reference
---

# 健康保険料控除とAnexo H（一般論）

ポルトガルIRSにおける健康保険料（prémios de seguros de saúde）の控除と、Anexo H が必要になる条件の整理。

## 1. 控除の性質・率・上限

- **控除方式**: 税額控除（dedução à coleta）。所得から差し引く所得控除ではなく、算出税額（coleta）から直接差し引く。
- **控除率**: 支払額の **15%**。
- **上限**: **世帯あたり €1,000**（グローバル上限）。
  - 別々申告（separado）を選んだ夫婦は **1人あたり €500** に分割。
- この €1,000 は健康保険料**専用の枠ではない**。医療費全般（despesas de saúde）と**合算した共通上限**。
- CIRS 第78.º条7項の全体上限（総所得に応じた deduções à coleta の総枠）の**対象**（家庭一般費とは異なる扱い）。

> 根拠: **CIRS 第78.º-C条**（Dedução de despesas de saúde）

## 2. 控除対象となる保険料

- 健康リスク**のみ**を担保する保険料（第78.º-C条1項c、"exclusivamente riscos de saúde"）。
- 混合契約（死亡・傷害等もカバー）の場合、控除対象は健康リスク部分の保険料に限られ、区分できなければ全額不可。
- 保険会社等による補填分（comparticipação）は控除対象外。

## 3. 申告経路 ― 国内保険 vs 外国保険（最重要）

健康保険料は e-fatura の請求書認証システムには流れない（NIF付きfaturaが発生しないため）。ではどう控除を受けるか。**保険会社の所在**で分かれる。

### 国内（ポルトガル）の保険会社 → Anexo H は原則不要

- 国内保険会社は毎年**1月末**までに **Modelo 37** で保険料額を AT へ通報する**法的義務**がある。
- これにより pré-preenchida（事前記入済み申告書）に保険料が自動反映される。
- 契約者は**確認するだけ**でよく、Anexo H を手動で付ける必要はない。
- 確認方法: Portal das Finanças の「Consultar despesas para deduções à coleta」→「Saúde e seguros de saúde」→「Importâncias suportadas com prémios de seguros de saúde」欄。

### 外国（日本等）の保険会社 → Anexo H を手動で付ける必要あり

- 外国保険会社は Modelo 37 を提出しない。
- そのため保険料は e-fatura にも pré-preenchida にも**一切流れない**。
- 控除を取るには、**自分で Anexo H を追加**し、**Quadro 6C1** で手入力する必要がある。

## 4. Anexo H で手入力する場合の手順

1. 申告書に **Anexo H を追加**する（pré-preenchida に無い場合）。
2. **Quadro 6C1 の campo 01 に「Sim」**を付ける。
3. これにより **IRS Automático を放棄**することになり、以後 AT 通報値は使われない。よって**世帯全員・全カテゴリー（医療・教育・不動産・介護施設・家事使用人等）の金額を全部手入力**する必要が生じる（AT通報値と同額のものも含めて）。
4. 支出コードを選択。海外で支払った保険料・医療費には**「ポルトガル領域外」区分のコード**を使用（各ガイドでは Código 651／652 系。**正確なコードは AT の記入指示書で必ず確認**）。
5. 領収書等は **4年間保管**。

> 「一部だけの差し替え」は不可。campo 01=Sim にした時点で全額手入力が原則。

## 5. ポイントの要約

- 「健康保険料は e-fatura に流れないから Anexo H が必要」という理解は、**外国保険なら正しい**。
- ただし理由は「保険料だから」ではなく「**Modelo 37 通報がないから**」。
- 国内保険なら Modelo 37 で自動反映され、Anexo H は不要（確認のみ）。

## 参照条文・一次資料

- **CIRS 第78.º-C条** — Dedução de despesas de saúde（15%・上限€1,000・健康リスク限定・補填分除外）
- **CIRS 第78.º条7項** — deduções à coleta の全体上限
- Diário da República「Código do IRS」consolidado: https://diariodarepublica.pt/dr/legislacao-consolidada/lei/2014-70048167-70048268
- Portal das Finanças「Artigo 78.º-C」: https://info.portaldasfinancas.gov.pt/pt/informacao_fiscal/codigos_tributarios/cirs_rep/Pages/irs78c.aspx
- AT「Modelo 3 – Anexo H 記入指示書」PDF（コード・手順の一次資料）: https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/modelos_formularios/irs/documents/mod_3_anexo_h.pdf
- Portal das Finanças FAQ「Despesas Dedutíveis à coleta」: https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/questoes_frequentes/Pages/faqs-00061.aspx

## 参考解説（内容正確・実務手順つき）

- Santander「Seguro de saúde no IRS: como deduzir」: https://www.santander.pt/salto/seguro-saude-irs-deducao
- Doutor Finanças「Seguro de saúde no IRS: como declarar」: https://www.doutorfinancas.pt/seguros/seguro-de-saude/seguro-saude-irs-como-declarar/
- ACIS「Declaração Modelo 37」（保険会社の通報義務）: https://acis.org.pt/declaracao-modelo-37/
- Sage「Como preencher o quadro 6C do anexo H」: https://www.sage.com/pt-pt/blog/irs-modelo-3-anexo-h/
- Doutor Finanças「Anexo H do IRS, o que tenho de preencher?」（Anexo H は任意）: https://www.doutorfinancas.pt/impostos/anexo-h-do-irs-o-que-tenho-de-preencher/

## 関連ノート

- [[categoria-f-vs-anexo-h-efatura]]
- [[anexo-h-6c-override-efatura]]
- [[despesas-gerais-familiares-limites]]
- [[efatura-prazo-validacao-78B-5]]
