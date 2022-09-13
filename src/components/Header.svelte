
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
        border-bottom: 1px solid #ddd;
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

    @media (max-width: 1200px) {
        header {
            justify-content: center;
            padding: 10px;
        }

        header > div:first-child, header div:last-child {
            display: none;
        }
    }
</style>