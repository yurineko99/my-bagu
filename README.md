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
| * 1 | [#2205](https://github.com/pyro-ppl/pyro/issues/2205) | bug | closed | [content]() | MCMC cannot jit_compile for a simple logistic regression model |  | algorithm/accuracy | [Test]() |  4 Dec 2019 | committed on 14 Dec 2019 |
| * 2 | [#2081](https://github.com/pyro-ppl/pyro/pull/2081) | bug、Pending review | closed | [content]() | Fix autoguide's init_to_median strategy for multivariate distributions |  | algorithm/accuracy | [Test]() |  23 Oct 2019 | committed on 23 Oct 2019 |
| * 3 | [#2223](https://github.com/pyro-ppl/pyro/issues/2223) | bug | closed | [content]() | Undocumented restrictions on discrete inference? | | algorithm/accuracy | [Test]() |  12 Dec 2019 | committed on 23 Dec 2019 |
| * 4 | [#2227](https://github.com/pyro-ppl/pyro/issues/2227) | bug | closed | [content]() | Student T tests fail on GPU [bug] | | algorithm/accuracy | [Test]() |  19 Dec 2019 | committed on 19 Dec 2019 |
| * 5 | [#2272](https://github.com/pyro-ppl/pyro/issues/2272) | bug、high priority | closed | [content]() | [bug] MCMC run throws exception when using num_chains>1 as of Pyro 1.2.0. | | algorithm/accuracy | [Test]() |  21 Jan 2020 | committed on 22 Jan 2020 |
| * 6 | [#2317](https://github.com/pyro-ppl/pyro/issues/2317) | bug、enhancement | closed | [content]() | NeuTraReparam does not work as supposed: AssertionError thrown | | algorithm/accuracy | [Test]() |  20 Feb 2020 | committed on 5 Mar 2020 |
| * 7 | [#2627](https://github.com/pyro-ppl/pyro/issues/2627) | bug | closed | [content]() | Problem in HMC/NUTS with custom potential_fn  | | algorithm/accuracy | [Test]() |  16 Sep 2020 | committed on 21 Sep 2020 |
| * 8 | [#2726](https://github.com/pyro-ppl/pyro/pull/2726) | bug、Pending review| closed | [content]() | Make replay work correctly with vectorized_markov | | algorithm/accuracy | [Test]() |  29 Dec 2020 | committed on 21 Sep 2020 |
| * 9 | [#2091](https://github.com/pyro-ppl/pyro/issues/2091) | bug | closed | [content]() | Progressbar Bug with tqdm v4.36.1 and Pyro v0.4.1 leading to exception, displaying progress for multiple chains | | dimension/boundary | [Test]() |  24 Oct 2019 | committed on 24 Oct 2019 |
| * 10 | [#2122](https://github.com/pyro-ppl/pyro/issues/2122) | bug | closed | [content]() | Predictive class fails for non-scalar sites | [Test]() |  6 Nov 2019 | committed on 7 Nov 2019 |
| * 11 | [#2226](https://github.com/pyro-ppl/pyro/pull/2226) | bug、Pending review | closed | [content]() | Pyro enum bugfix [WIP] | | dimension/boundary | [Test]() |  17 Dec 2019 | committed on 21 Dec 2019 |
| * 12 | [#2270](https://github.com/pyro-ppl/pyro/issues/2270) | bug | closed | [content]() | MaskedMixture distribution doesn't work properly when Delta distribution is used as a component | | dimension/boundary | [Test]() |  20 jan 2020 | committed on 23 jan 2020 |
| * 13 | [#2366](https://github.com/pyro-ppl/pyro/issues/2366) | bug | closed | [content]() | [bug] pyro.distributions.InverseGamma.sample does not work on GPU | | dimension/boundary | [Test]() |  14 Mar 2020 | committed on 14 Mar 2020 |
| * 14 | [#2384](https://github.com/pyro-ppl/pyro/pull/2384) | bug、Pending review | closed | [content]() | log_abs_det_jacobian will be recalculated when necessary | | dimension/boundary | [Test]() |  26 Mar 2020 | committed on 27 Mar 2020 |
| * 15 | [#2607](https://github.com/pyro-ppl/pyro/issues/2607) | bug | closed | [content]() | Sampling Categorical Quits After Two Samples [bug, but probably user error]  | | dimension/boundary | [Test]() |  20 Aug 2020 | committed on 1 Sep 2020 |
| * 16 | [#2678](https://github.com/pyro-ppl/pyro/issues/2678) | bug | closed | [content]() | Elbo.compute_marginals throws an error for basic model | | dimension/boundary | [Test]() |  21 Oct 2020 | committed on 23 Oct 2020 |
| * 17 | [#2699](https://github.com/pyro-ppl/pyro/issues/2699) | bug、jit | closed | [content]() | JitTraceEnum_ELBO fail with nvrtc: error: invalid value for --gpu-architecture (-arch) on RTX 3090 for pytorch 1.7.0 | | dimension/boundary | [Test]() |  19 Nov 2020 | committed on 30 Nov 2020 |
| * 18 | [#2710](https://github.com/pyro-ppl/pyro/pull/2710) | bug、Pending review | closed | [content]() | Stabilize Bethe approximation in matching distributions | | dimension/boundary | [Test]() |  8 Dec 2020 | committed on 6 Aug 2021 |
| * 19 | [#2814](https://github.com/pyro-ppl/pyro/pull/2814) | bug、Pending review、ease of use | closed | [content]() | Simplify param names in callable optim configs | | dimension/boundary | [Test]() |  22 Apr 2021 | committed on 23 Apr 2021 |
| * 20 | [#2815](https://github.com/pyro-ppl/pyro/issues/2815) | bug | closed | [content]() | intro SVI example has bug | | dimension/boundary | [Test]() |  24 Apr 2021 | committed on 25 Apr 2021 |
| * 21 | [#2827](https://github.com/pyro-ppl/pyro/issues/2827) | bug | closed | [content]() | [bug] CSIS error when parameters are not fully used  | | dimension/boundary | [Test]() |  29 Apr 2021 | committed on 29 Apr 2021 |
| * 22 | [#2840](https://github.com/pyro-ppl/pyro/pull/2840) | bug、Pending review | closed | [content]() | Fix math expressions for latex pdf docs.  | | dimension/boundary | [Test]() |  13 May 2021 | committed on 17 May 2021 |
| * 23 | [#1988](https://github.com/pyro-ppl/pyro/pull/1988) | bug | closed | [content]() | Make Loss negative (#1982)  | | General numerical | [Test]() |  1 Aug 2019 | committed on 10 Aug 2019 |
| * 24 | [#2724](https://github.com/pyro-ppl/pyro/issues/2724) | bug | closed | [content]() | contrib.funsor.infer.TraceEnum_ELBO can compute inaccurate elbo for certain guide-enumerated models  | | General numerical | [Test]() |  26 Dec 2020 | committed on 11 Mar 2021 |
| * 25 | [#2641](https://github.com/pyro-ppl/pyro/pull/2641) | bug、Pending review | closed | [content]() | Fix cyclic import in DistributionMeta | | Language/translation | [Test]() |  25 Sep 2020 | committed on 6 Oct 2020 |
| * 26 | [#2764](https://github.com/pyro-ppl/pyro/pull/2764) | bug、Pending review | closed | [content]() | Fix bitwise & for bool and Tensor in MaskMessenger | | Language/translation | [Test]() | 11 Feb 2021  | committed on 11 Feb 2021 |
| * 27 | [#2886](https://github.com/pyro-ppl/pyro/issues/2886) | bug | closed | [content]() | RuntimeError: unsupported input to tensordot, got dims=0 | | Language/translation | [Test]() |  27 Jun 2021 | committed on 2 Jul 2021 |
| * 28 | [#2971](https://github.com/pyro-ppl/pyro/issues/2971) | bug | closed | [content]() | RuntimeError: The size of tensor a (4928) must match the size of tensor b (4940) at non-singleton dimension 3 | | Language/translation | [Test]() |  20 Nov 2021 | committed on 25 Nov 2021 |
| * 29 | [#2608](https://github.com/pyro-ppl/pyro/issues/2608) | bug、documentation | closed | [content]() | Pyro docs no longer show up on Google | | documentation | [Test]() |  20 Aug 2020 | committed on 20 Aug 2020 |
| * 30 | [#2688](https://github.com/pyro-ppl/pyro/issues/2688) | bug、documentation | closed | [content]() | [Doc] Inconsistent of param signature between AutoIAFNormal and affine_autoregressive | | documentation | [Test]() |  4 Nov 2020 | committed on 6 Nov 2020 |
| * 31 | [#2227](https://github.com/pyro-ppl/pyro/issues/2227) | bug | closed | [content]() | Student T tests fail on GPU [bug]  | | system | [Test]() |  19 Dec 2019 | committed on 19 Dec 2019 |
| * 32 | [#2792](https://github.com/pyro-ppl/pyro/pull/2792) | bug | closed | [content]() | assert in JitTraceMeanField_ELBO throws TracerWarning | | system | [Test]() |  4 Apr 2021 | committed on 6 Apr 2021 |
| * 33 | [#3014](https://github.com/pyro-ppl/pyro/issues/3068) | bug | closed | [content]() | Memory leak using TraceEnum_ELBO | [Test]() |  18 Feb 2022 | committed on 30 Aug 2022 |
| * 34 | [#3068](https://github.com/pyro-ppl/pyro/issues/3068) | bug | closed | [content]() | Memory leak using TraceEnum_ELBO | | memory leak | [Test]() |  14 Apr 2022 | committed on 30 Aug 2022 |
| * 35 | [#2034](https://github.com/pyro-ppl/pyro/issues/2034) | bug | closed | [content]() | pyro pytorch 1.2. compatibility | | compatibility | [Test]() |  10 Sep 2019 | committed on 11 Sep 2019 |
| * 36 | [#2390](https://github.com/pyro-ppl/pyro/issues/2390) | bug | closed | [content]() | PyroModule incompatible with torch.nn.RNN | | compatibility | [Test]() |  30 Mar 2021 | committed on 31 Mar 2020 |
| * 37 | [#2746](https://github.com/pyro-ppl/pyro/pull/2746) | bug | closed | [content]() | Make TransformReparam compatible with .to_event() | | compatibility | [Test]() |  22 Jan 2021 | committed on 23 Jan 2021 |
| Bug Id | Issue  | label |  Modify | Status | Type |Issue Registered | Issue Resolved |
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
| * 1 | [#146](https://github.com/pyro-ppl/numpyro/issues/146) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/147/files) | binomial/multinomial tests fail with the new version of jax |  | Algorithmic/accuracy | [Test]() |  16 May 2019 | committed on 21 May 2019 |
| * 2 | [#241](https://github.com/pyro-ppl/numpyro/issues/241) | bug、enhancement | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/237/files) | Handle dynamic support |  | Algorithmic/accuracy | [Test]() |  11 Jul 2019 | committed on 31 Jul 2019 |
| * 3 | [#307](https://github.com/pyro-ppl/numpyro/issues/307) | bug | closed | [bug fix]() | Sequential chains in MCMC is broken |  | Algorithmic/accuracy | [Test]() |  29 Aug 2019 | committed on 29 Aug 2019 |
| * 4 | [#333](https://github.com/pyro-ppl/numpyro/issues/333) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/332/files) | Problem with sample_shape |  | Algorithmic/accuracy | [Test]() |  11 Sep 2019 | committed on 12 Sep 2019 |
| * 5 | [#1012](https://github.com/pyro-ppl/numpyro/issues/1012) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1013/files) | Error using AutoDiagonalNormal with SVI + Predictive |  | Algorithmic/accuracy | [Test]() |  19 Apr 2021 | committed on 20 Apr 2021 |
| * 6 | [#1015](https://github.com/pyro-ppl/numpyro/issues/1015) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/issues/1015) | Initialization issues when using mask/latent variables |  | Algorithmic/accuracy | [Test]() |  21 Apr 2021 | committed on 23 Apr 2021 |
| * 7 | [#1241](https://github.com/pyro-ppl/numpyro/issues/1241) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1248/files) | Need help: NUTS does't converge |  | Algorithmic/accuracy | [Test]() |  28 Nov 2021 | committed on 24 Jan 2022 |
| * 8 | [#1399](https://github.com/pyro-ppl/numpyro/issues/1399) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1401/files) | Providing warning/error when conditioning on extreme values |  | Algorithmic/accuracy | [Test]() |  29 Apr 2022 | committed on 6 May 2022 |
| * 9 | [#1402](https://github.com/pyro-ppl/numpyro/issues/1402) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1419/files) | Sampling from posterior predictive with Categorical and AutoDiagonalNormal occasionally samples outside support |  | Algorithmic/accuracy | [Test]() |  2 May 2022 | committed on 13 Jun 2022 |
| * 10 | [#2](https://github.com/pyro-ppl/numpyro/issues/2) | bug | closed | [bug fix]() | Enable jit compilation in minipyro |  | Dimension/boundary-value | [Test]() |  21 Feb 2019 | committed on 21 Feb 2019 |
| * 11 | [#45](https://github.com/pyro-ppl/numpyro/issues/45) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/50/files) | Disable generic args checking for discrete distributions |  | Dimension/boundary-value | [Test]() |  16 Mar 2019 | committed on 22 Mar 2019 |
| * 12 | [#76](https://github.com/pyro-ppl/numpyro/issues/76) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/78/files) | Discrete distribution does not respect initial seed |  | Dimension/boundary-value | [Test]() |  2 Apr 2019 | committed on 3 Apr 2019 |
| * 13 | [#142](https://github.com/pyro-ppl/numpyro/issues/142) | bug、performance | closed | [bug fix]() | standard_gamma not caching compiled function  |  | Dimension/boundary-value | [Test]() |  10 May 2019 | committed on 10 May 2019 |
| * 14 | [#249](https://github.com/pyro-ppl/numpyro/issues/249) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/250/files) | HMC adaptation stuck at warmup phase due to step_size -> nan |  | Dimension/boundary-value | [Test]() |  18 Jul 2019 | committed on 18 Jul 2019 |
| * 15 | [#252](https://github.com/pyro-ppl/numpyro/issues/252) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/267/files) | fori_collect does not work with non-float arrays  |  | Dimension/boundary-value | [Test]() |  18 Jul 2019 | committed on 30 Jul 2019 |
| * 16 | [#288](https://github.com/pyro-ppl/numpyro/issues/288) | bug、performance | closed | [bug fix]() | mcmc is so slow with the new version of JAX |  | Dimension/boundary-value | [Test]() |  23 Aug 2019 | committed on 26 Aug 2019 |
| * 17 | [#552](https://github.com/pyro-ppl/numpyro/issues/552) | bug、question | closed | [bug fix]() | "Cannot find valid initial parameters" after data size exceeds some threshold |  | Dimension/boundary-value | [Test]() |  3 Mar 2020 | committed on 6 Mar 2019 |
| * 18 | [#566](https://github.com/pyro-ppl/numpyro/issues/566) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/572/files) | Predictive distribution fails on model with lax.scan |  | Dimension/boundary-value | [Test]() |  8 Apr 2020 | committed on 25 Jun 2020 |
| * 19 | [#691](https://github.com/pyro-ppl/numpyro/issues/691) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/694/files) | Can't use jit_model_args for multi chains |  | Dimension/boundary-value | [Test]() |  24 Jul 2020 | committed on 25 Jul 2020 |
| * 20 | [#771](https://github.com/pyro-ppl/numpyro/issues/771) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/775/files) | Omnistaging does not work when enabling distributions' validation |  | Dimension/boundary-value | [Test]() |  3 Oct 2020 | committed on 15 Oct 2020 |
| * 21 | [#779](https://github.com/pyro-ppl/numpyro/issues/779) | bug | closed | [bug fix]() | Enumeration generates invalid dimensions at observation nodes |  | Dimension/boundary-value | [Test]() |  14 Oct 2020 | committed on 20 Oct 2020 |
| * 22 | [#820](https://github.com/pyro-ppl/numpyro/issues/820) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/824/files) | Sample Tensorflow distributions with numpyro.sample() fail inside with handlers.seed(): statement |  | Dimension/boundary-value | [Test]() |  20 Nov 2020 | committed on 24 Nov 2020 |
| * 23 | [#1020](https://github.com/pyro-ppl/numpyro/issues/1020) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1022/files) | Issue with AutoContinuous guides when using numpyro.deterministic |  | Dimension/boundary-value | [Test]() |  23 Apr 2021 | committed on 24 Apr 2021 |
| * 24 | [#1323](https://github.com/pyro-ppl/numpyro/issues/1323) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1327) | Bayesian Hierarchical Stacking Example |  | Dimension/boundary-value | [Test]() |  5 Feb 2022 | committed on 9 Feb 2022 |
| * 25 | [#393](https://github.com/pyro-ppl/numpyro/issues/393) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/395/files) | Investigate discrepancy in effective sample size computation |  | General numerical bugs | [Test]() |  9 Oct 2019 | committed on 10 Oct 2019 |
| * 26 | [#698](https://github.com/pyro-ppl/numpyro/issues/698) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/699/files) | handlers.mask not working when enable_validation(True) |  | General numerical bugs | [Test]() |  25 Jul 2020 | committed on 26 Jul 2020 |
| * 27 | [#896](https://github.com/pyro-ppl/numpyro/issues/896) | bug、enhancement | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1044/files) | [FR] Implement a surrogate loss for discrete, e.g. categorical, distributions |  | General numerical bugs | [Test]() |  26 Jul 2021 | committed on 23 Jun 2021 |
| * 28 | [#911](https://github.com/pyro-ppl/numpyro/issues/911) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/912/files) | ZeroDivisionError when running SVI with num_steps < 20 |  | General numerical bugs | [Test]() |  11 Feb 2021 | committed on 13 Feb 2021 |
| * 29 | [#942](https://github.com/pyro-ppl/numpyro/issues/942) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/943/files) | Beta Distribution samples wrong for a=b--->0 |  | General numerical bugs | [Test]() |  6 Mar 2021 | committed on 10 Mar 2021 |
| * 30 | [#1416](https://github.com/pyro-ppl/numpyro/issues/1416) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1418/files) | signature error when running SA MCMC sampler in parallel |  | General numerical bugs | [Test]() |  2 Jun 2022 | committed on 8 Jun 2022 |
| * 31 | [#1453](https://github.com/pyro-ppl/numpyro/issues/1453) | bug | closed | [bug fix](https://github.com/google/jax/issues/11586) | Unable to fit MA(1) time series model when theta is greater than 1. |  | General numerical bugs | [Test]() |  18 Jul 2022 | committed on 23 Jul 2022 |
| * 32 | [#279](https://github.com/pyro-ppl/numpyro/issues/279) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/280/files) | HMM example failing on travis with jax=0.1.41  |  | Language/translation | [Test]() |  9 Aug 2019 | committed on 14 Aug 2019 |
| * 33 | [#945](https://github.com/pyro-ppl/numpyro/issues/945) | bug | closed | [content]() | AutoDelta raises duplication error  |  | Language/translation | [Test]() |  7 Mar 2021 | committed on 9 Mar 2021 |
| * 34 | [#1177](https://github.com/pyro-ppl/numpyro/issues/1177) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1179/files) | ZeroInflatedDistribution Errors with continuous/discrete distributions |  | Language/translation | [Test]() |  8 Oct 2021 | committed on 2 Jul 2021 |
| * 35 | [#1321](https://github.com/pyro-ppl/numpyro/issues/1321) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1040/files)[bug fix2](https://github.com/pyro-ppl/numpyro/pull/1325/files) | compat module: compat.infer.MCMC broken |  | Language/translation | [Test]() |  4 Feb 2022 | committed on 14 Feb 2021 |
| * 36 | [#1455](https://github.com/pyro-ppl/numpyro/issues/1455) | bug | closed | [content]() | Example Docker Image fails to build |  | Language/translation | [Test]() |  22 Jul 2022 | committed on 7 Aug 2021 |
| * 37 | [#112](https://github.com/pyro-ppl/numpyro/issues/112) | bug | closed | [content]() | Some custom primitives does not work with the newest version of jax |  | version error | [Test]() |  17 Apr 2019 | committed on 3 May 2019 |
| * 38 | [#216](https://github.com/pyro-ppl/numpyro/issues/216) | bug、performance | closed | [content]() | Timeseries model does not work with new version of lax.scan |  | version error | [Test]() |  21 Jun 2019 | committed on 15 Aug 2019 |
| * 39 | [#1385](https://github.com/pyro-ppl/numpyro/issues/1385) | bug | closed | [content]() | NumPyro is broken after jax 0.3.5 |  | version error | [Test]() |  8 Apr 2022 | committed on 10 Apr 2022 |
| * 40 | [#169](https://github.com/pyro-ppl/numpyro/issues/169) | bug | closed | [content]() | tqdm hangs when set_postfix_str with refresh=True |  | hangup | [Test]() |  26 Apr 2019 | committed on 30 May 2019 |
| * 41 | [#414](https://github.com/pyro-ppl/numpyro/issues/414) | bug、jax | closed | [content]() | vectorized elbo does not work with beta bernoulli model |  | Functional issue | [Test]() |  27 Oct 2019 | committed on 9 Jan 2020 |
| * 42 | [#447](https://github.com/pyro-ppl/numpyro/issues/447) | bug。performance | closed | [content]() | NUTS with GPU (doesn't work for bnn.py) |  | memory leak | [Test]() |  17 Nov 2019 | committed on 15 Dec 2020 |
| * 43 | [#489](https://github.com/pyro-ppl/numpyro/issues/489) | bug、awaiting review | closed | [content]() | Release patch for python 3.7 incompatibility |  | compatibility issue | [Test]() |  5 Dec 2019 | committed on 5 Dec 2020 |
| * 44 | [#1165](https://github.com/pyro-ppl/numpyro/issues/1165) | bug | closed | [content]() | Possible incompatibility with latest jax? |  | compatibility issue | [Test]() |  25 Sep 2021 | committed on 26 Sep 2021 |
| * 45 | [#886](https://github.com/pyro-ppl/numpyro/issues/886) | bug、awaiting review | closed | [content]() | Make TransformReparam compatible with .to_event() |  | Compatibility issue | [Test]() |  24 Jan 2021 | committed on 24 Jan 2021 |
| * 46 | [#114](https://github.com/pyro-ppl/numpyro/issues/114) | bug | closed | [content]() | Make tscan jittable |  | others | [Test]() |  18 Apr 2019 | committed on 20 Apr 2019 |
| * 47 | [#154](https://github.com/pyro-ppl/numpyro/issues/154) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/155/files) | NUTS doesn't converge on a stan model |  | other | [Test]() |  12 May 2019 | committed on 13 May 2019 |
| * 48 | [#254](https://github.com/pyro-ppl/numpyro/issues/254) | bug | closed | [content]() | Usage of the scale effect handler? |  | others | [Test]() |  24 Jul 2019 | committed on 25 Jul 2019 |
| * 49 | [#287](https://github.com/pyro-ppl/numpyro/issues/287) | bug | closed | [content]() | substitute logic in autoguide is inconsistence |  | others | [Test]() |  22 Aug 2019 | committed on 28 Aug 2019 |
| * 50 | [#355](https://github.com/pyro-ppl/numpyro/issues/355) | bug | closed | [content]() | plate has unexpected behaviour when dist has batch_shape |  | others | [Test]() |  26 Sep 2019 | committed on 27 Sep 2019 |
| * 51 | [#475](https://github.com/pyro-ppl/numpyro/issues/475) | bug、performance | closed | [content]() | Regression in fori_collect when progress bar disabled |  | others | [Test]() |  30 Nov 2019 | committed on 10 Dec 2019 |
| * 52 | [#650](https://github.com/pyro-ppl/numpyro/issues/650) | bug | closed | [content]() | Indepedent distribution does not have enumerate_support implemented |  | others | [Test]() |  30 Jun 2020 | committed on 30 Jun 2020 |
| * 53 | [#671](https://github.com/pyro-ppl/numpyro/issues/671) | bug | closed | [content]() | Cannot reshape the output of chained MCMC |  | others | [Test]() |  8 Jul 2020 | committed on 26 Jul 2020 |
| * 54 | [#728](https://github.com/pyro-ppl/numpyro/issues/728) | bug、awaiting review | closed | [content]() | Fix init_strategy argument not respected in hmc and sa |  | others | [Test]() |  10 Sep 2020 | committed on 10 Sep 2020 |
| * 55 | [#749](https://github.com/pyro-ppl/numpyro/issues/749) | bug、jax | closed | [content]() | NumPyro is breaking with JAX 0.2 |  | others | [Test]() |  24 Sep 2020 | committed on 26 Sep 2020 |
| * 56 | [#759](https://github.com/pyro-ppl/numpyro/issues/759) | bug、jax | closed | [content]() | jax.tree_utils do not keep dict key order |  | others | [Test]() |  29 Sep 2020 | committed on 29 Sep 2020 |
| * 57 | [#907](https://github.com/pyro-ppl/numpyro/issues/907) | bug | closed | [content]() | UnexpectedTracerError with DiscreteHMCGibbs, a latent discrete variable with more than 1 dim, and num_chains>1 |  | others | [Test]() |  8 Feb 2021 | committed on 14 Feb 2021 |
| * 58 | [#964](https://github.com/pyro-ppl/numpyro/issues/964) | bug | closed | [content]() | Test for collapse beta bernoulli is failing |  | others | [Test]() |  18 Mar 2021 | committed on 21 Mar 2021 |
| * 59 | [#972](https://github.com/pyro-ppl/numpyro/issues/972) | bug | closed | [content]() | Fix a regression bug for ExpandedDistribution |  | others | [Test]() |  24 Mar 2021 | committed on 1 Jun 2021 |
| * 60 | [#983](https://github.com/pyro-ppl/numpyro/issues/983) | bug | closed | [content]() | dist.DirichletMultinomial can't handle zero_total count |  | others | [Test]() |  1 Apr 2021 | committed on 8 Apr 2021 |
| * 61 | [#997](https://github.com/pyro-ppl/numpyro/issues/997) | bug | closed | [content]() | HMC fails to sample posterior properly while PyMC3 works fine |  | others | [Test]() |  7 Apr 2021 | committed on 14 Apr 2021 |
| * 62 | [#1024](https://github.com/pyro-ppl/numpyro/issues/1024) | bug | closed | [content]() | Scan fails with empty PYRO_STACK |  | others | [Test]() |  26 Apr 2021 | committed on 28 Apr 2021 |
| * 63 | [#1092](https://github.com/pyro-ppl/numpyro/issues/1092) | bug、high priority、usability | closed | [content]() | import numpyro error (version 0.7) |  | others | [Test]() |  12 Jul 2021 | committed on 12 Jul 2021 |
| * 64 | [#1176](https://github.com/pyro-ppl/numpyro/issues/1176) | bug | closed | [content]() | Scope handler doesn't add prefix to cond_indep_stack frames |  | others | [Test]() |  8 Oct 2021 | committed on 9 Oct 2021 |
| * 65 | [#1231](https://github.com/pyro-ppl/numpyro/issues/1231) | bug、help wanted | closed | [content]() | TFP distributions |  | others | [Test]() |  20 Nov 2021 | committed on 27 Nov 2021 |
| * 66 | [#1296](https://github.com/pyro-ppl/numpyro/issues/1296) | bug | closed | [content]() | Sparse Poisson different log_prob values depending on type |  | others | [Test]() |  21 Jan 2022 | committed on 23 Jan 2022 |
| * 67 | [#1328](https://github.com/pyro-ppl/numpyro/issues/1328) | bug | closed | [content]() | Vectorized sampling: error when var size is 0 |  | others | [Test]() |  9 Feb 2022 | committed on 10 Feb 2022 |
| * 68 | [#1433](https://github.com/pyro-ppl/numpyro/issues/1433) | bug | closed | [content]() | A bug in AutoMultivariateNormal guide |  | others | [Test]() |  20 Jun 2022 | committed on 22 Jun 2022 |
| * 69 | [#1438](https://github.com/pyro-ppl/numpyro/issues/1438) | bug | closed | [content]() | issues when numpyro.enable_validation(is_validate=True) |  | others | [Test]() |  22 Jun 2022 | committed on 25 Jun 2022 |
| * 70 | [#1442](https://github.com/pyro-ppl/numpyro/issues/1442) | bug | closed | [content]() | A bug in the way enumeration handles batch dimensions |  | others | [Test]() |  26 Jun 2022 | committed on 2 Jul 2022 |
| * 71 | [#1455](https://github.com/pyro-ppl/numpyro/issues/1455) | bug | closed | [bug fix](https://github.com/pyro-ppl/numpyro/pull/1464/files) | Example Docker Image fails to build |  | others | [Test]() |  22 Jul 2022 | committed on 7 Aug 2022 |

cornellius-gp/gpytorch
https://github.com/cornellius-gp/gpytorch/issues
バグ数　335
| Bug Id | Issue  | label |  Modify | Status | Type |Issue Registered | Issue Resolved |
| --- | --- | --- | --- | --- | --- | --- | --- | 
| * 1 | [#67](https://github.com/cornellius-gp/gpytorch/issues/67) | bug | closed | [bug fix]() | Cannot compute gradient of variance |  | Language/translation | [Test]() |  25 Jan 2018 | committed on 27 Jan 2018 |
| * 2 | [#94](https://github.com/cornellius-gp/gpytorch/issues/94) | bug | closed | [bug fix](https://github.com/cornellius-gp/gpytorch/pull/95) | Test failure in test_function_factory.py |  | Language/translation | [Test]() |  23 Mar 2018 | committed on 24 Mar 2018 |
| * 3 | [#60](https://github.com/cornellius-gp/gpytorch/issues/60) | bug | closed | [bug fix]() | gradients didn't backward to the end |  | others | [Test]() |  16 Jan 2018 | committed on 28 Jan 2018 |
| * 4 | [#61](https://github.com/cornellius-gp/gpytorch/issues/61) | bug | closed | [bug fix](https://github.com/cornellius-gp/gpytorch/commit/34af54a7ce4849778d548fc0782da81449c50c3c) | Interpolation expects things to be floats |  | others | [Test]() |  18 Jan 2018 | committed on 16 Feb 2018 |
| * 5 | [#2197](https://github.com/cornellius-gp/gpytorch/issues/2197) | bug | closed | [bug fix]() | [Bug] Bug Name won't fit in description (Runtime Error) |  | others | [Test]() |  19 Nov 2022 | committed on 29 Nov 2022 |
