# Tinkita-Projet
Menu deroulant avec sous-menu 
<!DOCTYPE html>
<html>
<head>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="
	<title>MD</title>


<div class="menu">
  <li><a href="#">Visit me</a>
    <ul class="sub-menu-1">
      <li class="hover-me"><a href="#"> Aides/Guides</a><i class="fa fa-angle right"></i>
      </li>
      <li><a href="#">Vols</a></li>
      <li><a href="#">Voitures</a>
     <li><a href="#">Dico</a></li>
      </li>
      <li><a href="#">Conseils</a></li>
    </ul>
    <li><a href="#">Lieux</a>
    <ul class="sub-menu-1">
      <li><a href="#">Dakar</a></li>
      <li><a href="#">Casamace</a></li>
      <li><a href="#">Mbour</a></li>
      <li><a href="#">Sine Saloum</a></li>
    </ul>
     <li><a href="#">Hotels</a>
    <ul class="sub-menu-1">
      <li><a href="#">Hotel 0</a></li>
      <li><a href="#">Hotel 1</a></li>
      <li><a href="#">Hotel 2</a></li>
      <li><a href="#">Sine Saloum 2</a></li>
    </ul>
    <li><a href="#">Galley </a>
        <ul class="sub-menu-1">
    <li><a href="#">Images<img src="arrow_1.png" height="20"></a>
<ul class="sub-menu-2">
    <li><a href="#">Momuments</a></li>
     <li><a href="#">Restaurants</a></li>
      <li><a href="#">Plages</a></li>
       <li><a href="#">Cultures</a></li>
</ul>
    </li>
    <li><a href="#">Videos<img src="arrow_1.png" height="20"></a>
         <ul>
<li><a href="#">Cultures</a></li>
<li><a href="#">Touristes</a></li>
<li><a href="#">Paysages</a></li>
<li><a href="#">Documentaire</a></li>
         </ul>
    </li>
    </ul>
    </li>
    <li><a href="#">Contact</a></li>
     <li><a href="#">Apropos</a></li>
     <li><a href="#">Cartes</a>
        <ul class="sub-menu-1">
    <li><a href="#">Restaurants</a></li>
    <li><a href="#">Hotels</a></li>
    <li><a href="#">Sites Historiques</a></li>
    <li><a href="#">Plages</a></li>
    </ul>
     </li>
  </li>
</div>

<style type="text/css">
    /*submenu2*/
    .menu li:hover ul ul {display:none;
    }
    .menu li:hover ul {display:block;
        background-color: white;

    }
    .menu li li:hover ul {
    display:block;
}/*submenu2*/
    div{
        list-style: none;
        list-style-type: none;
    }
   .sub-menu-1 a{
      list-style: none;
        list-style-type: none;
        text-decoration: none;
  
    }

    div li a:hover{ /*hover en blanc menu nav bar*/
    color: blue; 
background-color: black;
    }
    .menu {
  display: flex;
  margin: 0 auto;
  position: relative;
}

.menu > li > a {
    position: relative;
  background: blue;
  color: #fff;
  display: block;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
}
.menu ul :hover{/* hover du sub-menu1*/
background-color: violet;
color: black;
}
.menu ul {
display: block;
  background: transparent;
  height: 0;
  left: 0;
  opacity: 0;
  position:;
  transition: all .5s ease;
  top: 35px;
  width: 100%;
}

.menu li {  /*list sub-menu-1*/
text-decoration: none;
list-style-type: none;
}
.menu li:hover ul {
    background-color:;
  height: 200px;
  opacity: 1;
  transform: translateY(0);
}

.menu ul a {
  text-decoration: none;
    list-style-type: none;  
  color: #000;
  display: block;
  padding: 5px 20px;
}
.sub-menu-1 li a {
    text-decoration: none;
    list-style-type: none;
}
</style>
<!-- <style>
    .dropdown:hover>.dropdown-menu{
        display: block;
    }
</style>
   code pour ouverture sans clic mais avec hover -->
