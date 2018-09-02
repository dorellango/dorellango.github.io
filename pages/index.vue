<template>
  <div class="wrapper">
    <div class="logo">
      <Logo class="icn"/>
    </div>
    <div class="bio">
      <h1>Hello!</h1>
      <p>I'm Diego Orellana, a multidisciplinary web developer from <strong>Santiago, Chile.</strong></p>
      <p>I'm currently available for small & big projects. If you'd like to talk about your projects or an advice about product design, just shot me an email.</p>
    </div>
    <div class="contact">
      <h3>Let's DO it!</h3>
      <ul>
        <li>
            <Envelope class="icn"/>
            <a href="mailto:dev@dorellango.cl">dev@dorellango.cl</a>
        </li>
        <li>
            <Twitter class="icn"/>
            <a href="http://twitter.com/dorellango">dorellango</a>
        </li>
        <li>
            <Phone class="icn"/>
            <span>+56949529064</span>
        </li>
      </ul>

    </div>
  </div>
</template>

<script>
import Logo from '~/assets/svg/logo.svg'
import Phone from '~/assets/svg/phone.svg'
import Twitter from '~/assets/svg/twitter.svg'
import Envelope from '~/assets/svg/envelope.svg'

export default {
  components: {
    Logo,
    Phone,
    Twitter,
    Envelope
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
