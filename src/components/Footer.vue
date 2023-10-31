<template>
    <footer id="footerType" :class="['footer__wrap', element]">
        <h2 class="blind">푸터 영역</h2>
        <div class="footer__inner container">
            <div class="footer__menu">
                <div>
                    <h3>사이트</h3>
                    <ul>
                        <li><a href="/">웹표준 사이트</a></li>
                        <li><a href="/">반응형 사이트</a></li>
                        <li><a href="/">패럴랙스 사이트</a></li>
                        <li><a href="/">포트폴리오 사이트</a></li>
                    </ul>
                </div>
                <div>
                    <h3>헤더 유형</h3>
                    <ul>
                        <li><a href="/">헤더 유형01</a></li>
                        <li><a href="/">헤더 유형02</a></li>
                    </ul>
                </div>
                <div>
                    <h3>슬라이드 유형</h3>
                    <ul>
                        <li><a href="/">슬라이드 유형01</a></li>
                        <li><a href="/">슬라이드 유형01</a></li>
                    </ul>
                </div>
                <div>
                    <h3>이미지 유형</h3>
                    <ul>
                        <li><a href="/">이미지 유형01</a></li>
                        <li><a href="/">이미지 유형02</a></li>
                        <li><a href="/">이미지/텍스트 유형01</a></li>
                        <li><a href="/">이미지/텍스트 유형02</a></li>
                        <li><a href="/">텍스트 유형01</a></li>
                    </ul>
                </div>
                <div>
                    <h3>카드 유형</h3>
                    <ul>
                        <li><a href="/">카드 유형01</a></li>
                        <li><a href="/">카드 유형02</a></li>
                        <li><a href="/">카드 유형03</a></li>
                    </ul>
                </div>
                <div>
                    <h3>푸터 유형</h3>
                    <ul>
                        <li><a href="/">푸터 메뉴 유형01</a></li>
                        <li><a href="/">푸터 컨택트 유형02</a></li>
                        <li><a href="/">푸터 이메일 유형03</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer__right">
                2023 HEEJIN. Portfolio is Power<br />All rights reserved.
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    props: {
        Element: String,
        title: String // 문자열 타입의 title 속성 정의
    }
}
</script>