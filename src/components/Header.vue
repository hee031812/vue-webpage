<template>
    <header id="headerType" :class="['footer__wrap', element]">
        <div class="header__inner">
            <div class="header__logo">
                <a href="/">web <em>class</em></a>
            </div>
            <nav class="header__menu">
                <ul>
                    <li><a href="/">헤더 영역</a></li>
                    <li><a href="/">슬라이드 영역</a></li>
                    <li><a href="/">배너 영역</a></li>
                    <li><a href="/">컨텐츠 영역</a></li>
                    <li><a href="/">푸터 영역</a></li>
                </ul>
            </nav>
            <div class="header__member">
                <a href="/">로그인</a>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    props: {
        Element: String,
        title: String // 문자열 타입의 title 속성 정의
    }
}
</script>