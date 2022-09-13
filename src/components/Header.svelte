
<header>
    <div>

    </div>
    <div class="brand">
        <h2>Svelte</h2>
        <h3>Ecommerce</h3>
    </div>
    <div class="auth">
        <p>Login | Cadastre-se</p>
    </div>
</header>

<style>
    header, header > div {
        display: flex;
    }

    header {
        padding: 5px 10px;
        justify-content: space-between;
        border: 1px solid #ddd;
    }

    header > div {
        padding: 0;
    }

    header > .brand > h2 {
        color: orangered;
    }

    header > .brand > h3 {
        color: #ddd;
        margin-left: 2px;
    }
</style>