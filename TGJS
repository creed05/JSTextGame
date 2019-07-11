var displayedImage = document.querySelector('.displayed-img');
var thumbBar = document.querySelector('.thumb-bar');
var btn = document.querySelector('button');
var overlay = document.querySelector('.overlay');
var Grid = document.querySelector('.GridContainer');



This will create the new images to put in the new divs
for (let i = 1; i <= 10; i++) {

var newImage = document.createElement('img');
  newImage.setAttribute('src', "images/pic" + i + "small.jpg");
  newImage.setAttribute('class', "pic" + i);
  newImage.setAttribute('class', "SmallPic");
  Grid.appendChild(newImage);
  newImage.onclick = function(picture){
  var srcImage = picture.target.getAttribute('src');
  changeDisplayedImageSrc(srcImage);
  }
}

  function changeDisplayedImageSrc(srcImage){
	  displayedImage.setAttribute('src', srcImage);
  }
