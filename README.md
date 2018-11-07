### Mcaptcha
随机生成验证码，支持验证


## 使用方法
-----------------------------------
var mcaptcha = new Mcaptcha({
            el: 'canvas',
            width: 80,
            height: 35,
            createCodeImg: ""
        });
        
## api
-----------------------------------
> 刷新 mcaptcha.refresh()
> 验证 mcaptcha.validate(code)
        
