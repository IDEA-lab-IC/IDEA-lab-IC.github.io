<h1> Ways to present pictures <h1>


<h2> Using a table <h2>

dummy1       |  dummy2      | dummy3 | dummy4
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](/../_profilePhotos/dummy1.png)  |  ![](/../_profilePhotos/dummy2.png)   |  ![](/../_profilePhotos/dummy3.png)   |  ![](/../_profilePhotos/dummy4.png)




<h2>Responsive "Meet The Team"</h2>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="../_profilePhotos/dummy1.png" alt="Jane" style="width:100%">
      <div class="container">
        <h4>Jane Doe</h4>
        <p class="title">Title</p>
        <p>(20XX-20XX)</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="../_profilePhotos/dummy2.png" alt="Mike" style="width:100%">
      <div class="container">
        <h4>Mike Ross</h4>
        <p class="title">Title</p>
        <p>(20XX-20XX)</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="../_profilePhotos/dummy3.png" alt="Mike" style="width:100%">
      <div class="container">
        <h4>Mike Ross</h4>
        <p class="title">Title</p>
        <p>(20XX-20XX)</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <img src="../_profilePhotos/dummy4.png" alt="John" style="width:100%">
      <div class="container">
        <h4>John Doe</h4>
        <p class="title">Title</p>
        <p>(20XX-20XX)</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="../_profilePhotos/dummy1.png" alt="Jane" style="width:100%">
      <div class="container">
        <h4>Jane Doe</h4>
        <p class="title">Title</p>
        <p>(20XX-20XX)</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="../_profilePhotos/dummy1.png" alt="Mike" style="width:100%">
      <div class="container">
        <h4>Mike Ross</h4>
        <p class="title">Title</p>
        <p>(20XX-20XX)</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>

<style>
/* Three columns side by side */
.column {
  float: left;
  width: 25%;
  margin-bottom: 16px;
  padding: 0 8px;
}

/* Display the columns below each other instead of side by side on small screens */
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

/* Add some shadows to create a card effect */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

/* Some left and right padding inside the container */
.container {
  padding: 0 16px;
}

/* Clear floats */
.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: rgb(109, 158, 242);
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: rgb(156, 178, 214);
}

</style>