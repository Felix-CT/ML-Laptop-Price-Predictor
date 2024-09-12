# Data
The data being used will be https://www.kaggle.com/datasets/ironwolf404/laptop-price-dataset . This dataset will be used to train an algorithm that can predict laptop prices.

## Qualms with the data
Although the data has a lot of sections which is a good thing, many of the sections don't use numbers. This isn't necessarily an issue as we can use one hot encoding, however I don't know if it will be very useful in the case that there are hundreds of options. Will this make the one hot encoding less effective? I will have to research this, test it myself, and decide what to do. options will include:
- Using one hot encoding, if there are no issues
- omitting certain attributes (Such as laptop name, which may not have much effect on the price)
- finding a replacement for one hot encoding which works better when there are many non-number attributes.