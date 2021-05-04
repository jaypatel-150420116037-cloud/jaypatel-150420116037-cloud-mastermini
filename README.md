# jaypatel-150420116037-cloud-mastermini
<!DOCTYPE html>
<html>
<title>CAFE</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inconsolata">
<style>
    body, html {
        height: 100%;
        font-family: "Inconsolata", sans-serif;
    }

    .bgimg {
        background-position: center;
        background-size: cover;
        background-image:<img src="C:\Users\jay\Desktop\master mini project\safecoffee.jpg">
        min-height: 75%;
    }

    .menu {
        display: none;
    }
</style>
<body>
<img src="C:\Users\jay\Desktop\master mini project\safecoffee.jpg">

    <!-- Links (sit on top) -->
    <div class="w3-top">
        <div class="w3-row w3-padding w3-black">
            <div class="w3-col s3">
                <a href="#" class="w3-button w3-block w3-black">HOME</a>
            </div>
            <div class="w3-col s3">
                <a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
            </div>
            <div class="w3-col s3">
                <a href="#menu" class="w3-button w3-block w3-black">MENU</a>
            </div>
            <div class="w3-col s3">
                <a href="#where" class="w3-button w3-block w3-black">WHERE</a>
            </div>
        </div>
    </div>

    <!-- Header with image -->
    <header class="bgimg w3-display-container w3-grayscale-min" id="home">
        <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
            <span class="w3-tag">Open from 6am to 5pm</span>
        </div>
        <div class="w3-display-middle w3-center">
            <span class="w3-text-white" style="font-size:90px">SCET CAFE<br>Cafe</span>
        </div>
        <div class="w3-display-bottomright w3-center w3-padding-large">
            <span class="w3-text-white">SURAT VESU.365</span>
        </div>
    </header>

    <!-- Add a background color and large text to whole page -->
    <div class="w3-sand w3-grayscale w3-large">

        <!-- About Container -->
        <div class="w3-container" id="about">
            <div class="w3-content" style="max-width:700px">
                <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ABOUT THE CAFE</span></h5>
                <p>This cafe was made by engineers, they are weak at study so they decided to build a cafe.</p>
                <p>we serve fresh made-to-order breakfast and lunch sandwiches, as well as a selection of sides and salads and other good stuff.</p>
                <div class="w3-panel w3-leftbar w3-light-grey">
                    <p><i>"Use products from nature for what it's worth - but never too early, nor too late." Fresh is the new sweet.</i></p>
                    <p>Chef, JAY JIGAR KEPASS</p>
                </div>
                <img src="/w3images/coffeeshop.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
                <p><strong>Opening hours:</strong> everyday from 6am to 5pm.</p>
                <p><strong>Address:</strong> SURAT VESU,365.</p>
            </div>
        </div>

        <!-- Menu Container -->
        <div class="w3-container" id="menu">
            <div class="w3-content" style="max-width:700px">

                <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">THE MENU</span></h5>

                <div class="w3-row w3-center w3-card w3-padding">
                    <a href="javascript:void(0)" onclick="openMenu(event, 'Eat');" id="myLink">
                        <div class="w3-col s6 tablink">Eat</div>
                    </a>
                    <a href="javascript:void(0)" onclick="openMenu(event, 'Drinks');">
                        <div class="w3-col s6 tablink">Drink</div>
                    </a>
                </div>

                <div id="Eat" class="w3-container menu w3-padding-48 w3-card">
                    <h5>Bread Basket</h5>
                    <p class="w3-text-grey">Assortment of fresh baked fruit breads and muffins 100.RS</p><br>

                    <h5>Honey Almond Granola with Fruits</h5>
                    <p class="w3-text-grey">Natural cereal of honey toasted oats, raisins, almonds and dates 75.RS</p><br>

                    <h5>Belgian Waffle</h5>
                    <p class="w3-text-grey">Vanilla flavored batter with malted flour 40.RS</p><br>

                    <h5>Scrambled eggs</h5>
                    <p class="w3-text-grey">Scrambled eggs, roasted red pepper and garlic, with green onions 150.RS</p><br>

                    <h5>Blueberry Pancakes</h5>
                    <p class="w3-text-grey">With syrup, butter and lots of berries 40.RS</p>
                </div>

                <div id="Drinks" class="w3-container menu w3-padding-48 w3-card">
                    <h5>Coffee</h5>
                    <p class="w3-text-grey">Regular coffee 35.RS</p><br>

                    <h5>Chocolato</h5>
                    <p class="w3-text-grey">Chocolate espresso with milk 25.RS</p><br>

                    <h5>Corretto</h5>
                    <p class="w3-text-grey">Whiskey and coffee 10.RS</p><br>

                    <h5>Iced tea</h5>
                    <p class="w3-text-grey">Hot tea, except not hot 20.RS</p><br>

                    <h5>Soda</h5>
                    <p class="w3-text-grey">Coke, Sprite, Fanta, etc. 46.RS</p>
                </div>
                <img src="/w3images/coffeehouse2.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
            </div>
        </div>

        <!-- Contact/Area Container -->
        <div class="w3-container" id="where" style="padding-bottom:32px;">
            <div class="w3-content" style="max-width:700px">
                <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">WHERE TO FIND US</span></h5>
                <p>Find us at some address at some place.</p>
                <img src="/w3images/map.jpg" class="w3-image" style="width:100%">
                <p><span class="w3-tag">FYI!</span> We offer full-service catering for any event, large or small. We understand your needs and we will cater the food to satisfy the biggerst criteria of them all, both look and taste.</p>
                <p><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
                <form action="/action_page.php" target="_blank">
                    <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
                    <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
                    <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
                    <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
                    <p><button class="w3-button w3-black" type="submit">SEND MESSAGE</button></p>
                </form>
            </div>
        </div>

        <!-- End page content -->
    </div>

    <!-- Footer -->
    <footer class="w3-center w3-light-grey w3-padding-48 w3-large">
        <p>WE LOVE CAFE<a href=</a></p>
    </footer>

    <script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
    </script>

</body>
</html>
