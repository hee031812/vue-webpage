<template>
    <section id="bannerType" :class="['banner__wrap', element]">
        <h2 class="blind">{{ title }}</h2>
        <div class="banner__inner">
            <h3 class="title">웹표준 사이트</h3>
            <p class="desc">
                성공하려면 당신을 찾아오는 모든 도전을 다 받아들여야 한다. 마음에 드는 것만 골라 받을 수는 없다.
                <a href="/" title="유튜브 페이지 이동">- 마이크 가프카</a>
            </p>
            <span class="small">배너 유형01</span>
        </div>
    </section>
</template>

<script>
export default {
    props: {
        Element: String,
        title: String // 문자열 타입의 title 속성 정의
    }
}
</script>