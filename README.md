# A RNN for temporal consistency in videos enhanced by single-frame methods

## Abstract
Low-light video enhancement (LLVE) has received little attention compared to low-light image enhancement (LLIE) mainly due to the lack of paired low-/normal-light video datasets. Consequently, a common approach to LLVE is to enhance each video frame individually using LLIE methods. However, this practice introduces temporal inconsistencies in the resulting video. In this work, we propose a recurrent neural network (RNN) that, given a low-light video and its per-frame enhanced version, produces a temporally consistent video preserving the underlying frame-based enhancement. We achieve this by training our network with a combination of a new forward-backward temporal consistency loss and a content-preserving loss. At inference time, we can use our trained network to correct videos processed by any LLIE method. Experimental results show that our method achieves the best trade-off between temporal consistency improvement and fidelity with the per-frame enhanced video, exhibiting a lower memory complexity and comparable time complexity with respect to other state-of-the-art methods for temporal consistency.

## Demo videos

https://github.com/user-attachments/assets/b0c90bc1-5077-4a99-b00f-371ad9115f61

https://github.com/user-attachments/assets/9b96f1ed-330a-45a3-b6b1-2286441441a3

https://github.com/user-attachments/assets/51d640d0-72a4-4efd-b3db-c63d7d754093

https://github.com/user-attachments/assets/876597e1-c1f6-4518-baa6-78c9601f55d0

## Code

The code will be available after acceptance.


