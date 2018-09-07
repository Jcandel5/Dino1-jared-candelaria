<template>
    <section>
        <h2>Job Listings</h2>
        <ul id="job-listings">
            <li
                is="Listings-item"
                v-for="(Listings, index) in todos"
                v-bind:key="Listings.id"
                v-bind:title="Listings.title"
                v-on:remove="Listings.splice(index, 1)">
            </li>
        </ul>
      </section>
</template>

<script>
export default {
    name: "Job-List"
}
</script>

<style>

</style>
