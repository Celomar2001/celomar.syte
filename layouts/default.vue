<template>
    <div>
        <header>
            <h2>Probando Nuxt</h2>
        </header>

        <main>
            <slot>
                
            </slot>
        </main>

        <footer>&copy; Celomar - {{ currentYear }} </footer>
    </div>
</template>


<script setup>
const currentYear = new Date().getUTCFullYear();
</script>