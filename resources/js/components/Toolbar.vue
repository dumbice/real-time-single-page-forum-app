<template>
    <v-toolbar>
        <v-toolbar-title>Y-knou</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-toolbar-items>
            <v-btn text>Forum</v-btn>
            <v-btn text>Ask Question</v-btn>
            <v-btn text>Category</v-btn>
            <v-btn text>Login</v-btn>
        </v-toolbar-items>

        <template v-if="$vuetify.breakpoint.smAndUp">
<!--            <v-btn icon>-->
<!--                <v-icon>mdi-export-variant</v-icon>-->
<!--            </v-btn>-->
<!--            <v-btn icon>-->
<!--                <v-icon>mdi-delete-circle</v-icon>-->
<!--            </v-btn>-->
<!--            <v-btn icon>-->
<!--                <v-icon>mdi-plus-circle</v-icon>-->
<!--            </v-btn>-->
        </template>
    </v-toolbar>
</template>

<script>
    export default {

    }
</script>

<style scoped>

</style>




