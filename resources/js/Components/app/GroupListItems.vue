<script setup>

import GroupItem from "@/Components/app/GroupItem.vue";
import TextInput from "@/Components/TextInput.vue";
import {ref} from "vue";

const searchKeyword = ref('');
</script>

<template>
    <TextInput :model-value="searchKeyword" placeholder="Type to search" class="w-full mt-4"/>
    <div class="mt-3 h-[200px] lg:flex-1 overflow-auto">
        <div v-if="false" class="text-gray-400 text-center p-3">
            You are not joined to any groups
        </div>
        <div v-else>
            <GroupItem image = "https://picsum.photos/100"
                       title="Laravel Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Vue.js Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Laravel Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Vue.js Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Laravel Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Vue.js Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Laravel Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Vue.js Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Laravel Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>
            <GroupItem image = "https://picsum.photos/100"
                       title="Vue.js Developers"
                       description="oamfosamfo aofioafnufuan asfnofksmaffifa ifanifaf."/>

        </div>
    </div>
</template>

<style scoped>

</style>
