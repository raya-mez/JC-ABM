# Simulated-Annealing for Optimality Theory (SAOT) Model (with Iterated Learning) of Jespersen's Cycle (JC)

# Overview
The goal of this project is to model Jespersen's cycle form - both at a synchronic and diachronic level. The first part is a replication of the Simulated Annealing for Optimality Theory (SAOT) model proposed by Lopopolo and Biró (2011) but implemented it in Python instead of the OTKit software package (Biró 2010) the authors used. The second part is a translation of the model into a simpler Bayesian framework. Both models produce only the first transition of the cycle (from preverbal to discontinuous negation). 

# Requirements
```bash
pip install mesa numpy pandas matplotlib
```

# References
- Lopopolo, A., & Biro, T. (2011). Language Change and SA-OT: The case of sentential negation. Computational Linguistics in the Nether-
lands Journal. doi: 10.7282/T3BC3WKH.
- Biró, T. (2010), OTKit: Tools for Optimality Theory. A software package. http://www.birot.hu/OTKit/.
- Swart, H. de (2010), Expression and Interpretation of Negation: An OT Typology, Vol. 77 of Studies in Natural Language and Linguistic Theory, Springer, Dordrecht, etc., chapter 3: Markedness of Negation.
