<template>
    <div class="columns">
        <div class="column is-3-fullhd is-2-desktop is-1-tablet"></div>
        <div class="column is-7-fullhd is-8-desktop">
            <section class="section">
                <p class="title">
                    <Content slot-key="title"/>
                </p>
                <p class="subtitle">
                    <Content slot-key="subtitle"/>
                </p>
            </section>
            <section class="">
                <Content slot-key="hero"/>
            </section>
            <section class="section">
                <Content/>
            </section>
        </div>
        <div class="column is-3-fullhd is-2-desktop is-1-tablet"></div>
    </div>
</template>

<script lang="ts">
export default {
    props: ['data']
}
</script>

<style lang="scss" scoped>

    h1{
        color: aqua;
    }

</style>