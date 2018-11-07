### Mcaptcha
微信小程序中随机生成验证码，支持验证
彩色四位字符，英文加数字

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
        
