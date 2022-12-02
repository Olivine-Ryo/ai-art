# Stable Diffusionに呪文を入力してあなたの好きな画像を生成しよう

日経電子版ビジュアルデータのコンテンツ「[AIが描く絵 見分けられる？ 画像生成 AI はノイズから絵を描く
](https://vdata.nikkei.com/newsgraphics/ai-art/)」では、擬似体験としてあらかじめAIが生成した画像を表示していました。下記ノートブックでは実際にあなたの好きな呪文を入力してStable Diffusionに画像を生成させることができます。

## 📖 ノートブックを実行する前に読んでください / README

- ノートブックの実行は Google Colaboratory 上で行うことができます。ローカル環境では基本的に動作しません。

- 画像生成は[The CreativeML OpenRAIL M license](https://github.com/CompVis/stable-diffusion/blob/main/LICENSE)のライセンスに従う必要があります。

- 生成された画像の利用についてはユーザーが一切の責任を負います。

- 日本経済新聞社は本ノートブックを使用して発生したいかなる損失にも一切の責任を負いません。

## 実行方法

[こちらのGoogle Colaboratory のリンク](https://colab.research.google.com/drive/1mWVx2L09TXPvIarEstH1bY0bChSny1FV)にアクセスしてください。実行には Google のアカウントが必要です。

## 🔍 出典 / Reference

オリジナルの Stable Diffusion モデルは以下の研究者や [Stability.ai](https://stability.ai/) の協力によって作成されました。
  
The original [Stable Diffusion](https://github.com/Stability-AI/stablediffusion) model was created in a collaboration with Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer and the [Stability.ai](https://stability.ai/) Team.

[High-Resolution Image Synthesis with Latent Diffusion Models](https://ommer-lab.com/research/latent-diffusion-models/)
[Robin Rombach](https://github.com/rromb)*, [Andreas Blattmann](https://github.com/ablattmann)*, [Dominik Lorenz](https://github.com/qp-qp), [Patrick Esser](https://github.com/pesser), [Björn Ommer](https://hci.iwr.uni-heidelberg.de/Staff/bommer)
[CVPR '22 Oral](https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html) | [GitHub](https://github.com/CompVis/latent-diffusion) | [arXiv](https://arxiv.org/abs/2112.10752) | [Project page](https://ommer-lab.com/research/latent-diffusion-models/)

Japanese Stable Diffusion は rinna株式会社によって作成されました。

[Japanese Stable Diffusion](https://github.com/rinnakk/japanese-stable-diffusion),
[Shing Makoto](https://huggingface.co/mshing)*, [Sawada, Kei](https://huggingface.co/keisawada) | [Github](https://github.com/rinnakk/japanese-stable-diffusion)