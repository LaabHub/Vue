<template>
    <div>
  <div class="page-title">
    <h3>Посты</h3>
  </div>

  <section>
    <PostTable/>
  </section>
</div>
</template>

<script>
import PostTable from '@/components/PostTable'
export default{
    name: "post",
    methods: {
        pageChange(){}
    },
    components: {
        PostTable
    }
}
</script>