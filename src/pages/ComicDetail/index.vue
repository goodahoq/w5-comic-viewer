<script>
import axios from 'axios'
export default {
  name: 'comicDetail',
  data() {
    return {
      detail: {
        id: 1,
        title: 'MY HEXSCHOOL',
        description:
          'If your banker breaks, you snap; if your apothecary by mistake sends you poison in your pills, you die.Therefore, I say, I saw that this situation of mine was the precise situation of every mortal that has this Siamese connexion with a plurality of other mortals.',
        cover: '/static/images/1.jpg',
        author: 'Namae Shiranai',
        type: 'Fusce/vehicula/dolor',
        score: 4,
        status: 'Ongoing',
        chapters: [
          {
            id: 102,
            text: 'Chapter 1: The F2E Challenge Start!'
          },
          {
            id: 101,
            text: 'Chapter 2: Todo List is Going Crazy!'
          }
        ]
      }
    }
  }
}
</script>

<template src="./template.html"></template>
<style lang="scss" src="./style.scss" scoped></style>
