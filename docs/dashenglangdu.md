---
感谢酷安大佬 @丨丨丨丨丨  做出这么优秀的 TTS引擎
感谢官方公众号 开源阅读 给出的修改方法
为何方便快速修改，把代码贴出来了，直接复制就行。
晓 开头的是女声，云 开头的是男声。
---
#### 晓晓
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-XiaoxiaoNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 晓萱
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-XiaoxuanNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 晓睿
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-XiaoruiNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 晓墨
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-XiaomoNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 晓涵
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-XiaohanNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 晓悠
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-XiaoyouNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 云希
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-YunxiNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 云野
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-YunyeNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---

#### 云扬
```
<speak version="1.0" xml:lang="zh-CN"><voice name="zh-CN-YunyangNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%">${text}</prosody></voice></speak>
```
---
#### 晓晓的语气修改模板
```
<speak version="1.0" xmlns="http://www.w3.org/2001/10/synthesis" xmlns:mstts="https://www.w3.org/2001/mstts" xml:lang="zh-CN"><voice name="zh-CN-XiaoxiaoNeural"><prosody rate="${(rate-100)?c}%" pitch="${(pitch-100)?c}%"><mstts:express-as style="cheerful" styledegree="2">${text}</mstts:express-as></prosody></voice></speak>
```
只需要将其中的cheerful修改为你比较喜欢的风格单词即可，然后粘贴进去即可：
晓晓的style(发音风格）有:（填引号里的英文单词即可）


-  "General"/*一般*/
-  "Assistant"/*助理*/
-  "Chat"/*聊天室*/
-  "CustomerService"/*客户服务*/,
-  "Newscast"/*新闻广播*/
-  "Affectionate"/*深情的*/
-   "Angry"/*愤怒的*/
-  "Calm"/*冷静的*/
-  "Cheerful"/*愉快的*/
-  "Disgruntled"/*不满的*/
-  "Fearful"/*恐惧的*/
-   "Gentle"/*温和的*/
-   "Lyrical"/*抒情的*/
-  "Sad"/*悲伤的*/
-  "Serious"/*严肃*/
-  "Empathy"/*同情的*/

