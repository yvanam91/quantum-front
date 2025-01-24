<script>
	let { children } = $props();
</script>

<header class="flex col">
    <div class="main-head flex row pad-4">
        <div class="logo">
            <p>
                QUANTUM CELL
            </p>
        </div>
        <div class="nav flex row">
            <div class="titled-icon flex col">
                <div class="squared-icon">
                    <svg width="40" height="40" viewBox="0 0 42 67" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M42 21C42 32.598 32.598 42 21 42C9.40202 42 0 32.598 0 21C0 9.40202 9.40202 0 21 0C32.598 0 42 9.40202 42 21Z" fill="#E1FF00"/>
                        <path d="M1.83588e-06 67C2.32278e-06 61.4305 2.2125 56.089 6.15076 52.1508C10.089 48.2125 15.4305 46 21 46C26.5695 46 31.911 48.2125 35.8492 52.1508C39.7875 56.089 42 61.4305 42 67H1.83588e-06Z" fill="#E1FF00"/>
                    </svg>
                </div>
                <p>Connexion</p>
            </div>
            <div class="titled-icon flex col">
                <div class="squared-icon">
                    <svg width="40" height="40" viewBox="0 0 56 67" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M42.9955 16.111C42.9243 16.1237 42.8397 16.1356 42.7401 16.146C42.0786 16.2149 41.0635 16.1894 39.6704 16.126C39.3505 16.1115 39.0141 16.0952 38.6621 16.0781C36.0151 15.9497 32.4882 15.7786 28.4723 16C24.9431 16.0004 21.5142 16.0754 18.648 16.1381C17.8114 16.1564 17.0227 16.1736 16.2935 16.1877C14.6682 16.219 13.3513 16.2341 12.4442 16.2113C12.2689 16.2068 12.1142 16.2011 11.9792 16.1943C12.3862 7.70671 19.1876 1 27.46 1C35.9081 1 42.7942 7.48198 42.9955 16.111Z" stroke="#E1FF00" stroke-width="2"/>
                        <path d="M49.2327 61C47.5053 66 10.7508 67 8.1054 61C5.45999 55 -1.54006 20.5 1.95994 18C5.45994 15.5 50.4599 15 53.9599 18C57.4599 21 50.96 56 49.2327 61Z" stroke="#E1FF00" stroke-width="2"/>
                    </svg>
                </div>
                <p>Panier</p>
            </div>
        </div>
    </div>

    <div class="sub-head">
        <ul class="flex row">
            <li>Produits</li>
            <li>Formations</li>
            <li>Blog</li>
        </ul>
    </div>
</header>

{@render children() };


<footer>
    <p>This is a test</p>
</footer>