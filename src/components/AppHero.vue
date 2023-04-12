:<template>
    <div>
        <h3>{{ paragrafo }}</h3>
        <button>Fammi Dormire</button>
    </div>
</template>

<script>
export default {
    name:'AppHero',
    data () {
        

        return {
            paragrafo: 'boolean non mi fa piu dormire la notte...premi il bottone per spegnermi!'
        }
    }
}
</script>

<style lang="scss" scoped>

</style>