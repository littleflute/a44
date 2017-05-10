[v0.0.7](https://github.com/littleflute/a44/edit/master/cd1/readme.md)

[show this page](https://littleflute.github.io/a44/cd1)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/a44/cd1/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 

html += fNewBtn(1);
html += fNewBtn(2);
html += fNewBtn(3);
html += fNewBtn(4);
html += fNewBtn(5);
html += fNewBtn(6);
html += fNewBtn(7); 
html += fNewBtn(8); 
html += fNewBtn(9); 
html += fNewBtn(10); 
html += fNewBtn(11); 
html += fNewBtn(12); 
html += fNewBtn(13); 
html += fNewBtn(14); 
html += fNewBtn(15); 
html += fNewBtn(16); 
html += fNewBtn(17); 
html += fNewBtn(18); 
html += fNewBtn(19); 
html += fNewBtn(20); 
html += fNewBtn(21); 
html += fNewBtn(22); 
html += fNewBtn(23); 
 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a44/cd1/";
    if(i<10) 
    {
    	s += "0";
    } 
    s += i;
    s += "_曲目 ";
    s += i;
    s += ".mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>



