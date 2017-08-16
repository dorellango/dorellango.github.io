<template>
  <div>
    <nuxt/>
  </div>
</template>

<style lang="sass">
  @import ~normalize.css
  @import ../assets/variables

  body
    font-family: 'Roboto', Helvetica, Arial, sans-serif
    font-size: 1.125rem
    line-height: 1.5em
    color: #6d6d6d
    background-color: #f1f1f1
    .icn
      display: inline-block
      vertical-align: text-bottom
      width: 1rem
      height: 1rem

    .wrapper
      max-width: 580px
      padding: 30px
      text-align: left
      @media screen and (min-width: $break-md)
          padding-left: 18%
    a
      color: $primary
      text-decoration: none
      &:hover
          text-decoration: underline
</style>
