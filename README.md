# VUE-PDF-SWIPER
使用PDFjs读取pdf文件生成图片，初始化swiper实现幻灯片的效果。


## Install
```
npm i vue-pdf-swiper
```

## Usage
```
<template>
    <div>
        <h4>pdf</h4>
        <s-pdf :url='pdfUrl'></s-pdf>
    </div>
</template>
<script>
import SPdf from 'vue-pdf-swiper'

export default {
    data() {
        return {
            pdfUrl: "../assets/img/2.pdf",
        }
    },
    components:{SPdf}

}
</script>

```
## API
+ url: pdf链接地址，外链注意处理跨域问题。

