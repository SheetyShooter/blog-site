<nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/signin">Sign In</a>
</nav>

<slot />

<style>
    nav {
        background: rgb(59, 255, 255);
        height: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 40px;
    }

    a {
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 1.2em;
        font-weight: 200;
        color: #fff;
        text-decoration: none;
    }
</style>