
```
model
 ㄴ transformer.py    ﹒﹒﹒ 트랜스포머 모델
 ㄴ util.py           ﹒﹒﹒ 모델에 사용되는 유틸
 ㄴ visualization.py  ﹒﹒﹒ 모델의 각 부분 시각화
train_translation.py﹒﹒﹒ 한국어-영어 번역 학습
run_translation.py  ﹒﹒﹒ 한국어-영어 번역 테스트
```

***
https://velog.io/@nawnoes/Transformer%EB%A1%9C-%ED%95%9C%EA%B5%AD%EC%96%B4-%EC%98%81%EC%96%B4-%EB%B2%88%EC%97%AD-%EB%AA%A8%EB%8D%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0

#### Headings by default:
```
1. Introduction
2. Transformer
  2.1 Architecture
  2.2 Embedding
  2.3 Positional Encoding
    2.3.1 논문과 가장 흡사하게 구현한 positional matrix
    2.3.2 Github에 구현한 코드 (pytorch 문서 참고)
  2.4 Masking 
    2.4.1 Padding Mask 핵심 내용
    2.4.2 No Peaking Mask (Look Ahead Mask 핵심)
  2.5 Residual Dropout
  2.6 Multi-Headed Attention
    2.6.1 Q, K, and V
    2.6.2 Linear Model
    2.6.3 Multi-Head
  2.7 Scaled Dot-Product Attention
    2.7.1 QK^T
    2.7.2 1/sqrt(d_k)
    2.7.3 Masking and Dropout
  2.8 Position-wise Feed-Forward Networks
3 Training
  3.1 Optimizer and Learning Rate
  3.2 Loss Function 
    3.2.1 Y_true and Y_pred
    3.2.2 Cross Entropy Pytorch Version
    3.2.3 Cross Entropy Numpy Version
```
{% highlight markdown %}
## Heading first level
### Heading second level
#### Heading third level
{% endhighlight %}

***

#### Lists

###### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

###### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

{% highlight markdown %}
1. Order list item 1
2. Order list item 1

* Unordered list item 1
* Unordered list item 2
{% endhighlight %}

***

#### Quotes

###### A quote looks like this:

> Never put off till tomorrow what may be done day after tomorrow just as well. — Mark Twain

***

#### Syntax Highlighter

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

#### Images

![]({{site.baseurl}}/images/2.jpg)

***

#### Videos

###### Youtube

<iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>
