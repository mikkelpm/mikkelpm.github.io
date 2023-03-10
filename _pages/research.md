---
permalink: /research/
title: Research
---

## Working papers

**Local Projections vs. VARs: Lessons From Thousands of DGPs** (with Dake Li and Christian K. Wolf). 2022.\
<small><a href="#/" onclick="visib('lp-var-simul')">Abstract</a> &bull; [Working paper](../files/lp_var_simul.pdf) &bull; [Supplement](../files/lp_var_simul_supplement.pdf) &bull; [Slides](../files/lp_var_simul_slides.pdf) &bull; [Matlab code](https://github.com/dake-li/lp_var_simul) &bull; [arXiv](https://arxiv.org/abs/2104.00655)</small>
<div id="lp-var-simul" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We conduct a simulation study of Local Projection (LP) and Vector Autoregression (VAR) estimators of structural impulse responses across thousands of data generating processes, designed to mimic the properties of the universe of U.S. macroeconomic data. Our analysis considers various identification schemes and several variants of LP and VAR estimators. A clear bias-variance trade-off emerges: LP estimators have lower bias than VAR estimators but substantially higher variance at intermediate and long horizons. Consequently, unless researchers are overwhelmingly concerned with bias, shrinkage via Bayesian VARs or penalized LPs is attractive.
</small></div>

**Standard Errors for Calibrated Parameters** (with Matthew D. Cocci). 2021.\
<small><a href="#/" onclick="visib('calibration')">Abstract</a> &bull; [Working paper](../files/calibration.pdf) &bull; [Slides](../files/calibration_slides.pdf) &bull; [Python code](https://github.com/mikkelpm/stderr_calibration_python) &bull; [Matlab code](https://github.com/mikkelpm/stderr_calibration_matlab) &bull; [arXiv](https://arxiv.org/abs/2109.08109)</small>
<div id="calibration" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
Calibration, the practice of choosing the parameters of a structural model to match certain empirical moments, can be viewed as minimum distance estimation. Existing standard error formulas for such estimators require a consistent estimate of the correlation structure of the empirical moments, which is often unavailable in practice. Instead, the variances of the individual empirical moments are usually readily estimable. Using only these variances, we derive conservative standard errors and confidence intervals for the structural parameters that are valid even under the worst-case correlation structure. In the over-identified case, we show that the moment weighting scheme that minimizes the worst-case estimator variance amounts to a moment selection problem with a simple solution. Finally, we develop tests of over-identifying or parameter restrictions. We apply our methods empirically to a model of menu cost pricing for multi-product firms and to a heterogeneous agent New Keynesian model.
</small></div>


## Publications

**Full-Information Estimation of Heterogeneous Agent Models Using Macro and Micro Data** (with Laura Liu). *Quantitative Economics* 14(1), 2023, 1-35.\
<small><a href="#/" onclick="visib('het_agents')">Abstract</a> &bull; [Published version](https://doi.org/10.3982/QE1810) &bull; [Working paper](../files/het_agents.pdf) &bull; [Supplement](../files/het_agents_supplement.pdf) &bull; [Slides](../files/het_agents_slides.pdf) &bull; [Replication files and Matlab code suite](https://github.com/mikkelpm/het_agents_bayes) &bull; [arXiv](https://arxiv.org/abs/2101.04771)</small>
<div id="het_agents" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We develop a generally applicable full-information inference method for heterogeneous agent models, combining aggregate time series data and repeated cross sections of micro data. To handle unobserved aggregate state variables that affect cross-sectional distributions, we compute a numerically unbiased estimate of the model-implied likelihood function. Employing the likelihood estimate in a Markov Chain Monte Carlo algorithm, we obtain fully efficient and valid Bayesian inference. Evaluation of the micro part of the likelihood lends itself naturally to parallel computing. Numerical illustrations in models with heterogeneous households or firms demonstrate that the proposed full-information method substantially sharpens inference relative to using only macro data, and for some parameters micro data is essential for identification.
</small></div>

**Discussion of "Narrative Restrictions and Proxies" by Raffaella Giacomini, Toru Kitagawa, and Matthew Read**. *Journal of Business & Economic Statistics* 40(4), 2022, 1434-1437.\
<small><a href="#/" onclick="visib('narrative_discussion')">Abstract</a> &bull; [Published version](https://doi.org/10.1080/07350015.2022.2096042) &bull; [Working paper](../files/narrative_discussion.pdf) &bull; [Slides](../files/narrative_discussion_slides.pdf) &bull; [Replication files](../files/narrative_discussion_replication.zip)</small>
<div id="narrative_discussion" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
In this discussion of an insightful paper by Giacomini, Kitagawa & Read (GKR), I make two points. First, the proxy approach to exploiting narrative restrictions has several appealing robustness properties relative to the likelihood approaches of Antolín-Díaz &amp; Rubio-Ramírez&nbsp;(2018) and GKR (2021): The proxy approach allows the narrative signals to be imperfect and arrive non-randomly, and furthermore, the economic shocks are allowed to be non-invertible. Second, the weak instrument problem that GKR discuss can be overcome by using procedures designed for small samples, such as permutation tests.
</small></div>

**SVAR Identification From Higher Moments: Has the Simultaneous Causality Problem Been Solved?** (with José Luis Montiel Olea and Eric Qian). *AEA Papers and Proceedings* 112, 2022, 481-448.\
<small>This article has not been peer reviewed.<br>
<a href="#/" onclick="visib('higher_moments')">Abstract</a> &bull; [Published version](https://doi.org/10.1257/pandp.20221047) &bull; [Working paper](../files/svar_higher_moments.pdf) &bull; [Slides](../files/svar_higher_moments_slides.pdf) &bull; [Replication files](https://github.com/eric-qian/higher_moments)</small>
<div id="higher_moments" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
Two recent strands of the literature on Structural Vector Autoregressions (SVARs) use higher moments for identification. One of them exploits independence and non-Gaussianity of the shocks; the other, stochastic volatility (heteroskedasticity). These approaches achieve point identification without imposing exclusion or sign restrictions. &nbsp;We review this work critically, and contrast its goals with the separate research program that has pushed for macroeconometrics to rely more heavily on credible economic restrictions and institutional knowledge, as is the standard in microeconometric policy evaluation. Identification based on higher moments imposes substantively stronger assumptions on the shock process than standard second-order SVAR identification methods do. We recommend that these assumptions be tested in applied work. Even when the assumptions are not rejected, inference based on higher moments necessarily demands more from a finite sample than standard approaches do. Thus, in our view, weak identification issues should be given high priority by applied users.
</small></div>

**Robust Empirical Bayes Confidence Intervals** (with Timothy B. Armstrong and Michal Kolesár). *Econometrica* 90(6), 2022, 2567-2602.\
<small><a href="#/" onclick="visib('ebci')">Abstract</a> &bull; [Published version](https://doi.org/10.3982/ECTA18597) &bull; [Working paper](../files/ebci.pdf) &bull; [Supplement](../files/ebci_supplement.pdf) &bull; [Slides](../files/ebci_slides.pdf) &bull; [Replication files](../files/ebci_replication.zip) &bull; [R code](https://github.com/kolesarm/ebci) &bull; [Matlab code](https://github.com/mikkelpm/ebci_matlab) &bull; [Stata code](https://github.com/kolesarm/ebciStata) &bull; [arXiv](https://arxiv.org/abs/2004.03448)</small>
<div id="ebci" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We construct robust empirical Bayes confidence intervals (EBCIs) in a normal means problem. The intervals are centered at the usual linear empirical Bayes estimator, but use a critical value accounting for shrinkage. Parametric EBCIs that assume a normal distribution for the means (Morris, 1983) may substantially undercover when this assumption is violated. In contrast, our EBCIs control coverage regardless of the means distribution, while remaining close in length to the parametric EBCIs when the means are indeed Gaussian. If the means are treated as fixed, our EBCIs have an average coverage guarantee: the coverage probability is at least $1-\alpha$ on average across the $n$ EBCIs for each of the means. Our empirical application considers the effects of U.S. neighborhoods on intergenerational mobility.
</small></div>

**Instrumental Variable Identification of Dynamic Variance Decompositions** (with Christian K. Wolf). *Journal of Political Economy* 130(8), 2022, 2164-2202.\
<small><a href="#/" onclick="visib('decomp_iv')">Abstract</a> &bull; [Published version](https://doi.org/10.1086/720141) &bull; [Working paper](../files/decomp_iv.pdf) &bull; [Supplement](../files/decomp_iv_supplement.pdf) &bull; [Slides](../files/decomp_iv_slides.pdf) &bull; [Replication files and Matlab code suite](https://github.com/mikkelpm/svma_iv) &bull; [arXiv](http://arxiv.org/abs/2011.01380)</small>
<div id="decomp_iv" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
Macroeconomists increasingly use external sources of exogenous variation for causal inference. However, unless such external instruments (proxies) capture the underlying shock without measurement error, existing methods are silent on the importance of that shock for macroeconomic fluctuations. We show that, in a general moving average model with external instruments, variance decompositions for the instrumented shock are interval-identified, with informative bounds. Various additional restrictions guarantee point identification of both variance and historical decompositions. Unlike SVAR analysis, our methods do not require invertibility. Applied to U.S. data, they give a tight upper bound on the importance of monetary shocks for inflation dynamics.
</small></div>

**Local Projection Inference is Simpler and More Robust Than You Think** (with José Luis Montiel Olea). *Econometrica* 89(4), 2021, 1789-1823.\
<small><a href="#/" onclick="visib('lp_inference')">Abstract</a> &bull; [Published version](https://doi.org/10.3982/ECTA18756) &bull; [Working paper](../files/lp_inference.pdf) &bull; [Supplement](../files/lp_inference_supplement.pdf) &bull; [Corrigendum: Assumption 3](../files/lp_inference_corrigendum.pdf) &bull; [Slides](../files/lp_inference_slides.pdf) &bull; [Replication files and Matlab code suite](https://github.com/jm4474/Lag-augmented_LocalProjections) &bull; [arXiv](https://arxiv.org/abs/2007.13888) &bull; [Video of online seminar](https://youtu.be/UrFoU8GsoBs)</small>
<div id="lp_inference" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
Applied macroeconomists often compute confidence intervals for impulse responses using local projections, i.e., direct linear regressions of future outcomes on current covariates. This paper proves that local projection inference robustly handles two issues that commonly arise in applications: highly persistent data and the estimation of impulse responses at long horizons. &nbsp;We consider local projections that control for lags of the variables in the regression. We show that lag-augmented local projections with normal critical values are asymptotically valid uniformly over (i) both stationary and non-stationary data, and also over (ii) a wide range of response horizons. Moreover, lag augmentation obviates the need to correct standard errors for serial correlation in the regression residuals. Hence, local projection inference is arguably both simpler than previously thought and more robust than standard autoregressive inference, whose validity is known to depend sensitively on the persistence of the data and on the length of the horizon.
</small></div>

**Local Projections and VARs Estimate the Same Impulse Responses** (with Christian K. Wolf). *Econometrica* 89(2), 2021, 955-980.\
<small><a href="#/" onclick="visib('lp_var')">Abstract</a> &bull; [Published version](https://doi.org/10.3982/ECTA17813) &bull; [Working paper](../files/lp_var.pdf) &bull; [Supplement](../files/lp_var_supplement.pdf) &bull; [Correction: Typo in Example 2](../files/lp_var_corrigendum.pdf) &bull; [Slides](../files/lp_var_slides.pdf) &bull; [Replication files](../files/lp_var_replication.zip)</small>
<div id="lp_var" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We prove that local projections (LPs) and Vector Autoregressions (VARs) estimate the same impulse responses. This nonparametric result only requires unrestricted lag structures. We discuss several implications: (i) LP and VAR estimators are not conceptually separate procedures; instead, they are simply two dimension reduction techniques with common estimand but different finite-sample properties. (ii) VAR-based structural identification -&nbsp;including short-run, long-run, or sign restrictions -&nbsp;can equivalently be performed using LPs, and <em>vice versa</em>. (iii) Structural estimation with an instrument (proxy) can be carried out by ordering the instrument first in a recursive VAR, even under non-invertibility. (iv) Linear VARs are as robust to non-linearities as linear LPs.
</small></div>

**When is Growth at Risk?** (with Lucrezia Reichlin, Giovanni Ricco, and Thomas Hasenzagl). *Brookings Papers on Economic Activity* 2020 (Spring), 167-229.\
<small><a href="#/" onclick="visib('gar')">Abstract</a> &bull; [Published version](https://www.brookings.edu/bpea-articles/when-is-growth-at-risk/) &bull; [Working paper](../files/gar.pdf) &bull; [Supplement](../files/gar_supplement.pdf) &bull; [Replication files (6 GB)](https://www.dropbox.com/s/68lmjwgzfexvap2/replication_files.zip?dl=0)</small>
<div id="gar" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
This paper empirically evaluates the potentially non-linear nexus between financial indicators and the distribution of future GDP growth, using a rich set of macroeconomic and financial variables covering 13 advanced economies. We evaluate the out-of-sample forecast performance of financial variables for GDP growth, including a fully real-time exercise based on a flexible non-parametric model. We also use a parametric model to estimate the moments of the time-varying distribution of GDP and evaluate their in-sample estimation uncertainty. Our overall conclusion is pessimistic: Moments other than the conditional mean are poorly estimated, and no predictors we consider provide robust and precise advance warnings of tail risks or indeed about any features of the GDP growth distribution other than the mean. In particular, financial variables contribute little to such distributional forecasts, beyond the information contained in real indicators.
</small></div>

**Dominant Currency Paradigm** (with Gita Gopinath, Emine Boz, Camila Casas, Federico J. Díez, and Pierre-Olivier Gourinchas). *American Economic Review* 110(3), 2020, 677-719.\
<small>Based on merging "Global Trade and the Dollar" with a pre-existing paper called "Dominant Currency Paradigm" by Casas, Diez, Gopinath & Gourinchas.<br>
<a href="#/" onclick="visib('dcp')">Abstract</a> &bull; [Published version](https://www.aeaweb.org/articles?id=10.1257/aer.20171201) &bull; [Working paper](../files/dcp.pdf) &bull; [Supplement](../files/dcp_supplement.pdf) &bull; [Replication files](https://doi.org/10.3886/E111161V1) &bull; ["Global Trade and the Dollar" working paper](../files/global_trade_dollar.pdf)</small>
<div id="dcp" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We propose a 'dominant currency paradigm' with three key features: dominant currency pricing, pricing complementarities, and imported inputs in production. We test this paradigm using a new data set of bilateral price and volume indices for more than 2,500 country pairs that covers 91% of world trade, as well as detailed firm-product-country data for Colombian exports and imports. In strong support of the paradigm we find that: (1) Non-commodities terms of trade are uncorrelated with exchange rates. (2) The dollar exchange rate quantitatively dominates the bilateral exchange rate in price pass-through and trade elasticity regressions, and this effect is increasing in the share of imports invoiced in dollars. (3) U.S. import volumes are significantly less sensitive to bilateral exchange rates, compared to other countries' imports. (4) A 1% U.S. dollar appreciation against all other currencies predicts a 0.6% decline within a year in the volume of total trade between countries in the rest of the world, controlling for the global business cycle. We characterize the transmission of, and spillovers from, monetary policy shocks in this environment.
</small></div>

**Dollar Invoicing and the Heterogeneity of Exchange Rate Pass-Through** (with Emine Boz and Gita Gopinath). *AEA Papers and Proceedings* 109, 2019, 527-532.\
<small>This article has not been peer reviewed.<br>
<a href="#/" onclick="visib('dollar_inv_het')">Abstract</a> &bull; [Published version](https://www.aeaweb.org/articles?id=10.1257/pandp.20191009) &bull; [Working paper](../files/dollar_inv_het.pdf) &bull; [Supplement](../files/dollar_inv_het_supplement.pdf) &bull; [Replication files](https://www.dropbox.com/s/1o467vl6cuf4hq4/code_data.zip?dl=0)</small>
<div id="dollar_inv_het" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We show empirically that the variation across country pairs in exchange rate pass-through and trade elasticity is meaningfully explained by the dollar's dominance as invoicing currency. We use a hierarchical Bayesian approach to directly and flexibly model pass-through heterogeneity conditional on the invoicing currency share. We estimate that the importer's country-level dollar invoicing share explains 15 percent of the overall variance across trading pairs in dollar exchange rate pass-through into bilateral prices.
</small></div>

**Bayesian Inference on Structural Impulse Response Functions**. *Quantitative Economics* 10(1), 2019, 145-184.\
<small><a href="#/" onclick="visib('irf_bayes')">Abstract</a> &bull; [Published version](http://qeconomics.org/ojs/index.php/qe/article/view/644) &bull; [Working paper](../files/irf_bayes.pdf) &bull; [Supplement](../files/irf_bayes_supplement.pdf) &bull; [Replication files](../files/irf_bayes_replication.zip)</small>
<div id="irf_bayes" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
I propose to estimate structural impulse responses from macroeconomic time series by doing Bayesian inference on the Structural Vector Moving Average representation of the data. This approach has two advantages over Structural Vector Autoregressions. First, it imposes prior information directly on the impulse responses in a flexible and transparent manner. Second, it can handle noninvertible impulse response functions, which are often encountered in applications. Rapid simulation of the posterior distribution of the impulse responses is possible using an algorithm that exploits the Whittle likelihood. The impulse responses are partially identified, and I derive the frequentist asymptotics of the Bayesian procedure to show which features of the prior information are updated by the data. The procedure is used to estimate the effects of technological news shocks on the U.S. business cycle.
</small></div>

**Simultaneous Confidence Bands: Theory, Implementation, and an Application to SVARs** (with José Luis Montiel Olea). *Journal of Applied Econometrics* 34(1), 2019, 1-17.\
<small><a href="#/" onclick="visib('conf_band')">Abstract</a> &bull; [Published version](http://dx.doi.org/10.1002/jae.2656) &bull; [Working paper](../files/conf_band.pdf) &bull; [Supplement](../files/conf_band_supplement.pdf) &bull; [Replication files](http://qed.econ.queensu.ca/jae/datasets/monteil001/) &bull; [Matlab code](https://github.com/jm4474/Confidence_Bands)</small>
<div id="conf_band" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
Simultaneous confidence bands are versatile tools for visualizing estimation uncertainty for parameter vectors, such as impulse response functions. In linear models, it is known that that the sup-t confidence band is narrower than commonly used alternatives, for example Bonferroni and projection bands. We show that the same ranking applies asymptotically&nbsp;even in general nonlinear models, such as VARs. Moreover, we provide further justification for the sup-t band by showing that it is the optimal default choice when the researcher does not know the audience's preferences. Complementing existing plug-in and bootstrap implementations, we propose a computationally convenient Bayesian sup-t band with exact finite-sample simultaneous credibility. In an application to SVAR impulse response function estimation, the sup-t band - which has been surprisingly overlooked in this setting - is at least 35% narrower than other off-the-shelf simultaneous bands.
</small></div>

**Essays in Macroeconometrics**. PhD dissertation, Department of Economics, Harvard University, 2016.\
<small><a href="#/" onclick="visib('dissertation')">Abstract</a> &bull; [Dissertation](../files/dissertation_mikkel_plagborg_moller.pdf)</small>
<div id="dissertation" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
This dissertation consists of three independent chapters on econometric methods for macroeconomic analysis. In the first chapter, I propose to estimate structural impulse response functions from macroeconomic time series by doing Bayesian inference on the Structural Vector Moving Average representation of the data. This approach has two advantages over Structural Vector Autoregression analysis: It imposes prior information directly on the impulse responses in a flexible and transparent manner, and it can handle noninvertible impulse response functions. The second chapter, which is coauthored with B. J. Bates, J. H. Stock, and M. W. Watson, considers the estimation of dynamic factor models when there is temporal instability in the factor loadings. We show that the principal components estimator is robust to empirically large amounts of instability. The robustness carries over to regressions based on estimated factors, but not to estimation of the number of factors. In the third chapter, I develop shrinkage methods for smoothing an estimated impulse response function. I propose a data-dependent criterion for selecting the degree of smoothing to optimally trade off bias and variance, and I devise novel shrinkage confidence sets with valid frequentist coverage.
</small></div>

**Empirical Evidence on Inflation Expectations in the New Keynesian Phillips Curve** (with Sophocles Mavroeidis and James H. Stock). *Journal of Economic Literature* 52(1), 2014, 124-188.\
<small><a href="#/" onclick="visib('infl_expns_nkpc')">Abstract</a> &bull; [Published version](http://dx.doi.org/10.1257/jel.52.1.124) &bull; [Working paper](../files/infl_expns_nkpc.pdf) &bull; [Replication files](https://www.aeaweb.org/jel/app/mar14_Mav_doc.zip)</small>
<div id="infl_expns_nkpc" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
We review the main identification strategies and empirical evidence on the role of expectations in the New Keynesian Phillips curve, paying particular attention to the issue of weak identification. Our goal is to provide a clear understanding of the role of expectations that integrates across the different papers and specifications in the literature. We discuss the properties of the various limited-information econometric methods used in the literature and provide explanations of why they produce conflicting results. Using a common dataset and a flexible empirical approach, we find that researchers are faced with substantial specification uncertainty, as different combinations of various a priori reasonable specification choices give rise to a vast set of point estimates. Moreover, given a specification, estimation is subject to considerable sampling uncertainty due to weak identification. We highlight the assumptions that seem to matter most for identification and the configuration of point estimates. We conclude that the literature has reached a limit on how much can be learned about the New Keynesian Phillips curve from aggregate macroeconomic time series. New identification approaches and new datasets are needed to reach an empirical consensus.
</small></div>

**Consistent factor estimation in dynamic factor models with structural instability** (with Brandon J. Bates, James H. Stock, and Mark W. Watson). *Journal of Econometrics* 177(2), 2013, 289-304.\
<small>Special issue of Journal of Econometrics in honor of Hashem Pesaran.<br>
<a href="#/" onclick="visib('dfm_instability')">Abstract</a> &bull; [Published version](http://dx.doi.org/10.1016/j.jeconom.2013.04.014) &bull; [Working paper](../files/dfm_instability.pdf) &bull; [Replication files](../files/dfm_instability_replication.zip)</small>
<div id="dfm_instability" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
This paper considers the estimation of approximate dynamic factor models when there is temporal instability in the factor loadings. We characterize the type and magnitude of instabilities under which the principal components estimator of the factors is consistent and find that these instabilities can be larger than earlier theoretical calculations suggest. We also discuss implications of our results for the robustness of regressions based on the estimated factors and of estimates of the number of factors in the presence of parameter instability. Simulations calibrated to an empirical application indicate that instability in the factor loadings has a limited impact on estimation of the factor space and diffusion index forecasting, whereas estimation of the number of factors is more substantially affected.
</small></div>

**A note on proper scoring rules and risk aversion** (with Alexander Peysakhovich). Economics Letters 117(1), 2012, 357-361.\
<small><a href="#/" onclick="visib('scoring_rules')">Abstract</a> &bull; [Published version](http://dx.doi.org/10.1016/j.econlet.2012.05.030) &bull; [Longer working paper](../files/scoring_rules.pdf)</small>
<div id="scoring_rules" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
When risk averse forecasters are presented with risk neutral proper scoring rules, they report probabilities whose ratios are shaded towards 1. If elicited probabilities are used as inputs to decision-making, naive elicitors may violate first-order stochastic dominance.
</small></div>

**New Calculation of Danmarks Nationalbank's Effective Krone-Rate Index** (with Erik Haller Pedersen). Danmarks Nationalbank Monetary Review, 2nd Quarter 2010, 139-144.\
<small>This article has not been peer reviewed.<br>
<a href="#/" onclick="visib('efer')">Abstract</a> &bull; [Published version](http://www.nationalbanken.dk/en/publications/Documents/2010/07/new_calculation_2Q_2010_A.pdf) &bull; [Danish version](http://www.nationalbanken.dk/da/publikationer/Documents/2010/06/kvo_2kvt_dk.pdf)</small>
<div id="efer" style="display: none; text-align: justify; line-height: 1.1; margin: -1em 0em 1em 0em" ><small>
Danmarks Nationalbank regularly publishes an index of the development in the strength of the krone, the effective krone-rate index, and an index of the competitiveness of the Danish manufacturing sector, the real effective krone-rate index. Changing trade patterns make it necessary to revise the weights of the currencies in the index from time to time. The 2009 weights are presented below. The most recent revision of the weights is documented in Pedersen (2004).
</small></div>


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>