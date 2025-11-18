**Abstract**

This project implements an automated system for detecting and analysing
currency exchange arbitrage opportunities using graph-based algorithms.
Exchange rates are modelled as a directed weighted graph where each currency
represents a node and each conversion rate an edge. To detect arbitrage, the
Bellman-Ford algorithm is applied in the transformed -log(rate) space, allowing
negative cycle detection to signify profitable arbitrage loops. An additional
profit threshold is introduced to suppress false positives arising from rounding
errors and floating-point imprecision, aligning the model with realistic market
constraints. For completeness the system also computes optimal conversion
paths using the same graph representation when no arbitrage is present. The
solution includes robust input validation, modular design, logging, and
structured output consistent with specifications outlined in the brief. Testing
against multiple synthetic and real-world datasets, implementing a live exchange
rate data pipeline through exchangeratesapi.io. The code is available at {
https://github.com/Hayden-RM/currency-arb }.
