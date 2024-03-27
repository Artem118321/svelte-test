<nav>
    <div class="nav-container">
 <a href="/" class="nav-logo" title="Back to Homepage">Имя Фамилия</a>
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

<style>
    .container{
        max-width: 1400px;
        margin: 50px auto;
    }
</style>