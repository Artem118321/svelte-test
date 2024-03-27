<nav>
    <div class="nav-container">
<div class="nav-links">
    {#each nav as link}
    {#if link.isShow}
     <a href={link.href} class="link">{link.title}</a> 
    {/if}
{/each}
</div>
    </div>
</nav>

<div class="container">
    <slot></slot>
</div>

          
<script>
    const nav = [
{
    title: 'Тур-агентство',
    href: '/about',
    isShow: true
}
    ]
</script>

