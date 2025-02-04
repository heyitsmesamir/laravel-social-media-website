<script setup>

import PostItem from "@/Components/app/PostItem.vue";
const post1 = {
    user: {
        id:1,
        avatar: 'https://randomuser.me/api/portraits/men/66.jpg',
        name:'John Smith'
    },
    group: null,
    attachments:    [
        {
            id: 1,
            name: 'test.png',
            url: 'https://picsum.photos/1000',
            mime: 'image/png'
        },
        {
            id: 2,
            name: 'test2.png',
            url: 'https://picsum.photos/1000',
            mime: 'image/png'
        },
        {
            id: 3,
            name: 'MyDocument.docx',
            url: '#',
            mime: 'application/msword'
        },
    ],
    body: '<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>',
    created_at:'2023-11-19 15:12',
}
const post2 = {
    user: {
        id:1,
        avatar: 'https://randomuser.me/api/portraits/men/60.jpg',
        name:'James Doe'
    },
    group: {
        id :1,
        name: 'Laravel Developer'
    },
    body: '<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry\'s standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>',
    created_at:'2023-11-19 15:12',
}


</script>

<template>
   <div class ="overflow-auto">
       <PostItem :post="post1"/>
       <PostItem :post="post2"/>
   </div>
</template>

<style scoped>

</style>
