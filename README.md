# stady_of_orm_slam2
orb_slamについて勉強したことをまとめる

# ORB_SLAM
単眼カメラ、ステレオカメラ、およびRGB-Dカメラ用のリアルタイム SLAM ライブラリであり、カメラの軌道とスパース 3D 再構成 (ステレオおよび RGB-D の場合、真のスケールで) を計算する。ループを検出し、リアルタイムでカメラの位置を再設定することができる。

## ほかのSLAMと比較したときの利点
- 実行が比較的高速
- 一度カメラがロスト（位置を見失う）しても再度特徴点からマッチングを行うことで自己位置推定と周辺環境の地図作成を再開することができる

## 実行OS
- Linux (Ubuntu 20.04)

## 使用されている主な言語
- C++
- Python

## ROSについて


