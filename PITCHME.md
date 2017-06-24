### gitpitch サンプルスライド

---
### スライド2枚め
* スライドはここ：[slide](https://gitpitch.com/Algo1970/gitpitch#)  
* 参考サイト：[gitpitch](http://paiza.hatenablog.com/entry/2017/06/22/GitHub%E3%81%A0%E3%81%91%E3%81%A7%E8%B6%85%E9%AB%98%E6%A9%9F%E8%83%BD%E3%81%AA%E3%82%B9%E3%83%A9%E3%82%A4%E3%83%89%E8%B3%87%E6%96%99%E3%81%8C%E4%BD%9C%E3%82%8C%E3%82%8B%E3%80%8CGitPitch%E3%80%8D%E3%81%AE)
* 参考サイト：[background](https://gitpitch.com/gitpitch/feature-demo/customize-image-size)

---
### スライド3枚目
*This text will be italic*
**This text will be bold**

---
### 下方向のスライド
reveal.jsのような下方向スライド

+++
### スライド3.1枚目
* Item 1
* Item 2
  * Item 2a
  * Item 2b  

+++
### スライド3.2枚目
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

+++
### スライド3.3枚目
I think you should use an
`<addr>` element here instead.

+++
### スライド3.4枚目
As Kanye West said:

> We're living the future so
> the present is our past.

---
### アニメーション表示
- AAA
- BBB |
- CCC |
- DDD |

---
### 画像表示1
<img src="/img/dog.JPG" title="dog" width="250">

+++
### 画像表示1.1
![dog](/img/dog.JPG)

---
### syntax highlighting
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

+++
### code-presenting
```python
from time import localtime

activities = {8: 'Sleeping', 9: 'Commuting', 17: 'Working',
              18: 'Commuting', 20: 'Eating', 22: 'Resting' }

time_now = localtime()
hour = time_now.tm_hour

for activity_time in sorted(activities.keys()):
    if hour < activity_time:
        print activities[activity_time]
        break
else:
    print 'Unknown, AFK or sleeping!'
```
@[1]
@[3-4]
@[6-7]
@[9-14]

+++
### table
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

---
### URL
http://www.github.com/

---
### emoji

* :smile: 
* :muscle: |
* :muscle: |

---?image=img/bluski.JPG
### background
Custom size: not specified
Image size defaults to 100% 100%

---?image=img/bluski.JPG&size=auto
### background
Custom size: auto

---?image=img/bluski.JPG&size=cover
### background
Custom size: cover

---?image=img/bluski.JPG&size=auto 90%
### background
Custom size: auto 90%

---?image=img/bluski.JPG&size=90% 90%
### background
Custom size: 90% 90%

---?video=/img/ground.MOV
### movie file
<figcaption><a href="https://github.com/dropbox/pygerduty" style="color: white">https://github.com/dropbox/pygerduty</a></figcaption>

---
### Video
![Video](/img/ground.MOV)


