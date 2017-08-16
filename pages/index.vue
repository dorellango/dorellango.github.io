<template>
  <div class="wrapper">
    <div class="logo">
      <svg class="icn"><use xlink:href="#logo"></use></svg>
    </div>
    <div class="bio">
      <h1>Hello!</h1>
      <p>I'm Diego Orellana, a multidisciplinary web developer from <strong>Santiago, Chile.</strong></p>
      <p>I'm currently available for small & big projects. If you'd like to talk about your projects or an advice about product design, just shot me an email.</p>
    </div>
    <div class="contact">
      <h3>Let's Work!</h3>
      <ul>
        <li>
            <svg class="icn"><use xlink:href="#envelope"></use></svg>
            <a href="mailto:dev@dorellango.cl">dev@dorellango.cl</a>
        </li>
        <li>
            <svg class="icn"><use xlink:href="#twitter"></use></svg>
            <a href="http://twitter.com/dorellango">dorellango</a>
        </li>
        <li>
            <svg class="icn"><use xlink:href="#phone"></use></svg>
            <span>+56949529064</span>
        </li>
      </ul>

    </div>
  </div>
</template>

<script>
import '~/assets/svg/logo.svg'
import '~/assets/svg/phone.svg'
import '~/assets/svg/twitter.svg'
import '~/assets/svg/envelope.svg'

export default {
  components: {
  }
}
</script>

<style lang="sass">
  .logo
      margin: 3rem 0
      svg
          height: 100px
          width: 100px
  .contact
      margin-top: 3rem
      position: relative
      &:before
          content: ''
          position: absolute
          bottom: 100%
          width: 100px
          height: 1px
          background-color: #a0a0a0
          margin-bottom: 1.5rem
      ul
          list-style: none
          padding: 0
      svg
          fill: #6d6d6d
          margin-right: .5rem
</style>
