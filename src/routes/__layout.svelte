<script lang="ts">
	
    
</script>
<body>
 
<header id="header" class="header">
        <div class="container header__container">
            <nav class="menu">
                <ul class="menu__list">
                    <li class="menu__item">
                        <a href="/Home">Home</a>
                    </li>
                    <li class="menu__item">
                        <a href="/About">About me</a>
                    </li>
                    <li class="menu__item">
                        <a href="/Projects">Projects</a>
                    </li>
                    <li class="menu__item">
                        <a href="/Comic">Comic</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
   
</body>

<style>

body {
    padding-top: 80px;
}

.container {
    max-width: 100%;
    margin: 0 auto;
    padding: 0 15px;
}

.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: rgba(179, 177, 177, 0.089);
    backdrop-filter: blur(8px);
}

.header__container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 25px;
    padding-bottom: 25px;

}

.menu__list {
    display: flex;
    align-items: center;
    list-style-type: none;
    padding: 0;
    margin: 0;
}

.menu__item {
    margin-left: 40px;
    
}

a {
    font-size: 20px;
    font-weight: 600;
    color: #fff;
    text-decoration: none;
}
</style>
