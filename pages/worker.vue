<template>
  <div class="Worker">
    <page-header class="mb-3">
      {{ $t('企業の皆様・はたらく皆様へ') }}
    </page-header>
    <StaticCard>
      <h3>
        <a
          href="http://www.pref.tochigi.lg.jp/e01/welfare/chiikifukushi/zenpan/seikatuhukushishikinntokurei.html"
          target="_blank"
          rel="noopener noreferrer"
          >新型コロナウィルス感染症の影響を踏まえた資金の特例貸付
        </a>
      </h3>
      <p>
        今般発生した新型コロナウイルスの感染症の発生による休業等により、一時的又は継続的に収入減少した世帯を対象として、生活福祉資金貸付制度における緊急小口資金及び総合支援資金（生活支援費）について、特例貸付を実施します。通常の貸付と異なり、貸付の対象世帯を低所得者世帯以外に拡大するなどの特例措置を設けましたので、休業や失業等により生活費にお困りの方は下記により御相談ください。
      </p>
    </StaticCard>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { MetaInfo } from 'vue-meta'
import StaticCard from '@/components/StaticCard.vue'
import PageHeader from '@/components/PageHeader.vue'

export default Vue.extend({
  components: {
    PageHeader,
    StaticCard
  },
  head(): MetaInfo {
    return {
      title: this.$t('企業の皆様・はたらく皆様へ') as string
    }
  }
})
</script>
