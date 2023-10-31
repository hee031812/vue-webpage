<template>
    <section id="cardType" :class="['cardType section', element]">
        <h2>{{ title }}</h2>
        <p>
            웹표준 사이트만들기 연습 페이지 입니다.<br />
            TheJamsil 22px 150% #666666
        </p>
        <div class="card__inner container">
            <article class="card" v-for="(card, key) in cardInfo" :key="key">
                <figure class="card__header">
                    <img :src="card.img" :alt="card.tilte" />
                </figure>
                <div class="card__body">
                    <h3 class="tit">{{ card.tilte }}</h3>
                    <p class="desc">{{ card.desc }}</p>
                    <a class="btn" href="/">
                        더 자세히 보기
                        <span aria-hidden="true">
                            <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z"
                                    fill="#5B5B5B"></path>
                            </svg>
                        </span>
                    </a>
                </div>
            </article>
        </div>
    </section>
</template>

<script>
export default {
    props: {
        element: String,
        title: String,
    },

    data: function () {
        return {
            cardInfo: [
                {
                    img: "src/assets/img/card_bg01.jpg",
                    tilte: "웹표준 사이트 만들기",
                    desc: "사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을 익히고, 웹 표준을 준수하면서 코딩하는 방법을 익힙니다. 다양한 예제를 통해 사이트를 만드는 사이....."
                },
                {
                    img: "src/assets/img/card_bg02.jpg",
                    tilte: "반응형 사이트 만들기",
                    desc: "사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을 익히고, 웹 표준을 준수하면서 코딩하는 방법을 익힙니다. 다양한 예제를 통해 사이트를 만드는 사이....."
                },
                {
                    img: "src/assets/img/card_bg03.jpg",
                    tilte: "패럴랙스 사이트 만들기",
                    desc: "사이트를 만들기 위한 기초 강의입니다. 기본 코딩에 대한 감각을 익히고, 웹 표준을 준수하면서 코딩하는 방법을 익힙니다. 다양한 예제를 통해 사이트를 만드는 사이....."
                }
            ]
        }
    }
}
</script>

<style>
.card__inner {
    display: flex;
    justify-content: space-between;
}

.card {
    width: 32%;
    background-color: #f5f5f5;
}

.card__body {
    padding: 24px;
}

.card__body .tit {
    font-size: 24px;
    margin-bottom: 10px;
    line-height: 1;
}

.card__body .desc {
    font-size: 18px;
    line-height: 1.4;
    color: #666;
    margin-bottom: 20px;
    font-weight: 300;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 4;
    -webkit-box-orient: vertical;

}

.card__body .btn {
    font-size: 16px;
    color: #222;
}
</style>