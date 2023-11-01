<script>
    let rtl = false;
    function toggleRtl(){
        rtl = !rtl;
    }
</script>
<button on:click={toggleRtl}>Toggle RTL</button>
 <div class="grid gap-6" dir={rtl ? 'rtl': 'ltr'}>
    <header class="border p-4 gap-6 justify-between flex items-center">
        <div class="font-bold uppercase text-24 text-blue">Logitech</div>
        <div class=""><iconify-icon class="text-30" icon="mdi:cart-outline"></iconify-icon></div>
    </header>
    <main class="grid gap-6 md:grid-cols-12">
        <div class="border p-6 md:col-span-3">Filters</div>
        <div class="border p-6 md:col-span-9">
            <h1 class="font-bold text-20">Main Content</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam sed gravida ligula. Fusce congue sem mi. Nam consectetur sit amet risus in pulvinar. Nam vehicula nunc vel purus semper, a mattis arcu pulvinar. Vestibulum ut erat at leo commodo posuere at nec metus. Curabitur efficitur justo eu gravida faucibus</p>
        </div>
    </main>
    <footer class="p-6 flex flex-wrap gap-6 justify-between bg-gray-200 text-white">
        <div class="">&copy;2023 Logitech</div>
        <div class="text-blue flex flex-wrap gap-6">
            <a href="#" class="hover:underline">About</a>
            <a href="#">Contact</a>
            <a href="#">Support</a>
            <a href="#">Privacy</a>
        </div>
    </footer>
 </div>