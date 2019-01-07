# FlowerImageClassifier

The code in this file develops a flower image classifier across 102 different types of flowers.  Current implementation includes the following:

1.  Option to train the model on GPU using Google Colab
2.  Tracking of metrics for train and validation sets
3.  Saving of checkpoints and best model
4.  Transfer learning based on pre-trained models to speed up training time
5.  Adjustment of learning rates over time
6.  Graphical display of output

Planned optimizations:
1.  Identification of optimal learning rate
2.  Loading last checkpoint to re-start training  

### Best Results

So far the best model has achieved a 95% accuracy on the validation set in less than 10 epochs of training.

### Notes

1.  In training on Google colab it was noticed that with poor internet connection or during peak periods model training performed poorly.  If accuracy rates seem low re-try with better connection or during lower rates of usage.
