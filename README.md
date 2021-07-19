# Denoising-autoencoder
半導體材料影像處理

在半導體材料製造過程中，透過電子顯微鏡掃描產生影像可以辨識材料表
面是否有缺陷發生。不過影像的原子分割、定位、降噪和超分辨率處理是一項
具有挑戰性的任務，特別是當背景干擾很強且不可預測時，往往容易失敗。以
下是電子顯微鏡掃的訓練影像數據:

輸入:https://github.com/xinhuolin/TEM-ImageNet-v1.3/tree/master/image

輸出:https://github.com/xinhuolin/TEM-ImageNet-v1.3/tree/master/noNoiseNoBackgroundSuperresolution

測試資料(需做影像重構):https://github.com/xinhuolin/AtomSegNet/tree/master/test_img


使用語言:Python

環境:

tensorflow=2.0

python=3.7
