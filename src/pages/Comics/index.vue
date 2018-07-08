<script>
import axios from 'axios'
import ComicItem from '@/components/ComicItem'
export default {
  name: 'comics',
  data() {
    return {
      list: [
        {
          id: 1,
          title: 'MY HEXSCHOOL',
          description:
            'If your banker breaks, you snap; if your apothecary by mistake sends you poison in your pills, you die.Therefore, I say, I saw that this situation of mine was the precise situation of every mortal that has this Siamese connexion with a plurality of other mortals.',
          cover: '@/assets/comic_cover.png'
        }
      ]
    }
  },
  methods: {
    clickHandler(id) {
      this.$router.push('/comics/' + id)
    }
  },
  components: {
    ComicItem
  }
}
</script>

<template src="./template.html"></template>
<style lang="scss" src="./style.scss" scoped></style>
