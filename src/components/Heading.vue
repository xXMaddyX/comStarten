<script setup>
import { RouterLink } from 'vue-router';   
</script>


<template>
    <div class="content">
        <div class="content-inner">
            <RouterLink to="/" id="link">Home</RouterLink>
            <RouterLink to="forum" id="link">Forum</RouterLink>
            <p id="link">About</p>
        </div>
    </div>
</template>


<style lang="scss" scoped>
.content {
    display: flex;
    flex-direction: column;
    background: linear-gradient(131deg, #707070 0%, #262626 100%);
    box-shadow: 0px 0px 10px black;
    max-height: 78px;

    .content-inner {
        display: flex;
        flex-direction: row;
        justify-content: end;
        padding: 15px;
        gap: 30px;
        #link {
            all: unset;
            cursor: pointer;
            border: 2px solid black;
            border-radius: 10px;
            padding: 15px;
            padding-top: 10px;
            padding-bottom: 10px;
            color: white;
            font-size: 20px;
            text-shadow: 2px 2px 10px black;
            box-shadow: 0px 0px 6px black;
            transition: .3s;
            &:hover {
                background-color: rgb(141, 141, 141);
            }
        }
    }
}
</style>