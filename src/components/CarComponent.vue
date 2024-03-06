<template>
   <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg">

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ documents }}
      </q-card-section>
    </q-card>
</template>

<script>
    import { useStore } from "src/stores/store";
    const store = useStore();
    await store.one_GetAll(getOneDocuments);
    export default {
        props: ["index"],
        setup(props){
            // const id = store.many.documents
            console.log(props)
        }
    }

    let documents = 0
    documents
    function getOneDocuments(){
        documents = store.one.documents
    }
</script>

<style lang="scss" scoped>
.my-card {
    width: 300px;
}
</style>