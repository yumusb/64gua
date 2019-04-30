# 六十四卦象加密/Base64  

当时看到群里在传一个很牛逼的聊天记录，然后就动手做了一个  
原理:使用Base64中的字符对应古典六十四卦象  
疑点:Base64中,加密后密文长度不足4的倍数会用=补齐，这里我也没想到用什么比较科学的办法，目前用了`卦`这个字代替。  
Base64.min.js来自[https://github.com/dankogai/js-base64](https://github.com/dankogai/js-base64)

如果你有更好的建议 欢迎讨论