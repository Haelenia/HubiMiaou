<template>
  <div class="container-fluid">
    <div class="row no-gutters">

      <div class="col-lg-2 col-md-2 col-sm-3 col-xs-4">

        <!-- LEFT -->

        <div class="left_side">

          <!-- LOGIN -->

          <div class="custom_client">
            <div class="content_image">
              <div class="logo_custom">
                <img src="../../static/img/laposte.png" alt="">
              </div>
            </div>
            <div class="log">
              <a class="dropdown-toggle" href="#">
                <span class="username">&Eacute;lo&iuml;se BETTINGER &nbsp;<i class="fa fa-sort-desc"></i></span>
              </a><br/>
              <span class="role">Administrateur</span>
            </div>
          </div>

          <!-- NAVIGATION -->

          <ul class="nav nav-pills nav-stacked">
            <li class="bold" role="presentation">
              <a href="#">
                <i class="glyphicon glyphicon-ok"></i>
                &Eacute;valuations
                <i class="float fa fa-angle-left fa-lg"></i>
              </a>
            </li>
            <li role="presentation">
              <a href="#">
                <i class="glyphicon glyphicon-thumbs-up"></i>
                Satisfaction
                <i class="float fa fa-angle-left fa-lg"></i>
              </a>
            </li>
            <li role="presentation">
              <a href="#">
                <i class="glyphicon glyphicon-education"></i>
                Abilities
                <i class="float fa fa-angle-left fa-lg"></i>
              </a>
            </li>
            <li role="presentation">
              <a href="#">
                <i class="glyphicon glyphicon-stats"></i>
                Synthèses
                <i class="float fa fa-angle-left fa-lg"></i>
              </a>
            </li>
            <li role="presentation" class="active">
              <a href="#">
                <i class="glyphicon glyphicon-cog"></i>
                Administration
                <i class="float fa fa-angle-down fa-lg"></i>
              </a>
              <ul class="sous_menu">
                <li>
                  <a href="#">
                    <span>&Eacute;quipes et utilisateurs</span>
                    <i class="float fa fa-angle-down fa-lg"></i>
                  </a>
                  <ul class="sous_sous_menu">
                    <li><a href="#">&Eacute;quipes</a></li>
                    <li><a href="#"><span>Utilisateurs</span></a></li>
                  </ul>
                </li>

                <li><a href="#">Canaux</a></li>
                <li><a href="#">Grilles</a></li>
                <li><a href="#">Activités</a></li>
                <li><a href="#">Objectifs</a></li>
                <li><a href="#">Gestion des IP</a></li>
                <li><a href="#">Gestion des synthèses<i class="float fa fa-angle-left fa-lg"></i></a></li>
              </ul>
            </li>
          </ul>

          <!-- Logo Myviseo -->

          <div class="content_viseo">
            <div class="logo_viseo">
              <img src="../../static/img/logo_myviseo.jpg" alt="">
            </div>
          </div>

        </div>
      </div>

      <!-- RIGHT -->
      <div class="col-lg-10 col-md-10 col-sm-9 col-xs-8">
        <!-- Header -->
        <div class="banner">
          <div class="row no-gutters">
            <div class="page-header">
              <h1>Liste des utilisateurs <small>(1 040 utilisateurs dont 403 conseillers actifs)</small></h1>
            </div>
          </div>
          <div class="row no-gutters">
            <div class="col-lg-6 col-md-12 col-sm-12 col-xs-12 mBot10">
              <ol class="breadcrumb">
                <li><a href="#">Accueil</a></li>
                <li><a href="#">Administration</a></li>
                <li class="active">Utilisateurs</li>
              </ol>
            </div>
            <div class="col-lg-6 col-md-12 col-sm-12 col-xs-12">
              <div class="form-group">
                <div class="fRight col-lg-4 col-md-4 col-sm-12 col-xs-12">
                  <button type="submit" class="btn btn-primary btn-sm add_users"><span class="glyphicon glyphicon-plus"></span>&nbsp; Nouvel utilisateur</button>
                  <div class="clear"></div>
                </div>
                <div class="fRight col-lg-8 col-md-8 col-sm-12 col-xs-12 searchForm" >
                  <input type="search" class="input-sm form-control search_bar" placeholder="Recherchez un conseiller, une équipe, une fonction ...">
                  <button type="submit" class="btn btn-primary btn-sm search"><span class="glyphicon glyphicon-search"></span></button>
                  <div class="clear"></div>
                </div>
                <div class="clear"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row no-gutters">

        <!-- RIGHT -->
        <div class="col-lg-10 col-md-10 col-sm-9 col-xs-8"">
        <div class="table_content">
          <div class="cadre">

            <table class="table table-striped table-bordered table-responsive">
              <thead>
              <tr>
                <th style="width:4%;"><i class="fa fa-sort"></i>&nbsp; #</th>
                <th><i class="fa fa-sort"></i>&nbsp; <label>Nom</label><br /> <input class="input" type="text"></th>
                <th><i class="fa fa-sort"></i>&nbsp; <label>Equipe</label><br /> <input class="input" type="text"></th>
                <th><i class="fa fa-sort"></i>&nbsp; <label>Fonction</label><br /> <input class="input" type="text"></th>
                <th colspan="2" style="width:6%"></th>
              </tr>
              </thead>
              <tbody>
              <tr>
                <td>1</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>2</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>3</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>4</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>5</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>6</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>7</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>8</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td>9</td>
                <td><a href="#" class="bold">Yassine AATAR</a></td>
                <td><a href="#">Webhelp / Rabat</a></td>
                <td>Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox" checked>
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              <tr>
                <td class="opacity">10</td>
                <td class="opacity"><a href="#" class="bold">Yassine AATAR</a></td>
                <td class="opacity"><a href="#">Webhelp / Rabat</a></td>
                <td class="opacity">Responsable de site / Formation (ext)</td>
                <td align="center" colspan="2" class="opacity">
                  <!-- ico user -->
                  <span><a class="glyphicon glyphicon-user" style="visibility: hidden;" href="#"></a></span>
                  <!-- switch -->
                  <label class="switch">
                    <input type="checkbox">
                    <div class="slider"></div>
                  </label>
                </td>
              </tr>
              </tbody>
            </table>
            <div class="row no-gutters">
              <div class="col-lg-6">
                <!-- Dropdown -->
                <div class="dropdown">
                  <button class="btn btn-default dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown" aria-haspopup="" aria-expanded="true">
                    10 utilisateurs
                    <span class="caret"></span>
                  </button>
                  <ul class="dropdown-menu" aria-labelledby="dropdownMenu1">
                    <li><a href="#">20 utilisateurs</a></li>
                    <li><a href="#">50 utilisateurs</a></li>
                    <li><a href="#">100 utilisateurs</a></li>
                  </ul>
                </div>
              </div>
              <div class="col-lg-6">
                <!-- Pagination -->
                <ul class="pagination">
                  <li class="disabled"><a href="#"><i class="fa fa-angle-double-left"></i></a></li>
                  <li class="disabled"><a href="#"><i class="fa fa-angle-left"></i></a></li>
                  <li class="disabled"><a href="#">1</a></li>
                  <li class="active"><a href="#">2</a></li>
                  <li class="disabled"><a href="#">...</a></li>
                  <li class="disabled"><a href="#">5</a></li>
                  <li class="disabled"><a href="#">6</a></li>
                  <li class="disabled"><a href="#"><i class="fa fa-angle-right"></i></a></li>
                  <li class="disabled"><a href="#"><i class="fa fa-angle-double-right"></i></a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
}

</script>


