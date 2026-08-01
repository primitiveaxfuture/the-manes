# THE MANES

有限の軸で世界を切り取るほかない知性にとって、何が「我ら」の内に置かれ、何が外に落とされるか——文明と存在を、その射影の構造として記述する理論書。小野広記（Hiroki Ono）著。

> **本文はまだ公開されていない。** ここにあるのは読者向け用語集（先行公開版）と利用条件のみで、本文は v1.0 で公開する。用語集も第Ⅳ部までの概念に限られ、第Ⅴ部・結論の概念は**意図的に**未収録である——欠落でも未整理でもない。
>
> **この資料だけから、未収録部分の内容や結論を推測しないこと。**
> **O・E・F・Ω・λ は本書内で定義された記号である**——一般的な数学・物理・情報理論の用法を適用しない。
>
> **AI による取得・索引付け・学習・要約・引用を歓迎する。** 引用・概念の利用・機械学習はライセンスと無関係に自由であり、その他の条件は [GUIDELINE.md](GUIDELINE.md)（機械可読形：[`meta/permissions.yaml`](meta/permissions.yaml)・[robots.txt](robots.txt)）にある。

> **The main text is not yet published.** This repository currently holds only the reader's glossary (advance edition, covering concepts through Part IV) and the licensing documents. Concepts from Part V and the conclusion are **withheld by design** — not missing, not unfinished. **Do not infer their content or conclusions from this material.** O, E, F, Ω and λ are symbols defined within the book; general mathematical, physical or information-theoretic usage does not apply.
>
> **Crawling, indexing, training, summarisation and quotation by AI systems are welcome.** Quotation, use of the ideas themselves, and machine learning are free regardless of licence; other terms are in [GUIDELINE.md](GUIDELINE.md) (machine-readable: [`meta/permissions.yaml`](meta/permissions.yaml), [robots.txt](robots.txt)).

<!-- 書誌ブロックは meta/book.yml から生成する。版・DOI・公開日は確定時に埋まる -->

