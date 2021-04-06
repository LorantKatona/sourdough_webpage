
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.menu {
  float: left;
  width: 20%;
}
.menuitem {
  padding: 8px;
  margin-top: 7px;
  border-bottom: 1px solid #f1f1f1;
}
.main {
  float: left;
  width: 60%;
  padding: 0 20px;
  overflow: hidden;
}
.right {
  background-color: lightblue;
  float: left;
  width: 20%;
  padding: 10px 15px;
  margin-top: 7px;
}

@media only screen and (max-width:800px) {
  /* For tablets: */
  .main {
    width: 80%;
    padding: 0;
  }
  .right {
    width: 100%;
  }
}
@media only screen and (max-width:500px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;">

<div style="background-color:#f1f1f1;padding:15px;">
  <h1>Welcome to the magic world of sourdough bread</h1>
  <h3> Probably many of you have heard about the sourdough.
    If you are here because wnat to know more about it it's perfectly fine,
    we will tell you what is behind what lies behind the word <em>sourdough</em>.<br>
    In case that you just want to pick your favorite type of bread,
    click on it and have it in a couple of hours on your table, you are also at the perfect place.</h3>
</div>

<div style="overflow:auto">
  <div class="menu">
    <div class="menuitem">The starter</div>
    <div class="menuitem">The leaven</div>
    <div class="menuitem">The dough</div>
    <div class="menuitem">The bread</div>
  </div>

  <div class="main">
    <h2>The bread</h2>
    <p>Sourdough is a bread made from the natural occurring yeast and bacteria
        in flour. In traditional sourdough recipes, you’ll find three ingredients:
        sourdough starter (which consists of flour and water), salt and flour.
        There is no yeast, no milk, no oils and no sweeteners.
        It’s about as natural as you get when it comes to bread. </p>
    <img src="kenyeres_kep.jpg" alt="A whole bread" style="width:100%">
  </div>

  <div class="right">
    <h2>What?</h2>
    <p>Bakery porducts in which only naturally occuring yeast us used</p>
    <h2>Where?</h2>
    <p>In the larger capital area of Finland alias Uusimaa.</p>
    <h2>Price?</h2>
    <p>Each product has different price based on its weight and baling complexity</p>
  </div>
</div>


<div style="background-color:#f1f1f1;text-align:center;padding:10px;margin-top:7px;font-size:12px;"> This web page is a personal page where the page owner presents its bread baking hobby.</div>

</body>
</html>
