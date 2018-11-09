var cnt=1;
function changing(){
	var img1=document.getElementById("img1");
	var img2=document.getElementById("img2");
	var img3=document.getElementById("img3");
	if(cnt==1){
		img1.src="stop.png";
		img2.src="square.png";
		img3.src="square.png";
	}else if(cnt==2){
		img2.src="stop.png";
		img1.src="square.png";
		img3.src="square.png";
	}else{
		img3.src="stop.png";
		img2.src="square.png";
		img1.src="square.png";
	}
}