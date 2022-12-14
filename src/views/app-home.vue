<template>
    <section class="main-container">
        <app-summary></app-summary>
        <app-features></app-features>
        <app-main-feature></app-main-feature>
        <app-reviews></app-reviews>
        <app-join></app-join>
    </section>
</template>

<script>
import appSummary from '../cmps/app-summary.vue';
import appFeatures from '../cmps/app-features.vue';
import appMainFeature from '../cmps/app-main-feature.vue';
import appReviews from '../cmps/app-reviews.vue';
import appJoin from '../cmps/app-join.vue';

export default {
    name: 'home',
    components: {
        appSummary,
        appFeatures,
        appMainFeature,
        appReviews,
        appJoin
    }
}
</script>
