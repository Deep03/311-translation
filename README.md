# 311-translation

This is a repository to track development of a new translation model for service requests through Boston 311. Please see the [wiki](https://github.com/monum/311-translation/wiki) to get a better understanding how we implemeneted the different models by training it over Local data to get better translations.

The ideal outcome of this project is:

- The creation of new, accurate bi-directional machine translation models for English - Spanish, and English - Vietnamese focused on grievance data.

- Updated accuracy
Epoch 1/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 96s 60ms/step - accuracy: 0.7120 - loss: 2.2110 - val_accuracy: 0.8057 - val_loss: 1.2232
Epoch 2/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 58s 44ms/step - accuracy: 0.8139 - loss: 1.1869 - val_accuracy: 0.8524 - val_loss: 0.8881
Epoch 3/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 83s 45ms/step - accuracy: 0.8532 - loss: 0.8974 - val_accuracy: 0.8670 - val_loss: 0.7856
Epoch 4/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 82s 45ms/step - accuracy: 0.8680 - loss: 0.7832 - val_accuracy: 0.8736 - val_loss: 0.7394
Epoch 5/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 82s 45ms/step - accuracy: 0.8785 - loss: 0.7047 - val_accuracy: 0.8758 - val_loss: 0.7126
...
Epoch 25/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 60s 46ms/step - accuracy: 0.9296 - loss: 0.4128 - val_accuracy: 0.8860 - val_loss: 0.8036
Epoch 26/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 82s 45ms/step - accuracy: 0.9305 - loss: 0.4098 - val_accuracy: 0.8860 - val_loss: 0.8118
Epoch 27/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 83s 46ms/step - accuracy: 0.9317 - loss: 0.4037 - val_accuracy: 0.8859 - val_loss: 0.8258
Epoch 28/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 81s 45ms/step - accuracy: 0.9327 - loss: 0.3974 - val_accuracy: 0.8862 - val_loss: 0.8363
Epoch 29/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 59s 45ms/step - accuracy: 0.9331 - loss: 0.3970 - val_accuracy: 0.8852 - val_loss: 0.8457
Epoch 30/30
1315/1315 ━━━━━━━━━━━━━━━━━━━━ 61s 46ms/step - accuracy: 0.9346 - loss: 0.3902 - val_accuracy: 0.8868 - val_loss: 0.8467