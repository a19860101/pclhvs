# CSS 文字
###### tags: `css`
## color
文字顏色
> 快速鍵 c

```css=
h1 {
    color: red;                /*色彩名稱*/
    color: rgb(255,0,0);       /*RGB色碼*/
    color: rgba(255,0,0,.5);   /*RGBA色碼*/
    color: #ff0000;            /*16進位*/
    color: #f00;               /*16進位縮寫*/
}
```
在網頁中使用顏色的方式有下列幾種:
* 色彩名稱
* rgb色碼
* rgba色碼
* 16進位色碼

## text-align
文字對齊
>快速鍵:ta


* left
* center
* right
* justify
## text-decoration
文字裝飾
>快速鍵:td


* none
* underline
* overline
* line-through

## font-family
字體種類
> 快速鍵:ff
> 
```css=
font-family: 字體名稱 ;
```

除了使用預設的字體以外，也可以使用 Google 網路字體(Web Font)。
* 英文：[Google Font](https://fonts.google.com/) 
* 中文：[Google Font Early Access](https://fonts.google.com/earlyaccess)

## font-size
字體大小
> 快速鍵:fz
>
單位:
* px
* pt
* em
* rem

> em 與 rem 的差別
> em 的比例是依循最靠近的父元素；rem 的比例是依循根的比例。假設父元素是 24px，子元素是 1.6em，最後的大小就是 24 x 1.6；若子元素是1.6rem，則是 16 x 1.6。

>根可以透過 :root,html 修改。
>
## font-weight
粗體字
> 快速鍵:fw
> 
* bold
* 100-900
* normal
## font-style
斜體字
> 快速鍵:fs
> 
* italic
* normal

## letter-spacing
字元間距
> 快速鍵:ls

## word-spacing
單字間距
> 快速鍵:wos
> 
英文單字是用空格判別，但中文不是使用空格，所以中文無法使用此屬性
## line-height
行高、行距
> 快速鍵:lh
> 
行裡的文字會在行的正中間。
## text-transform
文字變形。指的是文字大小寫。
> 快速鍵:tt
> 
* uppercase
* lowercase
* capitalize

## font-variant
小型大寫字母
> 快速鍵:fv
> 
* small-caps