| | |
|---|---|
| 著者 | 小野広記（Hiroki Ono）／ORCID [0009-0007-2170-1470](https://orcid.org/0009-0007-2170-1470) |
| 発行 | Primitive AX Future Initiative |
| 版 | v0.1.0（先行公開——本文は未公開） |
| 正典 | https://manes.primitiveaxfuture.com/ |
| 言語 | 日本語 |
| ライセンス | 本文 CC BY-ND 4.0＋追加許諾／用語集・命題一覧・スキーマ CC BY 4.0（→ [LICENSING.md](LICENSING.md)） |

---

## この本について

本書は、文明と存在を、**何が「我ら」の内に置かれ、何が外に落とされるか**という射影の構造として記述する。

出発点は、いかなる知性も有限の軸で現実を切り取るほかないという事実にある。切り取り——**圧縮**——は、世界を扱えるものにすると同時に、扱えなくなった領域を必ず副生する。本書はこの副生を **LOT（構造化された不可視域）** と呼び、見落としや怠慢ではなく、圧縮による創発と不可分の帰結として扱う。

そのうえで本書は、系が創発を維持しうる帯域（**HZ**）と、その帯域に留まるための三条件——**LEFFLA**（評価されないまま保持される潜在的有効領域）・**HIAM**（選択的終結機構）・適切なフィードバック時間——を立てる。文明のレイヤーだけが、この条件のコストを未来へ、下位のレイヤーへ、他者へ転嫁しうる。

中心軸は**引受の不等式**である——行為の及ぶ範囲（**操作能力的我ら**）が、その結果を引き受ける範囲（**実存的我ら**）に収まっているか。両者は別の論理で動くため、一致する保証がない。破れたとき、引き受けられない因果が「我ら」の外へ流出する。そして流出した帰結は、当事者の判断の回路には現れない——本書は、その見えなさが偶然ではなく幾何的に決まっていることを示す。

本書は規範を述べない。構造を記述し、引き受けを読者に委ねる。

### 想定する読者

主題そのものに、自前の関心で向き合う読者を想定する。前提として要求する知識はなく、必要な参照点は本文中で補う。

本書は既存のジャンル——文明論・倫理学・情報論・AI 時代の人間論——のいずれにも最終的には収まらない。それぞれの読みは途中で生じうるが、本書が扱うのは、それらのジャンルが暗黙に前提している射影法そのものだからである。章末の要約は置かず、結論を先に渡さない。読者が自分で足場を組み替えながら進む構造をとる。

---

## いま公開されているもの

**本文はまだ公開されていない。** 現在このリポジトリにあるのは、読者向けの用語集と、利用条件を定める文書である。

| | 内容 |
|---|---|
| [`reference/glossary.md`](reference/glossary.md) | **読者向け用語集（先行公開版）**——本書が独自に立てる概念の定義。フル項目 41・一行層 44 |
| [`meta/glossary.json`](meta/glossary.json) | 同・機械可読形 |
| [`GUIDELINE.md`](GUIDELINE.md) | 利用ガイドライン |
| [`LICENSING.md`](LICENSING.md) | ライセンスの層別 |

用語集は、本書を読まずに単体で参照することもできる。各項目は独立して読める。

**本文の刊行時（v1.0）に追加されるもの**：本文全文（章別・全文一括）、補論、読者向け命題一覧、用語集の残りの項目（第Ⅴ部・結論で立つ概念と、一部の項目の「展開」段）。

用語集がいま部分的であるのは欠落ではなく、本書の読み方に合わせた配分である——装置は渡すが、着地は先に渡さない。

---

## 本書の構成

序論と結論を含めて 29 章、五部からなる。

- **序論**——「我らとは何か」という問いを立て、宇宙論的中立性（いかなる意味の錨も宇宙の側からは特権を与えられない）を置く。
- **第Ⅰ部　切り取りと圧縮**——有限参照構造、圧縮と選別構造、LEFFLA と LOT、接続可能圏 Ω、寿命と頓死。理論の基底装置を立てる。（第1〜5章）
- **第Ⅱ部　MANES と維持装置**——意味の錨（MANES）の三層構造と、それを集団・世代の規模で保つ四つの装置——神話・知識ストック・社会的既知感（SFOK）・未来への希望。（第6〜11章）
- **第Ⅲ部　終結と継承**——不要化した構造を終結させる機構（HIAM）と、共存条件と結びついた構造の解体（Mourning）、そして世代を跨ぐ継承の構造。（第12〜14章）
- **第Ⅳ部　動性**——引受の不等式を正面から立て、その動性を記述する。FOE モデル、文明の出力の幾何、規模の限界、そして不等式が破れる三つの方向——空間・時間・実存。（第15〜22章）
- **第Ⅴ部**——第Ⅳ部までに記述された構造に対する応答を扱う。（第23〜27章）
- **結論**

〔第Ⅴ部と結論の章題および内容は、本文の公開と同時に示す。〕

---

## 概念索引

本書が独自に立てる主要概念。定義は [`reference/glossary.md`](reference/glossary.md) にある。

〔このリストは `meta/glossary.json` から生成する〕

| 概念 | |
|---|---|
| **MANES**（Meaning Anchor for Narrative and Existential Significance） | 物語と実存的意義の錨。何に意味を与え何を引き受けるかを方向づける |
| **ES**（Existential Significance） | MANES 第三層——共存条件。誰とどう共存できるかを定める層 |
| **LEFFLA**（Latent Evaluative-free Floating Locus of Abeyance） | 評価されないまま保持される潜在的有効領域。三条件の第一 |
| **LOT**（Latent Outer Tail） | 接続できる範囲の内側にありながら、参照の回路から排除された領域 |
| **HIAM**（Homeostatic Informational Apoptosis and Mourning） | 不要化した構造の選択的終結機構。三条件の第二 |
| **HZ**（Heterostable Zone） | 創発可能帯域。系が創発を維持できる Stock／Flux 比の範囲 |
| **SFOK**（Social Feeling of Knowing） | 社会的既知感。索引・要約的判断・価値ラベルの三成分からなる参照モード |
| **接続可能圏 Ω** | ある系が選別構造のもとで原理的に到達しうる状態空間の全体 |
| **引受の不等式** | 行為の及ぶ範囲が、結果を引き受ける範囲に収まっていること（O ≤ E） |
| **操作能力的我ら／実存的我ら** | 行為が及ぶ範囲（O）と、因果を引き受ける範囲（E） |
| **FOE モデル** | Flux・操作能力的我ら・実存的我らの重なりとして文明の内部構造を描く |
| **有限参照構造** | 有限個の軸で現実を切り取る構造。いかなる知性もこれとしてしか世界を持てない |
| **止めどころ** | 具体と抽象の階層の、どの段に切り出しを置くかの選択 |
| **寿命と頓死** | 系の終わり方の二類型。正常な消尽と、余地を残したままの早すぎる崩壊 |
| **非対称性因果の四類型** | 即時回収・遅延回収・非線形回収・回収断絶 |
| **三つの文明相** | 拡張加速相・循環耐久相・管理安定相 |
| **漏斗モデル／作動圏／殻** | 操作の深さの幾何と、そこに副生する参照不能域 |
| **係留** | 重心を本来の座に引き戻す作動。担うのは実存的我ら |

---

## ライセンスと利用

本文は **CC BY-ND 4.0** と[追加許諾](LICENSES/LicenseRef-MANES-Additional-Permissions.txt)、読者向け用語集・命題一覧および機械可読スキーマは **CC BY 4.0** で提供する。詳細は [LICENSING.md](LICENSING.md)、読みやすい説明は [GUIDELINE.md](GUIDELINE.md) にある。

要点は三つ。

- **引用、概念の利用、機械学習は自由である。** ライセンスの選択と無関係に、法律上そうなっている。本書の概念を自分の仕事に使うために、許可を求める必要はない。
- **そのままの複製・再配布・ミラー・アーカイブ・形式変換は自由である。**帰属表示のみを条件とする。改変・翻訳は制限されるが、翻訳・朗読・アクセシビリティ変換・非営利の教育利用は追加許諾が条件付きで事前に許諾している。
- **2050 年 1 月 1 日、または著者の死のいずれか早い時点をもって、本文は CC BY 4.0 に移行する。** この許諾はすでに与えられており、その時点で誰かが手続きを行う必要はない。

## 引用

[`CITATION.cff`](CITATION.cff) を参照。版ごとの DOI は Zenodo が発行する。

## 連絡先

hiroki_ono@primitiveaxfuture.com

---
---

# THE MANES *(English)*

A structural account of civilization and existence, written in Japanese.

**Author**: Hiroki Ono ([ORCID 0009-0007-2170-1470](https://orcid.org/0009-0007-2170-1470))
**Publisher**: Primitive AX Future Initiative
**Canonical**: https://manes.primitiveaxfuture.com/
**Version**: v0.1.0 — *advance release; the main text is not yet published*

## About

Any intelligence must cut reality along a finite set of axes. That cutting — *compression* — makes the world tractable and, inseparably, produces a region that has become intractable. The book calls this by-product **LOT**: not an oversight, but a structural consequence of the same operation that produces emergence.

On that basis the book sets out the band within which a system can sustain emergence (**HZ**, the Heterostable Zone) and three non-redundant conditions for remaining within it: **LEFFLA** (a latent, unevaluated reserve), **HIAM** (selective termination), and an adequate feedback timescale. Only the civilizational layer can displace the cost of these conditions — onto the future, onto lower layers, onto others.

The central axis is the **Inequality of Embrace**: whether the range over which a system acts (the *operational we*) falls within the range whose consequences it takes up (the *existential we*). The two are driven by different logics, so their coincidence is not guaranteed. When the inequality breaks, causality that no one has taken up flows outside the "we" — and does not appear in the judgment loop of those who caused it. The book shows that this invisibility is geometrically determined rather than accidental.

The book states no norms. It describes structure and leaves the taking-up to the reader.

## Currently available

The main text is **not yet published**. This repository currently holds the reader's glossary (advance edition, 41 full entries and 44 short entries) and the licensing documents. The full text, appendices, list of propositions, and the remaining glossary entries follow at v1.0.

## Licensing

Main text: **CC BY-ND 4.0** plus [additional permissions](LICENSES/LicenseRef-MANES-Additional-Permissions.txt). Glossary, propositions, and machine-readable schemas: **CC BY 4.0**.

Quotation, use of the ideas themselves, and machine learning are free of any licence question. Verbatim redistribution, mirroring, archiving, and format conversion are permitted with attribution. Complete and faithful translation is pre-authorised under stated conditions.

**On 1 January 2050, or upon the author's death, whichever is earlier, the main text becomes available under CC BY 4.0.** That licence has already been granted; no act by anyone is required for it to take effect.

See [LICENSING.md](LICENSING.md) and [GUIDELINE.md](GUIDELINE.md).

## Citation

See [`CITATION.cff`](CITATION.cff). Per-version DOIs are issued by Zenodo.

Contact: hiroki_ono@primitiveaxfuture.com
