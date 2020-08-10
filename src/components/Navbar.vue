<template>
    <nav class="main-nav">
        <ul>
            <li><router-link to="/">Home</router-link></li>
            <li><router-link :to="{ name: 'About'}">About</router-link></li>
        </ul>
    </nav>
        
</template>