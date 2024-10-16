<script setup>
</script>

<template>
    <div>
        <header>
            <nav class="bg-slate-700">
                <div>
                    <Link class="text-white px-5" href="/">Home</Link>
                    <Link class="text-white px-5" href="/about">About</Link>
                </div>
            </nav>
        </header>
        <main class="py-5">
            <slot />
        </main>
        <footer>
            <p>Site sendo desenvolvido por Pablo Nogueira.</p>
        </footer>
    </div>
</template>