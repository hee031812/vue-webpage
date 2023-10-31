<script setup>
import Header from "@/components/Header.vue"
import Footer from "@/components/Footer.vue"
import Slider from "@/components/Slider.vue"
import Image from "@/components/Image.vue"
import ImgText from "@/components/ImgText.vue"
import Card from "@/components/Card.vue"
import Banner from "@/components/Banner.vue"
import Text from "@/components/Text.vue"

</script>

<template>
  <Header element="dream" />
  <main>
    <Slider element='dream section gray' />
    <Image element='section dream' title="포트폴리오가 실력이다." />
    <ImgText element='section dream gray' title="이미지 텍스트 유형" />
    <Card element='section dream' title="웹스토리보이 강의" />
    <Banner element='dream' title="배너영역" />
    <Text element='section dream' title="스크립트를 익히는 방법" />
  </main>
  <Footer />
</template>s