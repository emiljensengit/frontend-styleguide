--- 
permalink: /preview-components/example-aktindsigt-page-3.html
layout: iframed 
title: Example-aktindsigt-page-3.html
---
<header class="header" role="banner">

    <!--1A: Portal header -->
    <div class="portal-header">
        <div class="container portal-header-inner">
            <a href="javascript:void(0);" title="Hjem" aria-label="logo link" class="logo"></a>
            <button class="button button-secondary button-menu-open js-menu-open ml-auto"
                aria-haspopup="menu" title="Åben mobil menu">Menu</button>

            <!-- 1B: Portal header: info + actions-->
            <div class="portal-info">

                <p class="user"><b class="username">Christian Emil Vestergaard Christiansen</b>                    </p>

                <a href="#" class="button button-secondary" role="button">
                    Log ud
                </a>
            </div>
        </div>
    </div>

    <!--2A: Solutiuon header -->
    <div class="solution-header">
        <div class="container solution-header-inner">
            <div class="solution-heading">
                <a href="#" title="Hjem" aria-label="logo link">
                    Ansøg om indsigt
                </a>
            </div>

            <!--2B: Solution header: Authority name + text-->
            <div class="solution-info">
                <!-- nav-secondary -->

                <h6 class="h5 authority-name"> Styrelsen for Eksempler</h6>

                <p>
                    <button class="button-unstyled button-contact" data-micromodal-trigger="modal-contact">Kontakt<svg class="icon-svg "><use xlink:href="#menu-right"></use></svg></button>
                </p>

            </div>
        </div>
    </div>

    <div class="overlay"></div>
    <nav role="navigation" class=" nav">
        <!-- collapsible-->
        <button class="button button-tertiary button-menu-close js-menu-close" title="Luk mobil menu">
            <svg class="icon-svg "><use xlink:href="#close"></use></svg> Luk
        </button>

        <div class="portal-info-mobile">
            <p class="user"><b>Christian Emil Vestergaard Christiansen</b></p>
            <a href="#" class="button button-secondary button-signout">
                Log ud
            </a>
        </div>

        <div class="solution-info-mobile">
            <p><b>Erhvervsministeriet</b></p>
            <p>
                <button class="button-unstyled button-contact" data-micromodal-trigger="modal-contact">Kontakt<svg class="icon-svg "><use xlink:href="#menu-right"></use></svg></button>
            </p>
        </div>

    </nav>
    <!-- collapsible nav end-->
</header>

<main class="container page-container">

    <div class="overflow-menu  overflow-menu--open-right ">
        <button class="button-overflow-menu js-dropdown " data-js-target="#overflow_steps"
            aria-haspopup="true" aria-expanded="false">
            Trin 3 af 3
            <svg class="icon-svg"><use xlink:href="#menu-down"></use></svg>
            <span class="sr-only">Åbner overflow menu</span>
        </button>
        <div class="overflow-menu-inner" id="overflow_steps" aria-hidden="true">

            <ul class='sidenav-list'>
                <li>
                    <a href='/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-1'>
                        1. Inden du går igang
                        <span class='sidenav-icon'>
                            <svg class='icon-svg'><use xlink:href='#check'></use></svg>
                        </span>
                    </a>
                </li>
                <li>
                    <a href='/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-2'>
                        2. Oplysninger om dig
                        <span class='sidenav-icon'>
                            <svg class='icon-svg'><use xlink:href='#check'></use></svg>
                        </span>
                    </a>
                </li>
                <li>
                    <a href='/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-3'
                        class='active'>
                        3. Bekræft oplysninger
                    </a>
                </li>
            </ul>

        </div>
    </div>

    <h1>Bekræft oplysninger</h1>
    <div class="row">
        <div class="col-12 col-lg-8">
            <table class="table table--borderless table--compact table--responsive-headers">
                <tbody>
                    <tr>
                        <th class="w-percent-md-30">Navn</th>
                        <td>Karen Jensen</td>
                        <td class="align-text-md-right">
                            <a href="/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-2">Rediger</a>
                        </td>
                    </tr>
                    <tr>
                        <th class="w-percent-md-30">Adresse</th>
                        <td>Vængetstræde 77<br>0081 Købstad</td>
                        <td class="align-text-md-right">
                            <a href="/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-2">Rediger</a>
                        </td>
                    </tr>
                    <tr>
                        <th class="w-percent-md-30">Alder</th>
                        <td>39</td>
                        <td class="align-text-md-right">
                            <a href="/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-2">Rediger</a>
                        </td>
                    </tr>
                    <tr>
                        <th class="w-percent-md-30">Tidligere ansøgninger</th>
                        <td>Nej</td>
                        <td class="align-text-md-right">
                            <a href="/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-2">Rediger</a>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>

    <nav class="page-navigation">
        <a href="/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-4"
            class="button button-primary">Næste</a>
        <a href="/frontend-styleguide/pages/page-templates/aktindsigt/aktindsigt-2"
            class="button button-ghost">Tilbage</a>
    </nav>
</main>

<footer>
    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="col-12 col-sm-12 col-md-6 footer-col">
                    <div class=" align-text-left ">
                        <ul class="unstyled-list">
                            <li>
                                <span class="h5 weight-semibold">Ansvarlig myndighed</span>
                            </li>
                            <li>
                                <p>Styrelsen for Eksempel</p>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-12 col-sm-12 col-md-6 footer-col">
                    <div class=" align-text-right  ">
                        <ul class="unstyled-list">
                            <li>
                                <a class="function-link" href="mailto:support@example.dk">support@example.dk</a>
                            </li>
                            <li>
                                <a class="function-link" href="tel:12 34 56 78">12 34 56 78</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</footer>

<div class="modal" id="modal-contact" aria-hidden="true">
    <div class="modal__overlay bg-modal" tabindex="-1" data-micromodal-close>
        <div class="modal__container" role="dialog" aria-modal="true" aria-labelledby="modal-contact-1">
            <header class="modal__header">
                <h1 class="modal__title h2" id="modal-contact-1">
                    Kontakt
                </h1>
            </header>
            <main class="modal__content">
                <div class="alert alert-warning" role="alert" aria-label="Beskedbox der viser en advarsel">
                    <div class="alert-body">
                        <h3 class="alert-heading">Vi har noget information af advarende karakter</h3>
                        <p class="alert-text">Noget tekst, der forklarer det af advarende karakter,
                            som brugeren bør vide inden denne ringer eller skriver.
                            Noget tekst, der forklarer det af advarende karakter,
                            som brugeren bør vide inden denne ringer eller skriver.</p>
                    </div>
                </div>
                <h3>En form for support</h3>
                <p>Hvis du har spørgsmål om:</p>
                <ul>
                    <li>En ting som denne</li>
                    <li>Et andet emne som dette</li>
                </ul>
                <p>Kan du ringe direkte til: 12 34 56 78</p>
                <p>Telefonen er åben:</p>
                <p class="m-0">Mandag:&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                    kl. 9-17</p>
                <p class="m-0">Tirsdag-torsdag:&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp kl. 9-17</p>
                <p class="m-0">Fredag:&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                    kl. kl. 9-14</p>
            </main>

            <button class="modal__close button button-ghost" aria-label="Close modal" data-micromodal-close>Luk</button>
        </div>
    </div>
</div>