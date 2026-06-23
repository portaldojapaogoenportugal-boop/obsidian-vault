---
title: e-fatura の重要日程・Anexo H 上書き・IVA遅延コイマ対処
tags:
  - 税務
  - IRS
  - IVA
  - e-fatura
  - portugal
created: 2026-06-23
source: Portal das Finanças / Diário da República（一次情報で確認済み）
---

# e-fatura の重要日程・Anexo H 上書き・IVA遅延コイマ対処

> [!info] 根拠の確認レベル
> 期限と条文は **Diário da República（DL 49/2025 官報原文）** と **Portal das Finanças の Anexo H 公式記入要領** で裏取り済み。

---

## 1. e-fatura 関連の重要日程（前年N年 → 翌年N+1年に申告）

| 時期 | 内容 | 根拠 |
|---|---|---|
| 通年（翌月5日まで） | 事業者がインボイスを AT へ電子通信 | DL 198/2012 art.3.º |
| **〜2月末日** | 納税者がインボイスを検証（pendente の業種分類・確認） | **CIRS 78.º-B/5** |
| 3月16日〜31日 | AT 算定の控除額が公表、誤りは reclamação（異議申立） | CIRS 78.º-B 6・7項 |

### 検証期限は「2月25日」ではなく「2月末日」
- **CIRS 第78.º-B条 第5項**の現行文言：
  > 「O valor das deduções à coleta é apurado pela AT com base nas faturas que lhe forem comunicadas, por via eletrónica, **até ao final do mês de fevereiro** do ano seguinte ao da sua emissão...」
- **Decreto-Lei n.º 49/2025（2025年3月27日、施行 2025年7月1日）**で旧「até 25 de fevereiro」→「até ao final do mês de fevereiro」に改正。
- この改正は 78.º-B だけでなく **第12.º・22.º・78.º・78.º-C・78.º-D・119.º 条等を一括で「2月末日」に統一**（官報前文に "harmonização... que passam para o final do mês de fevereiro"）。
- ⚠️ 旧資料や検索AI要約に残る「2月25日」は**旧文言（誤り）**。2月末が週末の年は翌営業日に繰り延べ（例：**2026年は3月2日**）。

---

## 2. 3月31日後に控除額を変える唯一の手段 ＝ Anexo H Quadro 6C

3月31日（reclamação 締切）以降、e-fatura ポータル上ではもう前年分を操作できない。
しかし申告書（Modelo 3）の **Anexo H Quadro 6C** で上書きが可能。

### 仕組み
- Quadro 6C 冒頭の確認文：
  > 「Em alternativa aos valores comunicados à AT, pretende declarar as despesas de saúde, de formação e educação, os encargos...?」
- **campo 02（não）= 既定**：AT の e-fatura 算定値を使用。
- **campo 01（sim）**：e-fatura を無視し、手入力額のみで算定。

### campo 01（sim）を選ぶ場合の条件（公式記入要領で確認）
- **世帯全員・全カテゴリーの経費をすべて手入力**（AT通知値と同額のものも含め全件）。
- 一部だけ・一人だけの修正は**不可**。「apenas serão consideradas as despesas inscritas neste quadro」。
- 証憑の保管が前提。

> [!important] 重要な構造
> この確認文は **Anexo H 内にしか存在せず、Rosto には無い**。
> よって普段 Anexo H を出さない人（IRS automático 等）でも、上書きしたいなら通常申告に切替えて **Anexo H を追加しないと選択肢自体が画面に出てこない**。

### 別ルートの控除（混同注意）
- 不動産の賃貸経費 → **Anexo F**（Cat.F の実額経費。deduções à coleta ではない）。
- 健康保険料 → **Modelo 37 → Anexo H** に自動反映（e-fatura の Outros ではない）。

---

## 3. IVA 申告遅延の coima（€25 が支払えない場合）

「支払」ボタンが反応しない主な原因と対処。

### 主な原因
1. **支払参照（guia / referência / DUC）の有効期限切れ** ← 最も多い。期限切れで参照が無効化しボタンが反応しない。
2. **execução fiscal（強制徴収）への移行** ← 任意納付期間経過後。通常の支払画面からは払えなくなる。

### 対処の手順（Portal das Finanças）
1. **Cidadãos → Serviços → Pagamentos / 「A minha situação fiscal – Pagamentos」** で当該 coima のステータス確認。
2. そこで **新しい支払文書（emitir documento de pagamento / nova referência）を再発行** → Multibanco・homebanking・CTT・Finanças窓口で納付。
3. **「Situação Fiscal → Citações / Execuções Fiscais」** に出ていれば execução fiscal 移行済み → その画面から新DUC（juros + custas 加算の可能性）を発行。
4. 解決しなければ **e-balcão**（Atendimento → e-balcão）／**CAT 217 206 707**／管轄 **Serviço de Finanças**。

> [!warning] 放置すると juros de mora・custas が加算される。早めに参照を取り直す。

---

## 参考サイト

### 公式・一次情報
- Portal das Finanças（Pagamentos / A minha situação fiscal / e-balcão）— https://www.portaldasfinancas.gov.pt
- Diário da República — Decreto-Lei n.º 49/2025 全文 — https://dre.tretas.org/dre/6118455/decreto-lei-49-2025-de-27-de-marco
- Portal das Finanças — Modelo 3 Anexo H 記入要領（PDF）— https://info.portaldasfinancas.gov.pt/pt/apoio_contribuinte/modelos_formularios/irs/documents/mod_3_anexo_h.pdf
- RGIT（coima の額・減額の根拠：第29.º・30.º条等）

### 解説サイト
- Doutor Finanças — Atraso no pagamento de IVA — https://www.doutorfinancas.pt/impostos/pagamento-de-iva-com-atraso/
- OCC — Parecer técnico RGIT — https://www.occ.pt/pt-pt/noticias/parecer-tecnico-rgit
- Santander Salto — Prazos IRS 2026 — https://www.santander.pt/salto/prazos-irs-2026

---

## 関連ノート（Obsidian リンク用）
- [[Anexo F・Cat.F 不動産経費]]
- [[健康保険料 Modelo 37・Anexo H]]
- [[四半期申告 Declaração Trimestral 期限]]
