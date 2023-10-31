<template>
    <section id="sliderType" :class="['slider__wrap', element]">
        <h2 class="blind">슬라이드 유형</h2>
        <div class="slider__inner">
            <div class="slider">
                <div class="slider__img">
                    <div class="desc">
                        <span>developer</span>
                        <h3>new frontend</h3>
                        <p>
                            실수를 해보지 않은 사람은<br />
                            결코 새로운 것을 시도하지 않는다.
                        </p>
                        <div class="btn">
                            <a href="/">자세히 보기</a>
                            <a href="/" class="black">사이트 보기</a>
                        </div>
                    </div>
                </div>
                <div class="slider__arrow">
                    <a href="/" class="left"><span class="ir">이전 이미지</span></a>
                    <a href="/" class="right"><span class="ir">다음 이미지</span></a>
                </div>
                <div class="slider__dot">
                    <a href="/" class="dot actvie"><span class="ir">1</span></a>
                    <a href="/" class="dot"><span class="ir">2</span></a>
                    <a href="/" class="dot"><span class="ir">3</span></a>
                    <a href="/" class="play"><span class="ir">플레이</span></a>
                    <a href="/" class="stop"><span class="ir">정지</span></a>
                </div>
            </div>
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