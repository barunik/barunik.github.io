---
id: workingpapers
name: WorkingPapers
heading: Working Papers (Work in Progress)
---

<!--- USAGE: JUST FILL AND ADD THIS

[NAZEV](LINK){:target="blank"} (with COAUTHORS)<br/>
**JOURNALNAME** (YEAR), CITATION, <a href="LINKDOI" target="blank"><i class="ai ai-doi ai"></i></a>
code and package <a href="LINKCODE" target="blank"><i class="fas fa-keyboard"></i></a>
<br/>
-->

<br/>

[Predicting the distributions of stock returns around the globe in the era of big data and learning](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4925722){:target="blank"} (with M.Hronec and O.Tobek) (August 2024)<br/>

**Abstract**: This paper presents a method for accurately predicting the full distribution of stock returns, given a comprehensive set of 194 stock characteristics and market variables. Such distributions, learned from rich data using a machine learning algorithm, are not constrained by restrictive model assumptions and allow the exploration of non-Gaussian, heavy-tailed data and their non-linear interactions. The method uses a two-stage quantile neural network combined with spline interpolation. The results show that the proposed approach outperforms alternative models in terms of out-of-sample losses. Furthermore, we show that the moments derived from such distributions can be useful as alternative empirical estimates in many cases, including mean estimation and forecasting. Finally, we examine the relationship between cross-sectional returns and several distributional characteristics. The results are robust to a wide range of US and international data.

<br/>

<img src="/files/Fig_plot3d.png" alt="drawing" style="width:600px;"/>

<br/>

