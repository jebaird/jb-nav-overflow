# jb-nav-overflow
custom element that hides children in a secondary "menu/nav" if they don't fit on the first row


## Sample Usage


    <jb-nav-overflow>
    <nav>
        <ul class="jb-nav-overflow__items myapps-navclass">
            <li><a href="#">Home</a></li>
            <li><a href="#">resources</a></li>
            <li><a href="#">Clients</a></li>
            <li><a href="#">long Contact Us</a></li>
            <li><a href="#">Homer 2</a></li>
            <li><a href="#">About 2</a></li>
            <li><a href="#">Clients 2</a></li>
            <li><a href="#">Contact Us 2</a></li>
            <li><a href="#">Home 3</a></li>
            <li><a href="#">About 3</a></li>
            <li><a href="#">Clients 3</a></li>
            <li><a href="#">Contact Us 3</a></li>

            <li class="jb-nav-overflow__secondary_nav__handle">
                <a href="javascript://">More</a>
            </li>
        </ul>

    </nav>
    </jb-nav-overflow>

