<script>
import { onReady, onLaunch, onShow, onHide } from '@dcloudio/uni-app';
import { defineComponent } from 'vue';

// export default {
//   onLaunch: function () {
//     console.log('App Launch')
//   },
//   onShow: function () {
//     console.log('App Show')
//   },
//   onHide: function () {
//     console.log('App Hide')
//   },
// }
export default defineComponent({
  setup() {
    onLaunch(() => {
      console.log('App Launch')
    })
    onShow(() => {
      console.log('App Show')
    })
    onHide(() => {
      console.log('App Hide')
    })
  }
})
</script>

<style>
/*每个页面公共css */
</style>
