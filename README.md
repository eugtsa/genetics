## This is readme for binary genetics

Check out notebook in `exploration/genetics_example.ipynb`

### To get more exploration and less exploitation, do:
- more `n_samples`
- less `save_best_n`
- more `p_point_mutate` - if 1.0 - then every child's gene would be mutated, you'll get totally random child, so don't do more than 0.5
- more `top_n` - more parents would be used to construct children
- less `inbreed_prob` - less parents would be looked alike each other
- more `random_interchange_prob` - probability that child would be created as uniform interchange of parents genes, not in crossover
- less `tournament_rounds` - if 1 then maximum exploration - parents are randomly selected from top_n. Value 2 is good choice

### To get less exploration and more exploitation, do:
- opposite to previous, from `To get more exploration and less exploitation...`