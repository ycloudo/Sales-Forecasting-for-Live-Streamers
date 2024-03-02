# Sales-Forecasting-for-Live-Streamers
Final project in 112-1 NCCU Text Mining course. Our group got honorable mention award in the final competition.

# The model used for fintune
### BERT
> For Category Classification
  ```
  **Setting & HyperParameters**
  1. training / testing : 8 / 2
  2. Optimizer : Adam
  3. MAX_LENGTH = 64
  4. BATCH_SIZE = 128
  5. LEARNING_RATE = 2e-5
  6. EPOCH_NUM = 6
  ```
### GRU
> For Forecasting
  ```
  **Setting & HyperParameters**
  1. Take 11 months for training, 1 month for testing(Because our data only contain one yaer)
  2. Network architecture:
      GRU -> Dropout -> GRU -> Dense -> Dropout -> Dense -> Dense
  ```
    
