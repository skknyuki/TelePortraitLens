# M - Manual Settings

![](images/Lens_Top.png)

---
## Optics

カメラの視野角やボケの強さを変更できます。  
FOVの設定範囲は **12mm ～ 1000mm** 相当です。

- **0%** ：12mm
- **25%** ：53mm
- **50%** ：94mm
- **75%** ：135mm
- **100%** ：1000mm

![](images/Lens_Opticals.png)

- **[Main FOV]**  
  メインカメラの FOV を変更できます。

- **[Sync]**  
  ON 状態では、メインカメラの FOV と同期します。

- **[FOV [Fore]]** / **[FOV [Back]]**  
  これらを選択すると、対応する **[Sync]** は自動的に OFF になります。

<BR>

---
## FOV

メインカメラの FOV を変更できます。  

<BR><BR>

---
## Fore / Main / Back 


![](images/Lens_Unit_all.png)

### 共通設定

#### AutoLevel

![](images/AutoLevel.png)
  
各カメラの傾きを **左・正面・右** に固定できます。

<BR>

#### WorldFix

各カメラをワールドに固定できます。  
(Mainだけは下記の様な設定項目に移らず、ワールドに固定されます。)

![](images/Lens_WorldFix.png)

- **Return** ： メインカメラの位置に戻ります。
- **WorldFix** ： カメラをワールドに固定します。
- **Hand** ： カメラを手元と同期します。

<BR>

---

### Fore

#### clip Adjust

Fore カメラの Far の位置を、奥側へ微調整できます。

<BR>

#### Far Clipping

ON にすると、Foreカメラの **Far** が Backカメラの **Far** と同じになります。  
Skyboxを含め、遠景全体を写せるようになります。


---

### Main

#### Show UI Layer

ON にすると、UI Layer を描画できます。(メインのみ)

<BR>

#### Far Clipping

ON にすると、Mainカメラの **Far** が Backカメラの **Far** と同じになります。  
MainカメラではSkyboxは写りません。

---

### Back

#### Clip Adjust

Back カメラの Far の位置を、手前側に微調整できます。

<BR>



---
## Focus


ピントを合わせる距離(フォーカス距離)と、ピントが合う範囲(フォーカス範囲)を  
キーを入力する方向で調整できます。

- **↑** / Farther：フォーカス距離を奥へ移動
- **↓** / Closer ：フォーカス距離を手前へ移動
- **←** / Widen：フォーカス範囲を広げる
- **→** / Narrow：フォーカス範囲を狭くする

<BR>

---
## Focus Range

![](images/Lens_ForcusRange.png)

フォーカス距離を、一定の距離から選択できます。  
フォーカス範囲は **約 1.5m** になります。  
選択後の細かい調整は [Focus](#focus)で合わせます。

### Auto Focus

![](images/Lens_AutoFocus.png)

AutoFocusを選択すると、利き手と逆の手に**ピンク色の球**が表示されます。  
AutoFocus中は、この球とカメラの距離がフォーカス距離となります。  
  
- **AutoFocus Range** で、AutoFocus中のフォーカス範囲を調整できます。  
値を大きくするとピントの合う範囲が広くなります。
- **Look at AF** で、カメラが常にピンク級の方を向きます。
- **AutoFocus Drone** で、ピンク球をドローンのように  
好きな場所に移動させれます。
- **AutoFocus worldFix**で、好きな場所にピンク球を置いたり  
手元に引き寄せたり出来ます。
  
動かし方はカメラのドローンとほぼ同じです。  
回転機能はありません。