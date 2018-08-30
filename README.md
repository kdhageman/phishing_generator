# Domain name generator
A recurrent neural network implementation that learns to generate domain names. In the attached report (check out the `latex` directory), the RNN was used to generate domain names specifically registered for phishing purposes.

## How to use
This repository does not contain a training set. Before able to train the RNN, create `data/phishing_domains.dat`, which should be a pickled list of domain names, such as:
```
['first.domain.com', 'second.domain.com', 'last.domain.com']
```

Open the `phishing_domain_generator.ipynb` notebook and run all cells.
