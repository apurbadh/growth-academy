<template>
<div class="flexbox">
    <div class="card">
        <div class="card-image">
                <img src="/podcast.png"/>
        </div>
        <h1 class="title" style="text-align: center"> Listen to my Podcast </h1>
        <div class="card-content" style="display:flex;justify-content:center;">
              <button class="button is-link" style="text-align:center">Listen</button>
        </div>
    </div>
     <div class="card">
        <div class="card-image">
                <img src="/blog.png"/>
        </div>
        <br><br>
        <h1 class="title" style="text-align: center"> Read My Blog </h1>
        <div class="card-content" style="display:flex;justify-content:center;">
              <button class="button is-link" style="text-align:center">Read</button>
        </div>
    </div>
     <div class="card">
        <div class="card-image">
                <img src="/instagram.jpg"/>
        </div>
        <br><br>
        <h1 class="title" style="text-align: center"> Follow me on Instagram </h1>
        <div class="card-content" style="display:flex;justify-content:center;">
              <button class="button is-link" style="text-align:center">Follow</button>
        </div>
    </div>
</div>
</template>
<style scoped>
    .flexbox{
        display: flex;
        justify-content: center;
        width: 80%;
        margin-left: 10%
    }
    .card{
        padding: 5px;
        margin: 10px
        
    }
</style>