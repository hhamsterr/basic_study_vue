/* 配置模板结构*/
<template>
    <div>
        <h2>学校名：{{name}}</h2>
    </div>
</template>

/* 配置组件数据、交互、事件等*/
<script>
//暴露组件的配置，没有创建组件，因为没有调用vue.extend
export default{
    data(){
        return {
            name:'chd'
        }
    }
}
</script>
