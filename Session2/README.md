# Assignment-19
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 11s 190us/step - loss: 0.2796 - acc: 0.9306 - val_loss: 0.0591 - val_acc: 0.9819
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0575 - acc: 0.9832 - val_loss: 0.0594 - val_acc: 0.9798
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 5s 85us/step - loss: 0.0442 - acc: 0.9867 - val_loss: 0.0358 - val_acc: 0.9877
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 5s 85us/step - loss: 0.0387 - acc: 0.9881 - val_loss: 0.0371 - val_acc: 0.9878
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 5s 86us/step - loss: 0.0350 - acc: 0.9893 - val_loss: 0.0264 - val_acc: 0.9914
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 5s 84us/step - loss: 0.0329 - acc: 0.9898 - val_loss: 0.0249 - val_acc: 0.9918
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 5s 87us/step - loss: 0.0281 - acc: 0.9914 - val_loss: 0.0229 - val_acc: 0.9932
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 5s 86us/step - loss: 0.0278 - acc: 0.9909 - val_loss: 0.0247 - val_acc: 0.9923
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 5s 85us/step - loss: 0.0258 - acc: 0.9917 - val_loss: 0.0237 - val_acc: 0.9928
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 5s 90us/step - loss: 0.0247 - acc: 0.9923 - val_loss: 0.0269 - val_acc: 0.9911
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 5s 88us/step - loss: 0.0235 - acc: 0.9926 - val_loss: 0.0258 - val_acc: 0.9921
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 5s 86us/step - loss: 0.0227 - acc: 0.9930 - val_loss: 0.0232 - val_acc: 0.9924
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 5s 86us/step - loss: 0.0224 - acc: 0.9929 - val_loss: 0.0248 - val_acc: 0.9922
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 5s 85us/step - loss: 0.0220 - acc: 0.9930 - val_loss: 0.0214 - val_acc: 0.9935
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 5s 84us/step - loss: 0.0203 - acc: 0.9934 - val_loss: 0.0237 - val_acc: 0.9928
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 5s 86us/step - loss: 0.0191 - acc: 0.9942 - val_loss: 0.0248 - val_acc: 0.9921
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 5s 86us/step - loss: 0.0185 - acc: 0.9940 - val_loss: 0.0228 - val_acc: 0.9928
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 5s 87us/step - loss: 0.0180 - acc: 0.9945 - val_loss: 0.0207 - val_acc: 0.9929
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 5s 85us/step - loss: 0.0189 - acc: 0.9941 - val_loss: 0.0232 - val_acc: 0.9928
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 5s 85us/step - loss: 0.0185 - acc: 0.9943 - val_loss: 0.0208 - val_acc: 0.9942
Out[34]:
<keras.callbacks.History at 0x7f5d2603a0f0>



score = model.evaluate(X_test, Y_test, verbose=0)
print(score)

[0.020782691400182376, 0.9942]
