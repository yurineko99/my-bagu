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
| Bug Id | Issue No | label |  Modify | Status | Type |Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- | 
| * 1 | [#3014](https://github.com/pyro-ppl/pyro/issues/3014) | bug | closed |  [bug] Memory leak on GPU | memory space problem |   18 Feb 2022 | committed on 30 Aug 2022 |
| * 2 | [#3068](https://github.com/pyro-ppl/pyro/issues/3068) | bug | closed |  Memory leak using TraceEnum_ELBO | memory space problem |   14 Apr 2022 | committed on 30 Aug 2022 |
| * 3 | [#253](https://github.com/pyro-ppl/pyro/issues/253) | bug | closed |  Incorrect batching in Categorical.sample(one_hot=False) | algorithm/accuracy |   13 Oct 2017 | committed on 19 Oct 2017 |
| * 4 | [#2615](https://github.com/pyro-ppl/pyro/issues/2615) | bug | closed |  [bug] Samples from LKJCorrCholesky have the wrong shape | algorithm/accuracy |   2 Sep 2020 | committed on 4 Sep 2020 |
| * 5 | [#2792](https://github.com/pyro-ppl/pyro/pull/2792) | bug | closed |  assert in JitTraceMeanField_ELBO throws TracerWarning | algorithm/accuracy |   4 Apr 2021 | committed on 6 Apr 2021 |
| * 6 | [#2870](https://github.com/pyro-ppl/pyro/issues/2870) | bug | closed |  guide.quantiles() shape issue | algorithm/accuracy |   12 Jun 2021 | committed on 12 Jun 2021 |
| * 7 | [#3018](https://github.com/pyro-ppl/pyro/issues/3018) | bug | closed |  [Support for Python 3.10] MCMC example in documentation does not work: AttributeError: __enter__ | algorithm/accuracy |   21 Feb 2022 | committed on 2 Jun 2022 |
| * 8 | [#3044](https://github.com/pyro-ppl/pyro/issues/3044) | bug、discussion | closed |  [bug] Pyroizing modules with PyroModule[model] does not work for all layers. | algorithm/accuracy |   15 Mar 2022 | committed on 24 Apr 2022 |
| * 9 | [#3100](https://github.com/pyro-ppl/pyro/issues/3100) | bug、duplicate、question | closed |  Excessive RAM consumption when coding mean field VI for LDA | algorithm/accuracy |   2 Jun 2022 | committed on 4 Jun 2022 |
| * 10 | [#2815](https://github.com/pyro-ppl/pyro/issues/2815) | bug | closed | intro SVI example has bug | algorithm/accuracy |  24 Apr 2021 | committed on 25 Apr 2021 |
| * 11 | [#2699](https://github.com/pyro-ppl/pyro/issues/2699) | bug、jit | closed | JitTraceEnum_ELBO fail with nvrtc: error: invalid value for --gpu-architecture (-arch) on RTX 3090 for pytorch 1.7.0 | Dimension/boundary-value |   19 Nov 2020 | committed on 30 Nov 2020 |
| * 12 | [#2935](https://github.com/pyro-ppl/pyro/issues/2935) | bug | closed | pyro.param cannot be set to CPU correctly | Dimension/boundary-value |   24 Sep 2021 | committed on 25 Sep 2021 |
| * 13 | [#2724](https://github.com/pyro-ppl/pyro/issues/2724) | bug | closed | contrib.funsor.infer.TraceEnum_ELBO can compute inaccurate elbo for certain guide-enumerated models | General numerical |   26 Dec 2020 | committed on 11 Mar 2021 |
| * 14 | [#2833](https://github.com/pyro-ppl/pyro/issues/2833) | bug | closed |  RuntimeError: cannot reshape tensor of 0 elements into shape [-1, 0, 0] because the unspecified dimension size -1 can be any value and is ambiguous | Language/translation |   5 May 2021 | committed on 5 May 2021 |
| * 15 | [#2886](https://github.com/pyro-ppl/pyro/issues/2886) | bug | closed |  RuntimeError: unsupported input to tensordot, got dims=0 | Language/translation |   27 Jun 2021 | committed on 2 Jul 2021 |
| * 16 | [#2980](https://github.com/pyro-ppl/pyro/issues/2980) | bug | closed |  pyro.render_model() fails to draw overlapping non-nested plates | Language/translation |   8 Dec 2021 | committed on 3 Mar 2022 |
| * 17 | [#3032](https://github.com/pyro-ppl/pyro/issues/3032) | bug、test | closed | [CI] torch.meshgrid having new default indexing in 1.10.0 (CI server currently installs 1.9.0)  | version issue |   17 Mar 2022 | committed on 10 Apr 2022 |
| * 18 | [#3046](https://github.com/pyro-ppl/pyro/issues/3046) | bug | closed | ome pyro.contrib.funsor tests are failing in torch==1.11.0  | version issue |   2 Mar 2022 | committed on 18 Mar 2022 |
| * 19 | [#2964](https://github.com/pyro-ppl/pyro/pull/2964) | bug、awaiting review | closed | Fix provenance of kwargs  | others |   9 Nov 2021 | committed on 12 Nov 2021 |
jdb78/pytorch-予測
https://github.com/jdb78/pytorch-forecasting
発行終了 29
| Bug Id | Issue No | label | Fixed | Modify| Status |Version|Type|Test|Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| * 1 | [#85](https://github.com/jdb78/pytorch-forecasting/issues/85) | bug、help wanted | closed | [content]() | Tensor Dimension Error When Applying TFT to Multiple Groups in Own Data |  | algorithmic/accuracy | [Test]() |  8 Oct 2020 | committed on 7 Sep 2021 |
| * 2 | [#182](https://github.com/jdb78/pytorch-forecasting/issues/182) | bug | closed | [content]() | Is there leakage? |  | algorithmic/accuracy | [Test]() |  1 Dec 2020 | committed on 2 Dec 2020 |
| * 3 | [#403](https://github.com/jdb78/pytorch-forecasting/issues/403) | bug | closed | [content]() | DeepAR Example fails on predict(): AttributeError: 'NoneType' object has no attribute 'device' |  | algorithmic/accuracy | [Test]() |  18 Mar 2021 | committed on 19 Mar 2021 |
| * 4 | [#122](https://github.com/jdb78/pytorch-forecasting/issues/122) | bug、enhancement、help wanted | closed | [content]() | Categorical encoding bug |  | Dimension/boundary-value | [Test]() |  22 Oct 2020 | committed on 30 Nov 2020 |
| * 5 | [#131](https://github.com/jdb78/pytorch-forecasting/issues/131) | bug | closed | [content]() | Bug .get_parameters() |  | Dimension/boundary-value | [Test]() |  31 Oct 2020 | committed on 31 Oct 2020 |
| * 6 | [#159](https://github.com/jdb78/pytorch-forecasting/issues/159) | bug | closed | [content]() | warnings.warn Type error: expected string or bytes-like object |  | Dimension/boundary-value | [Test]() |  18 Nov 2020 | committed on 21 Nov 2020 |
| * 7 | [#240](https://github.com/jdb78/pytorch-forecasting/issues/240) | bug | closed | [content]() | Type Error |  | General numerial | [Test]() |  5 Jan 2021 | committed on 7 Jan 2021 |
| * 8 | [#49](https://github.com/jdb78/pytorch-forecasting/issues/49) | bug、dependencies| closed | [content]() | Error saving checkpoint |  | Language/translation | [Test]() |  20 Sep 2020 | committed on 24 Sep 2020 |
| * 9 | [#79](https://github.com/jdb78/pytorch-forecasting/issues/79) | bug、enhancement　| closed | [content]() | Issues running TDS Stallion Example with W&B logger |  | Language/translation | [Test]() |  6 Oct 2020 | committed on 5 Nov 2020 |
| * 10 | [#114](https://github.com/jdb78/pytorch-forecasting/issues/114) | bug | closed | [content]() | 'TimeSeriesDataSet' object has no attribute 'args'  |  | Language/translation | [Test]() |  20 Oct 2020 | committed on 20 Oct 2020 |
| * 11 | [#135](https://github.com/jdb78/pytorch-forecasting/issues/135) | bug | closed | [content]() | Error passing CUDA tensor to nn.utils.rnn.pack_padded_sequence |  | Language/translation | [Test]() |  1 Nov 2020 | committed on 26 Jan 2021 |
| * 12 | [#365](https://github.com/jdb78/pytorch-forecasting/issues/365) | bug | closed | [content]() | Trying to predict on GPU. RuntimeError: All input tensors must be on the same device. Received cuda:0 and cpu |  | Language/translation | [Test]() |  24 Feb 2021 | committed on 18 Mar 2021 |
パイロppl/numpyro
URL https://github.com/pyro-ppl/numpyro/issues?q=label%3Abug+is%3Aclosed
発行終了 77
| Bug Id | Issue No | label | Fixed | Modify| Status |Version|Type|Test|Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| * 1 | [#146](https://github.com/pyro-ppl/numpyro/issues/146) | bug | closed | [content]() | binomial/multinomial tests fail with the new version of jax |  | Algorithmic/accuracy | [Test]() |  16 May 2019 | committed on 21 May 2019 |
| * 2 | [#154](https://github.com/pyro-ppl/numpyro/issues/154) | bug | closed | [content]() | NUTS doesn't converge on a stan model |  | Algorithmic/accuracy | [Test]() |  12 May 2019 | committed on 13 May 2019 |
| * 3 | [#241](https://github.com/pyro-ppl/numpyro/issues/241) | bug、enhancement | closed | [content]() | Handle dynamic support |  | Algorithmic/accuracy | [Test]() |  11 Jul 2019 | committed on 31 Jul 2019 |
| * 4 | [#2](https://github.com/pyro-ppl/numpyro/issues/2) | bug | closed | [content]() | Enable jit compilation in minipyro |  | Dimension/boundary-value | [Test]() |  21 Feb 2019 | committed on 21 Feb 2019 |
| * 5 | [#45](https://github.com/pyro-ppl/numpyro/issues/45) | bug | closed | [content]() | Disable generic args checking for discrete distributions |  | Dimension/boundary-value | [Test]() |  16 Mar 2019 | committed on 22 Mar 2019 |
| * 6 | [#76](https://github.com/pyro-ppl/numpyro/issues/76) | bug | closed | [content]() | Discrete distribution does not respect initial seed |  | Dimension/boundary-value | [Test]() |  2 Apr 2019 | committed on 3 Apr 2019 |
| * 7 | [#142](https://github.com/pyro-ppl/numpyro/issues/142) | bug、performance | closed | [content]() | standard_gamma not caching compiled function  |  | Dimension/boundary-value | [Test]() |  10 May 2019 | committed on 10 May 2019 |
| * 8 | [#249](https://github.com/pyro-ppl/numpyro/issues/249) | bug | closed | [content]() | HMC adaptation stuck at warmup phase due to step_size -> nan  |  | Dimension/boundary-value | [Test]() |  18 Jul 2019 | committed on 18 Jul 2019 |
| * 9 | [#112](https://github.com/pyro-ppl/numpyro/issues/112) | bug | closed | [content]() | Some custom primitives does not work with the newest version of jax |  | version error | [Test]() |  17 Apr 2019 | committed on 3 May 2019 |
| * 10 | [#216](https://github.com/pyro-ppl/numpyro/issues/216) | bug、performance | closed | [content]() | Timeseries model does not work with new version of lax.scan |  | version error | [Test]() |  21 Jun 2019 | committed on 15 Aug 2019 |
| * 11 | [#169](https://github.com/pyro-ppl/numpyro/issues/169) | bug | closed | [content]() | tqdm hangs when set_postfix_str with refresh=True |  | hangup | [Test]() |  26 Apr 2019 | committed on 30 May 2019 |
| * 12 | [#114](https://github.com/pyro-ppl/numpyro/issues/114) | bug | closed | [content]() | Make tscan jittable | others | version error | [Test]() |  18 Apr 2019 | committed on 20 Apr 2019 |


