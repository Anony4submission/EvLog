# EvLog

This is the code repository for our submitted paper\#658: EvLog: Log-based Root Cause Analyzer over Software Evolution.

The content includes:
- `datasets/` contains the dataloader and multi-level feature extractor for rich representation and abstract representation.
- `networks/` contains the root cause discriminator. Theoretically, this module be replaced by any neural network architecture, demonstrating the extensibility of our approach. 
- `optim/` contains the training and evaluating process.
- We also release samples of our collected dataset in `sampled_data/sample.pkl`. The full dataset will be released upon acceptance.
