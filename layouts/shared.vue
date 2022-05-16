<template>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-ex1-collapse">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <NuxtLink to="/">Dr. Johan Van Robays</NuxtLink>
                <!-- @Html.ActionLink("Dr. Johan Van Robays", "Index", new { controller = "Home" }, new { @class = "navbar-brand" }) -->
            </div>

            <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="collapse navbar-collapse navbar-ex1-collapse">
                <ul class="nav navbar-nav navbar-right">
                    <li id="biografie">
                        <!-- @Html.ActionLink("Biografie", "Index", "Biografie") -->
                    </li>
                    <li id="patholoog">
                        <!-- @Html.ActionLink("Patholoog", "index", "Patholoog") -->
                    </li>
                    <li id="curator">
                        <!-- @Html.ActionLink("Curator", "Index", "Curator") -->
                    </li>
                    <li id="auteur">
                        <!-- @Html.ActionLink("Auteur", "Index", "Auteur") -->
                    </li>
                    <li id="vesalius">
                        <!-- @Html.ActionLink("Vesalius", "Index", "Vesalius") -->
                    </li>
                    <li id="carnaval">
                        <!-- @Html.ActionLink("Prins Carnaval Johan I", "Index", "Carnaval") -->
                    </li>
                    <li id="muzikant">
                        <!-- @Html.ActionLink("Muzikant", "Index", "Muzikant") -->
                    </li>
                    <li id="paterfamilias">
                        <!-- @Html.ActionLink("Pater Familias", "Index", "PaterFamilias") -->
                    </li>                
                </ul>
            </div>
            <!-- /.navbar-collapse -->
        </div>
        <!-- /.container -->
    </nav>

    <div id="progress" class="waiting">
    </div>

    <slot />

    <div class="container">
        <br/>
        <a href="">Top</a>
        <hr />
        <footer>
            <div class="row">
                <div class="col-lg-12 text-center">
                    <small>
                        <p>Copyright &copy; Daan Van Robays 2015</p>
                    </small>
                </div>
            </div>
        </footer>
    </div>
</template>