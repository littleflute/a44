[v0.0.7](https://github.com/littleflute/a44/edit/master/cd5/readme.md)

[show this page](https://littleflute.github.io/a44/cd5)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/a44/cd5/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
for(var n = 1; n<=24; n++)
{
  html += fNewBtn(n);
}

d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a44/cd5/";
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



