# LCKCL-2021-Talent-Identification
Descriptive project with the purpose of talent identification of players participating in LCK CL 2021, using publicly available data from https://oracleselixir.com/stats/players/byTournament. I developed performance metrics, vizualized them and ranked all players based on them. Check out the free paper to see what problems my metrics solve and what players I have identified. The folder src contains a Jupyter notebook, in which I describe data aggregation and creation of the paper's plots. I also created plotly HTML plots and a small dash app of the same plots for more interactivity.
The notebook also contains a section about Bayesian inference on winrates of several teams. There, it can be shown that, assuming a Beta(2,2) prior, that the PDFs of team's posteriors are quite similar, providing evidence for the comparability of players, independently of their team.
