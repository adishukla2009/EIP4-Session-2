# EIP4-Session-2

# Strategy used is - Reducing the number of kernels in the second convolutional layer to 16 from 32
WARNING:tensorflow:From /usr/local/lib/python3.6/dist-packages/tensorflow_core/python/ops/math_grad.py:1424: where (from tensorflow.python.ops.array_ops) is deprecated and will be removed in a future version.
Instructions for updating:
Use tf.where in 2.0, which has the same broadcast rule as np.where
WARNING:tensorflow:From /usr/local/lib/python3.6/dist-packages/keras/backend/tensorflow_backend.py:1033: The name tf.assign_add is deprecated. Please use tf.compat.v1.assign_add instead.

WARNING:tensorflow:From /usr/local/lib/python3.6/dist-packages/keras/backend/tensorflow_backend.py:1020: The name tf.assign is deprecated. Please use tf.compat.v1.assign instead.

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 13s 214us/step - loss: 0.5319 - acc: 0.8493 - val_loss: 0.1018 - val_acc: 0.9803
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 8s 130us/step - loss: 0.2495 - acc: 0.9267 - val_loss: 0.0551 - val_acc: 0.9868
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 7s 124us/step - loss: 0.2004 - acc: 0.9405 - val_loss: 0.0411 - val_acc: 0.9903
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 7s 122us/step - loss: 0.1659 - acc: 0.9485 - val_loss: 0.0347 - val_acc: 0.9908
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 8s 130us/step - loss: 0.1507 - acc: 0.9493 - val_loss: 0.0312 - val_acc: 0.9923
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 7s 124us/step - loss: 0.1365 - acc: 0.9531 - val_loss: 0.0319 - val_acc: 0.9915
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 8s 126us/step - loss: 0.1290 - acc: 0.9527 - val_loss: 0.0266 - val_acc: 0.9934
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 8s 129us/step - loss: 0.1216 - acc: 0.9535 - val_loss: 0.0235 - val_acc: 0.9931
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 7s 123us/step - loss: 0.1165 - acc: 0.9554 - val_loss: 0.0241 - val_acc: 0.9931
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 8s 129us/step - loss: 0.1117 - acc: 0.9556 - val_loss: 0.0230 - val_acc: 0.9927
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 8s 127us/step - loss: 0.1100 - acc: 0.9555 - val_loss: 0.0248 - val_acc: 0.9927
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 8s 128us/step - loss: 0.1051 - acc: 0.9570 - val_loss: 0.0228 - val_acc: 0.9932
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 7s 121us/step - loss: 0.1035 - acc: 0.9564 - val_loss: 0.0201 - val_acc: 0.9938
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 7s 125us/step - loss: 0.1004 - acc: 0.9565 - val_loss: 0.0206 - val_acc: 0.9937
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 8s 130us/step - loss: 0.0986 - acc: 0.9575 - val_loss: 0.0192 - val_acc: 0.9943
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 7s 124us/step - loss: 0.0980 - acc: 0.9575 - val_loss: 0.0201 - val_acc: 0.9935
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 8s 127us/step - loss: 0.0950 - acc: 0.9584 - val_loss: 0.0205 - val_acc: 0.9942
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 8s 125us/step - loss: 0.0952 - acc: 0.9572 - val_loss: 0.0183 - val_acc: 0.9947
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 8s 128us/step - loss: 0.0939 - acc: 0.9568 - val_loss: 0.0189 - val_acc: 0.9942
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 7s 123us/step - loss: 0.0919 - acc: 0.9592 - val_loss: 0.0204 - val_acc: 0.9938
<keras.callbacks.History at 0x7fc19a23c710>

# Model Evaluate
[0.020401735809084495, 0.9938]
