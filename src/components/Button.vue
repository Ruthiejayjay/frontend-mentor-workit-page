<template>
    <button class="
            bg-eucaplyptus 
            text-black 
            border
            py-2 
            px-6 
            hover:bg-dark-purple
            hover:text-eucaplyptus 
            hover:border-eucaplyptus
            ">{{ title }}</button>
</template>
<script>
export default{
    props: {
        title: String
    }
}
</script>