[Quantile Preferences in Portfolio Choice: A Q-DRL 1 Approach to Dynamic Diversification](https://ideas.repec.org/p/fau/wpaper/wp2024_21.html){:target="blank"} (with A.Sarkany and L.Janasek) (May 2024)<br/>

**Abstract**: We develop a novel approach to understand the dynamic diversification of decision makers with quantile preferences. Due to unavailability of analytical solutions to such complex problems, we suggest to approximate the behavior of agents with a Quantile Deep Reinforcement Learning (Q-DRL) algorithm. The research will provide a new level of understanding the behavior of economic agents with respect to preferences, captured by quantiles, without assuming a specific utility function or distribution of returns. Furthermore, we are challenging the traditional diversification methods as they proved to be insufficient due to heightened correlations and similar risk features between asset classes, and rather the research delves into risk factor investing as a solution and portfolio optimization based on them.

<br/>

[Predicting the volatility of major energy commodity prices: the dynamic persistence model](https://ideas.repec.org/p/arx/papers/2402.01354.html){:target="blank"} (with L.Vacha) revised draft (July 2024)<br/>Revise and resubmit, **Energy Economics**<br/>
replication code and package in Julia <a href="https://github.com/barunik/tvPersistence.jl" target="blank"><i class="fas fa-keyboard"></i></a><br/>

**Abstract**: Time variation and persistence are crucial properties of volatility that are often studied separately in energy volatility forecasting models. Here, we propose a novel approach that allows shocks with heterogeneous persistence to vary smoothly over time, and thus model the two together. We argue that this is important because such dynamics arise naturally from the dynamic nature of shocks in energy commodities. We identify such dynamics from the data using localised regressions and build a model that significantly improves volatility forecasts. Such forecasting models, based on a rich persistence structure that varies smoothly over time, outperform state-of-the-art benchmark models and are particularly useful for forecasting over longer horizons.

<br/>

["Who's the Boss?"" The Role of Shareholders in Banks' Lending Decisions](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4972832){:target="blank"} (with P.Katsoulis, E.Gerba and J.A. Smith)<br/>
preprint draft (Oct 2024)<br/>

**Abstract**: We investigate banks' lending decisions in the face of shareholder pressure to make payouts. We exploit the regulatory ban on banks' distributions during the Covid-19 pandemic to show that the conflict between the interests of banks' shareholders and their borrowers can persist even with such a ban. First, we find that restricted banks faced an increase in shareholders' required rate of return, which was even higher for the banks most exposed to income-oriented investors. This led to an increase in the required rate of return on their overall capital. Second, banks responded by increasing lending volumes only to medium-sized and larger firms and on smaller loans, which are less capital intensive. However, they utilised government guarantee schemes to increase lending volumes to smaller firms and on larger loans. The results suggest that distribution restrictions can incentivise banks to increase lending, but in a way that minimises the capital impact to appease shareholders.

<br/>

[Common Firm-level Investor Fears: Evidence from Equity Options](https://ideas.repec.org/p/arx/papers/2309.03968.html){:target="blank"} (with M.Bevilacqua and M.Ellington)<br/>
preprint draft (Sept 2023)<br/>

**Abstract**: We identify a new type of risk, common firm-level investor fears, from commonalities within the cross-sectional distribution of individual stock options. We define firm-level fears that link with upward price movements as good fears, and those relating to downward price movements as bad fears.  Such information is different to market fears that we extract from index options. Stocks with high sensitivities to common firm-level investor fears earn lower returns, with investors demanding a higher compensation for exposure to common bad fears relative to common good fears. Risk premium estimates for common bad fears range from -5.63% to -4.92% per annum.

<br/>


[Learning Probability Distributions of Day-Ahead Electricity Prices](https://ideas.repec.org/p/arx/papers/2310.02867.html){:target="blank"} (with L.Hanus)<br/>
preprint draft (Oct 2023)<br/>

**Abstract**: We propose a novel machine learning approach to probabilistic forecasting of hourly day-ahead electricity prices. In contrast to recent advances in data-rich probabilistic forecasting that approximate the distributions with some features such as moments, our method is non-parametric and selects the best distribution from all possible empirical distributions learned from the data. The model we propose is a multiple output neural network with a monotonicity adjusting penalty. Such a distributional neural network can learn complex patterns in electricity prices from data-rich environments and it outperforms state-of-the-art benchmarks.<br/>

code and package in Julia <a href="https://github.com/luboshanus/DistrNNEnergy.jl" target="blank"><i class="fas fa-keyboard"></i></a>

<br/>


[Currency Network Risk](https://ideas.repec.org/p/arx/papers/2101.09738.html){:target="blank"} (with M.Babiak)<br/>
preprint draft (May 2023)<br/>

**Presented at** at 2023 WFA (San Francisco), 2023 SGF Conference (Zurich), 2023 EEA-ESEM (Barcelona) <br/>

**Abstract**: This paper identifies a new currency risk stemming from linkages between option-implied currency volatilities. A volatility network strategy that buys net recipients and sells net transmitters of transitory shocks to ex-ante currency volatilities generates significant excess returns. Net recipients are more exposed to volatility spillovers and compensate investors with higher average returns. In contrast, net transmitters are more resilient to volatility transmissions and offer a lower risk premium because they hedge against volatility interdependencies. When volatility linkages are controlled for contemporaneous correlations, the strategy is uncorrelated with popular benchmarks. The volatility network factor is also priced in a currency cross-section.<br/>

The video below illustrates the short-term currency network during the Global Financial Crisis. If the video does not play properly, feel free to watch it [here](https://www.google.com/url?q=https%3A%2F%2Fwww.dropbox.com%2Fs%2Fbg6uk6prpodwnuj%2FCurrency%2520Network.mp4%3Fdl%3D0&sa=D&sntz=1&usg=AFQjCNEc2H1o7Yen4A_u-iPJZ7qFZOy1PQ).

<!-- blank line -->
<figure class="video_container">
  <video controls="true" poster="assets/files/currency_net_2.pdf">
    <source src="https://dl.dropboxusercontent.com/s/bg6uk6prpodwnuj/Currency%20Network.mp4?dl=0" type="video/mp4">
  </video>
</figure>
<!-- blank line -->

<br/>

[Taming data-driven probability distributions](https://ideas.repec.org/p/arx/papers/2204.06848.html){:target="blank"} (with L.Hanus)<br/>
preprint draft (May 2024)<br/>

**Abstract**: We propose a deep learning approach to probabilistic forecasting of macroeconomic and financial time series. By allowing complex time series patterns to be learned from a data-rich environment, our approach is useful for decision making that depends on the uncertainty of a large number of economic outcomes. In particular, it is informative for agents facing asymmetric dependence of their loss on the outcomes of possibly non-Gaussian and non-linear variables. We demonstrate the usefulness of the proposed approach on two different datasets where a machine learns patterns from the data. First, we illustrate the gains in predicting stock return distributions that are heavy tailed and asymmetric. Second, we construct macroeconomic fan charts that reflect information from a high-dimensional dataset.  <br/>
code and package in Julia coming soon


<br/>

[Risks of heterogeneously persistent higher moments](https://ideas.repec.org/p/arx/papers/2104.04264.html){:target="blank"} (with J.Kurka)<br/>
preprint draft (March 2024)<br/>

**Abstract**: Using intraday data for the cross-section of individual stocks, we show that both transitory and persistent fluctuations in realized market and average idiosyncratic volatility, skewness and kurtosis are differentially priced in the cross-section of asset returns, implying a heterogeneous persistence structure of different sources of higher moment risks. Specifically, we find that idiosyncratic transitory shocks to volatility as well as idiosyncratic persistent shocks to skewness contain strong commonalities that are relevant to investors. <br/>

<br/>
