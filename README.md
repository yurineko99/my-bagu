# 確率的プログラミング言語におけるバグ分類調査
## Label
**Bug Id**: Our own defined number  

**Issue No**：Number of bug we found :#XXXX  

**Tag**: Bug

**Fixed**: Fixed code link

**Modify**: For specific modifications, just provide a link 

**Status**: Open, Closed

**Version**: Updated version  

**Type**: Bug, feature  

**Test**: testing Code

**Issue Registered**: Time the bug was raised  

**Issue Resolved**: Time the bug was resovled  

| Bug Id | Issue No | Tag | Fixed | Modify| Status |Version|Type|Test|Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| * 1 | [#2205](https://github.com/pyro-ppl/pyro/issues/2205) | bug | closed | [content]() | MCMC は、単純なロジスティック回帰モデルに対して jit_compile を実行できません |  | algorithm/accuracy | [Test]() |  4 Dec 2019 | committed on 14 Dec 2019 |
| * 2 | [#2223](https://github.com/pyro-ppl/pyro/issues/2223) | bug | closed | [content]() | 離散推論に関する文書化されていない制限? | | algorithm/accuracy | [Test]() |  12 Dec 2019 | committed on 23 Dec 2019 |
| * 3 | [#2227](https://github.com/pyro-ppl/pyro/issues/2227) | bug | closed | [content]() | Student T テストが GPU で失敗する [バグ] | | algorithm/accuracy | [Test]() |  19 Dec 2019 | committed on 19 Dec 2019 |
| * 4 | [#2627](https://github.com/pyro-ppl/pyro/issues/2627) | bug | closed | [content]() | カスタム potential_fn を使用した HMC/NUTS の問題  | | algorithm/accuracy | [Test]() |  16 Sep 2020 | committed on 21 Sep 2020 |
| * 5 | [#2726](https://github.com/pyro-ppl/pyro/pull/2726) | bug、Pending review| closed | [content]() | vectorized_markov でリプレイが正しく動作するように | | algorithm/accuracy | [Test]() |  29 Dec 2020 | committed on 21 Sep 2020 |
| * 6 | [#2091](https://github.com/pyro-ppl/pyro/issues/2091) | bug | closed | [content]() | プログレスバー tqdm v4.36.1 と Pyro v0.4.1 で例外が発生し、複数のチェーンの進行状況が表示されるバグ | | dimension/boundary | [Test]() |  24 Oct 2019 | committed on 24 Oct 2019 |
| * 7 | [#2122](https://github.com/pyro-ppl/pyro/issues/2122) | bug | closed | [content]() | 非スカラーサイトの予測クラスが失敗する | | dimension/boundary | [Test]() |  6 Nov 2019 | committed on 7 Nov 2019 |
|* 8 | [#2226](https://github.com/pyro-ppl/pyro/pull/2226) | bug、Pending review | closed | [content]() | Pyro enum バグ修正 [WIP] | | dimension/boundary | [Test]() |  17 Dec 2019 | committed on 21 Dec 2019 |
| * 9 | [#2270](https://github.com/pyro-ppl/pyro/issues/2270) | bug | closed | [content]() | デルタ分布がコンポーネントとして使用されている場合、MaskedMixture 分布は正しく機能しません | | dimension/boundary | [Test]() |  20 jan 2020 | committed on 23 jan 2020 |
| * 10 | [#2366](https://github.com/pyro-ppl/pyro/issues/2366) | bug | closed | [content]() | [バグ] pyro.distributions.InverseGamma.sample が GPU で動作しない | | dimension/boundary | [Test]() |  14 Mar 2020 | committed on 14 Mar 2020 |
| * 11 | [#2384](https://github.com/pyro-ppl/pyro/pull/2384) | bug、Pending review | closed | [content]() | log_abs_det_jacobian必要に応じて再計算されます | | dimension/boundary | [Test]() |  26 Mar 2020 | committed on 27 Mar 2020 |
| * 12 | [#2699](https://github.com/pyro-ppl/pyro/issues/2699) | bug、jit | closed | [content]() | JitTraceEnum_ELBO が nvrtc: エラー: pytorch 1.7.0 の RTX 3090 で --gpu-architecture (-arch) の無効な値 #2699で失敗する | | dimension/boundary | [Test]() |  19 Nov 2020 | committed on 30 Nov 2020 |
| * 13 | [#2710](https://github.com/pyro-ppl/pyro/pull/2710) | bug、Pending review | closed | [content]() | マッチング分布でベーテ近似を安定化 | | dimension/boundary | [Test]() |  8 Dec 2020 | committed on 6 Aug 2021 |
| * 14 | [#2814](https://github.com/pyro-ppl/pyro/pull/2814) | bug、Pending review、ease of use | closed | [content]() | callable optim configs のパラメーター名を簡素化します。 | | dimension/boundary | [Test]() |  22 Apr 2021 | committed on 23 Apr 2021 |
| * 15 | [#2815](https://github.com/pyro-ppl/pyro/issues/2815) | bug | closed | [content]() | イントロ SVI の例にはバグ #2815があります | | dimension/boundary | [Test]() |  24 Apr 2021 | committed on 25 Apr 2021 |
| * 16 | [#2827](https://github.com/pyro-ppl/pyro/issues/2815) | bug | closed | [content]() | [バグ] パラメータが完全に使用されていない場合の CSIS エラー  | | dimension/boundary | [Test]() |  29 Apr 2021 | committed on 29 Apr 2021 |
| * 17 | [#2840](https://github.com/pyro-ppl/pyro/pull/2840) | bug、Pending review | closed | [content]() | latex pdf ドキュメントの数式を修正しました。  | | dimension/boundary | [Test]() |  13 May 2021 | committed on 17 May 2021 |
| * 18 | [#1988](https://github.com/pyro-ppl/pyro/pull/1988) | bug | closed | [content]() | 損失をマイナスにする  | | General numerical | [Test]() |  1 Aug 2019 | committed on 10 Aug 2019 |
| * 19 | [#2724](https://github.com/pyro-ppl/pyro/issues/2724) | bug | closed | [content]() | contrib.funsor.infer.TraceEnum_ELBO は、特定のガイド列挙モデルに対して不正確な elbo を計算できます  | | General numerical | [Test]() |  26 Dec 2020 | committed on 11 Mar 2021 |
| * 20 | [#2764](https://github.com/pyro-ppl/pyro/pull/2764) | bug、Pending review | closed | [content]() | MaskMessenger の bool と Tensor のビットごとの & を修正 | | Language/translation | [Test]() |  11 Feb 2021 | committed on 11 Feb 2021 |
| * 21 | [#2886](https://github.com/pyro-ppl/pyro/issues/2886) | bug | closed | [content]() | RuntimeError: tensordot への入力がサポートされていません。dims=0 を取得しました | | Language/translation | [Test]() |  27 Jun 2021 | committed on 2 Jul 2021 |
| * 22 | [#2971](https://github.com/pyro-ppl/pyro/issues/2971) | bug | closed | [content]() | RuntimeError: テンソル a (4928) のサイズは、非シングルトン次元 3 でテンソル b (4940) のサイズと一致する必要があります | | Language/translation | [Test]() |  20 Nov 2021 | committed on 25 Nov 2021 |
| * 23 | [#2688](https://github.com/pyro-ppl/pyro/issues/2688) | bug、documentation | closed | [content]() | [Doc] AutoIAFNormal と affine_autoregressive の間のパラメーター署名の不一致 | | documentation | [Test]() |  4 Nov 2020 | committed on 6 Nov 2020 |
| * 24 | [#2227](https://github.com/pyro-ppl/pyro/issues/2227) | bug | closed | [content]() | Student T テストが GPU で失敗する [バグ] | | system | [Test]() |  19 Dec 2019 | committed on 19 Dec 2019 |
| * 25 | [#2792](https://github.com/pyro-ppl/pyro/pull/2792) | bug | closed | [content]() | JitTraceMeanField_ELBO で assert すると TracerWarning #2792がスローされます | | system | [Test]() |  4 Apr 2021 | committed on 6 Apr 2021 |



