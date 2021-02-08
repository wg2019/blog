---
home: true
heroImage: /space.png
heroText: 学习日记
tagline: 新年伊始，整顿装备，重新出发
actionText: 阅读 →
actionLink: /go/
features:
- title: Go
  details: 基础知识，自学成才
- title: Java
  details: 学习记录，个人博客
---
<div class="footer">
    <span @click="open_beian">京ICP备18015988号-1</span>
</div>

<script>
  export default{
    methods:{
        open_beian(){
            window.open("http://beian.miit.gov.cn/")
        }
    }
  }
</script>
