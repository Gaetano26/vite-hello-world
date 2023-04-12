:<template>
  <div class="jumbo">
    <AppTitle />
    <AppHero />

  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
    
  }
}
</script>

<style lang="scss" scoped>

</style>