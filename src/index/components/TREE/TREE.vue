
<template>
  <div>
     <el-tree :data="data" :props="defaultProps" @node-click="handleNodeClick"></el-tree>
  </div>
</template>

<script>
export default {
 data() {
            return {
                data: [{
                label: '一级 1',
                children: [{
                    label: '二级 1-1',
                    children: [{
                    label: '三级 1-1-1'
                    }]
                }]
                }, {
                label: '一级 2',
                children: [{
                    label: '二级 2-1',
                    children: [{
                    label: '三级 2-1-1'
                    }]
                }, {
                    label: '二级 2-2',
                    children: [{
                    label: '三级 2-2-1'
                    }]
                }]
                }],
                defaultProps: {
                children: 'children',
                label: 'label',
                isBorder:false
                }
            }
        },
methods: {
 handleNodeClick(data) {
            },
}
};
</script>

<style scoped>

</style>
  
  