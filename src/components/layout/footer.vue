<template>
    <div :class="wrapClasses"><slot></slot></div>
</template>
<script>
    const prefixCls = 'ivu-components';
    export default {
        name: 'Footer',
        computed: {
            wrapClasses () {
                return `${prefixCls}-footer`;
            }
        }
    };
</script>
