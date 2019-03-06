Practice: Scrolling and Scaling
The learning objective for this exercise is to practice listening for the scroll event broadcast by the browser, and updating DOM elements in response.

Create the following three files, and copy pasta the code provided.

index.html

Put the following code into the <body> element.

<article id="container">
  <section id="audrey">Feed me, Seymour</section>
</article>
box.css

#container {
  display: flex;
  min-height: 1500px;
}

#audrey {
  background-color: purple;
  color: snow;
  min-height: 100px;
  width: 50px;
  position: fixed;
}
audrey.js

const audrey = document.getElementById("audrey")

/*
    Add an event listener to the `document` object to listen
    for the "scroll" event.
*/
.addEventListener("", function () {
    /*
        Adjust the width of audrey to be 1/3 the value of
        `window.scrollY`. No lower than 50px, though.
    */



    /*
        Adjust the height of audrey to be 1/4 the value of
        `window.scrollY`. No lower than 100px, though.
    */
})