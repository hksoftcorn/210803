# 업무일지

### ✔ Summary

- [x] 09:00~18:00 FE
- [x] 20:00~24:00 면접 대비 질문 리스트



## ✨ 오늘 배운 내용

- ESLint => 아직 미숙하여, 개발에 있어서 번거러움.... 사용을 해야하나?



## 👀 수행한 업무 및 작성한 코드

- CSS Grid 활용

```vue
<template>
  <div class="container">
    <div class="item item-1">
      <p class="sub-item selected">
        <img src="@/assets/icons/home.svg" alt="home">
      </p>
      <p class="sub-item selected">
        홈
      </p>
    </div>
    <div class="item item-2">
      <p class="sub-item icon">
        <img src="@/assets/icons/rwm.svg" alt="rwm">
      </p>
      <p class="sub-item">
        같이읽기
      </p>
    </div>
    <div class="item item-3">
      <p class="sub-item icon">
        <img src="@/assets/icons/mybook.svg" alt="mybook">
      </p>
      <p class="sub-item">
        내 서재
      </p>
    </div>
    <div class="item item-4">
      <p class="sub-item icon">
        <img src="@/assets/icons/mypage.svg" alt="mypage">
      </p>
      <p class="sub-item">
        마이페이지
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
}
</script>

<style scoped>

.container {  
  background-color: #bbbbbb;
  display: grid;
  padding: 0 3%;
  grid-template-columns: repeat(4, auto [col-start]);
  grid-template-rows: auto;
  justify-items: center;
}

.selected {
  color: #6695e5;
}

</style>
```





## 🐱‍💻 아쉬운 점 & 느낀 점

- ESLint.... 에러 잡기가 넘 어렵습니다.. 왜 이럴까요?

 

