<template>
  <q-page>
    <q-tabs v-model="tab">
      <q-tab name="special" label="Special" no-caps />
      <q-tab name="chef-picks" label="Chef Picks" no-caps />
      <q-tab name="soup" label="Soup" no-caps />
      <q-tab name="new" label="New" no-caps />
      <q-tab name="meat" label="Meat" no-caps />
      <q-tab name="appetizer" label="Appetizer" no-caps />
    </q-tabs>
    <q-list class="bg-white" separator bordered>
      <div class="q-pa-sm">
        <div class="row">
          <div class="col q-pa-sm">
            <q-card class="my-card">
              <q-parallax
                src="https://cdn.quasar.dev/img/parallax1.jpg"
                :height="120"
              />
              <q-card-section>
                <div class="text-subtitle2 text-right price">$ 32.00</div>
                <div>
                  Beetroot Salad
                </div>
              </q-card-section>
            </q-card>
          </div>
          <div class="col q-pa-sm">
            <q-card class="my-card">
              <q-parallax
                src="https://cdn.quasar.dev/img/parallax1.jpg"
                :height="120"
              />
              <q-card-section>
                <div class="text-subtitle2 text-right price">$ 32.00</div>
                <div>
                  Beetroot Salad
                </div>
              </q-card-section>
            </q-card>
          </div>
        </div>
      </div>
    </q-list>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
}
</script>

<style lang="scss">
.my-card {
  width: 100%;
  height: 100%;
  max-width: 650px;
  max-height: 650px;
}
.price {
  bottom: 0;
}
</style>
