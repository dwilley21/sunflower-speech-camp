<template>
    <v-container>
        <h1 class="subHeading">Camps</h1>
        <div class="camp-separator">
            <div>
                <h2>Students Camp</h2>
                <div class="dates">July 8th - July 13th</div>
                <div class="content">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perferendis iste consectetur quia saepe excepturi commodi porro ullam dolore, cupiditate quo quasi quidem fuga illum! Inventore nisi vel esse facilis similique?</div>
            </div>
            <div>
                <h2>Coaches Camp</h2>
                <div class="dates">July 10th -July 13th</div>
                <div class="content">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perferendis iste consectetur quia saepe excepturi commodi porro ullam dolore, cupiditate quo quasi quidem fuga illum! Inventore nisi vel esse facilis similique?</div>

            </div>
        </div>
    </v-container>
</template>

<script>
export default {
    
}
</script>

<style lang="less">
.camp-separator{
    display: flex; 
    justify-content: space-around; 
}
.content{
    margin-right: 12px;
}
.content:hover{
    
}
</style>