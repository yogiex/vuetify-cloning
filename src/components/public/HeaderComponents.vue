<template>
    <v-app-bar elevation="4">
        <v-app-bar-title>改善 Kaizen</v-app-bar-title>
        <v-text-field label="Search" clearable solo></v-text-field>

        <v-spacer></v-spacer>

        <!-- <v-btn><router-link to="about">About</router-link></v-btn> -->

        <v-list>
            <v-list-item link to="about">
                <v-list-item-action>
                    <!-- <v-icon>mdi-home</v-icon> -->
                </v-list-item-action>
                <v-list-item-content>
                    <v-list-item-title>About</v-list-item-title>
                </v-list-item-content>
            </v-list-item>
        </v-list>
    </v-app-bar>
</template>

<script>
export default {
    name: 'HeaderComponent'
}
</script>

<style>

</style>