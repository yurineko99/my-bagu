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

| Bug Id | Issue No | label | Fixed | Modify| Status |Version|Type|Test|Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| * 1 | [#2205](https://github.com/pyro-ppl/pyro/issues/2205) | bug | closed | [content]() | MCMC は、単純なロジスティック回帰モデルに対して jit_compile を実行できません |  | algorithm/accuracy | [Test]() |  4 Dec 2019 | committed on 14 Dec 2019 |
| * 2 | [#2081](https://github.com/pyro-ppl/pyro/pull/2081) | bug、Pending review | closed | [content]() | 多変量分布に対する autoguide の init_to_median 戦略を修正します。 |  | algorithm/accuracy | [Test]() |  23 Oct 2019 | committed on 23 Oct 2019 |
| * 3 | [#2223](https://github.com/pyro-ppl/pyro/issues/2223) | bug | closed | [content]() | 離散推論に関する文書化されていない制限? | | algorithm/accuracy | [Test]() |  12 Dec 2019 | committed on 23 Dec 2019 |
| * 4 | [#2227](https://github.com/pyro-ppl/pyro/issues/2227) | bug | closed | [content]() | Student T テストが GPU で失敗する [バグ] | | algorithm/accuracy | [Test]() |  19 Dec 2019 | committed on 19 Dec 2019 |
| * 5 | [#2272](https://github.com/pyro-ppl/pyro/issues/2272) | bug、high priority | closed | [content]() | [バグ] Pyro 1.2.0 の時点で num_chains>1 を使用すると、MCMC の実行で例外がスローされます。 | | algorithm/accuracy | [Test]() |  21 Jan 2020 | committed on 22 Jan 2020 |
| * 6 | [#2317](https://github.com/pyro-ppl/pyro/issues/2317) | bug、enhancement | closed | [content]() | NeuTraReparam が想定どおりに機能しない: AssertionError がスローされる | | algorithm/accuracy | [Test]() |  20 Feb 2020 | committed on 5 Mar 2020 |
| * 7 | [#2627](https://github.com/pyro-ppl/pyro/issues/2627) | bug | closed | [content]() | カスタム potential_fn を使用した HMC/NUTS の問題  | | algorithm/accuracy | [Test]() |  16 Sep 2020 | committed on 21 Sep 2020 |
| * 8 | [#2726](https://github.com/pyro-ppl/pyro/pull/2726) | bug、Pending review| closed | [content]() | vectorized_markov でリプレイが正しく動作するように | | algorithm/accuracy | [Test]() |  29 Dec 2020 | committed on 21 Sep 2020 |
| * 9 | [#2091](https://github.com/pyro-ppl/pyro/issues/2091) | bug | closed | [content]() | プログレスバー tqdm v4.36.1 と Pyro v0.4.1 で例外が発生し、複数のチェーンの進行状況が表示されるバグ | | dimension/boundary | [Test]() |  24 Oct 2019 | committed on 24 Oct 2019 |
| * 10 | [#2122](https://github.com/pyro-ppl/pyro/issues/2122) | bug | closed | [content]() | 非スカラーサイトの予測クラスが失敗する | | dimension/boundary | [Test]() |  6 Nov 2019 | committed on 7 Nov 2019 |
| * 11 | [#2226](https://github.com/pyro-ppl/pyro/pull/2226) | bug、Pending review | closed | [content]() | Pyro enum バグ修正 [WIP] | | dimension/boundary | [Test]() |  17 Dec 2019 | committed on 21 Dec 2019 |
| * 12 | [#2270](https://github.com/pyro-ppl/pyro/issues/2270) | bug | closed | [content]() | デルタ分布がコンポーネントとして使用されている場合、MaskedMixture 分布は正しく機能しません | | dimension/boundary | [Test]() |  20 jan 2020 | committed on 23 jan 2020 |
| * 13 | [#2366](https://github.com/pyro-ppl/pyro/issues/2366) | bug | closed | [content]() | [バグ] pyro.distributions.InverseGamma.sample が GPU で動作しない | | dimension/boundary | [Test]() |  14 Mar 2020 | committed on 14 Mar 2020 |
| * 14 | [#2384](https://github.com/pyro-ppl/pyro/pull/2384) | bug、Pending review | closed | [content]() | log_abs_det_jacobian必要に応じて再計算されます | | dimension/boundary | [Test]() |  26 Mar 2020 | committed on 27 Mar 2020 |
| * 15 | [#2607](https://github.com/pyro-ppl/pyro/issues/2607) | bug | closed | [content]() | サンプリング カテゴリカルは 2 つのサンプルの後に終了します [バグですが、おそらくユーザー エラーです]  | | dimension/boundary | [Test]() |  20 Aug 2020 | committed on 1 Sep 2020 |
| * 16 | [#2678](https://github.com/pyro-ppl/pyro/issues/2678) | bug | closed | [content]() | Elbo.compute_marginals は、基本モデルのエラーをスローします | | dimension/boundary | [Test]() |  21 Oct 2020 | committed on 23 Oct 2020 |
| * 17 | [#2699](https://github.com/pyro-ppl/pyro/issues/2699) | bug、jit | closed | [content]() | JitTraceEnum_ELBO が nvrtc: エラー: pytorch 1.7.0 の RTX 3090 で --gpu-architecture (-arch) の無効な値 #2699で失敗する | | dimension/boundary | [Test]() |  19 Nov 2020 | committed on 30 Nov 2020 |
| * 18 | [#2710](https://github.com/pyro-ppl/pyro/pull/2710) | bug、Pending review | closed | [content]() | マッチング分布でベーテ近似を安定化 | | dimension/boundary | [Test]() |  8 Dec 2020 | committed on 6 Aug 2021 |
| * 19 | [#2814](https://github.com/pyro-ppl/pyro/pull/2814) | bug、Pending review、ease of use | closed | [content]() | callable optim configs のパラメーター名を簡素化します。 | | dimension/boundary | [Test]() |  22 Apr 2021 | committed on 23 Apr 2021 |
| * 20 | [#2815](https://github.com/pyro-ppl/pyro/issues/2815) | bug | closed | [content]() | イントロ SVI の例にはバグ #2815があります | | dimension/boundary | [Test]() |  24 Apr 2021 | committed on 25 Apr 2021 |
| * 21 | [#2827](https://github.com/pyro-ppl/pyro/issues/2815) | bug | closed | [content]() | [バグ] パラメータが完全に使用されていない場合の CSIS エラー  | | dimension/boundary | [Test]() |  29 Apr 2021 | committed on 29 Apr 2021 |
| * 22 | [#2840](https://github.com/pyro-ppl/pyro/pull/2840) | bug、Pending review | closed | [content]() | latex pdf ドキュメントの数式を修正しました。  | | dimension/boundary | [Test]() |  13 May 2021 | committed on 17 May 2021 |
| * 23 | [#1988](https://github.com/pyro-ppl/pyro/pull/1988) | bug | closed | [content]() | 損失をマイナスにする  | | General numerical | [Test]() |  1 Aug 2019 | committed on 10 Aug 2019 |
| * 24 | [#2724](https://github.com/pyro-ppl/pyro/issues/2724) | bug | closed | [content]() | contrib.funsor.infer.TraceEnum_ELBO は、特定のガイド列挙モデルに対して不正確な elbo を計算できます  | | General numerical | [Test]() |  26 Dec 2020 | committed on 11 Mar 2021 |
| * 25 | [#2641](https://github.com/pyro-ppl/pyro/pull/2641) | bug、Pending review | closed | [content]() | MaskMessenger の bool と Tensor のビットごとの & を修正 | | Language/translation | [Test]() |  25 Sep 2020 | committed on 6 Oct 2020 |
| * 26 | [#2764](https://github.com/pyro-ppl/pyro/pull/2764) | bug、Pending review | closed | [content]() | DistributionMeta の循環インポートを修正 | | Language/translation | [Test]() | 11 Feb 2021  | committed on 11 Feb 2021 |
| * 27 | [#2886](https://github.com/pyro-ppl/pyro/issues/2886) | bug | closed | [content]() | RuntimeError: tensordot への入力がサポートされていません。dims=0 を取得しました | | Language/translation | [Test]() |  27 Jun 2021 | committed on 2 Jul 2021 |
| * 28 | [#2971](https://github.com/pyro-ppl/pyro/issues/2971) | bug | closed | [content]() | RuntimeError: テンソル a (4928) のサイズは、非シングルトン次元 3 でテンソル b (4940) のサイズと一致する必要があります | | Language/translation | [Test]() |  20 Nov 2021 | committed on 25 Nov 2021 |
| * 29 | [#2608](https://github.com/pyro-ppl/pyro/issues/2608) | bug、documentation | closed | [content]() | Pyro ドキュメントが Google に表示されなくなりました | | documentation | [Test]() |  20 Aug 2020 | committed on 20 Aug 2020 |
| * 30 | [#2688](https://github.com/pyro-ppl/pyro/issues/2688) | bug、documentation | closed | [content]() | [Doc] AutoIAFNormal と affine_autoregressive の間のパラメーター署名の不一致 | | documentation | [Test]() |  4 Nov 2020 | committed on 6 Nov 2020 |
| * 31 | [#2227](https://github.com/pyro-ppl/pyro/issues/2227) | bug | closed | [content]() | Student T テストが GPU で失敗する [バグ] | | system | [Test]() |  19 Dec 2019 | committed on 19 Dec 2019 |
| * 32 | [#2792](https://github.com/pyro-ppl/pyro/pull/2792) | bug | closed | [content]() | JitTraceMeanField_ELBO で assert すると TracerWarning #2792がスローされます | | system | [Test]() |  4 Apr 2021 | committed on 6 Apr 2021 |
| * 33 | [#3014](https://github.com/pyro-ppl/pyro/issues/3068) | bug | closed | [content]() | TraceEnum_ELBO を使用したメモリリーク | | memory leak | [Test]() |  18 Feb 2022 | committed on 30 Aug 2022 |
| * 34 | [#3068](https://github.com/pyro-ppl/pyro/issues/3068) | bug | closed | [content]() | TraceEnum_ELBO を使用したメモリリーク | | memory leak | [Test]() |  14 Apr 2022 | committed on 30 Aug 2022 |
| * 35 | [#2034](https://github.com/pyro-ppl/pyro/issues/2034) | bug | closed | [content]() | Pyro pytorch 1.2. 互換性 | | compatibility | [Test]() |  10 Sep 2019 | committed on 11 Sep 2019 |
| * 36 | [#2390](https://github.com/pyro-ppl/pyro/issues/2390) | bug | closed | [content]() | PyroModule は torch.nn.RNN と互換性がありません | | compatibility | [Test]() |  30 Mar 2021 | committed on 31 Mar 2020 |
| * 37 | [#2746](https://github.com/pyro-ppl/pyro/pull/2746) | bug | closed | [content]() | TransformReparam を .to_event() と互換性を持たせる | | compatibility | [Test]() |  22 Jan 2021 | committed on 23 Jan 2021 |
| Bug Id | Issue No | label |  Modify| Status | Type |Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- |
| * 1 | [#3014](https://github.com/pyro-ppl/pyro/issues/3014) | bug | closed |  [bug] Memory leak on GPU | memory space problem |   18 Feb 2022 | committed on 30 Aug 2022 |


