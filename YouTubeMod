// ==UserScript==
// @name       Fuck Google
// @description NO
// @version 1.0
// @match      https://www.youtube.com/watch?*
// @require http://code.jquery.com/jquery-latest.js
// ==/UserScript==

function FuckGoogle() {
        cd3.style="width 100%; calc(var(--ytd-rich-grid-content-max-width) + var(--ytd-rich-grid-item-margin)); display:flex; height: 100px"
        cd2[8].style = "style=margin-top:-780px;position:absolute; left:0; top:0; height:120px; overflow:scroll"
        cd3.firstElementChild.style="height: 100px";
        cd.style = "overflow:scroll; height:635px"
        cd3.firstElementChild.removeEventListener("mouseleave",FuckGoogle);
}


await new Promise(r => setTimeout(r, 7000));
var cd = document.getElementById("comments");
var cd2 = document.getElementsByClassName("ytd-rich-grid-renderer");
var cd3 = document.getElementsByClassName("style-scope ytd-watch-grid")[20];

cd.style = "overflow:scroll; height:635px"
cd2[8].style = "style=margin-top:-780px;position:absolute; left:0; top:0; height:120px; overflow:scroll"


cd3.addEventListener("mouseover", (event) => {
   cd3.style="position: absolute; left: 70px; top: 65px; height: 900px; overflow:scroll; width:1365px"
   cd3.firstElementChild.style="height:900px"
   cd2[8].style = "style=margin-top:-780px;position:absolute; left:0; top:0; height:740px; overflow:scroll"
   cd.style = "overflow:scroll; height:635px"
   cd3.addEventListener("mouseleave", FuckGoogle);
});
